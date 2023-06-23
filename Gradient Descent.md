It's an optimization algorithm for finding a local minimum of a differentiable function. The basic operation is applying partial derivatives over the cost function on each parameter being learned.

For example, for a [[cost function]] J which has theta as the parameter, with alpha as the learning rate, the optimization of theta would be:

$$
\theta_i = \theta_i - \alpha \frac{\partial}{\partial \theta_i} J(\theta)
$$