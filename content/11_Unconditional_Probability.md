# Unconditional Probability

## The Law of Total Probability
To find the unconditional (or marginal) probability of an event $A$ that depends on multiple mutually exclusive scenarios $B_i$, we use the Law of Total Probability:

$$ P(A) = \sum_{i=1}^{n} P(A|B_i)P(B_i) $$

## Evaluating Baseline Risk
Unconditional probability allows engineers to determine the overall baseline risk of a system failure, regardless of the specific operational scenario or state the aircraft is currently in.

## System Integration
Understanding the baseline, unconditional probabilities of component failures (e.g., motor burnout, avionics fault) is essential. These baseline metrics will be integrated into the Digital Thread, allowing the MATLAB models to simulate the unconditioned lifespan of the cargo UAV.
