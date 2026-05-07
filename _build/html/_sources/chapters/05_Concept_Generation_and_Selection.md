# 05. Concept Generation and Selection

## Expanding the Design Space
Once requirements are defined, we transition from the problem space to the solution space. Concept generation requires broad, unconstrained thinking to ensure we don't miss promising concepts.

## Brainstorming and Morphological Charts
**Brainstorming** rules require us to generate a large quantity of ideas without criticism. Wild ideas are welcome, and team members should build upon each other's concepts.
For a more structured approach, we use **Morphological Charts**. We list the primary functions the vehicle must perform on one axis, and every possible physical mechanism on the other. Connecting different mechanisms generates unique architectures.

## Pugh's Method (Controlled Convergence)
Stuart Pugh's method combines generation and selection, fostering team ownership. The steps include:
1. Choose criteria based on requirements (do not assign weights yet).
2. Form a matrix of concepts.
3. Choose a "Datum" (baseline) concept.
4. Run the matrix: score each concept against the Datum as Better (+), Worse (-), or Same (S).
5. Attack the negatives and enhance the positives (create hybrid concepts!).
6. Choose a new Datum and iterate until the best concepts emerge.

## Weighted Objectives
For final selection among top concepts, we use Weighted Objectives. Criteria are assigned weights, and concepts are scored quantitatively to rank the alternatives.

```python
import numpy as np

# A simplified Python evaluation of Weighted Objectives for our 3D Printed UAV
criteria = ["Manufacturability (Print Time)", "Aerodynamic Efficiency", "Payload Capacity"]
weights = np.array([0.5, 0.2, 0.3]) # Note the high weight on printability

# Scores for Concept A (Flying Wing) vs Concept B (Conventional) on a scale of 1-10
concept_a_scores = np.array([4, 8, 5])
concept_b_scores = np.array([8, 6, 7])

score_a = np.dot(weights, concept_a_scores)
score_b = np.dot(weights, concept_b_scores)

print(f"Flying Wing Total Score: {score_a:.1f}")
print(f"Conventional Total Score: {score_b:.1f}")
```
