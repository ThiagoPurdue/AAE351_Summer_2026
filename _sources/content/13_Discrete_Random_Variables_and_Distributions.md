# Discrete Random Variables and Distributions

## 13.1 Defining Discrete Variables
A random variable is a numerical description of the outcome of a statistical experiment. A **discrete random variable** can only take on a countable number of distinct values. In aerospace, this typically represents counts: the number of bird strikes in a year, the number of failed bolts on a flange, or the number of successful missions before a failure.

## 13.2 Probability Mass Function (PMF)
The probability distribution of a discrete random variable is described by its Probability Mass Function (PMF), denoted $P(X=x)$ or $p(x)$. It provides the exact probability that the variable $X$ will take the value $x$. The sum of all probabilities in the PMF must equal 1:
$$ \sum p(x) = 1 $$

## 13.3 The Binomial Distribution
One of the most important discrete distributions in engineering is the **Binomial Distribution**. It models the number of 'successes' in $n$ identical, independent trials, where each trial has a constant probability of success $p$. The PMF is given by:
$$ P(X=k) = inom{n}{k} p^k (1-p)^{n-k} $$
This is widely used in quality control to determine the probability of finding exactly $k$ defective parts in a batch of $n$ manufactured components.

## System Integration
Discrete distributions are highly applicable to analyzing the RCUAV's fleet operations, such as predicting the number of failed print jobs out of a batch, or the number of successful cargo deliveries before a major maintenance overhaul is required.
