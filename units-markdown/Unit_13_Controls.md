# Controls

**Module:** 13
**Category:** G2
**Word Count:** 27875

---

## 1.5 

Differential (psig)
Pressure drop before contacts close

## 3.5 

Cut-in Pressure (psig)
Pressure when contacts close again
The contacts close again when the steam pressure reduces by the differential setting, in this case, down to approximately 3.5 psig (24
kPa).
The main (cut-out) and differential on the operating pressure control are adjustable.

Red Seal Alignment
CSA Gas Trade Unit2014 Red Seal Block2014 Red Seal TaskTitle
11ATask 1Performs safety-
related functions
12ATask 2Maintains and uses
tools and equipment
13ATask 3Plans and prepares for
installation, service and
maintenance
14BTask 4Fits tube and tubing for
gas piping systems
15BTask 5Fits plastic pipe for gas
piping systems
16BTask 6Fits steel pipe for gas
piping systems
This table shows the alignment between CSA Gas Trade Units and the 2014 Red Seal certification tasks and
blocks.

Red Seal Alignment Continued
CSA Gas Trade Unit2014 Red Seal Block2014 Red Seal TaskTitle
17CTask 7Installs venting
18CTask 8Installs air supply system
19CTask 9Installs draft control systems
20DTask 10Selects and installs electronic
components
21DTask 11Selects and installs electrical
components
22DTask 12Installs automation and
instrumentation control systems

Red Seal Alignment Final Section
CSA Gas Trade Unit2014 Red Seal Block2014 Red Seal TaskTitle
23ETask 13Installs gas-fired
system piping and
equipment
24ETask 14Installs gas-fired
system components
-ETask 15Installs propane
storage and handling
systems
-FTask 16Tests gas-fired
systems
-FTask 17Commissions gas-
fired systems
-GTask 18-20Maintains, repairs,
and decommissions
gas-fired systems

Summary of Control Fundamentals
1
Control Principles
Understanding the physical principles that make controls work
Control Components
Recognizing the various components and their functions
Control Systems
Integrating components into functional control systems
Safety Controls
Ensuring safe operation of gas-fired equipment
Advanced Technology
Adapting to new electronic and smart control systems
Gas technicians must understand the fundamentals of controls to properly install, maintain, and troubleshoot gas-fired equipment. From basic principles of
thermal expansion to advanced electronic controls, this knowledge forms the foundation for safe and efficient system operation.

Industrial Boiler Control
Systems
This section explores the various control systems used in industrial
boilers, including pressure transmitters, system control concepts, and
safety mechanisms that ensure proper operation and prevent hazardous
conditions.

Operating Pressure Transmitters
What are Pressure Transmitters?
Industrial boilers may have remote electronic controllers that will require local sensors rather than
electrometrical operating controls. Pressure transmitters or transducers convert an applied pressure into a
measurable electrical signal.
Components
A pressure transmitter consists of two parts:
•an elastic material, which deforms when exposed to a pressurized medium
•an electrical device, which detects the deformation

How Pressure Transmitters
Work
Flexible Diaphragm Design
One of the most common methods
is to form the elastic material into a
thin flexible diagram. The electrical
device then detects this
deformation and converts it into a
proportional electrical signal.
Signal Conversion
When pressure is applied to the
diaphragm, it flexes in proportion
to the pressure. This mechanical
movement is detected by the
electrical component and
converted into a signal that can be
read by the control system.
Applications
These transmitters are essential for monitoring boiler pressure and providing
feedback to control systems, ensuring safe and efficient operation of
industrial boilers.

System Control Concepts
Primary Control Types
The two primary control concepts are either:
•on/off control used with electromechanical controllers
•closed-loop control used with sensors and a
microprocessor-based controller

On/Off Control Systems
Electromechanical
Measurement
When electromechanical
devices measure the controlled
variables (air temperature, water
temperature, etc.), they directly
act upon a set of electrical
contacts.
Built-in Logic
They were called controllers as
they would be installed directly
into an electrical circuit that
would be energizing or de-
energizing a load or relay. The
control sequencing and logic is
built into the circuitry.
Deadband Effect
On/off is a very simple form of
control, but its outcome will have
swings over and under the
desired setpoint (deadband).

Limitations of On/Off Control
Binary Operation
The equipment is only running at either 100% on or off
Temperature Swings
Creates temperature fluctuations above and below the setpoint
Differential Requirement
The electromechanical controller itself has to have a differential
designed into it
Rapid Cycling Risk
Without differential, contacts would be rapid firing constantly

Electronic Control Systems
Sensor-Based
The electronic devices
introduced are mostly
sensors that would be
measuring the controlled
variable and
communicating that
information to a master
controller.
Integrated Controls
Example of these
controllers are integrated
furnace controls and
integrated boiler controls.
They are referred to as
"integrated" because they
can combine two or more
functions to become more
effective.
Variable Operation
Modulating boilers and multistage furnaces can vary their firing
rate based on feedback that the controller gets from its various
internal and remote sensors.

Components of Electronic Control Systems
Sensors
Devices that measure variables like
temperature, pressure, and flow
Controller
The brain of the system that
processes sensor data and makes
decisions
Control Devices
Components that execute the
controller's commands, such as
valves and motors

Closed-Loop Control Systems
Feedback-Based Operation
A closed-loop control system can make adjustments to the manipulated variable (e.g., boiler
supply water temperature) based on feedback it receives from sensors in the controlled variable
(e.g., indoor air).
This enables a heating system to modulate its input and more closely match the load requirement
to avoid the overshoot and undershoot inherent with an on/off control system.

PID Control
PID Algorithm
Proportional-Integral-Derivative control
Error Analysis
Examines difference between target and measured values
Continuous Adjustment
Makes precise adjustments to maintain optimal operation
When the controller receives feedback from the sensors, it compares the information with the setpoint value and makes
adjustments. For example, the boiler may modulate its firing rate to better match the demand. The adjustments that the
controller makes are based on a stored set of instructions (algorithm). One of the most common control processing algorithms
used is called proportional-integral-derivative control (PID).

Components of PID Logic
Proportional
Output varies in proportion to how much error exists (e.g.,
how far is the boiler water temperature from the setpoint)
Integral
Examines the duration over which the error occurs (e.g.,
how long has the temperature been below the setpoint)
Derivative
Measures how fast the error is changing. This adjusts the
reaction time

Outdoor Reset Control
Weather-Based Adjustment
Outdoor reset is when the controller calculates the system
water temperature setpoint by monitoring weather
conditions. The controller lowers boiler water temperature
when the outdoor temperature is warmer and increases it
when the outdoor temperature is colder.
Benefits
•Improved energy efficiency
•Better comfort control
•Reduced temperature swings
•Required by energy conservation regulations in many
areas

Building Management Systems
Integrated Control
Today, many gas appliances have an integrate control
located right on the equipment. These may include sensor
(I/O) connections, as well as internal PID modules within the
control board.
Larger Systems
On larger commercial, institutional, and industrial systems,
the control loop for the gas equipment is only one piece of
the puzzle, and it needs to be able to work in harmony with
other HVAC equipment.
On these systems, it is common to use a DOC or PLC system
to communicate, operate, and coordinate the various HVAC
equipment.

BMS Components and
Functions
Comprehensive System
When all the systems are tied
into the building's main
network (Primary Bus), this is
referred to as a building
management system (BMS),
building automation system
(BAS), or energy management
systems (EMS).
Remote Access
This type of system gives
operators and managers the
ability to monitor and control
remotely from any networked
location.
System Benefits
Connecting all the systems to one BMS can improve occupant comfort,
system efficiency, energy consumption, and life cycle of equipment.

BMS Communication Protocols
Ethernet
Standard networking protocol used
for local area networks (LANs)
BACnet
Building Automation and Control
Network - a data communication
protocol for building automation
LonWorks
Local operating network - a
networking platform specifically
created to address control
applications
Modbus
A serial communications protocol originally published for
use with programmable logic controllers (PLCs)
KNX
A standardized, OSI-based network communications
protocol for intelligent buildings

BMS Integration
Considerations
Override Functions
Building management systems
may use the DOC or PLC to
control the equipment firing
rate and the outdoor reset
functions. In these cases, it may
be necessary to override these
functions within the appliance's
internal controller.
DIP Switch Settings
Could entail specific settings on
the appliance DIP switches and
I/O connections as well as a
network protocol interface
module.
Follow Manufacturer Instructions
Be sure to follow the manufactures instructions for setting up the
appliance onto a BMS.

Limit and Safety Controllers
Purpose
Limit and safety controls
include all the interlocking
controls to ensure that the
burner cannot operate unless
all associated functions to the
burner are normal.
Protection
In addition to the standard
pressure and temperature
safety limit controls used for
the protection of the fired
equipment, there are several
other controls used as limits or
interlocks.
Function
These safety systems monitor various aspects of boiler operation
and shut down the system if dangerous conditions are detected.

Low-Water Cut-Off Switch
Function
The low-water cut-off switch actuates in response to fluid
movement. If the water level in the boiler falls below the
minimum level, the low-water cut-off switch opens its
contacts and cuts off power to the main gas valve.
The Boiler and Pressure Vessel code lists when and where
low water cut-offs are required.
Types
There are two basic types of low-water cut-off switches:
•float type
•probe type

Float-Type Low-Water Cut-Off
Operation
The float type is a normally open switch that is held close by
the float on top of the water. If the water level falls below a
predetermined point, the float mechanism lowers and
breaks the electrical contact.

Probe-Type Low-Water Cut-Off
Operation
The probe type is a normally open switch. It has an electronic circuitry
that uses boiler water to conduct current between the terminals on
the end of the probes.
There are multiple and single probe types. The single probe type is
most common in commercial and residential applications.
Circuit Breaking
On the single probe type, if the water falls below the level of the probe,
the electronic circuit between the terminal and the boiler shell or
piping is broken. In response to no circuit, the low water cut-off switch
opens, cutting off power to the main gas valve.

High Limit Aquastat
Function
The high limit aquastat is similar to the operating aquastat but is adjusted
to a higher water temperature setting [commonly 200°F (93°C)]. It serves
as a backup safety switch in case the operating aquastat fails.
Manual Reset
Some models are equipped with a manual reset device. For example, if the
water temperature reaches 200°F (93°C) and the contacts open, the
switch must be manually reset to close to encourage the operator to check
the system and remedy the situation rather than continually resetting the
high limit.

Dual Temperature Sensors
Combined Components
The two aquastats can be mounted side by side. In some cases, they are
consolidated into one component, even sharing a single sensing element.
Dual Sensor Design
In the image, you can see four wires coming from this sensor well as a single
housing contains both the operating and high limit thermistor type
sensors.

Snap Disc Boiler High Limits
Surface Mount Design
Another common style of boiler high limit is the non-
adjustable surface mount snap disc type. Notice that they
must be in contact with a flat surface to get maximum
contact.

Flow Switch
Function
Flow switches actuate in response to water movement. They
ensure that the pumps are circulating water in the piping system
and the boiler before the main burner can fire.
Boilers that require flow switches have small water capacities, and
their water may turn to steam if the flow of water is inadequate.
Installation
Flow switches come with various paddle lengths for different pipe
sizes. Be sure to read the installation instructions carefully because
some paddle sizes may need to be stacked to create a stiffer paddle
or trimmed.

Sail Switch
Air Flow Detection
Flow switches can also be designed to detect air movement.
These are called sail switches.
A common application of a sail switch is proving air flow for
burner systems.

High-Limit Switch
Function
The high-limit switch actuates in response to an excessive rise in
air temperature. It is a normally closed switch that opens the
control circuit if overheating occurs.
Common Type
The snap disc temperature sensing switch is commonly used on
many small appliances as a limit switch. The sensing element
may extend into the air stream by employing an extended snap
disc thermostat limit switch.

Extended Snap Disc Thermostat
Design
The extended snap disc thermostat has a sensing element
that protrudes into the air stream for more accurate
temperature measurement.

High-Limit Switch Operation
Location
A common location for a high-limit switch on a forced warm-air furnace is next
to the heat exchanger.
Temperature Response
If the temperature of the heat exchanger reaches around 200°F (93°C) - the
normal setpoint for the high limit - the heat-sensitive bi metal will warp and
break the control circuit.
Automatic Reset
Once the temperature lowers to around 175°F (79°C), the contacts will
automatically reset. In this case, the differential between the opening and closing
temperature settings is 25°F (14°C).
Fixed Settings
The setpoint and differential are usually not adjustable as these are determined
by the manufacturer for the unit.

Flame Rollout Switch
Safety Application
The snap disc type of high-limit switch is often used as a
flame roll-out switch for various applications. It also includes
a small manual reset button between the electrical
connections.

Combination High-Limit/Fan Control Switch
Consolidated Design
Multiple controls or sensors may be consolidated into one
component. The combination high-limit/fan control is an
older-style electrometrical control that contains a normally
open fan switch on the left side and a normally closed high-
limit switch on the right side and also shares the same bi
metal helical sensing element.

Operation of Combination Control
Temperature Rise
As the temperature rises, the bimetal strip first closes the fan switch and starts the blower
Overheating Condition
If an overheating condition occurs due to insufficient air flow, the bi metal strip will continue to warp
Limit Activation
When the limit cut-out temperature is reached [around 200°F (93°C)], the limit switch opens
Fan Operation
The fan continues to run until the fan switch cools and opens

High-Limit Pressure Control
Function
A high-limit pressure control (pressuretrol) works similarly
to an operating pressure control except that it is adjusted to
a higher pressure setting.
Notice the high limit looks similar to the operating controller,
but it does not have a differential setting; instead, it has a
manual reset push button.

Gas-Pressure Switches
Code Requirement
Gas-pressure switches are required by code on burner systems that operate
with gas pressures greater than 1/2 psig (3.5 kPa).
Safety Function
They automatically de-energize the gas valve(s), shutting off the gas supply
to the burner in the event of an overpressure or an under pressure condition
in the burner valve train assembly.
Specialized Equipment
Gas pressure switches differ from other pressure switches in that they are
specifically approved to be used with combustible gases and are not
interchangeable with non-approved controls.
Verification
Always confirm the application with the manufacturer's literature.

Types of Gas Pressure Switches
TypeOperationCSA B149.3
Requirement
Low gas-pressure
switch
Are reverse acting
(RA) in that they open
if gas pressure falls
below the setpoint of
the appliance pressure
regulator
The switch opens if
the pressure drops to
50% of the regulator
setpoint.
High gas-pressure
switch
Are direct acting (DA)
in that they open
when gas pressure
exceeds the outlet
pressure of the
appliance regulator
The switch opens
when the appliance
regulator setpoint is
exceeded by 25% or
more.

Combination Gas Pressure Switch
Combined Function
As with many other controls, both the high and the low
pressure switches may be combined in a single unit.
Closer inspection of the settings shows that this
combination switch is set up to protect an appliance
operating with a maximum inlet gas pressure of 1/2 psig (14
inches w.c.) and a minimum of 1/4 psig (7 inches w.c.).

Combustion Safety Controls
Evolution
Combustion safety controls
have evolved over the years
from very basic flame
monitoring and supervision to
very complex microprocessor-
based control systems.
Purpose
The basic purpose of the control
system is the same for all fuel
systems: to safely operate the
appliance.
Function
Under safe conditions, the combustion safety control system will allow
the burner start-up sequence to begin.

