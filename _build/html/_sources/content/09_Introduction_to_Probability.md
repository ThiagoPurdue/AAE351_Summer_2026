# Introduction to Probability

## 9.1 The Need for Probability in Engineering
Traditional deterministic engineering assumes that inputs are perfectly known: if you apply a 100N force to a beam with a known cross-section, it will deflect by exactly $x$ millimeters. In reality, manufacturing tolerances mean the cross-section varies, and environmental factors mean the force is never exactly 100N. To design safe systems, we must model this uncertainty using probability.

## 9.2 Foundational Axioms
Probability is built on a few core axioms. First, the sample space $S$ is the set of all possible outcomes of an experiment (e.g., measuring the tensile strength of a 3D printed strut). An event $A$ is a subset of this sample space. The probability of any event $A$, denoted $P(A)$, must fall between 0 and 1:
$$ 0 \le P(A) \le 1 $$
Furthermore, the probability of the entire sample space occurring is exactly 1: $P(S) = 1$. If events $A$ and $B$ are mutually exclusive (they cannot happen at the same time), the probability of either happening is the sum of their individual probabilities:
$$ P(A \cup B) = P(A) + P(B) $$

## 9.3 Venn Diagrams and Set Theory
Systems engineers frequently use Venn diagrams to visualize overlapping failure modes. The intersection of two events, $A \cap B$, represents the probability that both failures occur simultaneously. The union, $A \cup B$, represents the probability that at least one failure occurs.

## System Integration
The foundational principles of probability allow us to quantify the uncertainties inherent in 3D-printing manufacturing tolerances. By modeling the variation in print quality and material strength as probabilistic events, we can begin to predict the overall structural reliability of the RCUAV.
