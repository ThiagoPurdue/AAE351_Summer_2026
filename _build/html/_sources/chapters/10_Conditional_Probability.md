# 10 Conditional Probability

Conditional Probability
AAE35103
\n\n\n\n![Image](../images/10_Conditional_Probability_p1_i1.png)\n\n\n\n![Image](../images/10_Conditional_Probability_p1_i2.png)\n\nThe probabilistic mindset is different from traditional, 
say physics or engineering, deterministic mindsets
2
Probabilistic mindset
Deterministic mindset 
X
Y
X
Y1
Y2
Y3
INPUT
OUTPUT
SYSTEM
Same
In Put
=
SAME
OUTPUT
but, repeat mony
, many times
-
=> WE
SEE
patterns
in the
INPUT
way
the
output
is
distributed
SYSTEM
SAMEInputs Diferent output
\n\n\n\n![Image](../images/10_Conditional_Probability_p2_i3.png)\n\nSome vocabulary
3
Sample space
Event
Outcome
OUTCOME
sample
·
SPACE
-> Space that
contains
all
of
the
&
possible
outcomes
for
a given
problem
,
EVENT A
e. g .,
six-sided dice
:
11 , 2
, 3
, 4
, 5
, 54
-
>
A
smaller
portion
of
the
sample
spare ,
e . g., [1, 3 ,53OD
-
>
e . g .. Individual
outomes
of
the dice roll .
1
,
or
3
or 5
\n\n\n\n![Image](../images/10_Conditional_Probability_p3_i4.png)\n\nExample: roll a six-sided dice; observe number of 
dots on side facing upward
4
1) Sample space? (all possible outcomes)
2) Event E1 = even roll (subset of sample space) => E1 = {?}
3) Event E2 = roll is a square of an integer => E2 = {?}
[1 , 2
, 3
, 4
, 5
, 63
42
, 4
, 63
[1 . 43
\n\n\n\n![Image](../images/10_Conditional_Probability_p4_i5.jpeg)\n\n\n\n![Image](../images/10_Conditional_Probability_p4_i6.png)\n\nWhy is all this relevant? Seems kind of basic
5
Defining the sample space and its outcomes are key elements of the solution of 
any probability problem
Probability problems arise from a practical situation that can be modeled as an 
experiment
To address the problem, it is important to carefully define the experiment and 
derive the sample space
Getting it right is important to gain an intuition about the problem, selecting the 
right mathematical tools, and a major step towards solving it
\n\n\n\n![Image](../images/10_Conditional_Probability_p5_i7.png)\n\nA probabilistic model is a mathematical description 
of an uncertain phenomenon
6
Experiment
Sample space
Event A
Event B
Probability
P(A)
P(B)
Events
Example:
roll a dice
A = {x | x = square of an integer}
B = {x | x > 2}
What is P(A)? and P(B)?
43
Y3
EVENT
end EVENT
DES .
SPACE
5 1 , 2 ,3 , 4
,5 ,6)
A = G
1
, 44 B = 33, 4 ,5 ,5)
P(A)==
G
2
4
OUTCOMES
OUTCOMES
P(B) =1=
OUTCOMES
\n\n\n\n![Image](../images/10_Conditional_Probability_p6_i8.png)\n\nLet’s think about aerospace examples
7
95% of objects shown are non-
functional spacecraft
Damage to spacecraft 
from orbital debris
Figures: NASA image - NASA Orbital Debris Program Office
\n\n\n\n![Image](../images/10_Conditional_Probability_p7_i9.jpeg)\n\n\n\n![Image](../images/10_Conditional_Probability_p7_i10.jpeg)\n\n\n\n![Image](../images/10_Conditional_Probability_p7_i11.jpeg)\n\n\n\n![Image](../images/10_Conditional_Probability_p7_i12.png)\n\nLet’s think about aerospace examples
8
LET'S
TAKE
,
FOR
EXAMPLE ,
TRADING
SPACE
DEBNIS
AND
Preventing
COLLISIONS .
Cross
2
SECTION
of
POSSIBLE
SPACEAE
Positions
⑦F
IOI
DEBRIS
orB
(SAMPLE
SPACE)
I WE
Don't
Know
The exent
would
be
if the
WHERE
THE
DEBAIS
IS
Within
ITS
piece
of debris
is
within
=>To
minimize theProbability
the
area
of the
spacecraft
of colision
you could minimize
theCross-sectional
area (rotate
\n\n\n\n![Image](../images/10_Conditional_Probability_p8_i13.png)\n\nMany experiments in probability have an 
intrinsic sequential character, such as a 
mission to the Moon…
9
https://en.wikipedia.org/wiki/Flight_dynamics_%28spacecraft%29 
A
mission will have mony
course
corrections
EACH
MANUEVER
is a
PROBABILiSt
EVENT
SINCE YOU
DON'T
KNOW
HOW
MUCH
IS
NEEDED
MULTIPLE RANDON
↑
AND
It DEPENDENS
ONE
=> EVENTS
HAPPENING
SEQUENTIALLY
THE
LAST
ONE .
\n\n\n\n![Image](../images/10_Conditional_Probability_p9_i14.png)\n\n\n\n![Image](../images/10_Conditional_Probability_p9_i15.png)\n\n… or simple dice rolling
10
Example: roll a 4-sided dice twice
Sample space of this experiment: 
Representing sample space: 
WRITE
AS
AN
ORDERED
PAIR
&
21
, 1)
,
21 , 23
, 2 , 3)
, (1 , 4)
,
I
I
&
i
i
i
"
(4 , 433
i =
outcome
of first
roll
[(i , j)4
j
=
outcome
of
Second roll
\n\n\n\n![Image](../images/10_Conditional_Probability_p10_i16.jpeg)\n\n\n\n![Image](../images/10_Conditional_Probability_p10_i17.png)\n\nThe entire theory of probability (theorems that will 
follow) is built on just three axioms
11
What is an axiom?
Start
with
the
assumption of probability theory
Consider
self-evident
truth
NEED
no proof
\n\n\n\n![Image](../images/10_Conditional_Probability_p11_i18.png)\n\nThe entire theory of probability (theorems that will 
follow) is built on just three axioms
12
The three axioms:
A probability measure P(.) is a function that maps events in the sample space to real 
numbers such that:
Non-negativity: for any event A 
 
 
 
Normalization: the probability of the entire sample space is one 
Additivity: the probabilities of two disjoint events, A and B, are additive
S
P(A) = O
B
A
DISJONT
Events
↑(S)
= 1
A
or
B
=
AUB
PLAUB)
=
P(A) +
P(B)
\n\n\n\n![Image](../images/10_Conditional_Probability_p12_i19.png)\n\nTHE
DISCRETE
PROBABILITY
LAW
LET
US
BUILD" NENT
PROBABILITIES
Let's
start
with
outcomes
.
Let's
call
on
outcome bi
All
outcomes
are by definition :
EQUALLY
LIKELY
In
MATH
:
P([bib)
= P(bjb)
for all i , j
Now
let's
define
on
event
B
= (b1, br , by
,
... but
then theProBABILITY
of
an
event
B = b1 ,b ... but is the
sum of the
probabities
of
the
outcomes
contained in the
event :
P(b) = P((bil)
= P
+ Put
... Pr
which
axiom
did
we
used
to
create this
law ? ADDI
-
\n\nNotation
14
More precise notation
Simpler, abbreviated notation
P(.) is the probability of an event, not an outcome
{bi} is the event that consists of the single outcome bi
U
=
union
A
U
B
:
m A
or
B
&
= Intersection
AMB :
in A
and
B
P([bib)
P(bi)
P(ANB)
P(AB)
&
Y
=
SET
A = [3 , 7
, 9
, 14]
1
=
such that
(GIVEN THAT)
A
= (x(XER
, x> ob
-
=
subset
ASB
:
A
is
m B
\n\n\n\n![Image](../images/10_Conditional_Probability_p14_i20.png)\n\nLet’s use the axioms to make some useful 
observations
15
(1)
S
A
B
A∩B
A∩B
EVENT
B
SAMPLE SPACE
EVENT A
P()
=
1
-
P(A)
&
↑
-
-
Probability
Probability
of not getting
of
event
event A
A
[A
= not A]
also
written
on [A
= not A]
4DERIVATION"
S
A
and I
are disjunt events
*
A
P(A) + P(π) = P(s)
= 1
=>
P(A)
= 1 - P(A)
-
\n\n\n\n![Image](../images/10_Conditional_Probability_p15_i21.png)\n\nLet’s use the axioms to make some useful 
observations
16
(2)
S
A
B
A∩B
A∩B
If
A S B
then
PLATE P(B)
Let's
say that
P(A)
= P(da , an
, a33)
=> P(an)
+ P(uz)
+ P(uz)
P()
= P((
, 92 , 03 , bay) - M , 12, 93
, b
= P(ui)
+ P(az)
+ Plus) + P(b1)
ARE
DiSJOINT
--
PA)
30
SINCE D)120
(non negative) = P(A) = P(B)
\n\n\n\n![Image](../images/10_Conditional_Probability_p16_i22.png)\n\nLet’s use the axioms to make some useful 
observations
17
(3)
S
A
B
A∩B
A∩B
And B
not disjoint
P (AUB)
= P(A)
+ P(B) - P(ANB)
3
↑
↑
Probability of
Probability
und
event A or B
of events A
and
B
B
DOESN'T
Sketch
A
VEIM
DIAGRAM :
Double
curt
PLA)
P(AVB) =
P(A) + P(B)
- P(ANB)
&
A "yy
is
~ P(B)
A OR B
All
"B11
OVERLAPY
Y P(A1B)
\n\n\n\n![Image](../images/10_Conditional_Probability_p17_i23.png)\n\nSome observations get to be called laws
18
The discrete uniform probability law lets us solve the dice problems (and some more useful 
problems too!)
For an experiment with n possible outcomes {ai} with i = 1 to n, and all outcomes equally likely, that is 
all single element events have the same probability, then:
Plai) = Plan)
= Px)
+ Plan) + Plazi +.... Plom
= I
=>
n . Plail = 1
P(A)
= -
ber of elements in
EVENT
A
n
EVENT
A
has multiple outcomes
in the experiment
.
For example,
If
n = 10
and
A
= Can
, ash
, them
P(A)
= 2/10
= As
\n\n\n\n![Image](../images/10_Conditional_Probability_p18_i24.png)\n\nSome Roll a pair of 4-sided dice. 
Assume the dice are “fair” get to be called laws
20
What is the sample space of this experiment? Draw it as a 2-D grid 
What is the probability of each outcome? 
1, 1
1, 2
1, 3
1, 4
2, 1
2, 2
2, 3
2, 4
3, 1
3, 2
3, 3
3, 4
4, 1
4, 2
4, 3
4, 4
First D4
Second D4
~SAMPLE
SPACE
has 16
Possible
OUTCOMES
Plai ,jhete
\n\n\n\n![Image](../images/10_Conditional_Probability_p19_i25.png)\n\nSome Roll a pair of 4-sided dice. 
Assume the dice are “fair” get to be called laws
19
What is the probability that the sum of the rolls is even?
1, 1
1, 2
1, 3
1, 4
2, 1
2, 2
2, 3
2, 4
3, 1
3, 2
3, 3
3, 4
4, 1
4, 2
4, 3
4, 4
First D4
Second D4
-
P([i + j
= even])
= = 1
25
2
\n\n\n\n![Image](../images/10_Conditional_Probability_p20_i26.png)\n\nSome Roll a pair of 4-sided dice. 
Assume the dice are “fair” get to be called laws
21
What is the probability that the first roll is equal to the second? 
Show this event on the 2-D grid sample space
1, 1
1, 2
1, 3
1, 4
2, 1
2, 2
2, 3
2, 4
3, 1
3, 2
3, 3
3, 4
4, 1
4, 2
4, 3
4, 4
First D4
Second D4
P([i =j)) =t
-
\n\n\n\n![Image](../images/10_Conditional_Probability_p21_i27.png)\n\nSome Roll a pair of 4-sided dice. 
Assume the dice are “fair” get to be called laws
22
What is the probability that at least one roll is equal to 4? 
Show this event on the 2-D grid sample space
1, 1
1, 2
1, 3
1, 4
2, 1
2, 2
2, 3
2, 4
3, 1
3, 2
3, 3
3, 4
4, 1
4, 2
4, 3
4, 4
First D4
Second D4
P(i = 4Vj = 4y)
=
\n\n\n\n![Image](../images/10_Conditional_Probability_p22_i28.png)\n\n23
So far, we’ve learned how to answer questions like “What is the 
probability of rolling a 4?” and “What is the probability of rolling an odd 
number?”
What about the probability of rolling a 2, given that the roll is even
How can we address this more generally?
CONDITION
=> the sample space here
is
reduced to
22 , 44
=>
P(2) = 1
2
this
is
an
example
of
CONDITIONAL
PROBABILITY ?
\n\n24
We need the concept of conditional probability to answer these questions
Let’s start by remembering how we defined P(A) in the first place
“amount of Nutella in S” = 1… because of which axiom?
In other words, you know you’re in “S”, the universal set or sample space, and the probability 
of being in A is the relative “size” of A to S
P(A) = "amount  of  Nutella  in  A"
"amount  of  Nutella  in  S"
S
A
B
NORMALIZATION
\n\n25
S
A
B
What does the relative size of A to B represent?
For example, let S be our dice roll’s event space, B even rolls, and A “2”
Then this ratio is the probability of rolling a 2, given that the roll is even
And since it’s a ratio, in math we write: 
 
