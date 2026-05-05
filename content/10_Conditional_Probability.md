# Conditional Probability

## Bayes' Theorem and Conditional Events
Conditional probability describes the likelihood of an event occurring given that another event has already occurred. This is mathematically defined as:

$$ P(A|B) = rac{P(A \cap B)}{P(B)} $$

## Cascading Failures
In complex systems, failures are rarely isolated. If a cooling fan fails (Event B), the probability of avionics overheating (Event A) increases drastically. Conditional probability models these cascading effects.

## System Integration
In the context of the RCUAV, conditional probability helps us understand cascading failures. For instance, what is the probability of a structural failure *given* that a layer adhesion defect occurred during printing? These conditional relationships will inform the transition rates in your final Markov Chain reliability models.
