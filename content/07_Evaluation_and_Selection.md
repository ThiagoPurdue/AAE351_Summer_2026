# Evaluation and Selection

## 7.1 Objective Decision Making
Engineering is about making choices under constraint. When multiple viable concepts exist, systems engineers must avoid subjective bias (e.g., "I like the quadcopter because it looks cool") and use objective evaluation frameworks.

## 7.2 The Pugh Matrix
The **Pugh Matrix** is a standard industry tool for concept selection. One concept is chosen as the "Datum" or baseline (often an existing, legacy system). All other concepts are evaluated against the Datum across a list of weighted criteria derived directly from the stakeholder needs (e.g., Cost, Range, Manufacturability). 
Concepts are scored as '+1' (better than Datum), '0' (same), or '-1' (worse). The weighted sum dictates the winning architecture.

## 7.3 Sensitivity Analysis
Because early-phase concept selection relies heavily on estimates, the winning concept might change if the estimates are slightly wrong. Sensitivity analysis involves changing the weightings of the criteria (e.g., prioritizing range over cost) to see if the "winner" changes. If the same concept wins regardless of minor shifts in weighting, the decision is robust.

## System Integration
Using tools like the Pugh Matrix, you will evaluate competing RCUAV architectures. The evaluation criteria must heavily weight Additive Manufacturing constraints—such as print time, required support structures, and assembly complexity—against aerodynamic efficiency and payload capacity.
