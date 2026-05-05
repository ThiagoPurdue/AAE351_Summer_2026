# System Reliability

## Core Principles of System Reliability

# 17 System Reliability

System Reliability
AAE35103 Introduction
2
Reliability is one of the core performance measures for any 
system under study
Today, more than ever, reliability is not only expected, but 
is in demand in the market
Reliability is the probability that the item or process 
operate properly for a specified amount of time
To maintain their competitiveness, 
system designers must design for 
reliability and make those system level 
trades early in the designing process
Attempting to improve reliability after 
the system has been designed is a 
costly approach as illustrated in the 
figure to the right showing the cost of 
reliability improvement versus time:
Source: Parnell et al., Decision Making in Systems Engineering and Management, 2nd ed., Wiley, 2011
higher
ONE
ORDER
OF
-
Magnitude Higher
---------------
· Basic system models
3
Most systems are composed of many subsystems, each of which can be composed of hundreds or thousands of 
components
In general, reliability analysis is performed at the lowest levels and the results then aggregated into a system level 
estimate
This is done to save time and money during the development process
System level testing cannot be accomplished until the entire system is designed and assembled
Waiting to test components and subsystems until the entire system is assembled is not time- or cost-effective
Usually, a system’s functional and physical decompositions are used to help construct a system level reliability 
block diagram. 
We utilize this structure to compute system level reliability performance in terms of the component and 
subsystem reliabilities
We will use basic probability concepts to explore the basic structures, series and parallel systems Series system
4
R1
R2
Rn
Let
T, . . . ., Tw
denote
the
comp.
lifetimes
,
and
Ri(t)
= P(T)t)
the reliability
function
of ith component
.
Assume
the
n
comp
.
operate independently
,
i
. e .,
the
Tis
are
independent
RVs
.
Let T
denote lifetime
of
the
series
system. Series system
5
The
system reliability
function
is
R(t)
= P(TXt)
= P)the system's lifetime
exceeds +)
= Pall
N
components
lifetimes
exceed +
= P(T
, < + 1Tz) + 1
.
.
.
. Tw >t) ;
Series
System
= P(T,
<t)
. P(+z) t)
...
P(TN > +)
= Ro(t)
. Rz(t)
...
Rw(t)
= Ri Parallel system
6
R1
R2
Rn
SAME
Assumptions
OF
INDEPENDENT
OPERATION
of
COMPONENTS
The system reliability
function
R()
= P(T > t)
= P)the system's lifetime
exceeds + ( Parallel system
7
= P) at
least
one
component lifetime exceeds t (
=
1 -P (all
components lifetime are + )
=
1
-
P(T ,
< + 1Tzz +
1
.... 1 Tr = + )
=
1
- P(T
, < +)
. P(Tz(t)
... P(TNet)
= INDEPENDENCE
=
1
- [1
- RoCt]]
.
... [1
- RNH)]
= 0- [0-Ri(t) Example 01
8
R1
R2
R3
R4
Given is a series system:
Need R ≥ 0.90. Find minimum Ri for each component.
R = Ri
=
RR
. R
. R
= Ri Assumins Ri
= ce
FOR
ALL i
= 1 ... 4
4
4
70
. 9
Ri
=
0 . 9
~0
. 974
(i = 1
... 4) Example 02
9
Consider three independently operating devices, each with lifetime exponentially distributed with mean 100 
hours and a failure rate " = 0.01/hour. Find the system reliability function if:
(a) Connected in a series:
(b) Connected in parallel:
Ri(t) = exp(
- Xt)
R() = Rit = expl-xt)
= (exp-0
= exp(
- 0 .03t)
R(t)
=
1 - (1
- RiH))
=
1 - (1 - exp(
- 0 . 01t))
=
1
-
(1
- exp(
- 0
. 01 +))3 Example 02
10
(c) Sketch the reliability functions:·
-----
I
I
t
/ hours)
11
100
100
300
400 Example 02
11
(d) Find the probability that the system’s lifetime exceeds 100 hours (i.e., the expected lifetime of a single 
component):
R >(100)
= exp(
- 0 . 03 (100)
= exp(
- 3) =
0
. 0498-5 %
Rp(100)
=
1
- (1 - exp(-0 . 01 (100)))3
=
1
- (1
- exp(
- 1))3
=
0
. 7974
(74 %) Example 03
12
R1
R2
R3
Consider the following system:
Assume the components operate independently. Determine the system reliability function:
P(AVB)
= P(A) + P(B)
- P(ARB)
R (H)
= P([T , <1Tz +] VT3 > t)
= P(T , < + 1Tz <t)
+ P(t>>f)
- P(T ,
< +1 Test 1 +3 st)
= P(T
, st)
. P(izst)
+ P(+st)
- P(T , c+) p(Tz>t)P(tsst)
= R, (t)
. Rz(t)
+ Rs(t)
- R . C)Rz()Ry(t) Example 03
13
If the components have $! % = exp(−0.01%) and mean lifetime of 100 hours (same as last example), write the 
reliability function and find the reliability at the mean lifetime:
R(+)
= [exp)
- 0
.at)]" + [exp(
- 0 .01t)]
- [exp)
- 0
. 01 +)]
= exp(-0 . 02t)
+ exp)
-
0 . 01t)
- exp(
- 0 .03t)
R (100)
= exp)
- 0 . 02
. 100) + exp)
- 0. 01
- 100)
- exp(0 . 03 . 200
= exp(
-2) + exp(
- 1)
- exp(z)
=
0
. 4534(45
, 3% ) Example 04
14
R1
R2
R3
Consider the following system:
Assume:
- Component operate independently
- One component has a Weibull failure distribution with a scale 
parameter ! = 1000 hours and shape parameter % = 2
- The other two have exponential failure distributions with '! =
.005/hour and '" = .0001/hour 
(a) Derive an expression for the system reliability:
-
Rwit)
= exp)
-(
=
exp
-t
Re (+)
= exp(b1t)
=
exp(-0
.003t)
Rez(t) = exp(x2t)
= exp)
- 0 .0001t) Example 04
15
R(t)
= P- (
- Ri(+)
=
n
- [(1
- Rw(t))(1 - Re(t))(1 - Rez(+))]
=
n
- [1
- exp)
-((2)(0
- exp(-0
,00st))()
- exp(
- 0. 000+))] Example 04
16
(b) Compute the reliability of the system for the first 1000 hours:
R11000
=...
...
=
0
. 94020
Eit Reading
17
Chapter 4.8 of Carlton and Devore, Probability with 
Applications in Engineering, Science, and Technology, 2nd 
ed., 2017


## System Integration

The culmination of the RCUAV reliability analysis is combining component-level data into a system-level Markov Chain model. Using MATLAB, you will simulate the vehicle's state transitions over its 100-flight lifecycle, proving to stakeholders that the fully integrated, 3D-printed architecture meets all safety and performance requirements.
