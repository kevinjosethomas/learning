The sigmoid function is a mathematical [[Activation Functions|activation function]] that represents [[Logistic Regression]].

![[Pasted image 20240604101122.png]]

The sigmoid function is modeled by
$$\sigma(z) \equiv \frac{1}{1 + e^{-z}}$$

Essentially, the sigmoid function bounds a value between 0 and 1, and is used for models to predict the probability of an output. The function is *differentiable*, which means we can find its slope at any point. However, the sigmoid function can cause a neural network to get stuck during training time. The [[Softmax Function]] is a more generalized logistic activation function that can be used for multiclass classification.

### Sources
- https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6