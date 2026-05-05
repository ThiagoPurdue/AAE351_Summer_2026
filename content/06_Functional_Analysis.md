# Functional Analysis

## Core Principles of Functional Analysis

# 06 Functional Analysis

Functional Analysis
AAE35103 In this lecture, we discuss the concept 
definition phase
2
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
CONCEPT ->
ENGINEERING
DEVELOPMENT
DEVELOPMENT
I
I
I
I
IMPLEMENTATION
1
Of
HARDWARE And
S
I
SOFTWARE
I
Specify the architecture of system concepted including the components.
I System materialization at the concept 
definition phase
3
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
#y
This
is
where
system
Define functions and high-level architecture
concept
STARTS
to be
ENGINEERED
of system
and
Major components. Concept 
definition 
phase flow 
diagram
4
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
RELATE
TO
OPERATIONAL
OBJECTIVES
DEVELOP
·ARCHITECTURE
SELECT
BASED ON
O
FUNCTIONAL
PERFORMANCE
, COST ,
TRADE-OFF
STUDIES OF
-
"
COSELY
Risk
-
COUPLED
DOES SYSTEM MEET
-
>
requirement? Describing the system functions
5
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
• Functional system building blocks
• Functional interactions
• Functional analysis products
o Functional flow diagram (FFD)
§
Functional Flow Block Diagram (FFBD)
o Integrated definition (IDEF) method
§
IDEF0 => see figure on left
o Functional block diagram (FBD)
o Sequence diagram (SD)
=> ATTRIBUTES :
SPEED, ACCURACY,
CAPACITY...
SIGNALS , DATA , MATERIALS, ENERGY ,
FONCE
INTERCONECTION TO
OTHER ELEMENTS AND
EXTERNAL
CONTROLS
& ENERGY
*
I
GETS
SENTTO
THE DESIGN
↑Engineer
TOLLS
to
DESCRIBE THE
SYSTEM
AND COMPONENT
FUNCTIONALITY Standard coffee maker example
6
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
• Input functions
• Accept user command (on/off)
• Receive coffee materials 
• Distribute electricity
• Transformative functions
• Heat water
• Mix hot water with coffee grinds
• Filter out coffee grinds
• Warm brewed coffee
• Output Functions
• Provide Status
• Facilitate removal of materials
• Dissipate heat
FUNCTIONS of
A
STANDARD
Coffee
MAKER Standard coffee maker example
7
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
SIGNAL
-
> MATERIAL
Functional Block
DIAGRAM
I
& ENERGY
( FBD(
-
EXTERNAL
Entities&
unt Energy
,once
A Standard coffee maker example
8
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
Materials
Receive coffee materials
Mix hot water with coffee grinds
Filter out coffee grinds
Facilitate removal of materials
Data
Provide status
Signals
Accept user commands
Energy
Distribute electricity
Heat water
Warm brewed coffee
Dissipate heat
Force
Distribute weight
CAN Categorize
FUNCTIONS
INTO
FIVE
BASIC Elements : Functional flow block diagram (FFBD)
9
1. Formulate the overall 
product function
2. Split overall function into 
sub-functions
3. Determine a simplified 
function structure
4. Identify material, energy, and 
information/signal flows
5. Add secondary/auxiliary 
functions and flows
BREW
-
OVERALL
~
- Coffee
-
FUNCTION
-
-
-
-
- ------
-
--
-
-
MATERIALS
-
-
-
- freciced
SUPPORTING
WATER
STORE
HEAT
HEAT
-
> WATER WATER
COFFEE
SUB-FUNCTIONS
↓
I
COFFEE
GROUND " &
S
=>
MiX COFFEE
STORE -
TORE
Coffee -
GROUNDS
AND WATER - COFFEE
, output
..........
F
- - ---- t
- +-
I
GRIND
STUT-OFF
I
USE BASIC
ELEMENTS
"
BEAMS
HEATER
I
- ---------- Functional flow diagram (FFD)
10
System functions:
F1.  
Accept user command (on/off)
F2. 
Receive coffee materials
F3. 
Distribute electricity
F4. 
Distribute weight
F5. 
Heat water
F6. 
Mix hot water with coffee grinds
F7. 
Filter out coffee grinds
F8. 
Warm brewed coffee
F9. 
Provide status
F10. 
Facilitate removal of materials
F11. 
Dissipate heat
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
↳
CONCERNED
WITH
HOW THE
ELEMENTS
ALE
CONNECTED
AND
THEIR
ORDER
(THE
FLOW)
- Fg
-
> F3T
START- > F1 -
> F2
AND
AND -F5-F6-F2-F8-AND-F10-AND >END
↑
&in t
-F11
Function
VFEEDBACK
Loop Sequence diagram (SD)
11
System functions:
F1.  
Accept user command (on/off)
F2. 
Receive coffee materials
F3. 
Heat water
F4. 
Mix hot water with coffee grinds
F5. 
Filter out coffee grinds
F6. 
Warm brewed coffee
Kossiakoff et al., Systems Engineering Principles and Practice, Third ed., Wiley, 2020 
FOCUSED ON
Specific
Capability
Limited
to
specific
Scenarios
ORDER
OF
ACTIONS
DOES
MATTER
F1
F2
F3
Fu
FS
FG
Command
-
>
MATERIALS
=
MEAT
->
Grinds
3
HEAT
-
FBD
AND/OR
FED
ASSIST IN
CONSTRUCTING
A
SD. Starship delivery functional analysis
12
• Your system is rarely doing just one thing at a time
• Need to capture all the different activities that are happening concurrently as well 
as in sequence
• Example: Starship delivery robot
Deliver 
Coffee
Transport 
Coffee
Store 
Coffee
Give 
Coffee
Store 
Energy
Interface 
with App
Image credit: IEEE Robotics
THE SYSTEM
OVERALL FUNCTION
--------B
-
FUNCTIONS
----------
AUX .
FUNCTIONS
&TOP LEVEL, FUNCTIONAL
FLOWS
BLOCK DIAGAm Starship delivery functional analysis
13
-Store Coffee / Energy
Store Coffee
Lock door
Insulate 
Payload
Hold cup 
in place
Store Energy
Monitor 
energy
Accept 
electrical 
energy
Maintain 
energy
Fully 
charged?
Low power 
warning
Make energy 
available for use
N
TOP
LAYER
TOP
LAYER
-------------------
-
-
----------
↓
AUX
2ND
LAYER
LAYER
---- -
DETAILS
OF
THAT
FUNGION
↳MAY
NOT BE
NEEDED Starship delivery functional analysis
14
Sense local 
environment
Detect 
obstacles
Determine 
position
Perform 
path 
planning
Determine 
control 
inputs
Supply 
motive 
power
Transport 
Coffee
(Repeat until at 
destination)
Store 
energy
Connect 
with App
Store 
Coffee
Get 
destination
Move 
Coffee
NEEDED BECAUSE YOU
WON'T
DO ALL IN ONE
- Step
FEEDBACK Loop
GPS
3
4
S
7
2
↑
OBSTACCE
AVOIDANCE
L
1
O
6
INFORMATION
<
FEEDS
INT
>
FUNCTION Starship delivery functional analysis
15
Give Coffee
Unlock 
door
Interface 
with App
Arrived 
Coffee
Wait for user 
to close door
Say “Boiler 
up!”
Customer 
has coffee
Coffee
Return to 
base
N
Y
4
1
2
3
These
functional diagrams
will help you to generate
REQUIREMENTS. In conclusion
16
• Functional analysis is a useful way of identifying requirements
• Functions are not the same as subsystems but can help us identify 
system concepts
oConcept generation and selection (last lecture) Reading
17
Chapter 7 of Kossiakoff et al., Systems Engineering 
Principles and Practice, Third ed., Wiley, 2020
Anon, Chapter 5 Functional Analysis and Allocation 
of Systems Engineering Fundamentals


## System Integration

Functional decomposition of the RCUAV forces us to break down 'Deliver Cargo' into sub-functions like 'Generate Lift', 'Provide Thrust', and 'Maintain Structural Integrity'. In System Composer, these functions must be modeled logically before they are allocated to specific physical components, ensuring that the 3D-printed airframe adequately supports all avionics and payloads.
