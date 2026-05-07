# 04. Requirements Analysis

## The Role of Requirements
As Akin's 13th Law of Spacecraft Design states: *"Design is based on requirements. There is no justification for designing something one bit better than the requirements dictate."* Adding unnecessary features increases complexity and cost. 

A common myth is that "everyone knows what the product is about" or that "nothing can be done about bad requirements." In reality, requirements are the single biggest source of project problems. They dictate what needs to be done, how well, and under what constraints. The later you change a requirement, the more expensive it becomes.

## Developing Good Requirements
Good requirements should adhere to the **SMART** criteria (Simple, Measurable, Attainable, Relevant, Time-bound). Furthermore, they must have:
- **Independence:** Stand alone without relying on other requirements.
- **Verifiability:** Can be proven via Test, Analysis, Inspection, or Demonstration.
- **No Operational Descriptions:** State *what* must be done, not *how* it should be done.

*Poor Example:* "The system shall be diesel-powered." (Dictates the solution).
*Good Example:* "The system shall transport 20 passengers within a 50-mile radius."

## Verification vs. Validation
- **Verification:** Did we build the system right? (Checking against the quantitative requirements).
- **Validation:** Did we build the right system? (Checking against the original stakeholder needs).

## MOEs, MOPs, and Compliance Matrices
We use Measures of Effectiveness (MOEs) at the system level and Measures of Performance (MOPs) at the subsystem level. We can distinguish between *Threshold* (minimum acceptable) and *Target* (desired) values, and track them using a Compliance Matrix.

```python
import pandas as pd

# Creating a Compliance Matrix in Python
reqs_data = [
    {"Requirement": "Cruise Speed (m/s)", "Threshold": 15.0, "Target": 20.0, "Achieved": 18.5},
    {"Requirement": "Range (km)", "Threshold": 80.0, "Target": 100.0, "Achieved": 95.0},
    {"Requirement": "Empty Weight (kg)", "Threshold": 15.0, "Target": 12.0, "Achieved": 13.2}
]

df = pd.DataFrame(reqs_data)
print("Compliance Matrix:")
print(df.to_markdown(index=False))
```
