# Deployment Instructions

## Step 1: Create GitHub Repository

If the repository doesn't exist yet on GitHub:

1. Go to https://github.com/MikeKapin
2. Click "New repository"
3. Repository name: `csa-training-data`
4. Description: "CSA B149.1-25 Knowledge Base for Canadian Gas Technician Programs"
5. Keep it **Private** (proprietary educational content)
6. Do NOT initialize with README, .gitignore, or license (we already have these)
7. Click "Create repository"

## Step 2: Push to GitHub

The repository is already initialized and committed locally at:
```
C:\LocalProjects\csa-training-data
```

To push to GitHub:

```bash
cd C:\LocalProjects\csa-training-data

# Add remote (replace with actual repo URL)
git remote add origin https://github.com/MikeKapin/csa-training-data.git

# Push to main branch
git branch -M main
git push -u origin main
```

If you need to authenticate, you can use:
- GitHub CLI: `gh auth login`
- Personal Access Token (PAT)
- SSH key

## Step 3: Verify Repository Contents

After pushing, verify on GitHub that you see:
- ✓ README.md
- ✓ index.json
- ✓ units/ directory with 24 JSON files
- ✓ .gitignore

## Step 4: Update data-sources.js

Update the data source configuration in your MCP server:

**File**: `C:\LocalProjects\mcp-servers\dev-tools\config\data-sources.js`

```javascript
export const dataSources = {
  CSA_UNITS: {
    type: 'github',
    owner: 'MikeKapin',
    repo: 'csa-training-data',
    path: 'index.json',
    description: 'CSA B149.1-25 Knowledge Base',
    structure: 'federated', // index.json points to units/*.json
  },
  // ... other sources
};
```

## Step 5: Update github-data-loader.js (if needed)

The loader should already support this structure, but verify it handles:
- Loading `index.json`
- Following references to `units/unit-XX.json` files
- Reconstructing the full knowledge base structure

**File**: `C:\LocalProjects\mcp-servers\dev-tools\utils\github-data-loader.js`

The loader needs to:
1. Fetch `index.json`
2. For each unit in `index.units`, fetch the referenced file
3. Build the complete `knowledgeBase` structure expected by the tool

Example implementation:
```javascript
async function fetchFromGitHub(dataSource) {
  // Fetch index
  const index = await fetchFile(dataSource.owner, dataSource.repo, dataSource.path);

  // If structure is federated, load referenced files
  if (dataSource.structure === 'federated' && index.units) {
    const knowledgeBase = {
      metadata: index.metadata,
      units: {}
    };

    // Load each unit file
    for (const unitMeta of index.units) {
      const unitData = await fetchFile(
        dataSource.owner,
        dataSource.repo,
        unitMeta.file
      );
      knowledgeBase.units[unitData.unit_name] = unitData;
    }

    return knowledgeBase;
  }

  return index;
}
```

## Step 6: Test the Integration

Test that the knowledge base loads correctly:

```javascript
// In your MCP server or test script
import { loadKnowledgeBase } from './tools/knowledge-base-tool.js';

const kb = await loadKnowledgeBase();
console.log('Units loaded:', Object.keys(kb.units).length);
console.log('Sample unit:', kb.units['Unit 1 - Safety'].editions);
```

## Step 7: Verify Tool Functions

Test each tool function to ensure compatibility:

1. **listUnits()** - Should return all 24 units
2. **getUnitContent({ unit_name: 'Unit 1' })** - Should return unit structure
3. **searchKnowledgeBase({ search_term: 'safety' })** - Should search across units
4. **getDocumentContent({ unit_name: 'Unit 1', filename: 'Chapter 1' })** - Should return chapter content
5. **getContentForTopic({ topic: 'electricity' })** - Should find relevant content

## Repository Statistics

After deployment, your repository will contain:
- **Total Files**: 27 (index.json + 24 unit files + README + .gitignore)
- **Total Size**: ~4.33 MB
- **Total Content Items**: 704 (99 chapters + 605 documents)
- **Units with 8th Edition**: 22
- **Units with 7th Edition**: 22

## Maintenance

To update the knowledge base in the future:

1. Update source file: `C:\LocalProjects\mcp-servers\dev-tools\csa_knowledge_base.json`
2. Run migration script: `node migrate-csa-kb.js`
3. Review changes: `git status` and `git diff`
4. Commit: `git add -A && git commit -m "Update: [description]"`
5. Push: `git push origin main`
6. The MCP server will fetch the latest version automatically

## Rollback Procedure

If an update causes issues:

```bash
cd C:\LocalProjects\csa-training-data

# View commit history
git log --oneline

# Revert to previous commit
git revert HEAD

# Or reset to specific commit (careful!)
git reset --hard <commit-hash>

# Force push if needed (use with caution)
git push --force origin main
```

## Validation

Before each deployment, run the validation script:

```bash
cd C:\Users\user\AppData\Local\Temp\claude\C--WINDOWS-system32\17c4f8aa-df1a-40df-915a-e68ffa158a70\scratchpad
node validate-structure.js
```

You should see:
```
✅ VALIDATION PASSED: All structures are valid!
The migrated data is compatible with knowledge-base-tool.js
```

## Security Notes

- Keep repository **PRIVATE** - this is proprietary educational content
- Do not share access tokens or credentials
- Use environment variables for any API keys
- Add secrets to `.gitignore` if configuration files are added later

## Support

For issues or questions:
- Check the validation output for structural issues
- Review knowledge-base-tool.js for expected format
- Verify github-data-loader.js is fetching correctly
- Check MCP server logs for loading errors

## Next Phase

After successful deployment:
- Update other question bank repositories (B149.2, refrigeration)
- Implement similar federated structure for large datasets
- Add caching layer if needed for performance
- Consider CDN for faster global access