Evolution of Combustion Controls
1
Simple Thermocouple
Early systems used basic thermocouples that
monitored the pilot flame
2
Electronic Ignition Control
Advanced to modules that monitor the flame and
sequence the burner cycle
3
Flame Safeguard Systems
Evolved to FSG control systems that control all
processes of burner operation
4
Integrated Management
Modern systems feature manufacturer-specific
integrated burner management and control systems

Flame Sensors
Purpose
Flame sensors are designed to detect the presence of a
flame, whether it be the pilot flame or the main burner.
Operation
If the flame is not detected, the flame sensor fails to send a
flame signal to the control module/system.
More complex systems are examined in the Gas Trade
Training: Advanced program above 400k BTU series.

Flame Rod Detectors
Common Detection Method
Flame rod detectors are the most common flame-sensing
devices.
Types
There are two basic types of flame rod detection systems:
•flame conductivity
•flame rectification
They work on the principle of flame ionization, whereby the
heat from the flame causes air molecules in and around the
flame envelope to collide so forcibly as to propel some
electrons out of their atoms, thus producing ions and free
electron.

Flame Conductivity System
Operation
For a conductivity system, two flame rods (electrodes) are placed
in the flame, and when an AC voltage is applied across the
electrodes, an equal current can be conducted through the flame
between the two rods. Since electricity consists of electrons
moving from atom to atom, the ions in the flame conduct the
movement of these electrons.
Limitation
Because the flame current in a conductivity system is AC, this
system cannot differentiate between a leakage current and an
actual flame current. It is possible for the system to falsely indicate
the presence of a flame (with possibly dangerous results) if the
flame electrode is shorted to ground through a leakage circuit with
about the same resistance as the flame.

Flame Rectification System
Design Difference
The flame rectification system also uses two electrodes, but with
one important difference - the ground electrode is always
designed to be much larger than the flame electrode (flame rod).
The amount of current conducted through the flame depends on
the relative size of the flame rods. In this system, the ground
electrode (usually the burner head) is much larger than the flame
electrode.
Size Ratio
To ensure adequate flame rectification, maintain a minimum
ratio of 4:1 between grounding area and the flame rod. This
means that the grounding area must be four times the size of the
flame rod.
In some cases, additional metal rods or plates are added to the
burner to increase the grounding surface area.

Flame Rod Materials
High Temperature Materials
The typical flame rod is made from Kanthal®, a high
temperature alloy capable of withstanding temperatures up
to 2462°F (1350°C), or Globar®, a ceramic material having a
maximum operating temperature of 2600°F (1425°C).
Typical flame rod setup for both residential and large
applications.

Flame Rectification Operation
Principle
Although powered by an AC source, the size difference
between the burner head and the flame rod creates a
pulsating current that can be read by a DC microammeter.

Flame Rectification Cycle
First Half of Cycle
1. AC voltage is supplied across the two
electrodes. The flame rod is positive, and
the grounding area is negative.
2. Positively charged ions flow to the
grounding area. Since the grounding
area is large, it holds many electrons.
3. Positively charged ions pull a high
stream of electrons into the flame. This
results in a high current flowing from the
grounding area to the flame rod during
the first half of the cycle.
Second Half of Cycle
In the second half of the cycle, the
reverse process occurs, but the flame rod
cannot hold as many electrons and the
resulting current is weaker.
Resultant Current
The resultant current acts like a pulsating
DC. The flame signal in a rectified system
should be steady and can be measured
with a DC microammeter.

Optical Flame Sensors
Flame Radiation
A flame radiates energy in the form of waves that produce
heat and light. Only approximately 6% of the radiation is
visible to the eye; the majority (90%) of the heat occurs at
the infrared end of the spectrum, while a small percentage
(3%) occurs at the ultraviolet end of the light spectrum.

Ultraviolet Flame Sensor
Construction
An ultraviolet sensing tube can detect the radiant energy in
a flame. This tube consists of quartz and filled with inert gas.
Operation
Two AC-energized electrodes within the tube will, upon
detection of ultraviolet radiation, create electrical
pulsations. These pulsations are used to signal the control
module that ultraviolet radiation has been detected, thus
proving the pilot flame.

Infrared Flame Sensor
Main Element
The main element of the infrared sensor is a lead sulphide cell that is used
as an electrical switch. The lead sulphide material is in itself a
semiconductor, but when exposed to infrared radiation, it loses its
resistance and allows free movement of electricity.
Application
When installed in the control circuit and (sighted) at the infrared part of the
pilot flame, the lead sulphide cell will energize the circuit only if it detects
infrared radiation, proving the pilot flame.

Air-Proving Switch
Function
Air-proving switches interlock the burner fan operation with the
flame safeguard control. They are used to sense combustion air
or flue gas flow on any appliance that incorporates a fan or
blower.
Design
Essentially, air-proving switches are sensitive diaphragm-
operated pressure switches used to sense positive, negative, or
differential air pressure changes at specific location on the gas
appliance to confirm air flow or alternately to indicate a
blockage.

Pressure Switch Operation
Single Sensing Design
The pressure switch shown has a single sensing hose connected to
the negative side of the induced vent blower, requiring at least a

## 0.50 inch w.c. pressure fall (WCPF) to complete the control circuit.

A pressure switch used to sense a positive pressure would be
labelled w.c. pressure rise (WCPR).
Differential Design
On high-efficiency condensing furnaces, the switch will have two
hose connections to measure pressure difference - one for sensing
the pressure at the burner enclosure and the other for sensing
proper venting pressure at the draft inducer/condensate collector
box.

Variable Capacity
Applications
Multiple Pressure
Switches
On variable capacity
appliances, there will be
multiple pressure switches
with different pressure set
points that correspond with
the pressures created by the
fan at different firing rates.
Calibrated Setpoints
Each pressure switch is
calibrated to activate at a
specific pressure level
corresponding to a particular
firing rate.
Safety Function
These switches ensure that proper air flow is maintained at each
operating level, preventing unsafe combustion conditions.

Ignition Control Modules
Function
Control modules provide
ignition and main flame failure
protection for automatically
ignited gas burners.
Operation
In conjunction with limit and
operating controls and interlock
devices, these controls
automatically sequence with
solid-state logic the
burner/blower motor, ignition,
and main fuel valves.
Cycling
The control cycles automatically when the operating controls close and
after a power shutdown. They must be manually reset after a safety
shutdown.

Evolution of Electronic Ignition
Original Design Purpose
Control systems with electronic ignition were originally
designed for rooftop units, infrared heaters, and other gas-
fired appliances where access to the pilot was difficult or
where environmental factors such as wind and rain caused
frequent pilot outages that involved expensive service calls.
Pilot Relight Kits
Pilot relight kits are flame sensors/igniters in one unit that,
upon a flame failure, begin to spark in order to relight the
pilot. This unit continues to spark for a predetermined
amount of time until the pilot relights or the control module
goes into lockout.

Types of Control Systems
Intermittent Pilot
Uses a spark to ignite a pilot flame, which
then ignites the main burner
Direct Spark Ignition
Uses a spark to directly ignite the main
burner without a pilot
Hot Surface Ignition
Uses an electrically heated element to
ignite the gas
Manufacturers make several models of each type, depending on the specific sequence of operation required. Instead of a
dedicated ignition control module, many appliances will have an integrated control board to manage all of the electronic
components, including the appropriate ignition sequence.

Integrated Control Boards
Modern Approach
Instead of a dedicated ignition control module, many
appliances will have an integrated control board to manage
all of the electronic components, including the appropriate
ignition sequence.
Flame Safeguard Controllers
On inputs less than 400,000 British thermal units per hour
(Btu/h), appliance manufacturers may also choose to use a
flame safeguard controller, which comes in a wide range of
makes and models.

Basic Operation of Ignition Systems
Heat Call
On a call for heat, the thermostat energizes the control module
Sequencing
The control module then sequences the safe light-up of the burner system
Safety Check
Performs a safe start check
Ignition
Ignites the flame and powers the gas valves
Monitoring
Proves presence of flame and monitors during the run cycle

Cycle Completion
Thermostat
Satisfaction
When the call for heat is
satisfied, the thermostat
de-energizes the control
module.
Valve Shutdown
The control module then
de-energizes both the pilot
and main gas valves.
Ready State
The system returns to standby mode, ready for the next call for
heat.

Ignition Control Terminology
TermDefinition
Trial for ignitionThe period of time allowed to establish
ignition. For modules that are part of a
100% safe system, the trial for ignition
period is stated on the module. Modules
that are part of a non-100% system
energize the pilot valve and source of
ignition until the flame is established.
LockoutWhat happens to the control module if the
trial for ignition time expires. The module
then requires a manual reset to restart the
ignition sequence, accomplished either by
depressing a reset button on the control
module or by turning the thermostat to its
lowest setting, depending on the make
and model.

Lockout Reset Procedure
De-energize Control
Turning the thermostat to its lowest setting de-energizes the
control module.
Wait Period
After a predetermined period (usually 1 to 3 minutes), the control
module resets.
Re-energize
The control can be energized by turning the thermostat back
to its setting.

Lockout Indicators
Visual Indicators
Depending on the control and how it is wired, a visual
(flashing LED) alarm accompanies lockout mode to indicate
that there has been an ignition or flame failure.
•Different flash patterns may indicate specific fault codes
•Some systems use colored LEDs to indicate different
states
•Modern systems may display numeric codes on a digital
display
Audio Indicators
Some systems also include audio alarms that sound when a
lockout condition occurs.
•Beeping patterns may indicate different fault types
•Volume and duration may vary by manufacturer
•Some systems allow for remote audio alarms

Boiler Control System Summary
Sensing Components
From pressure transmitters to flame sensors, modern boilers use a variety of
sensing devices to monitor operating conditions.
Safety Controls
Multiple safety systems including high-limit switches, low-water cut-offs, and
pressure controls work together to prevent hazardous conditions.
Control Logic
Advanced control systems use PID algorithms and closed-loop feedback to
maintain optimal operation and efficiency.
Integration
Modern boilers can be integrated into building management systems for
comprehensive monitoring and control of all building systems.

Gas Appliance Control
Systems
This presentation explores the various control systems used in gas
appliances, including flame failure response mechanisms, ignition
control modules, and valve systems that ensure safe and efficient
operation.

Flame Failure Response Time
Definition
The time it takes the flame sensor circuits to react to a
flame failure and de-energize the main gas valve
Control Module Response
Some control modules go directly into lockout on a flame
failure, while others recycle the trial for ignition.

Intermittent Pilot Control
Module
Call for Heat
On a call for heat by the control circuit, the control module
sequences the safe light-up of the pilot flame and then the
main burner.
Operation
The pilot flame ignites and operates only during main
burner operation.
Shutdown
When the call for heat is satisfied, the pilot and main gas
valves are shut off.

Intermittent Pilot Control Module Terminals
Terminal Layout
The terminals on the control module connect to the control
circuit, the main and pilot valves, and the igniter-sensor.
Each manufacturer of an intermittent pilot control module
designs a different terminal layout. However, all types have
terminals for input power, main and pilot gas valves, ground,
and the igniter sensor.
Redundant Gas Valve
The redundant gas valve has two internal valve seats for
extra safety.
This valve can be set up to operate separately for an
intermittent pilot system or simultaneously for non-pilot
systems such as direct spark ignition or hot surface ignition.

Intermittent Pilot Control
Module Components
Control Circuit
The control module is
energized when the control
circuit is complete.
Thermostat
On a call for heat, the
thermostat contacts close
to complete the control
circuit.
Voltage
The control circuit energizes the control module through the
terminals labelled "25V."

Intermittent Pilot Control Module Operation
Safe Start Check
Energizes the flame sensor and
performs a safe start check; if
false signal exists, it does not
energize the igniter.
Ignition Sequence
Energizes the igniter, then
energizes the pilot valve
through terminal marked "PV",
and lights the pilot flame with
the igniter.
Flame Proving
Proves the flame with the flame
sensor, de-energizes the
igniter, and energizes the main
gas valve through the terminal
marked "MV".
Monitoring
Monitors the pilot flame,
through the flame sensor,
during the entire run cycle of
the main burner.

Flame Failure Response
Flame Failure
If flame failure occurs, the control module responds
immediately
Valve Shutdown
De-energizes the main gas valve
Reignition
Re-energizes the igniter
Safety Lockout
On 100% safe systems, if unable to relight within trial
period, control module goes into lockout

Non-100% Safe Systems
Continuous Operation
For non-100% safe systems, the
spark generator remains energized
indefinitely or until a pilot flame is
finally established.
Safety Concerns
This approach presents potential
safety issues as unburned gas could
accumulate if ignition fails to occur.
Modern Standards
Most modern systems incorporate
lockout features to prevent
continuous attempts at ignition
when conditions are unsafe.

Direct Spark Ignition Control Module
Operating Principle
Direct spark ignition systems operate on a slightly different
principle from the intermittent pilot system.
Direct spark ignition does not use a pilot flame but rather directly
lights the main burner with a spark.
Valve Configuration
The control module does not have the terminals for pilot valves.
If a redundant type gas valve is used, both coils are wired in
parallel and are energized together.

Direct Spark Ignition
Terminals
Input Power
Terminals for connecting power to the control module
Main Gas Valve
Terminals for controlling the main gas valve
Ground
Terminals for proper grounding of the system
Igniter-Sensor
Terminals for the combination igniter-sensor

Direct Spark Ignition Operation
Call for Heat
Thermostat contacts close to
complete the control circuit
Safe Start Check
Flame sensor performs check; if false
signal exists, igniter is not energized
Ignition
Igniter energizes and main gas valve
opens to light main flame
Flame Monitoring
Flame sensor proves flame, igniter
de-energizes, and sensor monitors
flame during operation

Direct Spark Ignition Flame Failure Response
Flame Failure Detection
Flame sensor detects loss of flame
Reignition Attempt
Control module re-energizes the igniter
Safety Lockout
Goes into lockout if unable to relight within trial for ignition
period

Hot Surface Ignition Control Module
Operating Principle
Hot surface ignition systems operate the same as direct
spark ignition, except that a hot surface lights the main
burner.
The hot surface igniter requires line voltage to heat the
surface hot enough to ignite gas on contact.
Hot surface ignition with combination igniter-sensor

Hot Surface Ignition
Terminals
TerminalLabelled as
Line voltage input terminalsL1 and L2
Terminals to the hot surface
igniter
HSI
The terminals of a hot surface ignition are the same as direct spark
ignition, except for the terminals to the hot surface igniter.

Hot Surface Ignition Sequence
Operation
Control Circuit Completion
On a call for heat, the thermostat contacts close to complete the control
circuit. The control circuit energizes the control module through the
terminals labelled "24V."
Safe Start and Warm-up
Energizes the flame sensor and performs a safe start check; if a false
flame signal exists, it does not energize the igniter. Warms up the hot
surface igniter for approximately 30 seconds through terminals "HSI".
Main Burner Ignition
Energizes the main gas valve through terminals marked "valve".
Lights the main flame. De-energizes the igniter. Proves the main
flame through the flame sensor.

Hot Surface Ignition Flame Failure Response
Flame Failure Detection
If flame failure occurs, the control module responds immediately
Valve Shutdown
De-energizes the gas valve(s)
Reignition Attempt
Re-energizes the ignition cycle
Safety Lockout
Goes into lockout if unable to relight within trial for ignition period
Some modules are designed to cycle the ignition sequence three times before lockout.

