# 09 Introduction to Probability

Introduction to 
Probability
AAE35103
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p1_i1.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p1_i2.png)\n\n2
“It appears incontrovertible that understanding failure plays a key role 
in error-free design of all kinds, and that indeed all successful design is 
the proper and complete anticipation of what can go wrong.”
Henry Petroski
Design Paradigms
Case Histories of Error and Judgment in Engineering
Predictio
before-hand
what
cam go
wrong
in your design is
IMPORTANT.
Drive
your reliability analysis of
your design
and
vehicle
mission.
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p2_i3.png)\n\nSpace Shuttle Challenger disaster
3
“It appears that there are enormous 
differences of opinion as to the probability 
of a failure with loss of vehicle and of 
human life. The estimates range from 
roughly 1 in 100 to 1 in 100,000. The higher 
figures come from the working engineers, 
and the very low figures from 
management. What are the causes and 
consequences of this lack of agreement?”
Richard Feynman, opening of 
Appendix F to the Challenger Accident 
Report
-
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p3_i4.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p3_i5.jpeg)\n\nSpace Shuttle Challenger disaster
4
Complex system
(several
subsystems+ components.... )
Solid
rocket boosters
= 75 %
of trust & launch
Accident
CAUSED by burn-through of
O-Rings
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p4_i6.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p4_i7.jpeg)\n\nSpace Shuttle Challenger disaster
5
ruber
o-rings
seal gap
X
= o
Probability
=> that it will
burn
&
T
through o-rings
BUT
,THERE
ARE TWO
/III E
O-RINGS
-
> ASSUMING THAT THE
FAILURE
↳hot gas Ileft
OFtHE
FinST
O-RiNG
is
INDEPENDENT
Of THE 2nd ONE.
Variation
1 IN REALITY THEY
ARE
KEY Point :
COURELATED I
I N Sufficient
RIGOROUS
ACCESSMENT Of ProB.
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p5_i8.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p5_i9.jpeg)\n\nHow do we go about determining what can go wrong 
and whether and how we should address it?
6
How might we identify problems?
How might we characterize their importance?
How might we figure out how to address these problems?
- TESTING
- LESSONS
LEARNED
- PAST
FAILURES
- Omens ??!
- BrainSTORminG
-
HAVE
CHECKLISTS
- Estimate
likelihood
(VE Probability)
- Estimate
the consequence
- OTHERS ???
- change the design (redundancy
-change
operations
-
cost
benefit analysis
-
OTHERS ???
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p6_i10.png)\n\nCommon expressions in the aerospace community
7
• Reliability of 0.997
• No single point failure mode design
• Must not fail
• Design Assurance Level
oFailure rate 10-x /hour
30
-
>
SAUSSIAN DISTRIBUTION
=> NEED
REDUNDANCY
=>
VERY
HIGH
RELIABILITY
E . G .,
0 . 1 /on
on
/noun
Ens
An Average
Number
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p7_i11.png)\n\nCommon expressions in the aerospace community
8
• Graceful degradation is OK
• Fully redundant system
• Critical function redundancy only
• Faster, better, cheaper
System
will degrade
slowly
over time
=> Indicates
when to replace
=> redundancy of all
components
of
a system
Redundancy of
the parts of the system
that
are citical
for your
mission
e. g.
HAVE
at least
2 engines
our
Alc .
Hard
toFulfill
all , maybe
two
of three.
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p8_i12.png)\n\nOur goals for this module
9
• Understand the application of probability and statistics within 
systems engineering, particularly in the aerospace industry
• Understand the importance of reliability as an engineering discipline 
within systems engineering, particularly in the aerospace industry
• Understand key reliability concepts, such as constant failure rate, 
mean-time-between failure, and the “bathtub” curve
• Introduce different forms of system redundancy, including fault 
tolerance, functional redundancy, and fault avoidance
• Review ways to calculate reliability and the use of block diagrams
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p9_i13.png)\n\nReliability is the probability that the system-of-
interest will not fail for a given period of time under 
specified operating conditions
10
How can we characterize reliability?
FOR
EXAMPLE ,
we
are testing
a motor
, take many
and
run for some
time
I
function
R(t)
of
motors
10-
Y
"A RELIABILITY
Curves
still
GOES
DOWN
As FAILNE
operating = o some continue to
Starts
run for
a
O
-time
long time
t =0
(wone have failed
· Other
WAYS :
Mean time
to/BETWEEN Failure
(M+TF) - how long on average it takes to fail ?
FAILURE Rate -> fixed time , find
how many
on average will fail
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p10_i14.png)\n\nReliability is the probability that the system-of-
interest will not fail for a given period of time under 
specified operating conditions
11
Reliability engineering is a specialty discipline within the systems engineering process 
Reflected in key activities:
Design—including design features that ensure the system can perform in the predicted physical 
environment throughout the mission
Trade studies—reliability as a figure of merit. Often traded with cost
Modeling—reliability prediction models, reflecting environmental considerations and applicable 
experience from previous projects
Test—making independent predictions of system reliability for test planning/program; sets 
environmental test requirements and specifications for hardware qualification
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p11_i15.png)\n\nOur ultimate goal : finding out where the bathtub 
failure rate curve comes from
12
(or cycles)
N-
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p12_i16.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p12_i17.jpeg)\n\nWhere we’re heading? 
13
1. Cumulative distribution 
function of Time to 
Failure
2. Reliability (or survivor) 
function (complement 
of F)
3. Probability density 
function of TF (or simply 
failure pdf)
4. Hazard function (or 
failure rate)
n
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p13_i18.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p13_i19.png)\n\n\n\n![Image](../images/09_Introduction_to_Probability_p13_i20.png)\n\nReading
14
Feynman, Appendix F to the Roger’s Commission Report 
(available on Brightspace)
\n\n\n\n![Image](../images/09_Introduction_to_Probability_p14_i21.png)\n\n