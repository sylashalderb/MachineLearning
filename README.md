Simple Linear Regression

Introduction

Simple Linear Regression is a basic supervised learning algorithm used for predicting a continuous dependent variable (Y) based on a single independent variable (X). It establishes a linear relationship between them.

Mathematical Foundation

1. Hypothesis Function

A simple linear regression model is represented as:



Where:

 is the predicted output (dependent variable)

 is the input feature (independent variable)

 is the slope (coefficient)

 is the intercept (bias term)

2. Cost Function (Mean Squared Error - MSE)

The objective of Simple Linear Regression is to minimize the difference between the actual values (Y) and the predicted values (). This difference is quantified using the Mean Squared Error (MSE):



Where:

 is the number of training examples

 is the cost function

 is the predicted value

3. Gradient Descent Optimization

To minimize the cost function , we use Gradient Descent, which updates the parameters iteratively as follows:





Where:

 is the learning rate

The gradients represent the direction of steepest descent

4. Normal Equation (Closed-Form Solution)

Instead of using Gradient Descent, we can directly compute the optimal parameters using the Normal Equation:



This method is computationally efficient for small datasets but can be slow for large datasets.

Implementation

A simple Python implementation of Simple Linear Regression using Gradient Descent can be found in linear_regression.py.

Applications

Simple Linear Regression is widely used in:

House price prediction

Stock price forecasting

Sales estimation

Medical diagnosis (e.g., predicting disease progression)

Conclusion

Simple Linear Regression is a fundamental concept in machine learning and statistics. Understanding its mathematical foundation provides insights into more advanced techniques like Multiple Linear Regression, Polynomial Regression, and Neural Networks.

