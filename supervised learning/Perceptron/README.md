# The Perceptron

The Perceptron is a supervised, single layer neural network binary classifier. It is a type of linear classifier.

Typically, training the perceptron includes 3 steps. 
1. We initialize the weights. Weights may be initialized to 0 or to small random values.
2. We choose an activation function and learning rate. For each sample in the training dataset, performing the following steps:
   1. With the input, weights and activation function, we calculate the actual output.
   2. With actual output, true label and learning rate, we update the weights.
3. The 2nd step may be repeated until the iteration error is less than a specified error threshold, or a predetermined number of iterations has been completed.  

The algorithm updates the weights after steps 2a and 2b. These weights are immediately applied to a pair in the training set, and subsequently updated, rather than waiting until all pairs in the training set have undergone these steps.

In this repository, we first build a perceptron class by scratch. Then we implement it with the CVDs dataset. At last, we do the performance analysis.