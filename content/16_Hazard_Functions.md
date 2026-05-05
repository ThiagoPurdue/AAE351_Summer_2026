# Hazard Functions

## Understanding Failure Rates
The hazard function, or failure rate $\lambda(t)$, represents the instantaneous rate of failure at time $t$, given that the component has survived up to time $t$. It is defined as:

$$ \lambda(t) = rac{f(t)}{R(t)} $$

## The Bathtub Curve
Most aerospace components follow a 'bathtub curve' hazard function: high infant mortality initially, a constant failure rate during the useful life, and an increasing failure rate during wear-out.

## System Integration
Modeling the hazard function, $\lambda(t)$, for the RCUAV requires understanding how 3D-printed materials fatigue over time. Unlike metal, plastics may exhibit an accelerated 'wear-out' phase due to cyclic loading on the layer lines. This hazard function will directly drive the state transitions in your reliability models.
