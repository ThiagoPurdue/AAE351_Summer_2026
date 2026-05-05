# Independence

## Statistical Independence
Two events $A$ and $B$ are statistically independent if the occurrence of one does not affect the probability of the other. Mathematically, this is expressed as:

$$ P(A \cap B) = P(A)P(B) $$

## Series and Parallel Systems
Assuming independence simplifies reliability calculations. In a series system, all components must function; in a parallel (redundant) system, only one must function. However, assuming independence when components share a common environment can lead to dangerous underestimations of failure probability.

## System Integration
When designing the RCUAV's modular print blocks, assuming failure independence between physical blocks simplifies early analysis. However, you must carefully analyze whether a thermal failure in an avionics bay (printed in heat-sensitive PLA) is truly independent of a structural failure in the adjacent fuselage block.