Integrated Furnace Control (IFC)
Function
An integrated furnace control (IFC) manages the entire
operation of a furnace.
Options besides ignition control can include two-stage burner
operation, variable fan speed, electronic air cleaner, and
humidifier, depending on the furnace model.
The image shows a basic integrated furnace control board with
various connection terminals.

IFC Wiring
Field Wiring
Although there are a lot of wires connected to an IFC, the
only field wiring that needs to be installed is the thermostat
wiring, which is connected to the dedicated terminal block.
The field wiring is always identified on wiring schematics
with dotted lines.
Wiring diagram showing field connections to the IFC.

Unit Wiring Diagram
Factory Wiring
The unit wiring diagram shows all
factory-installed connections
between components.
Field Connections
Field connections are typically
shown with dotted lines to
distinguish them from factory
wiring.
Troubleshooting Aid
The wiring diagram serves as an
essential reference for technicians
when diagnosing system issues.

IFC Fault Analysis
IFCs include fault analysis LEDs to help in troubleshooting. If a fault is detected, the control immediately goes into fault mode
and flashes the LED at a different rate depending on which fault is detected.

IFC Error Flash Codes
Flashing slowNormal - no call for heat
Flashing fastNormal - call for heat
Continuous ONReplace IFC
Continuous OFFCheck power
2 flashesSystem lockout (retries or
recycles exceeded)
3 flashesDraft pressure error - possible
problems

Additional IFC Error Flash
Codes
4 flashesOpen temperature limit circuit
5 flashesFlame sensed when no flame
should be present
6 flashes115 Volt AC power reversed,
poor grounding, or system
voltage too low
7 flashesGas valve circuit error
8 flashesLow flame sense signal

Flame Safeguard Controls (FSG)
Definition
A flame safeguard control (FSG) is the central controller over the safe supply of gas
and air to the burner(s).
It processes inputs from the operating control, limits, interlocks, and flame detector
into outputs that sequence the burner motor, gas and air input valves, venter
motor/damper, ignition system, pilot valve(s), and main fuel valve(s).
Function
The FSG monitors and controls only the safe operation of the appliance and leaves
the functional operation to the main operating control.
Safe and functional operations are interconnected for proper system performance.

Primary Functions of Flame Safeguard Controls
Safe Start Check
Prevents burner start-up if flame simulation condition exists
Sequence Control
Manages start-up, running, and shutdown cycles
Flame Supervision
Monitors flame and cuts fuel if flame is not present

Flame Safeguard Control
System Components
Controller
The main operating control
that cycles the appliance
(thermostat, pressuretrol,
aquastat)
Limit Controls
Ensure safe operating limits
are maintained
(temperature/pressure
limits, low water cut-off)
Interlocks
Ensure proper control sequencing (low fire start switch, proof of
closure switch, air switch)

Interconnected
Components of FSG System
Input Signals
The flame safeguard control
receives inputs from the
operating control, limits, and
flame detector.
Output Control
These signals are transferred
into outputs that sequence the
burner motor, ignition system,
pilot valve(s), and main fuel
valve(s).
Safety Integration
The system ensures all components work together to maintain safe
operation under all conditions.

Types of Flame Safeguard Controls
Primary Controls
Also known as non-programming controls
Provide only the three basic functions of
burner operation and flame monitoring
Programming Controls
More complex control sequencing for safe
light off
Include additional safety features beyond
basic functions
Programmable Logic Controls
(PLCs)
Full function computers that must be
programmed during initial activation
Used primarily in manufacturing plants
with high input applications

Primary Controls
Definition
A primary or non-programming type of flame safeguard
control provides only the three basic functions of burner
operation and flame monitoring.
To be classified as a primary control, the device must
perform the three basic functions: safe start check,
sequence operation, and flame supervision.
Primary controls: Honeywell RA 890

Primary Control Operation
Input Signals
From controller, limits, and flame detector
Processing
Control translates inputs into sequenced outputs
Output Control
Controls burner motor, ignition, pilot, and main fuel
valve(s)

Primary Control System
Diagram
System Integration
The diagram shows how the
primary control integrates
with other system
components.
Signal Flow
Input signals from various
sensors and controls are
processed to produce
appropriate output actions.
Safety Chain
The system includes multiple safety devices that must all be
satisfied for operation to continue.

Programming Controls
Complex Sequencing
Newer residential
appliances and larger
burner systems usually
require more complex
control sequencing to
ensure safe light off and
control of other safety
functions.
Added Features
Pre-purge with proven air
flow, low fire start
positioning, timed pilot trial
for ignition, monitoring of
interlocks, and more.
Sequencing Methods
Unlike primary controls with fixed relays, programming controls
use electromechanical timing devices, plug-in relays, solid-state
circuitry, or microprocessor-based circuits.

Fireye M-Series
Programming Control
Mixed Technology
The Fireye M-Series II is an
example of a control that uses a
mixture of methods, with
electromagnetic relays working
with solid-state circuitry and
microprocessor circuit boards.
Advanced Features
Provides enhanced safety
features and more precise
control over the combustion
process.
Modular Design
Components can be replaced individually for easier maintenance and
upgrades.

Microprocessor-based Programming Controls
Enhanced Capabilities
Microprocessor-based programming controls extend the sequencing, monitoring, and data
collection/transfer options offered by solid-state controls.
They offer plug-in options for flame amplifier and purge cards and often offer field selectable
programming options such as recycling or non-recycling.
Design Variations
The main sequencing features may be fixed in the chassis, as is the case in Honeywell and Eclipse
units, or fixed in a removable card, as is the case for Fireye units.

Honeywell 7800 Series
Programming Control
Microcomputer-
based
A popular microcomputer-
based FSG is the Honeywell
7800 series programming
control.
Data Storage
Like other microcomputer-
based FSGs, they store and
process an operating and
fault history.
Display Options
History can be displayed on an optional plug-in display module or
transmitted to a remote computer.

Programmable Logic Controls
(PLCs)
Applications
PLCs are often employed for
process functions at
manufacturing plants in high input
applications, but the flame
safeguard functions are usually
performed by programming
controls.
Capabilities
PLCs are basically full function
computers that must be
programmed during initial
activation of the appliance.
Normally, only Gas Technician 1
classification would be exposed to
these control systems.
Flexibility
Programming options are almost unlimited and can be changed without a
change of hardware. These units can monitor more inputs and control more
aspects of the appliance operation than any other FSG.

PLC Programming
Considerations
Safety First
Extreme care must be
taken when programming
PLCs to ensure that the
functions entered into the
computer match the
requirements of the
particular appliance.
Manufacturer
Guidance
Since system applications
for PLCs are usually
manufacturer-based,
always consult the specific
manufacturer for operating
information.
Qualified Personnel
Programming should only be performed by properly trained and
certified technicians.

Valves and Regulators
Function
Valves and regulators open or close in varying amounts to control the flow of
gas, water, or steam.
There are many different types of valves: some are operated manually, others
automatically.
Categories
The presentation will cover:
•Non-electric process valves
•Water shut-off valves
•Relief valves
•Gas valves
•Regulators

Non-electric Process Valves
Process Fluid Control
These are common valves
used to control the process
fluid, such as the hot water
produced by the gas appliance
or the cold water supplied to
the gas appliance.
Manual Valves
A manual valve is one where a
gas technician/fitter must
manually open or close the
valve. These valves can be
installed to control water and
are used to isolate parts of the
system.
Automatic Non-electric Valves
Automatic non-electric valves typically operate on temperature and
pressure changes.

Water Shut-off Valves
Function
Water shut-off valves control the flow of water to hot water heaters, hot water
boilers, and steam boilers.
They are normally open valves that can be shut off to isolate an appliance for
repair or servicing.
Types
Two typical types of water shut-off valves are:
•Gate valve
•Globe valve

Gate Valve
Design
The gate valve has a gate that moves up or down to open or close the valve.
Because of excessive vibration and wear caused by partially opened gates, these valves
are not intended for throttling or regulating flow.
Application
They are designed to operate fully open or fully closed and are typically used on water
and steam installations.

Globe Valve
Design
Globe valves, unlike gate valves, are designed for steady use in
applications with frequent throttling or flow regulation.
The design of the globe valve keeps the seat erosion to a minimum.
The globe valve's design allows for precise flow control with
minimal wear.

Relief Valves
Purpose
Relief valves are safety devices designed to relieve high pressure or temperature conditions.
They are critical safety components that prevent dangerous pressure buildup in systems.
Types
Common types include:
•Pressure relief valve
•Combination pressure-temperature relief valve

Pressure Relief Valve
Function
The pressure relief valve is a mechanical valve used on hot
water boilers.
If pressure in the system rises above the set point, the valve
opens and dumps water until the pressure drops to an
acceptable level.
Pressure relief valve

Combination Pressure-Temperature Relief Valve
Requirements
Local and national codes require the installation of storage
water heaters with a combination pressure-temperature
relief valve.
The sensing stem of this valve extends into the water within
the top six inches of the tank. It will open to dump water if
the tank pressure or water temperature is excessively high.
Replacement
Whenever a water heater is replaced, a new valve should be
installed and the old valve discarded.
Some less-sophisticated relief devices use a fusible plug as
the sensing device. Once the plug has melted, it continues
to dump water until the water supply is manually turned off.

Water Pressure-Reducing Valve
Function
The water pressure-reducing valve reduces the high pressure (e.g., house line
pressure of 40 psig) to a lower operating pressure (e.g., 15 psig for a low pressure hot
water heating systems).
The valve actuates in response to a pressure drop in the low-pressure side.
Common Name
This valve is commonly called a water makeup valve.

Feedwater Valve
Application
As a gas technician/fitter, you may encounter an automatic electric valve that
controls water, such as the feedwater valve, which controls makeup water to a
boiler.
Operation
This valve is mounted directly into the feedwater line of a boiler and operates
in conjunction with low-water cut-off limit controls to maintain the boiler
water level above the safe minimum level.
Upon sensing a low water condition, the boiler low-water cut-off shuts down
the burner and powers the feedwater control that lets in makeup water.

Gas Valves
Valve Train
The series of controls and components from the appliance
main shut-off valve to the appliance burner is called the
valve-train or manifold assembly.
Although valve-trains vary in how they are assembled, they
all have these components in one form or another.
This diagram shows the components of the valve train used
to manually and automatically start, stop, and regulate the
gas flow to the appliance.

Gas Shut-off Valves
Purpose
A manual gas shut-off valve
provides a method of
ensuring that the gas has
been positively turned off
to any area of the piping
system or to a particular
appliance.
Code Requirements
The Code clearly requires
that a readily accessible gas
shut-off valve for each
appliance be installed
upstream and external to
the valve train assembly.
Types
The two main types of manual gas shut-off valves include: Plug-
type and Ball type.

Plug-Type Valves
TypeApproved useDescription
Spring loaded valveOnly for indoor useMade of brass. This
kind of valve is no
longer installed.
Lubricated plug
valve
For indoor or
outdoor use
Made of malleable
iron. The common
name for this valve is
Lube seal. It is
designed to be
lubricated and
maintained with the
valve in place and
with no interruption
of service.

Ball Type Valves
Operation
Ball valves also open and close with a quarter-turn of a handle.
They are approved for both indoor and outdoor use.
Construction
They are constructed with a Teflon seat and a stainless-steel sealing ball.
To control the flow, the ball has a hole drilled through its centre and fits tightly against the Teflon seat
in the closed position.
Lubrication is not a concern with this type of valve.
These valves can be used for water, oil, and gas (W.O.G) applications.

Needle-Type Valves
Applications
Needle valves are used for smaller application and internal
control.
When being used as the pilot b-cock, they can be used to
open, close, or throttle the flow with the use of a small
screwdriver.
Needle valves provide precise control for small gas flows.

Automatic Safety Shut-off
Valves
Function
The automatic safety shut-off
valve is one of the most
important valves in the valve
train, and it may be an individual
component of part of a
combination gas control.
Purpose
Its function is to provide gas
shutdown if a dangerous
situation could result from the
buildup of gas with no
controlled ignition source.
Operation
The gas safety shut-off valve shuts off the gas supply when de-
energized by a combustion safety control, safety limit control, or loss of
actuating medium.

Solenoid Valve
Application
Solenoid valves are commonly used as safety shut-off valves
on pilot lines of large input appliances.
When the solenoid's electromagnet coil is energized, a
metal plunger is drawn up into the coil's centre. By coupling
the plunger to the valve seat, the rising action of the plunger
is used to lift the seat off the valve port, opening the valve.
Solenoid valve in closed position

Types of Solenoid Valves
Direct Acting
A direct acting solenoid valve has the seat
directly coupled to the plunger. Energizing the
solenoid coil lifts the plunger and seating surface,
opening the valve outlet port.
Lever-Actuated
In the lever-actuated valve, the seating surface is
connected to the plunger through a lever arm.
When the solenoid is energized, the plunger lifts
the level arm arrangement, opening or closing
the valve with a greater force.
Pilot-Operated
The pilot-operated valve uses pressure
differential to assist the plunger in opening and
closing the main valve. When the solenoid is
energized, the rising plunger opens the pilot valve
causing pressure changes that help open the
main valve.

Direct Acting Solenoid Valve
Operation
The solenoid type of safety shut-off valves typically
operates on 120 V AC.
Many solenoid valves rely on the weight of the disc and stem
to assist the spring in seating them, so they must be
installed in an upright position.
120 V AC Direct acting solenoid valve

Thermoelectric Valve
Power Source
An internal electromagnet (solenoid) powered by a thermocouple that produces pilot flame heat-generated DC millivolts controls the
thermoelectric safety shut-off valve.
Functions
Note that the pilot flame's main function is to ignite the main burner when called upon and the thermocouple's function is to prove the
existence of the pilot flame.
Thermoelectric safety shut-off valves are often referred to as pilotstats as they thermally monitor the pilot flame.

Pilotstat Module
Integration
Safety shut-off valves may be one part of a combination gas valve.
In the image, you can see that the pilotstat module has been
removed from the body of a combination gas valve. It has been
placed in front aligned with its appropriate internal location.
Pilot stat and thermocouple removed from gas valve

Gas Pressure Regulators
Purpose
Gas pressures in service piping are often much higher than the pressures acceptable
for appliances and equipment.
Gas pressure regulators, when properly selected and installed, help maintain
constant downstream gas pressure over a wide range of upstream gas pressure
variations.
Categories
There are essentially three categories of gas pressure regulators:
•Service
•System (line pressure)
•Appliance

Service and Line Pressure Regulators
Service Regulators
For natural gas, service regulators are used to reduce the service-line pressure to house-line pressure at the gas meter
set in order to deliver an allowable pressure to the building.
For propane, the gas technician/fitter installs service regulators between the storage container and the building.
Line Pressure Regulators
In some cases, a system of appliances and/or equipment in a building requires a different gas pressure from the
building-line pressure delivered by the service regulator.
The use of a line pressure regulator is generally for reducing the building-line pressure accordingly. For example, a 2-
psig service needs to be reduced to a maximum of 0.5 psig as that is the maximum inlet pressure to most appliance
regulators.

Appliance Regulators
Function
Appliance regulators are necessary to reduce the building-line pressure to that
required for the proper performance of the appliances (e.g., approximately 3 inches
w.c. for natural gas and 11 inch w.c. for propane gas).
Valve Train Component
The appliance regulator is one of the components referred to in the valve train
components diagram (this one is shown connected to the A-cock).
The main purpose of the appliance regulator is to maintain a relatively constant gas
pressure.

