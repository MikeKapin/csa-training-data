# CSA B149.1-25 Training Data Repository

Comprehensive knowledge base for Canadian Gas Technician programs (G2 Units 10-24, G3 Units 1-9).

## Repository Structure

```
csa-training-data/
├── index.json              # Main index with metadata and unit references
├── units/                  # Individual unit files
│   ├── unit-01.json       # Unit 1 - Safety
│   ├── unit-02.json       # Unit 2 - Fasteners, Tools and Testing Equipment
│   ├── ...
│   └── unit-24.json       # Unit 24 - Air Handling
└── README.md              # This file
```

## Data Format

### Index Structure

The `index.json` file contains:
- **metadata**: Migration information, version, and repository details
- **editions**: Information about 8th Edition (2025) and 7th Edition
- **units**: Array of unit metadata with references to individual files

### Unit File Structure

Each unit file (e.g., `units/unit-01.json`) contains:

```json
{
  "unit_name": "Unit 1 - Safety",
  "unit_number": 1,
  "category": "G3",
  "editions": {
    "8th_2025": {
      "unit_name": "...",
      "edition": "8th Edition",
      "publication_date": "June 2025",
      "is_primary": true,
      "category": "Safety",
      "total_chapters": 4,
      "total_pages": 75,
      "chapters": [
        {
          "chapter_number": 1,
          "chapter_name": "On-the-job safety measures",
          "pages": "7-26",
          "topics": ["...", "..."],
          "content": "Full chapter text...",
          "assignment_questions": [...]
        }
      ]
    },
    "7th": {
      "unit_name": "...",
      "category": "G3",
      "documents": [
        {
          "filename": "...",
          "file_type": "pdf",
          "content": "Full document text...",
          "char_count": 12345
        }
      ]
    }
  }
}
```

### Edition Types

#### 8th Edition (2025) - Primary Content
- Structure: `chapters` array
- Content: Organized by chapter with topics and assignment questions
- Available for: Units 1, 2, 5, 7-23
- Fields:
  - `chapter_number`: Integer chapter identifier
  - `chapter_name`: Chapter title
  - `pages`: Page range (e.g., "7-26")
  - `topics`: Array of topic strings
  - `content`: Complete chapter text
  - `assignment_questions`: Array of questions with options and answers

#### 7th Edition - Fallback/Legacy Content
- Structure: `documents` array
- Content: Individual document files (PDF, DOCX)
- Available for: All units
- Fields:
  - `filename`: Original document filename
  - `file_type`: Document type (pdf, word, etc.)
  - `content`: Complete document text
  - `char_count`: Character count
  - `content_truncated`: Boolean indicating if content was truncated

## Units Available

### G3 Units (1-9)
1. **Unit 1 - Safety** (203 KB, 8th + 7th)
2. **Unit 2 - Fasteners, Tools and Testing Equipment** (119 KB, 8th + 7th)
3. **Unit 3 - Properties of Natural Gas and Fuels Safe Handling** (90 KB, 7th only)
4. **Unit 4 - Code and Regs** (64 KB, 7th only)
5. **Unit 5 - Introduction to Electricity** (276 KB, 8th + 7th)
6. **Unit 6 - Technical Manuals, Specs, Drawings and Graphs** (43 KB, 7th only)
7. **Unit 7 - Customer Relations** (111 KB, 8th + 7th)
8. **Unit 8 - Introduction to Piping and Tubing Systems** (112 KB, 8th + 7th)
9. **Unit 9 - Introduction to Gas Appliances** (159 KB, 8th + 7th)

### G2 Units (10-24)
10. **Unit 10 - Piping and Tubing Systems for Industrial and Commercial Applications** (117 KB, 8th + 7th)
11. **Unit 11 - Pressure regulators, overpressure protection, meters, and fuel containers** (344 KB, 8th + 7th)
12. **Unit 12 - Basic electricity for gas-fired equipment** (368 KB, 8th + 7th)
13. **Unit 13 - Controls: Fundamentals** (1085 KB, 8th + 7th)
14. **Unit 14 - The building as a system** (126 KB, 8th + 7th)
15. **Unit 15 - Domestic appliances** (114 KB, 8th + 7th)
16. **Unit 16 - Domestic gas-fired refrigerators** (114 KB, 8th + 7th)
17. **Unit 17 - Conversion burners** (71 KB, 8th + 7th)
18. **Unit 18 - Water heaters and combination systems** (179 KB, 8th + 7th)
19. **Unit 19 - Forced warm-air heating systems** (117 KB, 8th + 7th)
20. **Unit 20 - Hydronic heating systems** (112 KB, 8th + 7th)
21. **Unit 21 - Space heaters and fireplaces** (170 KB, 8th + 7th)
22. **Unit 22 - Venting practices** (116 KB, 8th + 7th)
23. **Unit 23 - Forced-air add-on devices** (64 KB, 8th + 7th)
24. **Unit 24 - Air Handling** (60 KB, 7th only)

## Usage

### Loading the Knowledge Base

```javascript
// Load index
const index = await fetch('https://raw.githubusercontent.com/MikeKapin/csa-training-data/main/index.json')
  .then(res => res.json());

// Load specific unit
const unit1 = await fetch('https://raw.githubusercontent.com/MikeKapin/csa-training-data/main/units/unit-01.json')
  .then(res => res.json());

// Access 8th edition content
const chapters = unit1.editions['8th_2025']?.chapters || [];

// Fallback to 7th edition if needed
const documents = unit1.editions['7th']?.documents || [];
```

### Edition Selection Logic

The knowledge base tool follows this priority:

1. **Primary**: Use 8th Edition (2025) if available (`editions['8th_2025']`)
2. **Fallback**: Use 7th Edition if 8th not available (`editions['7th']`)
3. **Legacy**: Some units only have 7th edition content

## Content Completeness

This repository contains **complete, untruncated content**:
- Full chapter text (not summaries)
- All assignment questions with answers
- All topics and subtopics
- Complete metadata (editions, publication dates)
- Total size: ~4.33 MB of educational content

## Integration

This repository is designed to work with:
- `knowledge-base-tool.js` in the dev-tools MCP server
- `github-data-loader.js` for fetching from GitHub
- CSA question bank tools for quiz generation

## Version Information

- **Structure Version**: 1.0.0
- **Source Version**: 8.24.0
- **Source Extraction**: 2025-10-28
- **Migration Date**: 2026-02-05
- **Total Units**: 24
- **Total Content**: 4.33 MB

## License

This content is proprietary educational material for Canadian Gas Technician training programs. All rights reserved.

## Maintenance

To update the knowledge base:
1. Update the source `csa_knowledge_base.json` file
2. Run the migration script to regenerate unit files
3. Validate the structure matches the tool expectations
4. Commit and push to this repository
5. Update version numbers in index.json

## Contact

Part of the LARK Labs suite of educational technology tools for Canadian HVAC and Gas Technician training programs.

- Repository: https://github.com/MikeKapin/csa-training-data
- Website: https://larklabs.org
