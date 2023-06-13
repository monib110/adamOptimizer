# adamOptimizer

This is an Adam optimizer implementation from scratch..


Gradient descent is an optimization algorithm that follows the negative gradient of
an objective function in order to locate the minimum of the function.

A limitation of gradient descent is that a single step size (learning rate)
is used for all input variables. Extensions to gradient descent like AdaGrad and RMSProp
update the algorithm to use a separate step size for each input variable but may result
in a step size that rapidly decreases to very small values.

The Adaptive Movement Estimation algorithm, or Adam for short, is an extension to
gradient descent and a natural successor to techniques like AdaGrad and RMSProp
that automatically adapts a learning rate for each input variable for the objective function
and further smooths the search process by using an exponentially decreasing moving average
of the gradient to make updates to variables.
