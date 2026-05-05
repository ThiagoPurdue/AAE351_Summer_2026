# 15 Introduction to Reliability

Introduction to 
Reliability
AAE35103
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p1_i1.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p1_i2.png)\n\nObjectives and Outline
2
• Provide a solid conceptual 
understanding of reliability, 
and related issues
• Present fundamental 
analytical methods in 
reliability engineering
Reliability is not an exercise in mathematical analysis, but should always be grounded in a thorough 
understanding of the underlying engineering choices and implications
•
Context and background
•
Reliability
•
Different approaches to reliability
•
Characterizing the failure process: four 
related probability functions
•
Failure rate models
!
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p2_i3.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p2_i4.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p2_i5.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p2_i6.png)\n\nR(t) = Pr TF > t
(
) =1−F(t)
F(t) = P TF ≤t
(
)
f t( ) = dF t( )
dt
= −dR t( )
dt
f (t) = dF(t)
dt
= lim
Δt→0
Pr t < TF ≤t + Δt
(
)
Δt
E TF
[
] = MTTF =
t ⋅f t( )
0
∞
∫
⋅dt =
R(t)⋅dt
0
∞
∫
The three 
pictures to 
keep in mind
We’re finally ready to fill out this picture!
1. Cumulative 
distribution function 
of time to failure
2. Reliability (or 
survivor) function 
(complement of F)
3. Probability density 
function of TF (or 
simply failure pdf)
4. Hazard function (or 
failure rate)
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p3_i7.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p3_i8.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p3_i9.png)\n\nWhat is reliability?
4
Your definition
repeatability
how
often
the
system
will
fail
-
how
well
a system performs
with respect to
specified
criteria
.
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p4_i10.png)\n\nWhat is reliability?
5
Reliability is the probability that an item (component, subsystem, or 
system) or process operates properly for a speciﬁed amount of time 
(design life) under stated use conditions (both environmental and 
operational conditions) without failure
Book Definition
a
lot
of
EXTRA
words ,
important but obscure the
definition
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p5_i11.png)\n\nWhat is reliability?
6
A stripped-down version
RELIABILITY
is
the
probability that
the item
or
process
operates
properly
for
a
specified
amount
of
time.
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p6_i12.png)\n\nWhat is reliability?
7
So, for any given system, the primary parameter of interest is
T
=
the
system
lifetime
=
duration
of
time
until the system
fails
Leither permanently
or
until
repairs/upgrades
are
mades
3
O
T
is
a
continuous random
variable
on [0 , 0]
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p7_i13.png)\n\nWhat is reliability?
8
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p8_i14.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p8_i15.png)\n\nWhat is reliability?
9
Definition
Let T denote the lifetime of some system. The reliability function of T (or of the 
system) is defined for t ≥0 by
R(t)
= P(T > t)
=
1
- F(t)
where
F(t)
is the
CdF of T.
that is
, R()
is the probability that the system lasts
more
thant
time
units .
RH)
is
sometimes
called
the survival function of T.
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p9_i16.png)\n\nIntuitively, what should a reliability curve look like?
10
R(t)
Time
What characteristics must our curve have?
RELIABILITY
DECREASES
high
With TimE
reliability-
It
Goes to
In the
/Erowith
beginning
t=0
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p10_i17.png)\n\nHow does the cdf F(t) look like?
11
the
pdf
f()
:
< FH)
failed-
,thetime
O
t
the
edf
is
found by integrating from
O tot :
I F(t)
1) F(t)↳
O
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p11_i18.png)\n\nAnd, since we have R(t) = 1 – F(t):
12
R(t)
Time
Use our equation for R(t) and plot examples of points for R(0), R(t>>1), and R(t ~ medium)
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p12_i19.png)\n\nHow can we calculate reliability?
13
F(t) = P(T(t)
R(t)
= 1 - F(t)
= fuldu
= 1- Fulda
=Tofuldu
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p13_i20.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p13_i21.png)\n\nHow about going from reliability to the pdf?
14
From the cdf of the time to failure to its pdf:
(t) ==
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p14_i22.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p14_i23.png)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p14_i24.png)\n\nHow might we characterize reliability for a real component?
15
USING
NUMBERS
-
#Of
Components
functioning at time t
- R(t
= + 12)
=
0 . 5 I time
to half
have failed,medium
life'
(
- Failure
rate
-
Mean time
toFailure
(mttf)
=> expected
value of time
to
failure
also,
calculate
the variance
- measure
of
the
UNCERTAINTY of
the
mean time to
failure
\n\nMean time to failure (mttf) is popular…
16
• Relatively easy to determine on a component basis based on test for components that are run continuously or 
for fixed periods of time
• Perform multiple tests and get a significant number of failures to get a distribution
• Compute mean and standard deviation
Tire/road simulator  tester
Shock absorber tester
Multi-axis load tester
http://www.actminc.com/products/Machines.html
A
LOT -
EXPENSIVE
For
AtroSPACE
Set the
WHOLE
CURVE
-
>
APPLICATIONS
OF R()
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p16_i25.jpeg)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p16_i26.jpeg)\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p16_i27.jpeg)\n\nThe mean time to failure or mttf is simply the expectation on T:
17
I
is
a
continuous
RV
in
the
interval
[0
, 0]
mttF
= Mr=(T)
= (t
. f()dt
recall :
E(x) = (*xx(x
\n\nWe’d like to be able to calculate mttf directly from R(t):
18
metF
= (tridt
=-]d
recall :
INTEGRATE
By Parts :
= [R() +]o-17 RAI It
Jh(x)g(x,dx
10
11
.0
= hexg(xs
-fixx)g(x)dx
= [limRt-limRt]) (t)dt
L
O
=
0
+
0
+ )R()dt
= foRIH de
\n\nRelation to failure rates
19
A lot of reliability calculations assume that the failure rate is constant
It makes calculations simple (mttf fully characterizes the distribution)
It is applicable to many cases (which part of the bathtub is it?)
A constant failure rate corresponds to an exponential distribution  (Next time you will be able to show that 
yourselves!)
bathtub
OVE
- ~
We rate
the
DISTRIBUTION
ExportSee
Fatigue is
Constant
described by
defects
7
Weiball distribution
Flaws
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p19_i28.png)\n\n20
Reminder : Exponential random variables
x
fX
How does this graph change as lambda decreases?
An exponential random variable X has the following pdf:
fX (x) =
λe-λx      for x ≥0
0            elsewhere
 
 
 
Verify that fX is a “legitimate” pdf
Calculate the mean and standard deviation of X
&
=
rate
at
which
events
occur
#(X) = 1/ ) , WAR = 1/12
= (x)
= 1/ =(X)
X = 2,0
highera
-
> EVENTS
CLUSTERED
L
AROUND
①
lower X
-
EVENTS
2x =0 . 5
SPREAD our
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p20_i29.png)\n\nNow consider an exponential random variable where x is the time to failure
21
T
them,
-xt
Xe
+ 20
fr (+ )
=
S
O
S
OTHERWISE
where
,
X
=
failure
rate
\n\nMean time to failure : example
22
The time to failure of a light bulb is modeled with the following pdf:
f (t) = 0.002e−0.002t        t ≥0
0                        otherwise
 
 
 
