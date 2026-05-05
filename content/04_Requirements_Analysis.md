# Requirements Analysis (Continued)

## 4.4 Requirement Verification Methods
Authoring a requirement is only half the battle; the systems engineer must also define exactly how compliance will be proven. During the Requirements Analysis phase, a verification method is assigned to every requirement:
1. **Inspection:** A visual check (e.g., "The wingspan shall not exceed 2 meters" can be verified with a tape measure).
2. **Analysis:** Using mathematical models or simulations (e.g., "The wing shall withstand a 3G load" might be verified via Finite Element Analysis before physical testing).
3. **Demonstration:** Observing the operation of the system without quantitative measurement (e.g., "The landing gear shall deploy within 3 seconds").
4. **Test:** A formal, quantitative measurement under controlled conditions (e.g., "The motor shall provide 50 Newtons of static thrust").

## 4.5 Managing Requirements in the Digital Thread
In modern aerospace engineering, requirements are not kept in static documents. They are managed in dynamic, model-based systems engineering (MBSE) environments. This ensures that if a requirement changes (e.g., the customer increases the payload from 50kg to 60kg), the software immediately flags all linked aerodynamic models, structural analyses, and propulsion sizing scripts that must be re-evaluated.

## System Integration
Translating the RCUAV stakeholder needs into formal 'Shall' statements is the foundation of our Digital Thread. In the Requirements Toolbox, you must specify structural requirements that account for the 'Print-to-Weight' trade-offs of materials like PLA+ or PETG, ensuring every requirement is verifiable and traceable to the mission ConOps.
