# Continuous Random Variables and Distributions

## 14.1 Probability Density Function (PDF)
Unlike discrete variables, **continuous random variables** can take on any value within an interval (e.g., exact flight time in hours, thrust output in Newtons). Because there are infinite possible values, the probability of the variable taking one exact value (e.g., exactly 10.000000N) is zero. Instead, we define the Probability Density Function (PDF), $f(x)$, where the area under the curve represents probability:
$$ P(a \le X \le b) = \int_{a}^{b} f(x) dx $$

## 14.2 The Normal Distribution
The **Normal (Gaussian) Distribution** is the most ubiquitous distribution in engineering due to the Central Limit Theorem. It describes variables that cluster around a mean value with a symmetrical bell-shaped curve. It is used to model manufacturing tolerances, aerodynamic noise, and sensor errors. It is defined by its mean $\mu$ and standard deviation $\sigma$.

## 14.3 The Exponential Distribution
The **Exponential Distribution** is foundational to reliability engineering. It describes the time between events in a Poisson process, making it the standard model for the lifespan of electronic components that do not "wear out" but fail randomly. Its PDF is:
$$ f(t) = \lambda e^{-\lambda t} 	ext{ for } t \ge 0 $$
where $\lambda$ is the constant failure rate.

## System Integration
Continuous variables like flight time, battery degradation, and cumulative stress on the 3D-printed wings are modeled using continuous distributions. These models will feed directly into your sizing scripts, ensuring the UAV meets the 100-flight lifecycle requirement.
