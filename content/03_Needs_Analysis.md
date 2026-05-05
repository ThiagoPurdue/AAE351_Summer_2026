# Needs Analysis

## 3.1 Understanding the Stakeholder
Before a single line of code is written or a CAD sketch is drawn, engineers must understand the fundamental problem they are trying to solve. This begins with **Stakeholder Elicitation**. Stakeholders are not just the immediate customers purchasing the aircraft; they include a broad spectrum of entities:
* **End-Users (Pilots/Operators):** Concerned with usability, range, and payload.
* **Maintainers:** Concerned with accessibility, diagnostics, and part replacement.
* **Regulatory Bodies (FAA/EASA):** Concerned strictly with safety, redundancy, and environmental impact.
* **Manufacturers:** Concerned with supply chain, tooling, and assembly complexity.

Gathering these needs often involves interviews, market research, and analyzing legacy systems. Crucially, stakeholder needs are usually qualitative and ambiguous (e.g., "The drone needs to be easy to fix in the field").

## 3.2 The Concept of Operations (ConOps)
The synthesis of these gathered needs forms the **Concept of Operations (ConOps)**. The ConOps is a descriptive document that narrates how the system will be used from the moment it is deployed to the completion of its mission. For a cargo UAV, the ConOps would describe:
1. **Pre-flight:** How is cargo loaded? How is the battery charged?
2. **Takeoff and Cruise:** Is it autonomous? What airspace is it operating in?
3. **Delivery:** How is the package dropped or unloaded?
4. **Post-flight:** Turnaround procedures and maintenance checks.

## 3.3 Translating Needs to Technical Metrics
The final step of needs analysis is beginning the transition from qualitative desires to quantitative metrics. If a stakeholder needs the aircraft to be "fast," the systems engineer must begin framing this as a specific cruise velocity requirement. This structured translation prevents misunderstandings late in the development cycle.

## System Integration
For the Regional Cargo UAV, stakeholder needs encompass not only the payload (50kg) and range (200km), but also the specific operational realities of a 3D-printed airframe. Needs analysis must capture the requirement for modular printability and material anisotropy. These needs will be formalized in the MATLAB Requirements Toolbox as the authoritative source of truth.
