# Introduction to Reliability

## The Reliability Function
Reliability is the probability that a system will perform its required function under specified conditions for a stated period of time. If $T_F$ is the time to failure, the Cumulative Distribution Function (CDF), $F(t)$, is the probability of failing before time $t$:

$$ F(t) = P(T_F \le t) $$

The Reliability function, $R(t)$, is the probability of surviving past time $t$:

$$ R(t) = 1 - F(t) = P(T_F > t) $$

## System Integration
The core of the RCUAV's safety case lies in reliability engineering. You must synthesize the failure rates of traditional COTS components with the specific failure modes of 3D-printed structures (e.g., delamination). This synthesis forms the basis of the FMEA you will develop for the final Digital Thread.