Gas Valves and Controls
This presentation explores the various types of gas valves and control
systems used in heating appliances. We'll examine how these critical
components regulate gas flow, ensure safe operation, and provide
precise temperature control in residential and commercial applications.

Appliance Regulators
Function
Appliance regulators maintain constant outlet pressure to
the burner(s) over a sometimes-fluctuating gas inlet
pressure. This assures a constant, even flame at the main
burners.
A-cock and appliance regulator shown above provides
consistent gas flow regardless of inlet pressure fluctuations.

Combination Control Valves
Integrated Design
Often, the appliance regulator is built into a combination control valve as is the case in the gas valve shown here. The appliance
regulator portion of the valve can be identified by the familiar shape of the spring housing and adjustment screw cover.

Automatic Gas Valves
Purpose
The automatic gas valve starts and stops the flow of gas to the
appliance main burners. A sensing device activates the automatic
gas valve, allowing the gas to flow to the burners where ignition
will take place.
Variety
There are many types of automatic gas valves with various
sensing devices and activation methods.

Methods of Operation
Mechanical Operation
Non-electric operation by a mechanical sensing device such as a capillary or
rod and tube acting directly as the valve operator
Electromagnetic Operation
Solenoid-operated where the control circuit is energized or de-energized to
activate the valve
Activation Methods
Electromechanical switches containing sensing devices or electronic control
modules monitoring sensing devices

Non-Electric Automatic Gas
Valves
Definition
Non-electric gas control valves rely upon a thermo-mechanical
sensing element to act directly upon them.
Common Types
•Rod and tube water heater gas valves
•Hydraulically operated gas valves

Rod and Tube Combination Gas Valve
Applications
The rod and tube combination gas valve is a multi-purpose valve
typically installed in storage type water heaters. They are
sometimes referred to as a Unitrol as this was one of the first
most popular models used.

Components of Rod and Tube
Valve
Safety Components
An automatic safety shut-off valve
and an over temperature energy
cut-off (eco) device
Control Components
A main and standby gas cock, a
thermostat, and an automatic main
gas valve
Regulation
A main pressure regulator

Rod and Tube Operation
Temperature Sensing
The Unitrol actuates in response to changes in water temperature.
Its sensing device works on the rod and tube principle.
Thermal Expansion
The copper tube expands or contracts based on the temperature
of the water it is immersed in.
Mechanical Action
The invar rod moves in and out of the valve body as the
copper tube changes length, controlling gas flow.

Energy Cut-Off (ECO) Device
Safety Feature
The ECO is a fusible link wired in series with the safety valve
solenoid. If the temperature-sensitive fuse exceeds 200°F,
the fuse will melt, and the electrical current to the safety
valve power unit coil will be interrupted, shutting all of the
gas off.
Most ECOs are one-shot controls; if the ECO has tripped,
the valve will have to be replaced.
The cutaway on the left has extra wires within the copper
tube. This is a built-in safety device called an Energy Cut-
Off (ECO).

Modern Hot Water Gas
Valves
Power
Requirements
More recent hot water
gas valves for higher
efficiency type water
heaters with ventor
motors require 120 V
power
Ignition Type
These valves use
direct-ignition
systems
Efficiency
Designed for higher
efficiency water
heaters

Modulating Valve
Definition
A modulating valve is a combination of two valves in a single
unit designed to give precision temperature control with
minimum cycling and maximum operating efficiency.
Modulating valves are also used for oven controls and liquid
temperature controls.

Modulating Valve Operation Sequence
Initial Heat Call
A snap-acting valve opens at the initial call for heat to provide the minimum rate of gas
flow
Temperature Assessment
If this gas flow is sufficient to bring the room up to the set temperature, the snap-
acting valve closes
Additional Heat
If more heat is required, a modulating valve adjusts the gas flow rate between the fixed
minimum and full burner capacity
Minimum Rate
The valve is provided with a minimum rate that is intended to match the minimum gas
flow requirement of the burner that it serves

Temperature Sensing Mechanism
Components
The temperature-sensing bulb,
capillary tubing, and bellows are filled
with a temperature-sensitive liquid.
Temperature Response
Changes in temperature at the bulb
contract the liquid on temperature fall
and expand it on temperature rise,
causing the bellows to shorten and
lengthen respectively.
Mechanical Action
This movement is transmitted to the
valve assembly by a horizontal pivot
arm.

Electric Automatic Gas
Valves
Prevalence
Most automatic gas valves are electrically actuated and are primarily
found on the gas valve train to control gas flow to the burner.
Advantages
•Precise control
•Remote operation
•Integration with electronic control systems
•Safety features

Diaphragm Valve
Description
The diaphragm gas valve is a pilot operated solenoid valve in
that it uses available gas pressure as the primary force to
open or close the valve. They are simply an on/off automatic
valve and do not regulate or modulate the flow.
Although this style of diaphragm valve is rare today, it serves
well as an introduction to an important concept used on
most advanced valves.
Cutaway view of a diaphragm gas valve

Diaphragm Valve Operation
Heat Call
On a call for heat, the electromagnet is energized
Armature Movement
The electromagnet pulls the armature to block the pressure port, allowing gas
pressure above the diaphragm to bleed off through the vent port
Pressure Differential
The gas pressure below the diaphragm lifts the diaphragm and valve disc from
the valve seat, allowing gas to flow
Valve Closing
When heat call ends, the electromagnet de-energizes, the armature blocks the
vent port, pressure equalizes, and the spring closes the valve

Alternative Diaphragm Valve Design
Key Differences
•An internal bleed line vents the gas back into the outlet chamber
•The valve disc is inverted, and working gas pressure is diverted to the
underside of the diaphragm
•The armature return spring is compressed when the operator is energized
Diaphragm gas valve with internal bleed

Combination Gas Valves
Purpose
Combination gas valves were designed to combine several
controls into one unit in order to save on space. These valves
are generally found in appliances with inputs 400,000 Btu/h or
less.
A typical combination gas valve integrating multiple functions

Combination Valve Components
Standard Components
The compact body of a combination
gas valve includes a manual shut-off
valve, an automatic gas valve, and a
pressure regulator.
Additional Controls
Some combination valves also
include 100% safety shut-off, pilot
gas adjustment, and control module.
System Integration
The system's ignition and the control system determine what additional controls
are included in the combination valve.

Servo Gas Valve
Design Principle
The servo regulated combination gas valve is essentially a
diaphragm gas valve with the addition of a servo regulator.
The servo gas valve uses the same principle as the
diaphragm gas valve in that it manipulates a small amount of
upstream gas flow onto the working chamber of a
diaphragm.
Whereas the diaphragm valve has strictly open or closed
valve, the servo gas valve can act as a pressure regulator by
partially opening or closing the valve seat.
Combination gas valve with servo operated regulator

Redundant Gas Valve
Safety Features
The redundant (in excess) gas valve is one of the most
popular gas safety controls used in the field today. It is of the
100% safety shut-off type with, as extra protection, a
second shut-off valve incorporated in the valve body.
This second (redundant) valve eliminates the possibility of
an operational failure, allowing gas to enter the combustion
chamber while a proper ignition source is absent.
Redundant gas valve with both valves closed before
operating cycle

Redundant Valve Pressure
Regulation
Servo Regulator Function
The servo pressure regulator is regulating the downstream pressure
with the first (pilot) valve.
Manufacturer Variations
For many manufacturers of redundant gas valves, the servo
regulator will use the second valve, and the pilot line pressure will be
throttled with an internal needle valve, rather than regulated.

Configurable Redundant Valves
Versatile Design
Gas valve manufacturers often design their redundant gas valves
with the ability to configure for intermittent pilot or for hot surface
ignition (HSI) and direct spark ignition (DSI) setups.
Configurable redundant gas valve

Configuration Methods
HSI/DSI Configuration
When used on HSI or DSI systems, a wiring harness is used to
energize both the pilot and main valve operators simultaneously.
Pilot Line Blocking
A threaded plug is installed in the pilot line connection for
HSI/DSI applications.
Intermittent Pilot Setup
For intermittent pilot applications, these components are
removed so the pilot tubing can be connected, and the
solenoid operators can signal independently from the control
module for separately sequenced operation.

Specialized Redundant Valves
Purpose-Built Designs
Other styles are designed specifically to be used for DSI or
HSI application, with the two operators internally wired
together without pilot tapping.
The servo system regulates a third main valve and large
diagrams of which chamber is visible on the side of this
valve.
Specialized redundant valve for direct ignition applications

Gas Conversion and
Pressure Compensation
Gas Conversion
Certified gas conversion
kits may require the
replacement of the
regulator spring to change
the manifolds pressure.
Regulator Vent
Regulator vent cover serves
as a dust cover only as air
must be able to move freely
in and out of the upper
chamber of the servo
regulator diaphragm.
Pressure Compensation
By connecting a combustion chamber pressure compensation
tube to the regulator vent opening, the gas valve can
automatically change the manifold pressure to maintain a
constant pressure differential across the orifice.

Two-Stage Redundant Gas Valves
Function
A two-stage gas valve is used with a two-stage thermostat
to supply fuel in quantities necessary to meet staged
demand.
The valve is built with two servo regulators, enabling it to
supply lower manifold pressure and less fuel on a first-stage
heating call. When the second stage is energized, 100% fuel
flow is sent to the burner.
Two-stage combination redundant gas valve

Two-Stage Valve Design
Structural Similarities
The valve body is very similar
to standard redundant valves
with key additions.
Additional Components
•Extra servo regulator
adjustment cover
•Additional wiring
connection to activate
servo switching solenoid
valve
Efficiency Benefits
Two-stage operation allows for more efficient heating by matching
fuel supply to actual demand.

Smart Valve Systems
Integrated Functions
Smart valve system controls combine gas flow control and
electronic intermittent pilot sequencing functions into a
single valve body and control system.
Smart valve system with integrated controls

Smart Valve Ignition System
Specialized Igniter
The igniter flame rod assembly for the smart valve contains a special 24 V HSI (Hot Surface
Igniter).
Smart valve igniter flame rod assembly

Motorized Valve
Operation Principle
The motorized valve is completely opened by the operation of an
electric motor and is generally automatically closed by a spring or
other mechanical means when the electrical circuit is broken.
Motorized hydraulic gas valve

Hydraulic Actuated Valve
Motor Operation
The electric motor runs an oil pump
Hydraulic Action
Oil fills the chamber and pushes
down on a piston or diaphragm
Full Open Position
When fully open, a switch turns off
the motor, and the oil remains
captured in the cylinder
Valve Closing
To close, the relief valve is released,
bleeding the cylinder as the return
spring closes the valve

Modulating Operation with Stepper Motor
Advanced Control
With the use of a stepper motor, diaphragm gas valves can
be used to modulate the firing rate. The valve has the same
body and internals as redundant gas valves previously
introduced with the addition of the DC motor operator.
This motor operator receives a signal from the controller
and adjusts the setting of the servo regulator to the required
manifold pressure. These valves can achieve a full range of
modulation from 35-100% with 1% increments.
DSI and HSI modulating combination gas valve

SIT Valves
Company Background
SIT is an Italian company originally focused on millivolt gas
controls. Its name became synonymous with gas valves used
on fireplaces so much that some gas fitters often use "SIT
valves" to refer to all slender millivolt gas valves used on
fireplaces.
SIT valve with remote control

SIT Valve Features
Redundant Design
There are millivolt redundant gas
valves, many of which have an
adjustable servo regulator to
change the flame size.
Adjustment Methods
The adjustable servo can be
manual dial, or electric motor
connected.
Remote Control
Many models feature battery-
powered burner control with
remote operation capabilities.

Oven Safety Valve
Safety Function
Electric oven gas valves are also safety devices that only
allow gas to flow to the bake or broil burners if the HSI (glow
bar) circuit is energized and creating adequate current.
Oven safety valve wiring diagram

Oven Safety Valve
Operation
Series Circuit
The thermostat, glow bar igniter, and gas safety valve are wired in
series, meaning electricity must pass through the glow bar and then
to the safety valve.
Resistance Principle
The glow bar blocks current to the gas valve through electrical
resistance, which declines as the bar's temperature rises.
Ignition Threshold
When the bar reaches yellow heat, sufficient to ignite the gas,
it allows passage of enough electricity to open the gas valve.

Oven Safety Valve Wiring
Wiring Diagram
The wiring diagram shows the electrical connections between the thermostat, glow bar igniter, and gas safety valve in a typical
oven installation.

Specialized Gas Valves
Purpose-Specific
Designs
There are some gas valves that
are designed for specific
purposes beyond standard
heating applications.
Safety Applications
•Seismic gas valves
•Fire suppression gas valves
Specialized Functions
These valves provide critical safety functions in emergency
situations.

Seismic Gas Valves
Purpose
Seismic gas valves are designed to shut off gas supply to a
building during an earthquake. This prevents gas from
escaping from any downstream lines that may have been
ruptured during the quake, thus minimizing the chance of a
gas fire.
Two models of seismic gas valves

Seismic Valve Operation
Installation
Requirements
Both popular models need
to be installed level as they
have an internal ball that
rolls when subject to
horizontal vibration.
Status Indication
They have an indicating
window to show valve
status.
Manual Reset
Must be manually reset once activated by seismic activity.

Fire Suppression Gas Valve
Application
The fire suppression gas valve is designed to shut off the gas supply to commercial cooking equipment if there is a
fire. They are activated by a cable connected to the fire suppression system and must be manually reset.
Cable release gas valve and fire suppression system activators

Fire Suppression System
Components
Release-to-Close Valve
The system has a release-to-close valve which is being held open by a cable.
Manual Pull Station
The cable can be released by a manual pull station for emergency shutdown.
Fusible Link
A temperature activated fusible link located above the cooking equipment can
automatically trigger the system.
Extinguishing Agent
When activated, the system releases extinguishing agent onto the cooking area.

Thermal Expansion Principle
Temperature DiscBimetallic StripRod and TubeOther Types
The temperature disc, bimetallic strip and rod and tube controls all operate on the principle of thermal expansion of solids. This fundamental principle allows these mechanical devices to respond to
temperature changes without requiring electrical power.

Comparing Gas Valve Types
Valve TypePower
Source
ApplicationsFeatures
Rod and
Tube
Non-electricWater
heaters
Simple,
reliable
DiaphragmElectricFurnaces,
boilers
On/off
control
RedundantElectricFurnaces,
boilers
Dual safety
valves
ModulatingElectricPrecision
heating
Variable flow

Gas Valve Selection Criteria
Safety Requirements
Primary consideration for all installations
Application Type
Heating, cooking, water heating, etc.
Capacity Needs
BTU requirements and flow rates
Control Method
Manual, automatic, or modulating
Power Source
Electric, non-electric, or millivolt

Gas Valve Troubleshooting
Visual Inspection
Check for physical damage or loose connections
Verify Power
Confirm proper voltage to valve
Pressure Testing
Measure inlet and outlet gas pressure
Component Replacement
Replace faulty valves or components

Gas Valve Maintenance
Regular Inspection
Visually inspect valves for signs of wear, damage, or corrosion.
Operational Testing
Verify proper operation through cycling and response testing.
Cleaning
Remove dust and debris from external components.
Documentation
Maintain records of all maintenance and testing performed.

Gas Valve Safety Considerations
Proper Installation
Gas valves must be installed according to manufacturer specifications and local
codes.
Ventilation
Ensure adequate ventilation for regulator vents and pressure relief devices.
Certification
Only use valves certified for the specific gas type and application.
Professional Service
Gas valve service should only be performed by qualified technicians.

