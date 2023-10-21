### Trust Region Policy Optimization
date: oct 3rd 2023


### Learning Neural Network Policies with Guided Policy Search under Unknown Dynamics
date: Oct 8th 2023
summary:
use iteratively refitted local linear models to optimize trajectory distributions
can handle nonlinear and even discontinuous dynamics
given KL-Divergence constraints and set transition to be gaussian distribution, we get very good linear approximations
(check cs285 lecture slides)

### Weight Uncertainty in Neural Networks
date: Oct 12, 2023
summary:
goal in rl context - for better exploration
method - Bayesian backpropagation (use an ensemble of nenural networks)
treating expectation under posterior as an ensemble of an uncountably infinite number of neural networks