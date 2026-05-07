# 03. Needs Analysis

## Identifying Needs: Explicit vs. Latent
A fundamental rule in systems engineering is that any system we develop must be centered on the needs of stakeholders, customers, and end-users. Needs can originate from an *operational deficiency* (e.g., an aging fleet) or a *technological opportunity* (e.g., a new efficient engine). 

When engaging with stakeholders, we must distinguish between:
- **Explicit Needs:** Clearly stated requirements (e.g., "Replace the aging cargo fleet").
- **Latent Needs:** Implied or unspoken needs (e.g., "Improve operational efficiency and safety while doing so").

Missing a critical real need can compromise the entire system. Needs must drive the specifications, not the other way around.

## The Mission Statement
The mission statement is the first step in the requirements analysis process. It must be clear, concise, and convey the purpose of the system without prescribing a specific product or solution. It describes *capabilities and benefits*, not detailed technical specs.

*Poor Example (A Requirement):* "The camera payload must capture at least one daytime image of the U.S. West Coast."
*Good Example (A Mission Statement):* "Investigate the effect of Earth's magnetic field on atomic oxygen in the upper atmosphere through dual antenna sensing."

## Concept of Operations (ConOps)
The ConOps describes how a system will operate across all lifecycle phases to meet stakeholder expectations. A helpful approach is to tell the story of "a day in the life" of your system. For our RCUAV, this includes pre-flight loading, autonomous cruise, package delivery, and post-flight maintenance. Mapping out the operational phases (like an aircraft mission profile of altitude vs. distance) is a great way to visualize the ConOps.

## System Integration
We can capture these needs and ConOps elements programmatically to ensure they flow down into our design scripts:

```python
rcuav_mission = {
    "Primary Market": "Rural medical clinics",
    "Key Capability": "Autonomous payload delivery under 100km",
    "Constraints": "Must be 100% 3D-printable on desktop FDM printers"
}

# A simple text-based ConOps trace
print(f"Mission Statement: Provide {rcuav_mission['Key Capability']} to {rcuav_mission['Primary Market']}.")
```