Gas Valve Evolution
1
Early Mechanical Valves
Simple mechanical designs with limited safety features
2
Electromechanical Valves
Introduction of solenoid operation and basic safety controls
3
Combination Valves
Integration of multiple functions into single compact units
4
Smart Valves
Modern microprocessor-controlled systems with advanced
diagnostics

Gas Valve Applications
Residential
Heating
Furnaces, boilers,
water heaters,
fireplaces
Commercial
Rooftop units,
makeup air systems,
commercial cooking
Industrial
Process heating, large
boilers,
manufacturing
Cooking
Ranges, ovens,
commercial kitchens

Gas Valve Sizing Considerations
Critical Factors
•BTU/h capacity requirements
•Gas type (natural gas or propane)
•Inlet pressure available
•Required outlet pressure
•Pressure drop across the valve
•Maximum and minimum flow rates
Proper valve sizing ensures adequate gas flow while maintaining safe operation. Undersized valves restrict flow, while oversized valves
may not provide precise control.

Gas Valve Certification and
Standards
Certification Bodies
Gas valves must be certified by recognized agencies such as CSA, UL,
or AGA.
Industry Standards
Valves must meet ANSI Z21 series standards for gas appliance
components.
Code Compliance
Installation must comply with local and national fuel gas codes.
Testing Requirements
Valves undergo rigorous testing for safety, durability, and performance.

Future Trends in Gas Valve
Technology
Smart Integration
Integration with home automation and building management
systems
Enhanced Efficiency
More precise modulation for improved energy efficiency
Advanced Diagnostics
Self-diagnostic capabilities and predictive maintenance
Remote Monitoring
Cloud-connected valves with remote monitoring and control

Gas Valve Installation Best
Practices
Proper Orientation
Install valves in the correct orientation as specified by the manufacturer,
particularly for valves with gravity-dependent components.
Adequate Support
Ensure valves are properly supported and not stressed by connected
piping.
Electrical Connections
Make secure electrical connections with proper wire gauge and
protection.
Leak Testing
Thoroughly test all connections for leaks using approved methods.

Common Gas Valve Issues
Electrical Problems
Faulty wiring, incorrect voltage, or failed
solenoids
Pressure Issues
Incorrect inlet pressure or regulator
failure
Contamination
Dirt or debris affecting internal
components
Mechanical Wear
Worn diaphragms, springs, or valve
seats

Gas Valve Testing Equipment
Manometers
Used to measure gas pressure at inlet and outlet of valves to verify proper operation and regulation.
Multimeters
Essential for checking electrical connections, resistance, and voltage to solenoids and operators.
Leak Detectors
Specialized electronic detectors or soap solutions to identify gas leaks at connections.

Gas Valve Replacement
Considerations
Exact Replacement
Always use the manufacturer's recommended replacement valve or an approved
equivalent.
Conversion Kits
When changing gas types, use certified conversion kits that include the proper regulator
spring.
System Compatibility
Ensure the replacement valve is compatible with the existing control system and ignition
method.
Documentation
Maintain records of the replacement including model numbers, settings, and test results.

CSA Unit 13
Chapter 2         Understanding
Electrical Control Systems
This presentation explores the fundamentals of electrical control
systems, including terminology, diagrams, symbols, and auxiliary
devices. We'll examine how to read and interpret wiring and schematic
diagrams, understand electrical symbols, and follow the sequence of
operations in control circuits.

Key Terminology
Electrical symbolsLadder diagramPhasingPolaritySchematic diagram
Understanding these key terms is essential for working with electrical control systems. Electrical symbols represent the switches and loads of a circuit. A ladder diagram is the same as a schematic diagram, which is the
basic means of communicating the language of control. Phasing refers to matching the polarity of the primary and secondary sides of a transformer. Polarity refers to the direction of current flow in a DC circuit and to the
differentiation between hot, neutral, and ground in an AC circuit.

Control Circuit Diagrams
Purpose of Diagrams
The control system's schematic and
wiring diagrams are the basis for
determining the specific sequence of
operation as well as for identifying the
electrical connections between safety
controls.
Availability
These diagrams are available in Unit 12
Basic electricity for gas-fired
equipment.
Control circuit diagrams provide essential information for understanding how electrical systems function and how
components are connected. They serve as the foundation for troubleshooting and maintaining electrical systems in gas-fired
equipment.

Wiring Diagrams
Maps of electrical circuits
Very useful for initially wiring a circuit and for troubleshooting
Show exact connections
They show exactly how and where the wires are connected between devices
Component locations
They show, as clearly as possible, the actual location of all the components of a circuit
Standard symbols
The components are usually shown as standard electrical symbols
Wiring diagrams are essential tools for electricians and technicians working with electrical systems.
They provide a visual representation of how components are physically connected in a circuit.

Wiring Diagram Example
Horizontal and Vertical Wires
To make the wiring diagram clearer and easier to follow, all wires are
run either horizontally or vertically.
Wire Connections
When the wires cross, a dot means that the two wires are connected.
If a dot is not shown, the wires cross each other but do not connect
electrically.
This wiring diagram shows the starting and stopping of two motors
complete with running light indication. The layout is designed to be as
clear as possible, making it easier to trace connections when
troubleshooting.

Schematic Diagrams
Definition
The basic means of communicating
the language of control is through the
use of the schematic diagram. This
type of diagram consists of a series of
symbols interconnected by line to
indicate the flow of current through
the various devices.
What They Show
•The power source
•How current flows through the
various parts of the circuit such as
contacts, coils, and overloads
The schematic diagram is intended to
show the circuitry that is necessary for
the basic operation of the system. It
gives no indication of the physical
relationship between the
components.
Also Known As
This schematic is also called a ladder
diagram.

Ladder Diagram Structure
Left-hand side
Represents the incoming voltage
Middle section
Wires and devices connecting the two sides form the "rungs" of the ladder
Right-hand side
Represents the outgoing current; each parallel load will have a separate
connection/rung
From the schematic, you can clearly see how the circuit works electrically and can use it to
trace the electrical sequence of operation. The ladder structure makes it easier to follow
the flow of current through the circuit.

Schematic Diagram
Example
This figure shows the same circuit as the previous wiring diagram, except
it is drawn as a schematic. As you can see, it is much easier to follow the
flow of current in this format. The schematic representation clearly
shows the electrical relationships between components, making it
simpler to understand how the circuit functions.

Series and Parallel Circuits
Series Circuits
The components are connected in such a way that
the electric current must pass through each one in
sequence.
Parallel Circuits
More than one path is available for current flow.
Series/Parallel Circuits
A complete electrical circuit may have some parts
wired in series and others wired in parallel.
Circuits often include more than one device or component. The several devices may be arranged in their circuits in any one of many ways, but any arrangement can be
classified by type of circuits.

Electrical Symbols
Wiring and schematic diagrams use symbols instead of pictures to represent the switches and loads of a circuit. These are the
international symbols for the most commonly used electrical devices in the gas industry. Understanding these symbols is
essential for reading and interpreting electrical diagrams.