(t in operating hours)
1. What is the mean time to failure of such a light bulb? Interpret this result (what does this number mean)
1 =
0
. 002 hd
mEF : E(tr)
= 1
. FHdt=
c*+
= Y=)
On
average ; these light bulbs will last
soon
which
is
rather
short
compared to
light bulbs
NOWADAYS.
\n\n\n\n![Image](../images/15_Introduction_to_Reliability_p22_i30.png)\n\n2. What is the reliability for the light bulb at mttf?
23
R(t)
=
1
-
F(H)
=
1
- ( f(u)du
=
1-)de-
u
-xt
-Xt
=
1 -)
- y+))"
=
e
+
1
-
1
=
e
&Int- 00021500
=
0. 367
=
36,7 %
that's
word ?! What is happening?
- Even though
metF = sooh
, only
36.7 % make it to
sooh , which is
much
less than
50%
= It makes
sense
since
we
have
a
exponential distribution
and I
is
low
=> zenis
are
spread
out
\n\n3. What is the median life of the light bulb?
24
medium
life
is
where
?
R()
=
0 . 5
-000t
e
=
0 . 5
- port
= In (0 . 5)
=
346 . h -
\n\nReading
25
Chapter 4.8 of Carlton and Devore, Probability with 
Applications in Engineering, Science, and Technology, 2nd 
ed., 2017
\n\n