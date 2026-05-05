# Discrete Random Variables and Distributions

## Core Principles of Discrete Random Variables and Distributions

# 13 Discrete Random Variables and Distributions

Discrete Random Variables 
and Distributions
AAE35103 Intuition First
2
Weapon accuracy is defined as the point of impact for a 
given aim point at the target
The distance between the point of impact and the aim 
point is a random variable.
The precise magnitude of this distance cannot be 
predicted in advance. Why do you think this is the case?
However, some general characteristics of its 
“randomness” can be estimated.
Weapon performance parameters:
- accuracy
- cost
- reliability
-range
- effectiveness
- time to target Weapon system performance
3
Aiming 
point
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
Impact 
point
Weapon performance parameters: 
Accuracy and the dispersion plane
•
Set up an experiment to test and measure the accuracy of a new heavy machine-gun
•
Let D be the distance between the aiming point and the impact point: How can you characterize the “randomness” of D 
given the data you have collected from the experiment? 
Lockheed AC-130 Gunship
D2
↑n
Fan Weapon system performance
4
Assume you fired 100 rounds. You measure D in increments of 1 m from the aiming 
point (i.e., number of rounds between 0 and 1 m (in the first bucket, number of 
rounds between 1 and 2 m (second bucket), … )
How can you represent / visualize the data you obtain?
D = {1,1, 2, 2, 2, 3, 3, 3, 3, 3, 4, 4, 4, 4, 4, 4, 4, 4, 4, 4, …}     Not very compact
What can you say about this new machine 
gun? Is it accurate? Not accurate? Can you 
quantify its accuracy? How?
What can you say about the central 
tendency of the random variable D?
x
x x
x
x
x
x
x
x
x
x
x
x
x
x
x
x
x x
x
x
x
x
x
x
x
x
x x
x
1
2
3
4
x
x x
x
x
x
x
x
x
x
x x
x
x
x
x
x
x x
x
x
x x
x
x
x
x
x
x
x
x
x
x
x
x x
x
Frequency (or sample) histogram
Number of 
impacts 
within…
… D (m)
0-1
2
1-2 2-3 3-4 4-5 5-6 6-7 7-8 8-9 9-10
3
5
10
15
20
17
13
10
5
w
-
↑
Tanger
D = O m Analyzing weapon system performance
5
Empirical average of D:
Frequency (or sample) histogram
Number of 
impacts within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9
9-10
3
5
10
15
20
17
13
10
5
D = {1,1, 2, 2, 2, 3, 3, 3, 3, 3, 4, 4, 4, 4, 4, 4, 4, 4, 4, 4, …}
000
= Dil = (d +D.DI Frequency (or sample) histogram
Number of 
impacts within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9
9-10
3
5
10
15
20
17
13
10
5
Analyzing weapon system performance
6
D = {1,1, 2, 2, 2, 3, 3, 3, 3, 3, 4, 4, 4, 4, 4, 4, 4, 4, 4, 4, …}
fi  = how many 
 
rounds in bucket i
f6 = 20
Or, in another way:
-
&
FG
= 20: D =
f1D1 + f2D2 + ...+ fNDN
(
)
f1 + f2 + ...+ fN
=
fiDi
i=1
N∑
fi
i=1
N∑
Frequency (or sample) histogram
Number of 
impacts within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9
9-10
3
5
10
15
20
17
13
10
5
Analyzing weapon system performance
D = {1,1, 2, 2, 2, 3, 3, 3, 3, 3, 4, 4, 4, 4, 4, 4, 4, 4, 4, 4, …}
Empirical average of D:
What is this?
We can define a “relative frequency” of the observation of D:
Frequentist 
interpretation of probability: 
when N à ∞, relative 
frequency “becomes” 
probability
= DD
N... FN . DN
-
N
N = 100
#
Number
of Rounds
FIRED
Pi =Pi
= 1.0 ; Di10
N-0
Di = #
is
the probability 8
What are some other examples of random variables in our world? 
How would you go about measuring / characterizing their randomness?
Notice for all these “random variables,” there is are underlying 
notions of experiment, range, and observations
Experiment
Sample space
Event A
Event B
Probability
P(A)
P(B)
Events
- ONE-TIME
PUSH
BACK
Of
An
AIRPLANE
- NUMBER
OF
CELL
PHONE
CALLS
YOU
ANSWER
TODAY
- TIME
BEFORE I
LOSE
MY
KEYS
: Formal definition of a random variable
9
A random variable consists of an experiment with a probability measure P(.) defined on a sample 
space and a function that assigns a real number to each outcome in the sample space
A random variable is a real-valued function of an experimental outcome
For a given sample space S of some experiment, a random variable is any rule that associates a 
number with each outcome in S Another way of defining a random variable
10
Random variables: My definition
The “variable” in “random variable” can be misleading. 
It’s not like what you’ve seen in (deterministic) 
calculus…
1.
Notation: a random variable will always be assigned a 
capital letter (e.g., X)
2. Not normally treated as a numerical value
3. It’s a bundle k and P(k) for a whole range of 
X; think of it as X = {k; P(k)}
4. It’s a function that assigns a numerical value to each 
possible outcome of an experiment
5. Notice the difference between the random variable X, 
and the outcome or observed value of the random 
variable, k (often noted as x)
6. When we write P(k), this is shorthand for 
 
P(X = k), that is the probability that X takes on the 
value k 
!
2 P(X =()
= 1 .0)
↑
X
=11
0 .2S
2
0,05
&
ALL
30
, 5
70
4
0
. 17
5
0 .03 3
↑
↑
K
P(X = k)
OUTCOMES
PROBABILITIES 11
Let’s apply this to our weapon accuracy example
Our random variable is the bucket containing the distance between the target and the impact
It’s a bundle k and P(k) for a range bin of D 
 
The function assigns a numerical value to each possible outcome of the experiment. In our 
example, the distance could go from 1 m to 10m
Frequency (or sample) histogram
Number of 
impacts within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9
9-10
3
5
10
15
20
17
13
10
5
D = 4k
; p(k)] Discrete and continuous random variables
12
!
Notation:
Random variable, X
Outcome or observed value of the 
random variable, k (often noted as x)
Continuous random variable
Y is a continuous random variable 
if it can take any real number y in 
an interval a ≤ y ≤ b
Example: push-back time
Discrete random variable
Set of possible outcomes can (in 
principle) be listed
X is a discrete random variable if the 
range of X is a countable* set SX = 
{k1; k2; k3;…; kn}
Example: number of phone calls you 
will receive today
• It can be finite or “countably infinite”,
      e.g., 0, 1, 2, …
-
Eme We can use a probability mass function (pmf) to characterize 
a discrete random variable
13
pmf of X (capital letter X, it’s the pmf of the random variable), 
denoted by PX(k) or P(X = k),
is the probability of the event X = k
PX(k) is explicitly defined for all real numbers, including all values that X 
could never take; it assigns such values a probability of zero
for
my
puf
,
we
have
P(X = K)20
and
EP(X = K = 1 .0
all K Follow these steps to calculate the pmf of a random variable, X
14
How to calculate the pmf of a random variable X:
1.
Collect all possible outcomes that give rise to the event X = k
2.
Add their probabilities to obtain PX(k) What’s the pmf of the weapon accuracy random variable?
15
How to calculate the pmf of a random variable X?
1. Collect all possible outcomes that give rise to the 
event X = k
2. Add their probabilities to obtain PX(k)
Frequency (or sample) histogram
Number of 
impacts 
within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9 9-10
3
5
10
15
20
17
13
10
5
PD(K)=0
1
k = 1
I
I
1 k
= 2
Pe =z =
(k = 1
:
↳
,17 = 10
100
O
&
OTHERWISE < HAVE
NO
DATA Probability mass function (pmf): Theorem
16
4.
For any
K
,
P(x = K), 0
2. [ex (k) = 1 .0
all K
3.
Assume
event
B = [K :; kid
them
P(b)
= Py(k1)
+ Px(kz)
more generally
,
for
any event
B2SX
P(B)
= [Px(k)
all
17 => B Average or central tendencies of random variables
17
The average or central tendency of a random variable (or a collection of numerical observations) is 
a statistic of the collection, a scalar or a single number, that “summarizes” the information of all k, 
and P(k) for the random variable X
Frequency (or sample) histogram
Number of 
impacts 
within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9 9-10
3
5
10
15
20
17
13
10
5
Different measures of central tendencies:
1. Mode
2. Median
3. Mean or expected value
Mode
Median
Mean
-
> most frequent
-
> splits data
m half
-
> average value Average or central tendencies of random variables
18
Frequency (or sample) histogram
Number of 
impacts 
within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9 9-10
3
5
10
15
20
17
13
10
5
Different measures of central tendencies:
1. Mode
2. Median
3. Mean or expected value
Mode: Most common number in the collection of observations. 
It need not be unique. If there is more than one number with 
this property, the collection is called multi-modal:
kmod is a mode of the random variable X iff:
-
P (kmodePx(K) Forall K
↑K mode = 6
NOTE
IfFIF
AND
ONLY
If Average or central tendencies of random variables
19
Frequency (or sample) histogram
Number of 
impacts 
within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9 9-10
3
5
10
15
20
17
13
10
5
Different measures of central tendencies:
1. Mode
2. Median
3. Mean or expected value
Median: Midpoint of a set of measurements. Defined to be 
the middle value when measurements are arranged from 
lowest to highest
kmed is median of the random variable X iff:
55/100
65/100
-
-
Rx(Xkmed)0,51
= SAMPLES
BEFORE
# SAMPLES
PX(X = kman),
0 ,5
k = =
20
AFTER
Es
k = 6
35
45
K : 7
55
38
=>
CAN't
SpuiT
EQUALLY
=> USE
Our
Definition
k = 6
35 + 20
45 + 20 Es
Satisfy Definition
mas = 5. 01,
=
53
= 65 Average or central tendencies of random variables
20
Frequency (or sample) histogram
Number of 
impacts 
within…
… D (m)
0-1
2
1-2
2-3
3-4
4-5
5-6
6-7
7-8
8-9 9-10
3
5
10
15
20
17
13
10
5
Different measures of central tendencies:
1. Mode
2. Median
3. Mean or expected value
Mean or Expected Value: µX or E[X]
Think of it as the “center of gravity” of the pmf of a random 
variable
E[x]
= Mx = k
. Px(k)
What
we get is the
"CENTER
of
mass"
of
the
pmF
,
or
the
mean value
. Beyond central tendency of a random variable: Need a 
measure of dispersion. Why?
21
Frequency histogram for M1
Incremental 
Number of 
impacts 
within…
… D (m)
1
2
3
4
5
6
7
8
9 10
25
20
15
10
5
25
20
15
10
5
Frequency histogram for M2
Incremental 
Number of 
impacts 
within…
… D (m)
1
2
3
4
5
6
7
8
9 10
60
10
5
60
10
5
E[DM1] = E[DM2]  yet …
Which one will you put on the new airplane you designed?
OI
[
Which
one
do
Smaller spread
& lot
of
spread
you
but
none
dose
but
some
close to
Select ?
very
to target
.
the target Beyond central tendency of a random variable: Need a 
measure of dispersion. Why?
22
Frequency histogram for M1
Incremental 
Number of 
impacts 
within…
… D (m)
1
2
3
4
5
6
7
8
9 10
25
20
15
10
5
25
20
15
10
5
Frequency histogram for M2
Incremental 
Number of 
impacts 
within…
… D (m)
1
2
3
4
5
6
7
8
9 10
60
10
5
60
10
5
The variance, or its close relative, the standard deviation, is a single number that somehow measures the 
dispersion of a random variable around its mean. Think of it as addressing the following questions:
•
How typical is the average?
•
What are the chances of observing an event far from the average? Variance, standard deviation, and moments of a random 
variable: Definition
23
1.
Define a new random variable: Y = X - μX
2.
What is Y?
3.
What is E[Y]?
4.
E[|Y|] can be a good measure of dispersion of X around μX …
5.
… but it is not easy to handle mathematically.
6.
We need something ≥ 0, take Y2
Standard deviation of a random variable X is:
The variation of a random variable X is:
distance
of
X
From
the
mean
Average
distance
From
Mx
(either directions)
INDEPENDENT Of
DIRECTION
not
a smooth
function
- 70
Nar[X]
= ELY"]
= El (X-MX1j-UN
is the UNIT of
X
SQUARED
~ UNIS THE
SRME
Of X
6 x
= VAR
IX]
=
mean Distance from the
mean
"TYPICAL"
VALUES
Of X
ARE
Within [Mx-6x
, Mx +GX] 24
Example: Consider the random variable X with the following pmf:
PX (x) = 1/9  if x is an integer in the range [−4;4]
0     otherwise
 
 
 
1. Calculate E[X]
2. Define a new variable Y2 = (X – μX)2
3. What is the pmf of Y2?
4. Calculate the variance and standard deviation of X
-
1) E[X] =
k
. P(x = k)
=-4-3-2
+3
=0
= MX
2)y = (X
- ux)" = X 25
Example: Consider the random variable X with the following pmf:
PX (x) = 1/9  if x is an integer in the range [−4;4]
0     otherwise
 
 
 
1. Calculate E[X]
2. Define a new variable Y2 = (X – μX)2
3. What is the pmf of Y2?
4. Calculate the variance and standard deviation of X
P(x) =k))
=
16
2/g
--
I
9
,
219
a
,
219
1
,
219
↑
↑
·
-
0
,
119
OUTCOME
ProBABILITY
4) VR[x]
= E[y] = EKP(y= KY)
=
16
. 2/9 + 9
. 2/9 + ..
. .
0
./9
= 60/9
8x = Via = Vote, 26
The variance of a random variable X is defined by:
It can be calculated by:
It is always ≥ 0. Its square root is the standard deviation of the random variable 
VAR [X]
= Ei(X-Mx)"]
WAR[X] = [ (x -Mx)? Px(x)
Xt Sx
WAR[X]
= El(X-Mx)2]
= &(k
- u) P(x = 1)
= &(1
- 2km
+ mijP(x = k)
-
> 27
= P(=)
- (((X
= 1))u+
-
E[X]
E[X] = M
= 1 .0
=
E[Xz]
- 2nm
+
m? 1
= E[xi]
- 12
I
VARIX]
= E[x]
- (E[X])
< 28
We can linearly transform expected value and variance using 
the following rules
Try to prove these results using 
the previous theorem 
If
Y =
ax
+ b
Y
and X
are
RVs
#[x]
= E[ax + b]
a
and
b
are
constants
= Elax]
+ #[b]
= at [x] + b
E)
. )
is
a linear
operator
VAR[Y]
= @ WAR[X]
-> DERIVATION in
COD 2 . 3
I FOR
YOU
TO DERIVE
En 29
Mean and variance of some families of random variables
In practical applications, a few families of random variables appear repeatedly
Within each family, the probability mass functions have the same mathematical 
form; they differ only in the values of one or two parameters
                 Bernoulli, binomial, Poisson, uniform, geometric
“Very few real-life situations satisfy perfectly the requirements for a binomial model, 
but for many the lack of agreement is so small that the binomial experiment still 
provides a very good model for reality” (Ott and Longnecker, 2001) 30
Bernoulli  random variable
X is a Bernoulli random variable if its pmf has the following form:
Example of experiments: one coin flip;  outcome of a test procedure on an integrated circuit (the 
outcome of the test, the circuit is either rejected with a probability p, or it is accepted with a  
probability 1 - p)
-1
0
1
2
x
P(x)
0.05
0.95
Px(X) =
S
1
-
P
/
X = 0
P
,
X
=
1
O
I
OTHERWISE
Nor
[orPx(X ; P)] 31
Calculate the mean and the variance of a Bernoulli random variable:
MEAN
#[x]
= [kP(X
= k)
=
1
. p
+ 0(1
- p)
= p
VARIANCE
NAR[X]
= #[x]
- 1E[X])
?
= [k"P(X =k)
- p2
K
= (1 ? p
+
0? (1 -p))
- ph
=
p
- p
=
p(1
-4)) 32
Bernoulli  random variable
X is a binomial (n, p) random variable if its pmf has the following form:
1.
Sequence of n identical trials
2. Trials are independent
3. Each with trial has two possible outcomes 
4. Probability of success in each trial is p
Then:
The random variable X defined as the number of 
successes observed during the n trials is binomial
Note that a Bernoulli random variable is a binomial 
random variable with n = 1
- thinking about order
-
of events
, rather concerned
about the number
of
successes.
Px(x)
= (4)* - 1)
-*
with
0
<
p -
1
n21
(integer)
and (4)
= 0
for
all x * 50, 1 ,2,
...N3
NOTE :
BiNOMIAL
COEF .
El =in!
n !
= n(n - 1)(n - 2)
.
.
.
. (2)
. (1) 33
Notice that you have/need two parameters (n, p) to characterize a binomial 
random variable
• n: number of identical independent trials 
• p: likelihood of success in each trial
Calculate the mean and variance of a binomial random variable:
E[X]
=
n
. p
VAR[X]
= up(1
- p) Example
34
p(H)=p=
0.5
n =
5
x (number H in 
experiment, the 5 
flips)
combination (n 
choose x)
p^x
(1-p)^(n-x)
P(x)
0
1
1
0.03125
0.03125
1
5
0.5
0.0625
0.15625
2
10
0.25
0.125
0.3125
3
10
0.125
0.25
0.3125
4
5
0.0625
0.5
0.15625
5
1
0.03125
1
0.03125
1
0
0.05
0.1
0.15
0.2
0.25
0.3
0.35
0
1
2
3
4
5
Outcome (number of H in the experiment - n flips)
Probability, P(x)
Flip
a
Fair
COIN
5 times
-
- How does the pmf change as we vary p?
35
0
0.05
0.1
0.15
0.2
0.25
0.3
0.35
0.4
0
1
2
3
4
5
Outcome (number of H in the experiment - n flips)
Probability, P(x)
0
0.1
0.2
0.3
0.4
0.5
0.6
0.7
0
1
2
3
4
5
Outcome (number of H in the experiment - n flips)
Probability, P(x)
0
0.05
0.1
0.15
0.2
0.25
0.3
0.35
0
1
2
3
4
5
Outcome (number of H in the experiment - n flips)
Probability, P(x)
(n = 5, p = 0.1)
(n = 5, p = 0.3)
(n= 5, p = 0.5)
Recall that you have/need two parameters (n, p) to characterize a binomial random variable
SKEWS
THE
PMF 36
Poisson random variable
1. Its time of occurrence is completely random 
(no dependence on time) 
2. There is an average number of occurrences 
per unit time
For the time-being, think of the probability 
model of a Poisson random variable as a 
description of a phenomenon that occurs 
randomly in time:
The Poisson model is widely used in many fields 
(e.g., information theory, radioactive decay)
The Poisson random variable is similar to a 
binomial random variable in which p is very small 
and n is very large
To describe a Poisson random variable, we 
call the occurrence of the phenomenon an 
arrival. A Poisson model specifies an average 
arrival rate λ per unit time. Let X be the 
Poisson random variable defined as the 
number of arrivals during a time interval T:
 