Common Electrical Symbols
ComponentSchematic symbol
Disconnect switchI I( I( r--
Circuit breaker1 1 )1 i i i
Limit switch (Normally Open)~
Limit switch (Normally Closed)o<:Jo
Temperature actuated switch~
Pressure and Vacuum switch°1°

More Electrical Symbols
ComponentSchematic symbol
Flow Switch (air, water, etc.)°1:
Liquid Level switch6
Fuses~
Power or Control Contacts0 ~
Instant openingJ\_ T
Iron core transformers~ (YYYl
GroundJ\_

Auxiliary Devices in Control Systems
Switches
Start or stop a system
Relays
Automatically operated switches
Contactors
Control large amounts of current
Protective Devices
Protect against overcurrent
In order for the loads to operate, auxiliary devices must be incorporated into the control system. These devices work together to ensure
the safe and efficient operation of electrical systems.

Switches in Control Systems
Purpose
Switches are the most common
auxiliary device found in control
systems; they are used to start or stop
a system.
Representation
All switch symbols in a wiring diagram
are shown in the "resting" position.
Resting means that the medium (heat,
pressure, etc.) has not caused the
switch to change positions.
Switches are fundamental components in electrical control systems, allowing for the control of current flow through circuits.
Understanding how switches are represented in diagrams is essential for interpreting electrical schematics.

Normally Open (NO) Switches
Normally Open Position
Switches are normally open (NO) when
the resting position of the switch is
open. Typically, actuating switches are
in the NO position.
Switch Position Above the Line
If the NO switch symbol is shown above
the line, the switch will close on a
decrease in the activating medium
(heat, pressure, etc.).
Switch Position Below the Line
If the NO switch symbol is shown below
the line, the switch will close on an
increase in the activating medium.

Normally Closed (NC) Switches
Normally Closed Position
Switches are designated normally closed (NC) when the resting position of the switch is closed. Typically, limit switches are in the NC position.
Switch Operation
NC switches remain closed until activated by their control medium, at which point they open the circuit.
Common Applications
NC switches are often used in safety circuits where the circuit must be broken if a problem occurs.

Multiple Terminal Switches
SPDT Switches
Switches that are SPDT (Single Pole, Double Throw) can be
wired either as NO or NC, depending on the application.
These switches have three terminals, but only two are
typically used.
For example, if wired in NO position, the wire will be
connected to the NO terminal and the common terminal.
Likewise, if wired in the NC position, the wire will be
connected to the NC terminal and the common terminal.

SPDT Switch Wiring Examples
NO Wiring Configuration
When wired as normally open, the circuit connects the common terminal to the NO terminal.
NC Wiring Configuration
When wired as normally closed, the circuit connects the common terminal to the NC terminal.
Versatile Applications
The flexibility of SPDT switches makes them useful in a variety of control applications where different circuit behaviors are needed.

Relays in Control Systems
Definition
In a broad sense, a relay is an automatically operated switch. A switch could
be operated by compressed air, in which case it is a pneumatic relay. For
electric control systems, the relay can be operated by an electromagnet or
solenoid.
In a solenoid relay, the electrical contacts open and/or close when the
contact relay's coil is energized or de-energized in response to a change in
the conditions of the electrical circuit.
The operations of the contacts affect the operation of other devices in the same circuit or in other circuits. Relays allow a low-power control circuit to switch
a relatively high current on or off in another circuit.

Relay Voltage
Considerations
Low Voltage Control
It is quite common for relays to
be powered by 24 V, but they
close a 120 V circuit. This way,
the control circuit can operate
on safer lower voltage wiring.
Voltage Availability
Relays are available in many
coil voltages to suit the
particular application. It is,
therefore, important to check
the relay coil for proper
voltage.
Voltage Verification
Always verify that the relay coil voltage matches the control circuit
voltage to ensure proper operation.

Relay Circuit Example
1
CR1 Relay
One coil (CR1) is located on a
24 V circuit while its contacts
are located in a line (120)
voltage circuit, thus the low
voltage coil controls the
higher voltage contact.
2
CR2 Relay
CR2's coil and contact are
both in line voltage circuits.
3
Voltage Separation
This arrangement allows for safer control of high-voltage circuits
using low-voltage control signals.
This example illustrates how relays can be used to interface between
different voltage levels in a control system, providing both safety and
functionality.

Relay Identification and Ratings
Identification
The switch portion of the relay is
identified the same way as a manual
switch by the number of poles and
throws with an additional solenoid
symbol. The relay terminals would be
labelled to match the schematic
stamped onto the exterior of the relay.
Contact Ratings
The rating for the switch contacts are
shown depending on the voltage they
are switching. These represent the
maximum voltage/current that the
switch can repeatedly connect and
interrupt without overheating or
arcing.
For example, the NO contacts when connected to a 120 V AC circuit are rated for: 1 horsepower (HP), 16 Amps full load (AFL),
96 Amps lock rotor (ALR), and 16 Ohms (0) contact resistance (RES). The solenoid coil rating is also shown as 24 V, 60 Hz 5
VA.

Time-Delay Relays (Timers)
Purpose
There are many reasons for controlling the operation of heating and air
conditioning equipment according to predetermined time intervals.
Terminology
Timing relays may be called by terms such as time-delay relays, timers, and
sequencers, according to their purposes.
Application Example
Sequenced control of several motors is often used in heating and air
conditioning systems to prevent simultaneous starting and excessive current
draw.
Diagram Notation
Time delay relays are commonly denoted in ladder diagrams by "TD", "TDR", or
"TR" designations near the coil symbol and arrows on the contact symbols.

Time-Delay Relay Diagrams
Time-Delay Relay Symbol
This diagram shows how time-delay
relays are represented in schematic
diagrams, with special notation to
indicate the timing function.
Time-Delay Contact Symbol
The contacts associated with time-
delay relays have special symbols to
indicate their delayed operation.
Modern Implementation
Most of the new equipment
manufactured today have integrated
control boards that include all the time-
delay functions needed to operate the
equipment.

Building Automation for
Equipment Coordination
Equipment Coordination Need
When it is necessary to coordinate multiple equipment starting and
stopping, a building automation strategy is implemented.
Centralized Control
Building automation systems provide centralized control of
HVAC, lighting, and other systems in a building.
Sequencing Benefits
Proper sequencing through automation reduces peak
electrical demand, extends equipment life, and improves
overall system efficiency.

Contactors
Definition
Heavy duty contactors are solenoid/armature operators for
switching heavy-duty electrical contacts. They are used to
control the large amounts of current and high voltages required
by industrial equipment.
This figure shows a contactor that might be used to turn on a
three-phase motor on a larger boiler. Note that the insulators
that hold the conductive crossbars are attached to the T-bar
armature that closes several sets of contacts at once.
The wiring diagram shows the switch in the 110 V solenoid circuit that simultaneously activates the 240 V three-phase lines to the
motor. (Overload protectors that are normally located in the motor are not shown in the wiring diagram.)

Protective Devices
Purpose
Protection of the control circuit
against overcurrent protects wiring,
electrical devices, and loads from
short circuit and overcurrent
Fuses
Circuit-protection devices
connected in series with a load
Circuit Breakers
Protect electrical conductors and
equipment from overload and
overcurrent
Reference
Unit 12 Basic electricity for gas-fired
equipment covers the operation of
these protectors in detail

Fuses
Function
Fuses are circuit-protection devices. They are
connected in series with a load. In the event of
excessive current flow, the fuse melts. This opens the
circuit and protects the load device and its supply
conductors from overheating.
Construction
The fuse element is usually made of an alloy such as
silver-tin. This alloy combines the high conductivity of
silver with the low melting point of tin.
Rating
A fuse is rated according to the value of current that
may continually flow through it without causing the
fuse-element to overheat and melt.
Time Characteristic
Fuses have an inverse time characteristic, which
means that the greater the value of a fault current, the
faster the fuse breaks the circuit.

Circuit Breakers
Function
Circuit breakers, like fuses, protect
electrical conductors and equipment
from the effects of overload and
overcurrent.
Applications
The type of circuit breaker shown is
used in low-voltage distribution
systems under 750 V. It is often used
to protect lighting and motor circuits.
Advantage
When a circuit breaker trips to open a
circuit, it can be reset by hand without
replacing any parts.

Polarity and Phasing
Importance
As more and more electronics
are introduced to the gas
industry, two factors have
become increasingly
important during normal
installation and service calls:
polarization and phasing.
Electronic Boards
Some of the electronics
boards being used today, with
flame rectification, will not
function properly - or at all -
unless the polarization is
correct.
Transformer Phasing
Phasing of primary to secondary voltage on transformers: some
electronic boards also require phasing of step-down transformers.

Understanding Polarity
DC Circuits
In a DC circuit, polarity refers to the
direction of current flow.
AC Circuits
In an AC circuit, polarity refers to the
differentiation between hot, neutral, and
ground.
WireDescription
Hot wireAny non-grounded conductor that carries current
Neutral wireCarries current when the circuit is closed
Ground wireIs connected to ground and only carries current when there is a
short to ground in the circuit

Ground Wire Function
Safety Purpose
The ground wire provides a path of least resistance for fault current
Resistance Comparison
The electrical resistance of the grounding wire is less than the
electrical resistance of a human body
Current Path
Electricity travels through the wire to ground rather than through a
person
Protection
This prevents electrical shock hazards when equipment develops a
fault

Determining Polarity - Step 1
Set Meter Range
Set the meter to a voltage range higher
than that of the branch circuit.
Connect Voltmeter
Connect the voltmeter across L1 and N
(L2) at the junction box, as shown in the
figure.
Check Voltage Potential
Determine if there is a voltage potential
between them.
This is the first step in determining the polarity of branch circuit leads - which is hot and which is neutral.

Determining Polarity - Step
2
Connect to Ground
If there is a voltage potential, connect the meter from each wire to
ground, as shown in the figure.
Identify Hot Wire
Determine which is hot (120 V AC reading) and which is neutral
(0 V AC reading).
Wire Designation
On 120 V circuits, L1 is used to designate the hot lead and N or
L2 the neutral.
The lead which shows a 120 V AC reading to ground is the hot wire and is
usually black.

Determining Polarity - Step 3
Disconnect Switch Test
Check the operation of the disconnect
switch to ensure it will turn off the
power on the hot lead.
Verification
After you have disconnected it (turned
it to the off position), you must check
the hot lead to ground.
Expected Reading
There should now be a 0 V AC reading,
confirming the disconnect switch is
functioning properly.

Understanding Phasing
Definition
Matching the polarity of the primary
and secondary sides of a transformer,
phasing, becomes important only
when the secondary side of the step-
down transformer must be grounded.
Application
For example, you must ensure proper
grounding and phasing when the
transformer is connected to certain
types of control modules that use a
flame sensor circuit operating with
flame rectification.
Examples
Some intermittent pilot, direct spark,
and hot surface ignition modules have
one of the transformer terminals
grounded.

In-Phase Transformer
Sine Wave Representation
A sine wave will indicate the polarity of
the current flow at any specific time.
In-Phase Condition
If the secondary side of the transformer
is in phase with the primary, its sine
wave will appear as the small sine wave
which is 24 V positive at the top and 24
V negative at the bottom.
Voltage Difference
If in phase, the difference between the
primary and secondary voltage is 96 V
(120V - 24V).

Out-of-Phase Transformer
Sine Wave Representation
Where the primary and secondary are
not in phase, the sine wave will appear
as shown.
Out-of-Phase Condition
When out of phase, the secondary
voltage is inverted relative to the
primary.
Voltage Difference
The difference in the potential between
the primary and secondary is now 144 V
(120V + 24V).

Checking Transformer
Phasing - Step 1
Identify Hot Lead
Check which lead in the junction box is hot (L1) and connect it to the
black lead of the transformer.
Connect Neutral
Connect the neutral lead (L2) in the junction box to the white
lead of the transformer.
Ground Secondary
Connect one side of the transformer secondary to ground.
You need a voltmeter to check the phasing of a transformer. This
procedure helps ensure proper operation of electronic control modules.

Checking Transformer Phasing - Step 2
Measure Voltage
Check the voltage between the
hot and the ungrounded side of
the secondary.
In-Phase Reading
If the primary and secondary are
in phase, the reading should be
96 V.
Out-of-Phase Reading
If the reading is 144 V, the
primary and secondary are not in
phase.
This step confirms whether the transformer is properly phased for the application.

Checking Transformer
Phasing - Step 3
Adjust If Out of Phase
If the reading is 144 V, move the ground to the other terminal of the
secondary.
Recheck Voltage
Now the reading between L1 and the ungrounded side of the
secondary will read 96 V.
Identify Hot Terminal
You have now identified the proper secondary side terminal to use
as Hot (R).
Once the primary and secondary sides of the transformer are placed in phase,
the hot (R) and grounded (C) side of the secondary can be connected to the
appropriate terminals on the control module.

Labeled Transformer
Terminals
Terminal Labeling
Some transformers have the
secondary terminals labelled C
for common, which would be
grounded when connected, and
R for hot.
Testing Procedure
When checking this type of
transformer, you would test
between L1 and R. If you find it
out of phase (144 VAC), then
you should switch the leads on
the primary (120 VAC)
connections to the transformer.
Result
This will place the secondary labels in phase.

Electrical Sequence of Operation
Importance
As a gas technician/fitter, you must be
able to determine the operating sequence
of gas appliances based on the electrical
circuitry provided by the manufacturer.
Skill Requirement
Since there are many variations on the
type of control systems installed, you will
need a solid grounding in reading wiring
and schematic diagrams so that you can
easily trace the electrical circuitry of any
system.
Understanding the electrical sequence of operation is crucial for proper installation, troubleshooting, and maintenance of gas appliances.

Electrical Sequencing Example
Diagram Components
The circuit for a simple residential warm-air furnace is
shown in the figure and will be used to explain how to read
an electrical sequence of operation.
Wiring Diagram
The wiring diagram on the right shows the electrical
connections between the switches and loads.
Schematic Diagram
The schematic diagram (ladder diagram) on the left is laid
out in order to follow the electrical sequence of operation.
Complexity Note
Control systems for large input appliances will have a more
complex sequence with more interlocks, safeties, etc.

Switches and Loads
Placement
Standard Placement
Switches connected to loads
are normally located on the
hot line - never in the neutral
line.
Exceptions
Occasionally manufacturers
will wire in a switch or load in
the neutral line, in which case
they provide a wiring diagram
showing this arrangement.
Safety Consideration
Placing switches on the hot line ensures that the circuit is fully de-
energized when the switch is open, enhancing safety.

Furnace Circuit Components -
Line Voltage
Circuit and powerSwitchesLoads
Line voltage - 120 VAppliance
disconnect (NC) -
not shown
Fan circuits - 120 VDoor switch (NC)Induced blower
motor (120 V)
Furnace relay
contacts (NO)
Circulating air blower
motor (120 V)
Combination fan
(NO) and limit
control (NC) switch

Furnace Circuit Components -
Control Voltage
Circuit and powerSwitchesLoads
Transformer circuit -
120/24 V
Limit switch (NC)Transformer 120/24 V
Control circuit - 24 VThermostat (NO)Furnace relay solenoid
Flame rollout switch
(NC)
Control module -
Igniter sensor
Vent safety switch
(NC)
- Pilot valve
Air proving switch
(NO)
- Redundant gas valve

Control Module Function
Dual Role
The electronic control module will
have transistors, diodes and a flame
sensing transformer inside of it so it
will act as both a load and a
switching device.
Internal Circuitry
The internal circuitry of control
modules differs with each model
and type. The control module
sequence as indicated represents a
typical example.
Manufacturer Information
Module sequencing information
would need to come from the
module manufacturer, as it cannot
be determined from a wiring
diagram alone.

Furnace Operation Sequence -
Part 1
Power to Transformer
With the door switch and the limit switch in the closed position, the
120/24 V transformer is powered
Thermostat Call
Thermostat calls for heat and the thermostat switch closes
Relay Activation
This powers the furnace relay coil, which in turn closes the furnace
relay contacts
Induced Blower
These contacts then power the induced blower motor

Furnace Operation Sequence -
Part 2
Air Proving
The running of the induced blower will cause the air proving switch to
close
Control Module Power
This powers the control module as the flame rollout switch and vent
switch are normally closed
Safe Start Check
The control module performs safe start check to confirm there is not
already an existing flame
Ignition Sequence
If safe start is indicated, the igniter and pilot valve are powered
simultaneously

Furnace Operation Sequence -
Part 3
Flame Proving
The pilot is proven through the flame sensor
Main Valve
If the pilot is proven, the main valve is powered, and the igniter is
de-energized
Main Burner
At this point, the main burner is firing
Circulating Fan
As the temperature rises to the fan control setpoint, the fan control
switch will close, energizing the circulating blower motor

Furnace Operation
Sequence - Part 4
Continued Operation
The burner will continue to fire until the thermostat is satisfied.
Blower Operation
The circulating blower motor will continue to operate after the
thermostat opens until the temperature drops below the fan
control switch setpoint differential.
System Shutdown
Once the temperature drops below the fan control setpoint,
the system enters standby mode until the next call for heat.
Note: The appliance disconnect is not shown in the diagram but would be
used to completely remove power from the system when needed.

Integrated Furnace Control (IFC)
Definition
An integrated furnace control (IFC)
manages the entire operation of a
furnace, besides the ignition control,
this can include two-stage burner
operation, variable fan speed,
electronic air cleaner, and humidifier
depending on the furnace model.
Sequence Determination
Just as you could not determine the
sequence of events for the ignition
control module from the previous
wiring diagram, you now cannot
determine the sequence for any load
shown connected to the IFC.
The sequence of operation needs to be determined from the operating instructions provided by the manufacturer.

IFC Wiring Diagram
Complex Integration
The wiring diagram shows how
the IFC connects to various
components of the furnace
system.
Multiple Functions
The IFC controls not just basic
heating functions but also
advanced features like variable
speed fans and accessory
components.
Manufacturer Documentation
Due to the complexity of the IFC, detailed operation sequences must
be obtained from manufacturer documentation.
Modern furnace control systems integrate multiple functions into a single
control board, simplifying wiring but requiring more detailed
documentation for service and troubleshooting.

Sequence of Operation Graph
Graphical Representation
Some manufacturers will include a graphical table to explain the sequence.
Layout
The stages are shown across the top row, and the various loads and switches that
change are listed on the left column.
Status Indication
The lines coming out horizontally from each component will move vertically to
indicate a change in their status at the appropriate stage.
Two-Stage Operation
This sequence graph represents a two-stage furnace; components such as the
gas valve, inducer, and blower will have extra upward movement associated with
their lines representing an increase for the second stage of heat.

Heat Mode Sequence Details
1
Standby
System is idle, waiting for call for heat
2
Call for Heat
Thermostat initiates heating cycle
3
Self-Check
System performs internal diagnostics
4
Pre-Purge
Inducer runs to clear combustion chamber (15s)
5
Ignition Warm-Up
Ignitor heats up (17s)
6
Ignition Activation
Gas valve opens, flame established (3s)
7
Heat ON Delay
Delay before blower starts (30/45s)
8
Heating
System runs until thermostat is satisfied
9
Post-Purge
Clears remaining combustion gases
10
Blower Off Delay
Blower continues to run (90-180s)

IFC Component Status During Operation
This chart shows the approximate active time for various components during a typical heating cycle. The exact timing may vary based on the specific furnace model and IFC settings.

LED Status Indicators
Amber LED - 1 flash
Indicates normal operation during call for heat, self-check, pre-purge, and
ignition warm-up
Amber LED - 2 flashes
Indicates ignition activation period
Green LED - 1 flash
Indicates normal heating operation
Red LED (not shown)
Would indicate fault conditions, with number of flashes corresponding to
specific error codes
LED indicators on the IFC provide valuable diagnostic information about the current
operating state of the furnace and can help identify problems when they occur.

IFC DIP Switch Configuration
Adjustable Parameters
The IFC is manufactured to be
used by different furnace models
and makes; therefore; they require
adjustable timing options to
maximize usability.
DIP Switch Functions
The IFC will have DIP switches that
can be used to change some of the
operating parameters such as heat
off delay, trail for ignition, heat on
delay, stage delay (for single-stage
thermostat), and cool of delay.
Replacement Caution
If you replace an IFC, make sure to match the DIP switch configuration to the
original IFC and/or manufacturer's specifications.

Summary of Electrical Control Systems
Diagrams
Wiring and schematic diagrams are
essential tools for understanding
electrical control systems
Symbols
Standardized electrical symbols allow
for clear communication of circuit
components
Auxiliary Devices
Switches, relays, contactors, and
protective devices work together in
control systems
Polarity & Phasing
Proper polarity and transformer
phasing are critical for modern
electronic control boards
Sequence of Operation
Understanding the electrical
sequence is vital for installation,
troubleshooting, and maintenance

CSA Unit 13
Chapter 3                       Servicing
and Troubleshooting Circuits
and Components
A gas technician's/fitter's regular duties include servicing and maintaining gas
equipment. Isolating problem areas, replacing components, and troubleshooting
control problems are learned skills that come with experience. An understanding
of servicing and troubleshooting procedures is essential in building these skills.
Testing circuits may require working with live voltage. Remember to use extreme
caution when doing any live testing. CSA Z462 provides the minimum
requirements that should be followed. Only proceed with live testing if you are
trained, authorized by your employer, and are using all recommended personal
protective equipment.

Control Modules and Manufacturer Approval
Variety of Control Modules
There are many different types of
control modules in use and available
from a wide variety of manufacturers.
Manufacturer Approval
Some control modules are
specifically approved for use with the
appliance and are not
interchangeable with other makes
and models of control modules,
including ones advertised as
universal control modules.
Technician Responsibility
Gas technicians/fitters must ensure
that the correct device is installed as
approved by the manufacturer of the
appliance.

Learning Objectives
Describe the servicing of controls and
components
Understanding how to properly maintain and service
various gas equipment controls and components.
Describe troubleshooting procedures of control
systems
Learning systematic approaches to identify and resolve
issues in gas control systems.
Describe the testing and troubleshooting of
ignition control modules
Understanding specific procedures for testing and
resolving issues with various ignition systems.
Describe the recalibration and the replacing of
components
Learning when and how to properly recalibrate or replace
gas system components.

Key Terminology
TermAbbreviation
(Symbol)
Definition
Sequence of
operation (in
manufacturer's
manual)
Flow chart to
understand the
overall operation of
the appliance from
top to bottom and
assist in
troubleshooting
Understanding the terminology used in gas equipment servicing is
essential for proper diagnosis and repair. The sequence of operation is
particularly important as it provides a roadmap for how the system
should function.

Servicing Controls and
Components: Initial Checks
Clean Electrical Contacts
Use a clean, sturdy paper that is non-oily. Electrical contacts may be
corroded, resulting in failure to close a circuit properly.
Clean Primary Air Vents
Primary air openings may be blocked by lint or other material, affecting
combustion quality.
Replace Dirty Furnace Filters
Dirty furnace filters may cause the furnace to cycle on the limit
control, giving the appearance of a short-cycling thermostat.
In the field of equipment servicing, many appliance malfunctions are due to dirt
and debris accumulated from lack of maintenance. On service calls, before
adjusting, repairing, or replacing components, complete these initial checks.

Servicing Controls and Components: Additional Checks
Clean Pilot System
Blow out or replace the pilot orifice. Failure of
an ignition system may be due to a dirty or
partially blocked orifice.
Clean Burner Orifices
Use a toothpick, never a piece of wire. Low
heat input may be due to a dirty or partially
blocked orifice.
Clean Valve Components
Clean the seat or pivot point in the valve. Dirt
on the seat or pivot point in the valve may
cause a valve to remain partially open.
Proper cleaning of components is essential before determining if replacement is necessary. Many issues can be resolved through thorough
cleaning of key components.

Servicing Controls and
Components: Final Adjustments
1
Readjust to Nameplate
To adjust the appliance input
rate: Change the manifold
pressure, adjust the gas
regulator, or put in new orifice
spuds if greater change is
required.
2
Flush Water
Heaters/Boilers
Remove sediment from the tank
bottom to improve efficiency
and prevent premature failure.
3
Verify Vent Operation
Make sure vents are clear and working properly to ensure safe operation
and proper combustion.
After cleaning components, these final adjustments and checks ensure the
appliance operates at peak efficiency and safety.

Understanding the
Sequence of Operation
A visual representation of the sequence of operation is presented in
manufacturer's manuals. This flow chart can help gas technicians/fitters
understand the overall operation of the appliance from top to bottom
and assist in troubleshooting.
The sequence of operation shows the logical progression of how an
appliance functions, from initial call for heat through ignition, operation,
and shutdown. Understanding this sequence is crucial for effective
troubleshooting.
When a system fails to operate properly, comparing its actual behavior
against the expected sequence helps identify exactly where in the
process the failure occurs.

Troubleshooting Control System
Problems: Tools
Electrical Meters
For measuring voltage,
current, and resistance in
circuits
Manometers
For measuring gas
pressure in the system
Thermometers
For measuring
temperatures at various
points
Flue Gas Analyzers
For testing combustion
efficiency and safety
Troubleshooting control systems requires special tools and instruments. The proper
use of these tools and instruments is directly related to proper diagnosis; in addition,
it minimizes the time necessary for repair or replacement.

Troubleshooting Procedure: Step 1
- Know the System
Study Technical Manuals
In other words, "Do your homework."
Study the manufacturer's technical
manuals. Know how the system
works.
Review Service Bulletins
Keep up with the latest service
bulletins. Read them and then file
them in a handy place. The problem
on your appliance may be addressed
in one month's bulletin, giving the
cause and remedy.
Understand System Operation
Having a thorough understanding of how the system should operate is essential for
identifying when something isn't working correctly.
The first step in any troubleshooting procedure is to thoroughly understand the system
you're working with. This knowledge forms the foundation for all subsequent
troubleshooting steps.

Troubleshooting Procedure: Step 2 - Ask
Questions
When does the shutdown
occur?
Timing of failures can provide
important clues about the cause.
During what part of the
cycle?
Identifying which part of the
operation sequence is failing.
How long after the start-
up?
Duration before failure can
indicate different types of
problems.
Does a shutdown occur after every start?
Consistency of the issue helps determine if it's
intermittent or constant.
How is the light-off?
The quality of ignition can reveal issues with the
ignition system.
Usually, the information available on arrival at the installation consists of a simple statement such as "The burner shuts down."
Start by asking all the questions possible of anyone who might have some knowledge of what happened.

Troubleshooting Procedure: Step 3 - Evaluate
Information
Consult Manuals
Use the supplied manufacturer's manuals
for reference
Review Charts
Check service suggestions and
troubleshooting charts
Apply Experience
Draw on personal experience with similar
issues
Form Hypothesis
Develop initial ideas about possible
causes
Use the supplied manufacturer's manuals, charts, service suggestions, together with your personal experience, to evaluate any information
you have concerning the problem. The conclusions drawn at this stage only provide an idea of where to look for the exact solution to the
problem.

Modern Appliances with Integrated Controls
Operational Parameters
On modern appliances that use integrated controls,
problems can be either operational parameters or faults.
Operational parameters will be discussed in more detail
within the study units related to each specific type of gas
appliance as there are many options depending on
application.
Fault Indicators
Faults are typically shown by way of an LED status light on
the control panel or a touch screen user interface. Units with
integrated controls typically can retrieve previous fault
codes.
Be aware that some appliances recover and display the
latest fault codes on power up. Be prepared to observe the
codes and have the manufacturers' error code chart
available for interpretation.

Troubleshooting Procedure:
Step 4 - Make a Trial Run
Observe the Sequence
Was each step of the start-up according to the design sequence?
Note Deviations
Did any deviations occur from the expected operation?
Verify Shutdown Issues
Did the shutdown occur exactly as described by the customer?
Document Observations
Make notes of any new information discovered during the trial run.
Cycle the burner system and observe its operation carefully. This hands-on
observation often reveals issues that weren't apparent from the initial description.

Troubleshooting Procedure: Steps 5-7
Step 5: Re-evaluate
The re-evaluation of available facts can often be made during the trial run. Look over your list of possible causes and decide which
are most likely and which are easiest to verify.
Remember that in some instances, more than one factor may be contributing to the problem and must be considered in the
solution.
Step 6: Test Your Conclusions
After determining the apparent cause(s) of appliance problem, perform a second test run to see if the evaluation is correct.
If you haven't found the answer, make a new evaluation that includes any new information that has been obtained during the
second test run.
Step 7: Correct the Condition(s)
At this stage, you would be confident in adjusting or replacing the faulty part(s).
Note that not all parts can be adjusted in the field - check with the manufacturer's manual.
Do a final run through to check that the problem has been solved.

Typical Electrical Checks
and Readings
Performing a thorough electrical check on the system allows you to
pinpoint whether the fault is electrical or mechanical. Mechanical failures
include bent, damaged, or seized components such as shafts, rods, and
operators.
The following procedures show how to conduct common electrical tests
in order to isolate a problem. Note that this circuitry is only one of many
you will encounter. On modern equipment, all of the logic and
sequencing circuitry is within electronic modules.
For the purpose of understanding the operation and sequencing of
components, it is best to first study the troubleshooting of older control
schemes as all of the logic can be seen within the actual wiring.

Safety Warning for Live
Testing
Never Work on Live
Circuits Without
Authorization
Never work on live circuits
unless you are authorized and
supervised!
Use Proper PPE
Before proceeding with any
live testing of electrical, ask
yourself if you have all the
personal protective
equipment required to keep
you safe.
Follow Safety Standards
CSA Z462 provides the minimum requirements that should be
followed for electrical safety in the workplace.

Problem 1: No 120V Power
Supply
Check Source Voltage
Check for source voltage by testing A to B and A to G. It should be 120V.
Verify Switch Position
If the switch is in closed (on) position and there is no voltage reading,
check whether the disconnect switch is closed.
Check Circuit Breaker
If disconnect is closed (on), check voltage S to G. If you get a 0
reading, check whether the branch circuit breaker at the main
electrical panel has tripped.
Replace Switch If Needed
If you obtain a 120V reading and switch contacts have failed to
close, replace the switch.

Problem 2: Fan Motor Fails to Run
Check Source Voltage
Check for source voltage in
the junction box. Place a
voltmeter across A to B to
see if 120V are present.
Check Fan Switch
If you obtain a 120V reading
in the junction box, check
the voltage across fan switch
C-D. If the main burner is
operating and the heat
exchanger is above the fan-
on set point, the fan switch
should be closed (on) and
the voltmeter should read
0V.
Replace Switch If
Needed
If the fan switch contacts are
open and the voltmeter
reads 120V, replace the
switch.
Check Motor Terminal
Voltage
Check the voltage at motor
terminal E-G. This should
read 120V to indicate there is
power to terminal E.

Problem 2: Fan Motor Fails to Run (Continued)
Check E to F Voltage
Check E to F. It will read 120V whether or not the motor windings
are good.
Check Motor Windings
To check the condition of the motor windings, disconnect the
wiring from E and reset the meter scale to read ohms. Place the
meter leads across the motor terminals and watch the meter.
•If the ohms scale moves to infinity, the windings are burnt out
•If the reading is 0Ω, the motor windings have a dead short to
ground
•A normal winding would display several ohms of resistance
produced by the large amount of wiring in the motor winding
Note: A voltmeter will display the same 120V reading across a
properly operating motor winding and one that is burned out.

Problem 3: Transformer Secondary Not Powered
Check Source Voltage
Check for source voltage in
the junction box between
the wire connections A to B.
If no power is available, refer
to the troubleshooting
procedure in Problem 1.
Check High Limit
Switch
If you obtain a 120V reading
in the junction box, check
the voltage across high limit
terminals H-I. A reading of
120V indicates the switch is
open. The switch is faulty
and should be replaced.
Check Voltage at
Terminal L
Check the voltage drop
between L-G. This will
indicate 120V if power is
present at terminal L.
Check Primary
Winding
Check J-L. It will read 120V
whether or not the
transformer coil is in good
working order.

Problem 3: Transformer Secondary Not Powered
(Continued)
Check Primary Winding Condition
To check the condition of the transformer windings, disconnect
the wiring from L and reset the meter scale to read ohms. Place the
meter leads across terminals J-L and watch the meter.
•If the ohms scale moves to infinity, the coil winding is broken
•If the reading is 0Ω, the transformer coil has a direct short
•Replace the transformer in either case
•If the coil is all right, several ohms of resistance will register
Check Secondary Winding
Place the meter leads across terminals K-M and watch the meter.
•If the ohms scale moves to infinity, the secondary winding is
broken
•If the reading is 0Ω, the transformer coil has a direct short
•If the coil is all right, several ohms of resistance will register
Note: A voltmeter indicates the same reading across normally
operating transformer windings regardless of whether or not the
windings are good. You must use the ohmmeter to determine the
condition of the winding. Double check that the power has been
disconnected!

Problem 4: Main Burner Fails to Operate
Check Transformer Secondary
Voltage
Check the source voltage at terminals
K-M on the secondary side of the
transformer. It should show 24V. If no
voltage reading is obtained, refer to the
troubleshooting procedure in Problem
3.
Check Thermostat
Check the voltage across P-O of the
thermostat. On a call for heat, the
thermostat contacts are closed, and the
meter reading should be 0V.
If the contacts have failed to close or
the circuit is open (broken/loose wire,
heat anticipator is burnt out), the
reading will be 24V. Replace the
thermostat.
Check Gas Valve Voltage
If the thermostat is all right, take a
voltage reading across terminals N-O of
the gas valve. It will read 24V whether
or not the valve coil is still in good
working order.

Problem 4: Main Burner Fails
to Operate (Continued)
Check Gas Valve Coil
To check the condition of the
valve coil, disconnect the
wiring from N, and reset the
meter scale to read ohms.
Place the meter leads across
terminals N-O and watch the
meter.
Interpret Readings
•If the ohms scale moves to
infinity, the coil is burnt out
•If the reading is 0Ω, the coil
has a direct short
•If the coil is all right, several
ohms of resistance will
register
Take Action
Replace the gas valve if the coil is burnt out or has a direct short.

Testing Intermittent Pilot
Ignition Control Modules
The following testing and troubleshooting procedures provide a general method
for testing intermittent pilot systems. For the purpose of this explanation, the
Honeywell S86 control module will be used.
Although the procedure for testing control modules follows a similar sequence as
outlined below, use the instructions and guides specific to the make and model of
the control module you are testing and troubleshooting.
Preliminary Checks
Initial inspection of power, gas supply, and wiring
System Troubleshooting
Observing system response and identifying issues
Component Checks
Testing specific components to isolate problems

Preliminary Checks for
Intermittent Pilot Systems
1
Check Power Supply
Check the disconnect switch and fuse to the S86 control system.
2
Verify Gas Supply
Check that the manual shut-off valve in the gas line to the appliance is
open.
3
Inspect Wiring
Ensure all wiring connections are clean and tight.
4
Check Lockout Status
Check that the module is not in safety lockout. If it is in lockout, follow
the procedure described for resetting the system after lockout.

System Troubleshooting for
Intermittent Pilot Systems
Start the System
Start the system by setting the temperature controller above room
temperature.
Observe Response
Observe the system response carefully during startup and operation.
Identify Malfunction
Establish the type of system malfunction or deviation from normal
operation by using manufacturer's sequence of operation or
troubleshooting charts.
Continue Checking
Continue checking until a solution, or how to make the repair, is
fully clear to you.

Component Checks for S86 Control Module
Reset System After
Lockout
Procedure to reset the module
before further operation or
checkout
Check Spark Ignition
Circuit
Testing the high voltage spark
generation circuit
Check Spark Igniter
Inspecting the physical condition
and positioning of the igniter
Check Grounding
Verifying proper electrical grounding of components
Check Flame Sensor Circuit
Testing the flame detection capability

Resetting System After
Lockout
S86 Control Module Lockout
If a system with an S86 C, D, G, or H control module goes into safety
lockout (other S86 modules do not offer this feature), reset the
module before attempting further operation or checkout. The
system will remain in safety lockout until it is reset.
Reset Procedure
1.Shut off the system by adjusting the thermostat below room
temperature or adjusting the controller to Off or disconnecting
electrical power.
2.Wait at least one minute, then turn the system on.

Checking Spark Ignition Circuit
The electronic module and step-up transformer in the S86 provide spark ignition at 15,000V (open circuit). You can check this
circuit at the S86 module as follows:
Prevent Gas Flow
Turn off the manual gas
valve to prevent the flow of
gas.
Isolate Circuit
Disconnect the ignition
cable at the S86 stud
terminal to isolate the circuit
from the pilot
burner/igniter-sensor.
Prepare Test Jumper
Prepare a short jumper lead
using heavily insulated wire,
such as ignition cable.
Caution! Do not touch any
bare wires or terminals. This
is a very high voltage circuit,
and electrical shock can
result from improper
handling of the cables.
Test Spark Generation
Energize the S86 while
touching one end of the
jumper firmly to the S86
ground terminal (GND). Do
not disconnect the existing
ground lead.

Checking Spark Ignition Circuit
(Continued)
Create Test Spark
Move the free end slowly toward the stud terminal to establish a spark.
Measure Arc Length
Pull the jumper lead slowly away from the stud. Note the length of the gap
at which arcing stops.
Evaluate Results
An arc length of 1/8 inch (3.2 mm) or more indicates satisfactory
voltage output.
Take Action
Replace the S86 if no arc can be established or the maximum gap is
less than 1/8 inch (3.2 mm) and the fuse and power to the S86 input
terminal are all right.

Checking Spark Igniter and Pilot Flame
Check Igniter Spark-Gap
Check the igniter spark-gap to make certain it is correct: 1/8
inch (3.2 mm).
If necessary, use needle-nose pliers and carefully bend the
tip of the outer electrode to the correct position.
Check Pilot Flame Adjustment
Check that the pilot flame is properly adjusted to cover 3/8
to 1/2 inch (9.5 to 12.7 mm) of the tip of the igniter sensor.
Proper pilot flame adjustment ensures reliable ignition and
flame sensing.

Checking Ignition Cable
1
Check Cable Routing
The ignition cable must not
touch metal surfaces or current-
carrying wires. Use ceramic
standoff insulators, if necessary.
2
Verify Cable Length
Check the length of the ignition
cable, which must not exceed 3
ft (0.9 m).
3
Inspect Connections
Check that connections to the
igniter and control module stud
are clean and tight. (Loose
connections may not conduct a
flame current even though the
ignition spark is satisfactory.)
4
Test Continuity
Check the electrical continuity of the cable.
5
Replace If Damaged
Replace the cable if it is damaged or has deteriorated.

Additional Spark Ignition Circuit Checks
Disconnect Cable at
Igniter
If the spark ignition circuitry
check was all right, yet no
spark or a weak spark occurs,
disconnect the ignition cable
at the igniter (or igniter-
sensor).
Measure Arc from
Cable
Measure the arc from the
cable end to the igniter stud.
Caution! Do not touch either
the exposed end of the
jumper or the stud terminal.
This is a very high voltage
circuit, and electrical shock
can result.
Replace Igniter If
Needed
If the arc is correct, replace
the igniter (or igniter-
sensor).
Test with Jumper Wire
If the arc is less than it should
be, disconnect the ignition
cable and use a jumper wire
from the control module
stud terminal.

Checking Grounding
A common ground is required for the pilot burner, the igniter-sensor, the GND terminal of the S86, and the main burner. The
main burner generally serves as the common ground.
Importance of Good
Grounding
If the ground is poor or erratic,
safety shutdowns may occur
occasionally even though operation
is normal at the time of the
checkout. Therefore, if nuisance
shutdowns have been reported, be
sure to check the grounding
precautions.
S86 System Control
Behavior
Note that if the ground circuit path
is incomplete, the S86 C, D, G, and
H system control will allow one trial-
for-ignition before going into safety
lockout.
Ground Connection Quality
Electrical ground connections at
the pilot burner, igniter-sensor, and
S86 must be clean and tight. If the
lead wire is damaged or
deteriorated, use only No. 14 or 18-
gauge, moisture-resistant,
thermoplastic insulated wire with
105°C (221°F) minimum rating for
replacement.

Checking Flame Sensor Circuit
The control module provides AC power to the igniter-sensor which the pilot burner flame rectifies to DC. If the flame signal back to the
control module is not at least 1.5 microampere (μA) DC, the system will lock out.
Since the output of the flame sensing circuit cannot be checked directly, check the flame sensing circuit indirectly by checking the
flame sensing current from the igniter-sensor to the control module as follows:
Connect Meter
Connect a meter (DC
microammeter scale) in series
with the flame signal ground
wire.
Disconnect Ground
Wire
Disconnect the ground wire at
the control module.
Connect Meter Leads
Connect the red (positive) lead
of the meter to the free end of
the ground wire. Connect the
black (negative) meter lead to
the quick-connect ground
terminal on the control
module.
Read Flame Current
Restart the system and read
the meter. The flame sensor
current must be at least 1.5 μA,
and the reading must be
steady.

Testing Direct Spark Ignition
Control Modules
The following provides a general method for testing direct spark ignition systems
(DSI). For the purpose of this explanation, the Honeywell S87 control module will
be used.
Although the procedure for testing control modules follows a similar sequence as
outlined below, use the instructions and guides specific to the make and model of
the control module you are testing and troubleshooting.
Preliminary Checks
Initial inspection of power, gas supply, and wiring
System Troubleshooting
Observing system response and identifying issues
Component Checks
Testing specific components to isolate problems

Preliminary Checks for Direct Spark Ignition Systems
1
Check Power
Check the power to the appliance and
control module.
2
Check Fuse
Check the fuse on the control module
and replace if necessary.
3
Verify Gas Supply
Check that the manual shut-off valve
in the gas line to the appliance and
the automatic gas valve are open.
4
Inspect Wiring
Make sure all wiring connections are
clean and tight.
5
Check Lockout Status
Check that the module is not in safety
lockout. If it is in lockout, follow the
procedure for resetting the system
after lockout.
6
Inspect Ceramic Insulators
Check the ceramic insulator on the
flame sensor and spark igniter or on
the igniter-sensor. A cracked
insulator will allow current to leak to
ground.
7
Check Flame Sensor Position
Check the flame sensor and its mounting bracket. Correct its position if it is bent out of shape.

System Troubleshooting for Direct Spark Ignition
Start the System
Start the system by setting the temperature controller above room temperature.
Observe Response
Observe the system response during startup and operation.
Identify Malfunction
Establish the type of system malfunction or deviation from normal operation by using the manufacturer's
sequence of operation or a troubleshooting table provided by the manufacturer.
Follow Troubleshooting Chart
Follow the questions supplied by the manufacturer's troubleshooting chart.
Continue Checking
Continue checking until a solution, or how to make the repair, is fully clear to you.

Component Checks for S87 Control Module
Reset System After
Lockout
Procedure to reset the module
before further operation
Check Spark Ignition
Circuit
Testing the high voltage spark
generation circuit
Check Spark Igniter
Inspecting the physical condition
and positioning of the igniter
Check Grounding
Verifying proper electrical grounding of components
Check Flame Sensor Circuit
Testing the flame detection capability

Resetting S87 System After Lockout
S87 Control Module Lockout
If a system with an S87 control module goes into safety
lockout, the module must be reset before attempting
further operation or checkout. The system remains in
safety lockout until it is reset.
Reset Procedure
1.Shut off the system by adjusting the thermostat
below room temperature or adjusting the controller to
Off or disconnecting electrical power.
2.Wait at least 30 seconds, then turn the system on.

Checking S87 Spark Ignition Circuit
The electronic module and step-up transformer in the S87 provide spark ignition at 30,000V (open circuit). This circuit can be
checked at the S87 module as follows:
Prevent Gas Flow
Turn off the manual gas
valve to prevent the flow of
gas.
Isolate Circuit
Disconnect the ignition
cable at the S87 stud
terminal to isolate the circuit
from the igniter or
igniter/sensor.
Prepare Test Jumper
Prepare a short jumper lead
using heavily insulated wire,
such as ignition cable.
Test Spark Generation
Energize the S87 while
touching one end of the
jumper firmly to the GND.
Caution! Do not touch any
bare wires or terminals. This
is a very high voltage circuit
and electrical shock can
result.

Checking S87 Spark Ignition Circuit (Continued)
Maintain Ground Connection
Do not disconnect the existing ground lead.
Create Test Spark
Move the free end slowly toward the stud terminal to establish a spark.
Measure Arc Length
Pull the jumper lead slowly away from the stud. Note the length of the gap at which arcing stops.
Evaluate Results
An arc length of 1/8 inch (3.2 mm) or more indicates satisfactory voltage output.
Take Action
Replace the S87 if no arc can be established or the maximum gap is less than 1/8 inch (3.2 mm), and the power to
the S87 input terminal was all right.

Checking DSI Spark Igniter
Check Igniter Position
Make sure that the spark igniter is
positioned so that the ground
electrode portion of the igniter is not
blocking the gas flow.
Check Spark Gap
Check the igniter spark-gap to make
certain it is correct, 5/32 to 3/16 inch
(4-5 mm).
If necessary, use needle nose pliers
and carefully bend the tip of the outer
electrode to its correct position.
Check Electrode Placement
Immerse only the tips of the
electrodes in the burner flame.
Spacing between tip assembly and
burner head is generally 1/4 to 1/2 inch
(6-13 mm).
Check for bent mounting bracket.

Checking DSI Ignition Cable
1
Check Cable Routing
The ignition cable must not
touch metal surfaces or current-
carrying wires. Use ceramic
standoff insulators, if necessary.
2
Verify Cable Length
Check the length of the ignition
cable. It must not exceed 3 ft
(0.9 m).
3
Inspect Connections
Check that connections to the
igniter and control module stud
are clean and tight. Loose
connections may not conduct a
flame current even though the
ignition spark is satisfactory.
4
Test Continuity
Check the electrical continuity of the cable.
5
Replace If Damaged
Replace the cable if it is damaged or deteriorated.

Testing Hot Surface Ignition
Control Modules
Hot surface ignition systems are used in a wide variety of central heating equipment
and on appliances found in agricultural equipment, industrial heating equipment,
and pool heaters. For the purpose of this explanation, the Honeywell S89 and S890
control modules will be used.
Although the procedure for testing control modules follows a similar sequence as
outlined below, use the instructions and guides specific to the make and model of the
control module you are testing and troubleshooting.
Preliminary Checks
Initial inspection of power, gas supply, and wiring
System Troubleshooting
Observing system response and identifying issues
Component Checks
Testing specific components to isolate problems

Preliminary Checks for Hot
Surface Ignition Systems
1
Check Power Supply
Check disconnect switch and fuse to the S89 or S890 control system.
2
Verify Gas Supply
Check that the manual shut-off valve in the gas line to the appliance is
open.
3
Inspect Wiring
Ensure all wiring connections are clean and tight.
4
Check Lockout Status
Check that the module is not in safety lockout. If it is in lockout, follow
the procedures for resetting the system after lockout.

System Troubleshooting for Hot Surface Ignition
Start the System
Start the system by setting the
temperature controller above
room temperature.
Observe Response
Observe the system response
during startup and operation.
Identify Malfunction
Establish the type of system
malfunction or deviation from
normal operation by using the
manufacturer's sequence of
operation or troubleshooting
chart.
Continue Checking
Continue checking until a
solution, or how to make the
repair, is fully clear to you.

Component Checks for
S89/S890 Control Modules
Reset System After Lockout
Procedure to reset the module before further operation
Check Ignition System
Testing the hot surface igniter and related components
Check Grounding
Verifying proper electrical grounding of components
Check Flame Sensor
Testing the flame detection capability

Hot Surface Ignition Module Operation Phases
Pre-purge
For the S890 only - clears
combustion chamber
Igniter Warm Up
Heating the igniter to ignition
temperature
Trial-for-Ignition
Opening gas valve and attempting
ignition
Burner Operation
Normal running with flame
supervision
The S89 and S890 provide 100% shut-off or safety lockout on ignition failure or on loss of established flame. Modules offer
either one or three trials-for-ignition.

Checking Hot Surface
Ignition System
Check Ignition Wire
Ensure ignition wire does not
touch any metal surface.
Inspect Connections
Connections to the module
and the igniter-sensor must
be clean and tight.
Test Wire Continuity
Ignition wire must provide good electrical continuity.
Proper installation and maintenance of the hot surface ignition system
components is essential for reliable operation. Any issues with wiring or
connections can lead to ignition failures or inconsistent performance.

Checking System Grounding for Hot Surface Ignition
Nuisance shutdowns are often caused in hot surface ignition systems by a poor or erratic ground. A common ground is required for the
module, igniter, flame sensor, and main burner.
1
Check Metal-to-Metal
Contact
Check for good metal-to-metal
contact between the igniter bracket
and the main burner.
2
Inspect Ground Lead
Check the ground lead from the GND
(burner) terminal on the module to
the igniter bracket.
3
Replace Damaged Wire
If the wire is damaged or
deteriorated, replace it with No. 14 or
18-gauge, moisture-resistant,
thermoplastic insulated wire with
105°C (221°F) minimum rating.
4
Protect from Heat
Use a shield, if necessary, to protect the ground wire from
radiant heat.
5
Check Temperature
Check the temperature at the igniter ceramic or flame sensor
insulator. Excessive temperature will permit leakage to
ground.

Testing Integrated Control Modules
Expanded Functionality
Just like the previous ignition control modules, integrated
controls are solid state devices that do not only control the
appliance ignition but also manage all other aspects of the
appliance.
For a furnace, these could include two-stage burner
operation, variable fan speed, variable induced blower
speed, electronic air cleaner, and humidifier.
Boiler Controls
For a boiler, these could be such things as room
temperatures, outdoor air temperature, boiler water
temperature, return water temperature, firing rate,
domestic hot water, boiler pump, system pumps, and zone
water temperatures.
The troubleshooting skills used previously on older wiring
circuits are still relevant for modern electronic controls as
the problem will often be with one of the external switches,
sensors, or loads that are connected to the module.

Troubleshooting Integrated Controls
Common Misconceptions
Far too often, the first assumption is
that the module is at fault when in
fact there is simply a bad
connection to one of the external
devices, or a wiring short has
caused a fuse to burn out.
Fault Analysis
One of the additional benefits of
microprocessor control is their
ability to continually monitor the
appliances operation. When an
error occurs, it can communicate
the fault analysis to the operator via
fault LEDs or a code displayed on a
user interface.
Testing Features
Often the module will test pins for
checking the flame current as well
as a fault code retrieval push
button. Depending on the
complexity of the equipment, the
number of potential faults can vary
greatly.

Fault Code Display Methods
LED Flash Codes
Some modules will display faults using a single LED with
multiple flashes. If the list of errors is short, they can be
shown right on the module.
For appliances with more complex operations and/or
additional external components, the list of codes will
increase. LED Flash code tables show that the LED changes
color to give normal status indicators as well as faults.
Digital Displays
More advanced systems may use digital displays or user
interfaces to show detailed fault information. These can
provide more specific information about the nature of the
fault and potential solutions.
Some systems store multiple fault codes in memory,
allowing technicians to see a history of issues that have
occurred over time.

Recalibrating and Replacing Components
Most controls are factory set or set upon installation of appliances according to manufacturer's instructions. For this reason,
never disturb settings unless you have definitely determined that the appliance malfunction is due to an improper setting.
Readjustment and Recalibration
Some controls may be recalibrated or readjusted on the
owner's premises. Some examples include room
thermostats, heat anticipators, oven thermostats,
improperly operating gas valves, spark ignition electrode
gaps, some pilots, and some solid-state control elements.
Most electronic controls cannot be field calibrated and must
be returned to the manufacturer or replaced.
When recalibrating or readjusting controls, always follow
manufacturer's instructions.
Replacement
Field repair of controls is often not practical. In many cases,
it is cheaper and safer to replace controls than to repair
them. This depends, of course, on the nature of the control
and the repair required.
The solenoid may be replaced on a solenoid valve for
instance, but a broken expansion bulb thermostat could be
replaced for less expense than a repair would cost.
Most electronic controls are not repairable and must be
replaced.

Replacing Electronic Control Modules
Verify the Fault
If the fault is in fact the control
module and it needs
replacement, make sure it is a
manufacturer-approved
matching component.
Compare Components
When it has been unpackaged,
compare it to the existing unit
to ensure the connections are a
match.
Label Wires
Label all the wires before
disconnecting them from the
old module. Taking a picture can
be helpful.
Match Settings
Check the DIP switch settings
on the new module to match the
old one.

Replacement Component
Options
Like-for-Like Replacement
Although this is the simplest solution,
the component may be outdated and
difficult to locate.
Universal Component
The advantages of universal
components are that you can keep a
supply of the most standard ones in
your van and you will also become
familiar with their installation and
operation, thus increasing your
efficiency on the job.
System Upgrade
This option, although more expensive initially for the customer, may well save
them money in the long run. Moreover, standards continue to improve, and so the
homeowner will benefit from current safety standards as well as current research
and manufacturing technology.

Considerations for Component Selection
When replacing components, review CSA B 149.3 for the field acceptance of ignition systems (e.g., from standing pilot to
automatic ignition), automatic safety shut-off valves, pilot-operated safety shut-off valves, and miscellaneous requirements.
Purpose of Operation
The component must serve the same function
Sequence of Operation
Must fit into the existing control sequence
Mechanical Characteristics
Physical operation must be compatible
Electrical Characteristics
Switching actions and amperage ratings must match
Differential Settings
Control ranges must be appropriate
Physical Dimensions
Mounting characteristics and size must fit
Resets
Manual or automatic reset as required
Availability
Parts must be obtainable in a timely manner

Final Considerations for Component Replacement
Ensure Proper Operation
To ensure proper and safe operation of the
mechanical equipment, it is necessary that
field replacement controls and wiring
corrections provide the same operation and
protection as was originally intended.
Consult Manufacturer
Always consult the manufacturer for an
approved replacement.
Follow Safety Standards
Adhere to all applicable codes and
standards when replacing components to
ensure safe and reliable operation.
Proper component selection and installation is critical for both safety and performance. Taking shortcuts or using unapproved parts can lead to
dangerous conditions and equipment failure. Always prioritize safety and manufacturer specifications when servicing gas equipment.

