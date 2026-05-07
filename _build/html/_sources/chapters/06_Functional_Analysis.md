# 06. Functional Analysis

## Translating Concepts into Architecture
During the Concept Definition phase, our main goal is to specify the complete functional architecture of our chosen concept. Functional analysis translates system requirements into a logical framework. It describes what the system must do before we specify physical hardware.

A function is an action the system must perform. We analyze how the system transforms **Signals, Data, Materials, and Energy/Force**.

## Tools for Functional Analysis
To organize this, we use several powerful diagramming methods:
- **Functional Block Diagram (FBD):** Shows physical or logical components, external entities (User, Environment), and their interconnections.
- **Functional Flow Block Diagram (FFBD):** Shows the hierarchical breakdown of functions (e.g., Make Coffee -> Prepare to Brew, Brew, Finish).
- **Functional Flow Diagram (FFD):** Focuses on the sequential order of operations and parallel paths (using AND/OR gates).
- **Sequence Diagram (SD):** Details interactions for a specific operational scenario over time.
- **IDEF0:** Maps Inputs, Controls, Outputs, and Mechanisms (ICOM).

## Complex System Example: Delivery Robot
Consider a Starship-style delivery robot (or our autonomous RCUAV). 
- *Store Cargo:* Requires locking the payload bay, insulating the compartment, and securing the contents.
- *Transport Cargo:* Requires path planning, supplying power to motors, and a continuous feedback loop checking GPS and sensors for obstacle avoidance.
- *Give Cargo:* Requires unlocking the bay, detecting removal, and returning to base.

By clearly defining these functions, we can seamlessly identify the physical 3D-printed components and avionics needed to perform them, bridging the gap between systems engineering and detailed design.
