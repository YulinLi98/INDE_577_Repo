# The Perceptron

The perceptron is an algorithm for supervised learning of binary classifiers. It is a type of linear classifier. There are generally four parts to implement perceptron, including input values, weights and bias, weighted sum and an activation function.

In this file, I applied the perceptron algorithm on the primary dataset, 2020 CDC Heart Disease Data. I chose the sign function as the activation fuction, and converted the 'HeartDisease' column my mapping 'Yes' to 1 and 'No' to -1. I also encoded other categorical variables by onehot encoding. Then I split the dataset into traning and testing data, trained the perceptron model on my training dataset and prredicted on the testing dataset. Finally, I did some performance analysis.