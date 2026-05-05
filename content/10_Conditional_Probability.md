# Conditional Probability

## 10.1 Updating Probabilities
In complex aerospace systems, the likelihood of a failure changes dynamically as the system operates. Conditional probability is the mathematical tool used to update the probability of an event based on the occurrence of another event. The probability of event $A$ occurring, *given* that event $B$ has already occurred, is defined as:
$$ P(A|B) = rac{P(A \cap B)}{P(B)} $$
where $P(B) > 0$.

## 10.2 Bayes' Theorem
Bayes' Theorem is derived directly from the definition of conditional probability. It allows engineers to "invert" the condition. If we know the probability of a sensor failing given a power surge $P(	ext{Sensor Fails} | 	ext{Surge})$, Bayes' Theorem allows us to calculate the probability that a power surge occurred given that we just observed a sensor failure $P(	ext{Surge} | 	ext{Sensor Fails})$.
$$ P(A|B) = rac{P(B|A)P(A)}{P(B)} $$

## 10.3 Application to Cascading Failures
Conditional probability is crucial for modeling cascading failures. In a redundant flight control system, if the primary computer fails, the probability of the backup computer failing might not be its baseline rate. If they share a cooling fan that failed, the backup computer's failure probability is now conditionally much higher.

## System Integration
In the context of the RCUAV, conditional probability helps us understand cascading failures. For instance, what is the probability of a structural failure *given* that a layer adhesion defect occurred during printing? These conditional relationships will inform the transition rates in your final Markov Chain reliability models.
