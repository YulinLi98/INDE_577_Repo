# The Perceptron

The Perceptron is a supervised, single layer neural network binary classifier. It is a type of linear classifier.

Typically, training the perceptron includes 3 steps. 
- 1. We initialize the weights. Weights may be initialized to 0 or to a small random value.
- 2. We choose an activation function. For each sample in the training dataset, performing the following steps:
  - a. With the input, weights and activation function, we calculate the actual output.
  - b. With actual outputs, true labels and learning rate, we update the weights.
- 3. The 2nd step may be repeated until the iteration error is less than a specified error threshold, or a predetermined number of iterations has been completed.  