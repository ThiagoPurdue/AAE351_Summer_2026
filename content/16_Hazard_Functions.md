# Hazard Functions

## 16.1 The Instantaneous Failure Rate
While the Reliability function $R(t)$ tells us the overall probability of survival from $t=0$, engineers often need to know the failure rate *right now*, assuming the component hasn't failed yet. This conditional failure rate is known as the **Hazard Function**, $\lambda(t)$.
It is mathematically defined as the ratio of the probability density function of failure, $f(t)$, to the current reliability:
$$ \lambda(t) = rac{f(t)}{R(t)} $$
If $\lambda(t)$ is constant, it means the component does not age or wear out; failures are purely random (modeled by the Exponential Distribution).

## 16.2 The Bathtub Curve
Most aerospace components exhibit a hazard function that looks like a bathtub:
1. **Infant Mortality (Decreasing $\lambda(t)$):** High early failure rates due to manufacturing defects. This is mitigated by "burn-in" testing before deployment.
2. **Useful Life (Constant $\lambda(t)$):** A low, flat failure rate where failures are random stress events.
3. **Wear-out (Increasing $\lambda(t)$):** Failure rate spikes at the end of life due to fatigue, corrosion, and material degradation.

## 16.3 Mean Time Between Failures (MTBF)
For repairable systems in the "Useful Life" phase (constant hazard rate $\lambda$), the Mean Time Between Failures is the inverse of the failure rate:
$$ MTBF = rac{1}{\lambda} $$
This metric is crucial for defining maintenance schedules and logistics.

## System Integration
Modeling the hazard function, $\lambda(t)$, for the RCUAV requires understanding how 3D-printed materials fatigue over time. Unlike metal, plastics may exhibit an accelerated 'wear-out' phase due to cyclic loading on the layer lines. This hazard function will directly drive the state transitions in your reliability models.
