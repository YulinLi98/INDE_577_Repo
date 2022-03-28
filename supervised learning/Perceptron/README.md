# The Perceptron

The Perceptron is a supervised, single layer neural network binary classifier. It is a type of linear classifier. The model structure is depicted in the figure below.

![image](https://github.com/YulinLi98/Sample_Repo/blob/main/images/Perceptron.png)

Typically, training the perceptron includes 3 steps. 
1. We initialize the weights. Weights may be initialized to 0 or to small random values.
2. We choose an activation function and learning rate. For each sample in the training dataset, performing the following steps:
   1. With the input, weights and activation function, we calculate the actual output.
   2. With actual output, true label and learning rate, we update the weights.
3. The 2nd step may be repeated until the iteration error is less than a specified error threshold, or a predetermined number of iterations has been completed.  

The algorithm updates the weights after steps 2.1 and 2.2. These weights are immediately applied to a pair in the training set, and subsequently updated, rather than waiting until all pairs in the training set have undergone these steps.

In the jupyter notebook, I first built a perceptron class by scratch. Then I implemented it with the CVDs dataset. At last, I did some performance analysis.

# References
The above introduction is mainly based on https://en.wikipedia.org/wiki/Perceptron. The coding part is mainly based on Dr. Davila's Lecture Notes.