More generally, we write: 
And read it as “P(A) given B, or the conditional probability that A occurs given that B has occurred”
P(A , GIVEN Bl = ADA)
P(B)
a
-
-
\n\n26
We need a way to calculate P(A|B) for all possible situations
Our Nutella diagram was easy because A was a subset of B:
What about the more general case, like this?
What should go in the numerator? How about the denominator?
S
A
B
S
A
B
And
\n\n27
S
A
B
The numerator is the probability of the intersection of A and B, or 
And the denominator is the probability of B
 
So, we can write:
A1B
A1B
-
A
AND B
PAIB)=
AB)Probabilitya
B
VERY
IMPORTANT !
\n\n28
Conditional probability allows us to reason about the outcome of an experiment given partial 
information
What is the probability that I get a “2” rolling a fair six-sided die?
Conditional probability: What is the probability that I get a 2 rolling a fair six-sided die, given that I 
got an even roll? 
What is the probability that the second letter in a word in the English language is an “h”? 
Conditional probability: what is the probability that the second letter is an “h” given that the first 
letter is a “t”?
What is the probability that a Purdue student can derive Bernoulli’s equation?
Conditional probability: What is the probability that a Purdue student can derive Bernoulli’s 
equation given that the student is in AAE?
!
\n\n\n\n![Image](../images/10_Conditional_Probability_p28_i29.png)\n\n29
S
A
B
In words, out of the total probability of the elements of B, 
P(A|B) is the fraction that is assigned to possible outcomes 
that also belong to A
P A | B
(
) = P A∩B
(
)
P(B)
Let’s check. Does this definition work with our original Nutella problem?
What is P(A|A)?
-
&
P(AIA)-
B =
\n\n\n\n![Image](../images/10_Conditional_Probability_p29_i30.png)\n\n30
S
A
B
In words, out of the total probability of the elements of B, 
P(A|B) is the fraction that is assigned to possible outcomes 
that also belong to A
P A | B
(
) = P A∩B
(
)
P(B)
How about P(S|A)?
w
RISIA)=
UA =A
5
-
ALL
SAMPLE
SPACE
A
Sub Space
of
S
=> Probability
of
S given A
corred is
guaranteed
\n\n\n\n![Image](../images/10_Conditional_Probability_p30_i31.png)\n\n31
S
A
B
In words, out of the total probability of the elements of B, 
P(A|B) is the fraction that is assigned to possible outcomes 
that also belong to A
P A | B
(
) = P A∩B
(
)
P(B)
And P(A|S)?
P(AIS)
= PAS)
=
Overlap
of
A
AndS ?
"At
P(s)
-
normalization
= 1
=
A
=
P(A)
\n\n\n\n![Image](../images/10_Conditional_Probability_p31_i32.png)\n\nReading
32
Chapter 1.1-1.4 of Carlton and Devore, Probability with 
Applications in Engineering, Science, and Technology, 2nd 
ed., 2017
\n\n