-
>
IMPORTANT
WHEN
DEALING
WITH
FAILRE
RATES
Let
X = XT
Px(x
=
c*
X = 0,
↑
I
①
,
Otherwise
puf
of
arrivals
in the time
intervalI 37
Poisson random variable
PX (x) =
α x e−α
x!    for  x = 0, 1, 2, ...
0   otherwise
 
 
 
 
 
 
 
Example: A call center receives on average 2 calls per minute. What’s the 
likelihood of getting no calls in 10 minutes? What is the likelihood of getting 
10 calls in 10 minutes? What is the pmf of the number of arrivals in a 10 
minute period?
0
0.01
0.02
0.03
0.04
0.05
0.06
0.07
0.08
0.09
0.1
0
3
6
9
12
15
18
21
24
27
30
33
36
39
42
45
48
Arrivals
Probability
alpha = 
20
x (arrivals)
P(x)
0
2.06115E-09
1
4.12231E-08
2
4.12231E-07
3
2.7482E-06
4
1.3741E-05
5
5.49641E-05
6
0.000183214
7
0.000523468
8
0.001308669
9
0.002908153
10
0.005816307
11
0.010575103
12
0.017625171
13
0.027115648
14
0.03873664
15
0.051648854
16
0.064561067
…
…
α = λT
-
↓= 2 calls/min .
T = 10 min
X = X
. T = 20
aug.
. # in the time
interval -
ARRIVALS
V 38
Poisson random variable
How many variables are required to characterize a 
Poisson random variable?
0
0.05
0.1
0.15
0.2
0.25
0.3
0
3
6
9
12
15
18
21
24
27
30
33
36
39
42
45
48
Arrivals
Probability
α = 2
0
0.02
0.04
0.06
0.08
0.1
0.12
0.14
0.16
0.18
0.2
0
3
6
9
12
15
18
21
24
27
30
33
36
39
42
45
48
Arrivals
Probability
α = 5
0
0.02
0.04
0.06
0.08
0.1
0.12
0.14
0
3
6
9
12
15
18
21
24
27
30
33
36
39
42
45
48
Arrivals
Probability
α = 10
PX (x) =
α x e−α
x!    for  x = 0, 1, 2, ...
0   otherwise
 
 
 
 
 
 
 
α = λT
-
Vary a
-
- 39
Poisson random variable: Mean and variance
PX (x) =
α x e−α
x!    for  x = 0, 1, 2, ...
0   otherwise
 
 
 
 
 
 
 
α = λT
E[X]
=
X
VAR[X] = X 40
Poisson random variable: Mean and variance
Binomial random variable:
Geometric random variable:
Uniform random variable:
Poisson random variable:
PX (k) = P(X = k) = n
k
 
  
 
  pk × 1−p
(
)
n−k    for k = 0, 1, 2, ..., n
PX (k) = P(X = k) = p × 1−p
(
)
k−1   for k = 0, 1, 2, ..., n
One parameter (p) characterizes this pmf.  What does this pmf represent?
Two parameters (n, p) characterize this pmf
PX (k) = P(X = k) = e−λ × λk
k!    for  k = 0, 1, 2, ..., n
PX (k) = P(X = k) = p   for k = 0, 1, 2, ..., n
FAMILIES
Of
DISCRETE
RANDOM
Variables
Interested
in the
success and
want
to
know
how
many tests
are
needed
for prob of success
EACH
RESULT IS
EQUALLY
LIKELY with probability
P
(X
= x) Definition
41
The cumulative distribution function (cdf) F(x) of a discrete random variable X with pmf p(x) is defined for every 
number x by
! " = $ % ≤" = '
!: !$%
((*)
For any number x, F(x) is the probability that the observed value of X will be at most x
Example
X
↑
2
3
4...
8
...
16
P(x)
0
. 05
0 . 10
35 40 10
F (1)
=
P(X ( 1)
=
0, 05
↑(2)
= P(x(2)
=
P(1) + P(z)
=
0,10
F(4)
=. 50
i
F(16)
=
1 .8 42
F(X)
1.0
1 . 0
----------------
9
----
F(X)
=
- --------
O
,
X < 1
· 8-
I
· 05 ,
12X4Z
I
-
- 15 12(XX)
I
· 6-
S
42X < 5
-
--
&
i
--
I
- 2
-
_
0.05
0 .15
· J i
!
!
----
I :
8X19
· 4 -
I
!
-
I
1
,
164X
-
-
-
#
v
11
I
I
I
I
01
2
5
8
10
1516
28 X 43
We
can
derive
the
puf
from
a
cof.
For example :
X
=
#
of
detective components
in
a shipment of
6 components
All Defective
X
=
0, 1,
.. .., 67
And
Let's
say
we know the
↑None Defective
edf = pmP
?
them ,
P(3)
= P(X =3) (exactly 3)
= [P(0)
+ P(n)
+
p(z)
+ p(3)]
- [P(0) + P(1)
+ P(z)]
P(xX3)
- P(X1) =
F3
- F2 Between
2
and
4
P(2(X(4)
=
P(z)
+
P(z)
+ P(4)
= [P(o) + P()
. .
.
.
. P(9)]
-[P(d) + P(1)]
= P(X(4)
- P(X(1)
=
F(4)
- F(1) =
X2
is
included
DON'T
SUBTRACT
17
but
4)(2
< x(4)
=
..
..
=
F(q)
- F(z)
X 2
is
NOT
INCLUDED
Subtract it Proposition
44
For any two numbers a and b with a £ b,
! " ≤$ ≤% = ' % −'("−)
where “" −” represents the largest possible X value that is strictly less than a. In particular, if the
only possible values are integers and if a and b are integers, then
! " ≤$ ≤% = ! $ = " or " + 1 or … or %
 
= ' % −'(" −1)
Taking a = b yields P(X = a) = F(a) –  F(a – 1) in this case Binomial cdf
45
For
XN
Bin (n , p)
,
the
cof
is denoted
by
B(Xin , 4)
= P(X -x)= b(yin ,m
where
X = 0
,
1
, 2
...
N
and
the
binomial put
is
b (x ; n
, p)
=
(m)p
+ (n
- p)n
- X
,
X
=
0 , 1 ... n
&
O
,
OTHERWISE 46
C&D Example 2.31: Each of six randomly selected cola drinkers is given a glass containing cola S and one containing cola F. 
The glasses are identical in appearance except for a code on the bottom to identify the cola. Suppose there is actually no 
tendency among cola drinkers to prefer one cola to the other. Then, p = P(a selected individual prefers S) = .5, so with X = the 
number among the six who prefer S, X ~ Bin(6, .5).
(a) What is the probability that exactly three prefer S?
n =
6
,
P =
S
,
X
=
3
,
X
= binomial
P(X = 3)
= ()p
+
(1
-p)
- X
= (3) (
. 5)" (1
- 0
.5)3-3
6 !
1
. 5)" (
. 513
=
0 . 313
=
3 ! (6-3)
. 47
C&D Example 2.31: Each of six randomly selected cola drinkers is given a glass containing cola S and one containing cola F. 
The glasses are identical in appearance except for a code on the bottom to identify the cola. Suppose there is actually no 
tendency among cola drinkers to prefer one cola to the other. Then, p = P(a selected individual prefers S) = .5, so with X = the 
number among the six who prefer S, X ~ Bin(6, .5).
(b)  What is the probability that at least three prefer S?
X 3, 5
P(X( 3) = b(X ; G
,%
= ()(. (
.-
= (3)
.
1
. 53" 1
. 5) +
+
+ 1
0
.5561, 48
C&D Example 2.31: Each of six randomly selected cola drinkers is given a glass containing cola S and one containing cola F. 
The glasses are identical in appearance except for a code on the bottom to identify the cola. Suppose there is actually no 
tendency among cola drinkers to prefer one cola to the other. Then, p = P(a selected individual prefers S) = .5, so with X = the 
number among the six who prefer S, X ~ Bin(6, .5).
(c)   What is the probability that at most one prefers S?
P(X = 1) = (4) 10 . 5)
*
10
. 81b
- x
=
t
-
-
E
0
. 109 49
C&D Example 2.32: Suppose that 20% of all copies of a particular textbook fail a binding strength test. Let X 
denote the number among 15 randomly selected copies that fail the test. Then X has a binomial distribution with n 
= 15 and p = .2.
(a) What is the probability that at most 8 fail the test?
P(X(8) = b(y
=
15 , 0 . 2)
tedious by
hand !
TABLE
A
.1
. C
=> USE
A
TABLE
-
( new
for each n)
V
TABLE
A
. 1 .
B(8 ;
15
,
0 .2)
0
. 999
↑
↑
row
column 50
C&D p. 597-
599 
de
- 51
C&D Example 2.32: Suppose that 20% of all copies of a particular textbook fail a binding strength test. Let X 
denote the number among 15 randomly selected copies that fail the test. Then X has a binomial distribution with n 
= 15 and p = .2.
(b)  What is the probability that exactly 8 fail the test?
P(x = 8)
=
b(8 ; 15 , 2)
= (5)
. 188
=
0
,00
TABLE
A . 1 . C
OB
P(X
= 8)
= P(x(8)(x
= B(8 ;
15
,2)
- B(7 ; 15
, 2)
=
0 . 999
-
0 . 996
=
0
. 003 52
C&D Example 2.32: Suppose that 20% of all copies of a particular textbook fail a binding strength test. Let X 
denote the number among 15 randomly selected copies that fail the test. Then X has a binomial distribution with n 
= 15 and p = .2.
(c)   What is the probability that at least 8 fail the test?
P(Xz8)
=
1 - p(X(z) HA
. 1
.d
=
1
- B(7 ; 15 , 2)
=
1
-
0, 996
=
0 . 004 53
C&D Example 2.32: Suppose that 20% of all copies of a particular textbook fail a binding strength test. Let X 
denote the number among 15 randomly selected copies that fail the test. Then X has a binomial distribution with n 
= 15 and p = .2.
(d)   What is the probability that between 4 and 7 fail the test?
P(q(X(z)
=
f(z)
- F(b +
=
F(z)
- F(z)
= P(x(z)
- P(x(z)
(m)
-
-
= B (7· 15 ,2)
- B(3 ; 15, 2)
=
0 . 996
-
0 . 698
=
0 . 348 54
C&D Example 2.35: Let X denote the number of creatures of a particular type captured in a trap during a given time period. 
Suppose that X has a Poisson distribution with μ = 4.5, so on average traps will contain 4.5 creatures. [Notation: the textbook 
uses μ as a ]
(a) What is the probability that a trap contains exactly five creatures?
(b) What is the probability that a trap has at most five creatures?
X
P(X = 5) = =4
=
0
, 1
4 . 33
P (x (5) =145
+ 45+ ...
=
0
. 7029 55
C&D p. 600 
[Note: the textbook uses μ as a ]
(continues on next slide)
E 56
C&D p. 600 
[Note: the textbook uses μ as a ]
C&D p. 600 
P(XiM)
up
X
Qu 57
C&D Problem 2.76: Let X be the number of material anomalies occurring in a particular region of an aircraft gas-
turbine disk. A Poisson distribution for X is proposed. Suppose a = 4.
(a) Compute both P(X ≤ 4) and P(X < 4)
_T. A .2
P(X(4)
=
P(4
, 4)
=
0 . 629
- T. A
. 2
P(X(4)
= P(X(3)
=
P(3 ; 4)
=
0 . 433 58
C&D Problem 2.76: Let X be the number of material anomalies occurring in a particular region of an aircraft gas-
turbine disk. A Poisson distribution for X is proposed. Suppose a = 4.
(b) Compute P(4 ≤ X ≤ 8)
-
P(4(X(8)
=
F(8)
- F(4
- )
=
F(8)
-
F(z)
= P(84)
- P(3; 4)
-> T
.A .2
=
0
. 979
-
0
. 433
=
0 . 546 59
C&D Problem 2.76: Let X be the number of material anomalies occurring in a particular region of an aircraft gas-
turbine disk. A Poisson distribution for X is proposed. Suppose a = 4.
(c) Compute P(8 ≤ X)
&
P(8(X)
=
P(Xz, 8)
=
1
-
P(X(8)
=
1
= p(X(t)
=
1
- P(z ; g) -
T
. A
. Z
=
1
-
0
. 949
=
0
. 0511, 60
C&D Problem 2.76: Let X be the number of material anomalies occurring in a particular region of an aircraft gas-
turbine disk. A Poisson distribution for X is proposed. Suppose a = 4.
(d) What is the probability that the observed number of anomalies exceeds the expected number by no more than 
one standard deviation?
M
-
E
We
want
to
know
the probability that
at
most
(M + 6
anomalies
are
observed
=> P(XM + 6)
Possom
moder
with =4
N
u = x
= 4
& XAn(X) = x
= 4
8
= Nan
= M
= 2
/TA2
P(X(y + 2)
=
p(x16)
=
4(6 ; 4)= Reading
61
Chapter 2.1 to 2.5 and 2.8 of Carlton and Devore, 
Probability with Applications in Engineering, Science, and 
Technology, 2nd ed., 2017


## System Integration

Discrete distributions are highly applicable to analyzing the RCUAV's fleet operations, such as predicting the number of failed print jobs out of a batch, or the number of successful cargo deliveries before a major maintenance overhaul is required.
