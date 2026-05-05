# System Reliability

## Reliability Block Diagrams (RBD)
To calculate the overall reliability of a complex aerospace vehicle, we use Reliability Block Diagrams. A series system requires all components to work, meaning $R_{sys} = R_1 	imes R_2 	imes ... 	imes R_n$. Redundant (parallel) systems significantly increase reliability.

## Markov Chain Modeling
For systems that can be repaired or exist in degraded states, static RBDs are insufficient. Markov Chains model the dynamic probability of transitioning between discrete states (e.g., 'Operational', 'Degraded', 'Failed') over time.

## System Integration
The culmination of the RCUAV reliability analysis is combining component-level data into a system-level Markov Chain model. Using MATLAB, you will simulate the vehicle's state transitions over its 100-flight lifecycle, proving to stakeholders that the fully integrated, 3D-printed architecture meets all safety and performance requirements.
