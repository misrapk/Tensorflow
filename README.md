# Tensorflow
TensorFlow is a free and open-source software library for dataflow and differentiable programming across a range of tasks. It is a symbolic math library, and is also used for machine learning applications such as neural networks.

# OverView
# cost function
We can use the cost function to measure how far off we are from the expected vlaue. We'll use following variabel:

y to represent the true value
a to represent neuron'sprediction
In terms of weights and bias:

w*x + b =z
pass z into avtivation function sigma(z) = a

Quadratic Cost 

 C= sum(sq(y-a))/n

​

​

#### Cross Entropy
 C = (-1/n) sum(y.ln(a) + (1-y).ln(1-a))

The cost function allows for faster learning 

The larger the difference the faster the neuron can learn

Gradient Descent and Backpropogation
Gradient Descent
Gradient Descent is an optimization algo for finding the minimum of a function. Using Gradient Descent we can figure out the best parameters for minimizing our cost, for eg, finding the best values for the weights of neuron inputs.

Backpropogation
It is used to calculate the error contribution of each neuron after a batch of data is processed. It relies heaviley on the chain rule to go back through the network and calculate these errors. It require a known desired output for each input value(supervies learning).


