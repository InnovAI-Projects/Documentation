# Linear_Regression_(LR)

## What is Linear Regression?
Linear Regression is a type of supervised learning algorithm used in machine learning and statistics. It is used to predict a continuous target variable based on one or more input features. The relationship between the input features and the target is assumed to be linear.

## How does it work?
The goal of LR is to minimize the residual sum of squares between the observed targets in the dataset, and the targets predicted by the linear approximation. Each individual node can be thought of as its own linear regression model, composed of input data, weights, a bias (or threshold), and an output. The output is passed through an activation function, which determines the output. If that output exceeds a given threshold, it “fires” (or activates) the node, passing data to the next layer in the network.

## Example of Linear Regression
Imagine we have a dataset of houses for a specific city, where we are given the number of bedrooms for each house as well as the price of each house. We can use this existing dataset to predict how much a new house will cost by trying to create a straight line, or in other terms, a linear function, which models the relationship between these two parameters (bedroom count and price). If a new house enters the dataset, all we need to do is take the number of bedrooms in that house and read off the price that our line marks at that specific number of bedrooms.

## Implementing Linear Regression
Linear regression can be implemented both from scratch as well as with the popular library scikit-learn in Python. The implementation involves finding the best fit line, using methods like the Normal Equation or Gradient Descent, and then using this line to predict the target variable.

## When to use Linear Regression?
Linear regression is best used when there is a clear linear relationship between the input features and the target variable. It is also useful when you want to understand the impact of each feature on the target variable, as the coefficients in a linear regression model give you this information.
