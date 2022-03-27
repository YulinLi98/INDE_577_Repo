# The Perceptron

In this file, I will apply the perceptron algorithm on the primary dataset, 2020 CDC Heart Disease Data and then evaluate the performance.

## Introduction

The perceptron is an algorithm for supervised learning of binary classifiers. It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

Perceptrons are trained in three phases:
#### Phase 1 - Data Processiing
The Perceptron is a binary classifier, meaning the result is meant to classify the input into two groups. In this place, I change the 'HeartDisease' column by replacing 'Yes' with 1 and 'No' with -1, as the activation funciton I chose is the sign function.
