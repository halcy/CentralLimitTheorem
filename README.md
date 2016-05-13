# CentralLimitTheorem
Visualization of the Central Limit Theorem

The central limit theorem states that, given certain conditions, the arithmetic mean of a sufficiently large number of iterates of independent random variables, each with a well-defined expected value and well-defined variance, will be approximately normally distributed, regardless of the underlying distribution.

The following code takes numVariables samples from either a uniform, exponential or binomial (binary, with P(1) = 0.4) distribution and calculates their mean. It does this numSamples times, collecting samples, and then draws their histogram.
