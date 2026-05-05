# The System Development Process

## 2.1 The V-Model of Systems Engineering
The development of complex aerospace systems is universally guided by the **V-Model**. This framework provides a structured methodology for moving from abstract concepts to a fully verified and validated physical system. 

The left descending branch of the "V" represents the **Decomposition and Definition** of the system:
1. **System-Level Architecture:** Defining the overall mission and top-level requirements.
2. **Subsystem-Level Design:** Allocating functions to specific systems (e.g., Propulsion, Avionics).
3. **Component-Level Design:** Detailed engineering of individual parts (e.g., a specific 3D-printed structural rib).

As the project moves down the left side, the design matures from logical abstractions into physical realities.

The right ascending branch of the "V" represents **Integration and Testing**:
1. **Component Testing:** Verifying that a specific part meets its tolerances.
2. **Subsystem Integration:** Ensuring parts assemble and function together.
3. **System Integration and Flight Test:** Verifying the entire vehicle performs the mission.

## 2.2 Verification vs. Validation (V&V)
A critical distinction in systems engineering is the difference between Verification and Validation.
* **Validation:** Asks the question, *"Did we build the right system?"* This process ensures that the final product actually satisfies the original stakeholder needs and the Concept of Operations (ConOps).
* **Verification:** Asks the question, *"Did we build the system right?"* This process ensures that the physical system meets the rigid, quantitative technical requirements defined during the decomposition phase.

## 2.3 Phased Design Gateways
The development process is gated by formal reviews to manage risk:
* **System Requirements Review (SRR):** Ensures all requirements are defined and traceable.
* **Preliminary Design Review (PDR):** Establishes that the basic architecture is sound and meets requirements.
* **Critical Design Review (CDR):** Freezes the detailed design before manufacturing begins.

## System Integration
Applying the V-Model to our RCUAV project requires a clear mapping from stakeholder needs down to the physical 3D-printed components. The system development process dictates that before any CAD is generated, the logical and functional architectures must be solidified. You will use System Composer to define these early development stages, laying the groundwork for a traceable Digital Thread.
