# Introduction to Reliability

## 15.1 Defining Reliability in Systems Engineering
In the context of aerospace engineering, **Reliability** is formally defined as the probability that a system or component will perform its required, intended function under specified operating conditions for a stated period of time. It is not merely a qualitative measure of "robustness," but a strict, mathematical probability function ranging from 0 to 1.

## 15.2 Time to Failure and the CDF
Reliability is fundamentally tied to time. Let $T_F$ be a continuous random variable representing the "Time to Failure" of a component. The Cumulative Distribution Function (CDF), denoted $F(t)$, represents the probability that the component will fail *before or at* time $t$:
$$ F(t) = P(T_F \le t) $$
This function is also known as the "Unreliability" function, as it tracks the cumulative likelihood of failure accumulating over time.

## 15.3 The Reliability Function
The true **Reliability Function**, $R(t)$, is the logical complement of the CDF. It represents the probability that the component survives *past* time $t$:
$$ R(t) = 1 - F(t) = P(T_F > t) $$
At $t=0$, reliability $R(0) = 1$ (assuming the component is not dead-on-arrival). As $t ightarrow \infty$, $R(t) ightarrow 0$, acknowledging that all physical systems eventually fail.

## System Integration
The core of the RCUAV's safety case lies in reliability engineering. You must synthesize the failure rates of traditional COTS components with the specific failure modes of 3D-printed structures (e.g., delamination). This synthesis forms the basis of the FMEA you will develop for the final Digital Thread.
