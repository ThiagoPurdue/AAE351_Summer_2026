# Unconditional Probability

## 11.1 The Law of Total Probability
Often, the total (or marginal/unconditional) probability of an event is not given directly. Instead, we know the conditional probabilities of the event across a set of mutually exclusive scenarios that make up the entire sample space. The Law of Total Probability allows us to reconstruct the unconditional probability:
$$ P(A) = \sum_{i=1}^{n} P(A|B_i)P(B_i) $$

## 11.2 Real-World Application
Consider an aircraft that operates in three distinct environments: clear weather ($B_1$), moderate rain ($B_2$), and severe storms ($B_3$). We might know the conditional probability of an engine stall in each of these environments. To find the unconditional, overall probability of an engine stall over the life of the aircraft, we sum the conditional probabilities weighted by the likelihood of encountering each weather condition.

## 11.3 Baseline Risk Assessment
Unconditional probability is used to establish the baseline risk metric for a component. Before conditional factors (like maintenance history or specific mission profiles) are applied, the systems engineer must guarantee that the unconditional failure rate meets regulatory safety targets.

## System Integration
Understanding the baseline, unconditional probabilities of component failures (e.g., motor burnout, avionics fault) is essential. These baseline metrics will be integrated into the Digital Thread, allowing the MATLAB models to simulate the unconditioned lifespan of the cargo UAV.
