# Independence

## 12.1 Mathematical Definition of Independence
Two events $A$ and $B$ are statistically independent if the occurrence of one provides absolutely no information about the occurrence of the other. Mathematically, this means the conditional probability of $A$ given $B$ is simply the baseline probability of $A$:
$$ P(A|B) = P(A) $$
This directly leads to the multiplication rule for independent events:
$$ P(A \cap B) = P(A)P(B) $$

## 12.2 The Danger of Assuming Independence
In systems engineering, assuming components are independent simplifies reliability mathematics immensely. If you have two independent computers each with a failure probability of 0.01, the probability of both failing is $0.01 	imes 0.01 = 0.0001$. 

However, assuming independence when components are actually coupled (e.g., they share the same power supply, or are subject to the same severe vibration environment) is a classic engineering trap. This is known as a **Common Cause Failure**.

## 12.3 Redundancy and Series Systems
In a series system, all components must work for the system to work. If components are independent, $R_{sys} = R_1 	imes R_2$. In a parallel (redundant) system, only one component needs to work. The probability of system failure is the probability that *both* fail, heavily relying on the assumption of independence.

## System Integration
When designing the RCUAV's modular print blocks, assuming failure independence between physical blocks simplifies early analysis. However, you must carefully analyze whether a thermal failure in an avionics bay (printed in heat-sensitive PLA) is truly independent of a structural failure in the adjacent fuselage block.
