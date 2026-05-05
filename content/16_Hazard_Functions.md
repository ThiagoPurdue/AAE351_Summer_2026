# Hazard Functions

## Core Principles of Hazard Functions

# 16 Hazard Functions

Hazard Functions
AAE35103 R(t) = Pr TF > t
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
Continuos
RV
~
lifetime
of=time to
failure
on
[0 , 8]
a system
TF modded
wh pdf
f(t)
CDF
RELIABILITY
IMPORTANT
GRAPH
MEAN TIME
TO
FAIWRE
OF TF
j Conditional failure rate: intuition first
3
Recall the conditional probability of an event:
P A | B
(
) = P A ∩B
(
)
P B
( )
B
S
A
I
↑
dis
Prob
. of A
Prob . of A
and
B
over
occurring
,
prob
.
of
given
that
B
occurred
B
To develop
a hazard
function
, we will talk
about
conditional
Failure rate
, but, conditional
on
what ?>Time Conditional failure rate: intuition first
4
Time
t0
t1
t2
nops_ i + n failed _ i = N total
∆"
∆"
#NationalItooperational
FRACTIONofHEMS OPERATIONAL
O
HENS
At
A
GIVEN Time ?
Not O time
to
R(to)
=
Note
= 1
Call
operational)
Notl
hops- 1 oper
NFAILED
- 1
at timet1
Failed & +2
R(te) =
1
< 1
Notal
Hops-2
NFAILED-2
R(t2)
= es-
2
< R(tz)
Nostal
Conditional
Reliability
R(tz (t1)
=
R(t21ts)
= hops-2
-& time +2 O ta
-
R(t1)
hops
- 1
- & tixe to Conditional failure rate: intuition first
5
Time
t0
t1
t2
nops_ i + n failed _ i = N total
∆"
∆"
Fraction operational
per
unit of time ?
We
want
to
know the
Failure
rate
NTotal
and
how
just
the
failure
set expands
.
ufailed
New , -2
how
fail
Hops-1
- I -
&
many
&
per unit of time
normalized
with
new
nfal ed
# operational right
Hops
- 2
before
d - 2
- I
#w=At
I
is the
Feilure rate Hazard function : derivation
6
Consider the conditional probability that  an item will fail between t and t +dt, knowing that it 
was operational/fully functional at time t:
P(t
< T
+
+ At(T > + )
F(t)
=p[( + <Tz + + At)1(5 >+)
↑
P(T > +) ·
=
P( + <TXt +t)
P( + xt)
t
=
F(t + At)
- F(t)
using the CDF
R()
*
K
reliability Hazard function : derivation
7
per
unit of
timeAt ,
we get lin
+ T + + A+ (+ xt)
At
= lim
F(t + At)- F(t) =F
Atto
R(t) At
ProB
.
Dens. Function
= f ==
HAZARD Function
&
Trevinociny -
CONDITIONAL
FAIWRE
RATE
Note : X(t) (t)
Since
R(t) < 1 Hazard function : derivation
8
↓(
=
F(t)
R(t)
The hazard function
says that the
rate of
occurrence
of the
event
at duration + equals
the density
of events
at t ,
divided by the
survaving
to that
duration
who experiencing the event . Hazard function: definition
9
Probability density function f(t):
f (t) = dF t( )
dt
= −dR(t)
dt
It’s the time-to-failure pdf but over a reduced sample space (or normalized with the reliability)
Conditional failure rate or hazard function:
Conditional probability density that an item will fail 
between t and t +dt, knowing that it was operational 
at time t
Representing reliability in this 
way often gives more insight into 
the underlying mechanisms of 
failure
A.k.a.
•
Instantaneous failure rate
•
Hazard rate
•
Force of mortality
λ(t) = f (t)
R(t) Find the failure rate of the exponential distribution
10
Answer: 
The reliability is
Failure rate is
This                       failure rate implies that the system
R(t)
= ( =*dx
=
e
- bt
(d
= cte)
== -de
CONSTANT
DOES
NOT AGE.
-> Failures
not
due to defects or aging rather
failures dre to
random
events.
EX:
A
SPACECRAFT experiencing a
random radiation spike dueto
a
solar storm - malfunction of components,
but failures may
also
increase/decrease
with time . You have probably heard of the bathtub curve…
11
Failure rate of an item as a function of time: bathtub 
curve and the three periods of operations 
      Failure rate or hazard function λ(t):
λ(t) = f (t)
R(t)
λ(t)
Time
0
Failure rate
Infant mortality or
burn-in period
Useful life
Wear-out
period
… it’s in fact the bathtub curve of the failure rate
This is just one model 
of a failure process; not 
all items fail according 
to this model
F(t)
f(t)
Time
R(t) You have probably heard of the bathtub curve…
12
λ(t) = f (t)
R(t)
λ(t)
Time
0
Failure rate
Infant mortality or
burn-in period
Useful life
Wear-out
period
Causes
Mitigation
↓
L
↓
-manufacturing
- aging
- friction
defects
- Fatigue
-
corrosion
- defective design
- burn-in testing
- redundancy
- preventive muintanence
-depends on-parts
replacement
- quality screening
the context 13
Source: A. M. Smith. “Reliability-Centered Maintenance.” McGraw-Hill, New York, 1993
Don’t take these 
numbers seriously
This “bathtub” is 
just one model of a 
failure process; not 
all items fail 
according to this 
model
Bathtub and non-bathtub curves
x(t)
INCHEASINGRese
time
-
FAILURE
I
Const.
Failure rate
SoFUNE
DECLEASING
EWE
MATE
CDFR) Bathtub and non-bathtub curves
14
Source: W. Kuo, M. J. Zuo. “Optimal Reliability Modeling.” Wiley, New Jersey, 
2003
time
λ(t)
Don’t take these too seriously. Just know that bathtub and non-bathtub like failure rate models exist and are 
appropriate for different items Example
15
The reliability of a widget is given by:
R t = & 1 −t
t!
"
for 0 ≤t ≤t!
0
elsewhere
Show that the widgets experience wear-out:
xR(t)
d(t)
is increasing
1
-
Failure
↓(t)
=
F(t)
↓& to
R(t)
O
to
Yt
f(t)
=-
=> x(+) = 2/o(1 - t(to)
2
2
=
=
X(t)/
(1
- t/to)
to (1-t/to)
to-t
~
-
> A()
Increases With time
-
"
-t
=> widget experiences wear-out Derive an expression for the mttf. Explain in words what this 
value means
16
metf
= (RHdt=d
=-/1-
Expected
time to
failure
is
to /3
or
on
average
the widget
will
LAST
to/3. Derive an expression for the median lifetime. Explain in 
words what this value means
17
R()
=
0 .5
1- 05 t = to 1-1
=
0 . 293 t
E
50 %
prob.
that any given widget
is
operating at
that time. Derive an expression for the design life, i.e., the life at which 
the reliability reaches a minimum acceptable value Rmin
18
here
Rmin
is
an arbitrary
selected
number
Rmine R
So ,
we
have
R(t)
= (1
- Eto)" = Rain
t = to (1-Rmin)
design life
YPlot
Rmin
, + (Rmin , to
↑
2 parameters 19
0
0.1
0.2
0.3
0.4
0.5
0.6
0.7
0.8
0.9
Rmin
0
500
1000
1500
Design Life [hrs]
Set t0 = 1,500 hours, and sketch the variation in design life with Rmin
to,----
--
-
I
I
I
I
I
tog-----------------------
↑item
↑
30%
HENS
90% PROB .
Hers work
FAILED
work 20
Discuss qualitatively what factors the manufacturer should consider 
in setting the required design life. In our example we have two 
“levers” we can use to set design life, Rmin, and t0. What does each 
lever represent from a manufacturing or customer perspective?
R min
can
be
used
to
determine
the time for maintenance
=> Szect Rmin
=
Maintenance discussion at time trmin
Fon EX .
Rmin
=
0 .3
=) tos =
700h
Wait untila took to
do inspection/maintenance
or replacement 21
Another formula… -
We have
= -
=-)
= -RH)
S
=
- d(t)dt
= dusdu
=Isaid
= In RH)
- In RIO) = -Cobusdu
=
In RC) = -J du
Iusdu)
= R(t)
=
e
CAN
Calculate
RELIABILITY given An
Arbitrary
Failure Rate Ch 22
From this we see quite trivially that constant λ (as in the 
case of the exponential distribution) implies:
Reliability 
curve:
Cumulative 
distribution 
function (cdf):
Time to failure 
distribution:
R()
= e-budu
- St
=
E
f(t)
=
1
- R(t)
=
1
-
e
-xt
f() = d 23
Example
A machine has the following hazard function:
4 t = 5.002
0 < t ≤200
.001
" > 200
This corresponds to a situation where a device with an exponentially distributed lifetime is 
replaced after 200 h of operation by another, better device also having an exponential lifetime 
distribution.
(a) Determine and graph the reliability function:
RECALL
h(t)
in
the
book
R()
= exp1-10
*
- yu) du
=
exp)
- (0002du) ,
0 < -200
I exp)-10tonda
- 50001du
, +
> 60
200
= (exp(
- 0 . 002 + )
,0+ 3 20
·xp(-0
.2-0. 001t)
, +> 20 24
(b) Determine the probability density function of the machine’s lifetime:
f(t)
= -
I
S
0
. 002
exp
.)
- 0
. 002t)
,
0
< =200
0
. 001
exp (-0 . 001t -0 .2)
,
+
> 200 25
↓
rate of
/
=> higher reliability
Marianence
Went
IfP
↓/
discontinuity 26
(c) Find the mean time to failure:
Mr= metf=RHdt
=
200
exp(-0 , 002t)d+
+ /Op(-0
.002t
- 02)
=> 500(1
- exp(
- 4)) + 1000 exp(-0.4)
=
835
.2h/, 27
Non-constant failure rate systems
• Many systems may not be appropriately characterized by a constant failure rate 
• In such cases, the most commonly assumed hazard function follows a power-law 
dependence of the form
-BB - 1
J()
=
f(t)
= 35t
1
- F(t)
-
0
=
failure
time
constant
Contras
the magnitude
(SCOLE)
B
=
weibull
modulus
conmos
the
sharpe 28
Power law hazard function
1
1.5
2
2.5
3
3.5
4
4.5
5
t
0
0.05
0.1
0.15
0.2
0.25
0.3
(t)
 = 6
 = 1
 = 0.5
 = 3
B = 2 By
3.
↑
Y3 = 0 . S
B)
1
=
INCREASING
↓(t)
with
time
33
=
1
=
Constant
((t)
1
2)
B < 1
=
DECREASING
↓(f)
"
11 29
Weibull distribution
*
is
a
RV
and
has
a
WEIBULL
distribution w/ > 0
and
> 0
If
the
pdf
of
X
is
- (X ;
B , 5)= X
* " exp)-(() ,
x30
S
O
,
X 0
and
the
colf X
is
↑(x ; B
, 5) =
S
1
- exp)
- ())
, X30
O
,
X < 0 30
Weibull distribution
(exponential)
A 13
= 5
= 1
-
-B
= 2
, 5 = 2
M
+3
= 2 , 5 = 0,6
i
17 X
10 Reading
31
Chapter 3.5.1 and 4.8 of Carlton and Devore, Probability 
with Applications in Engineering, Science, and 
Technology, 2nd ed., 2017


## System Integration

Modeling the hazard function, $\lambda(t)$, for the RCUAV requires understanding how 3D-printed materials fatigue over time. Unlike metal, plastics may exhibit an accelerated 'wear-out' phase due to cyclic loading on the layer lines. This hazard function will directly drive the state transitions in your reliability models.
