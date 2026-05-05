# System Reliability

## 17.1 Reliability Block Diagrams (RBD)
Component reliability must be aggregated to determine overall system reliability. This is mapped using Reliability Block Diagrams. 
* **Series Systems:** All components must function for the system to function. The system reliability is the product of individual reliabilities:
  $$ R_{sys} = R_1 	imes R_2 	imes \dots 	imes R_n $$
  Adding components in series always *decreases* overall reliability.
* **Parallel (Redundant) Systems:** Only one component needs to function. The system fails only if *all* parallel components fail:
  $$ R_{sys} = 1 - (1-R_1)(1-R_2)\dots(1-R_n) $$
  Adding components in parallel always *increases* overall reliability.

## 17.2 Active vs. Standby Redundancy
* **Active Redundancy:** All redundant components are operating simultaneously (e.g., dual flight computers). If one fails, the other is already running.
* **Standby Redundancy:** The backup component is off and only activated when the primary fails. This preserves the lifespan of the backup but introduces the risk of the "switching mechanism" failing.

## 17.3 Markov Chain Modeling
Static RBDs are insufficient for complex systems that undergo continuous repair or exist in degraded states. **Markov Chains** are used to model the dynamic probability of a system transitioning between discrete states over time (e.g., State 0: Fully Operational, State 1: Primary Sensor Failed, State 2: Critical Failure). Transition rates between these states are governed by the component hazard rates $\lambda$ and repair rates $\mu$.

## System Integration
The culmination of the RCUAV reliability analysis is combining component-level data into a system-level Markov Chain model. Using MATLAB, you will simulate the vehicle's state transitions over its 100-flight lifecycle, proving to stakeholders that the fully integrated, 3D-printed architecture meets all safety and performance requirements.
