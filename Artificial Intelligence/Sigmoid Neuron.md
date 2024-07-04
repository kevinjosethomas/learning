A sigmoid neuron is similar to a [[Perceptron]] but they are modified so that small changes in their weights and biases only cause a small change in their output. This allows a network of sigmoid neurons to learn. 

Just like a perceptron, the sigmoid neuron has inputs and outputs as well. However, they will not be binary. Inputs and outputs can take on any values between 0 and 1. Now, instead of the output being 0 or 1, it is:
$$\sigma(\mathbf{w} \cdot \mathbf{x} + \mathbf{b})$$
where $\sigma$ is the *sigmoid function* (logistic function).

## Sigmoid Function
The sigmoid function is defined by
$$\sigma(z) \equiv \frac{1}{1 + e^{-z}}$$

A sigmoid function shapes values between 0 and 1 so they look like the following:
![[Pasted image 20240701162759.png]]