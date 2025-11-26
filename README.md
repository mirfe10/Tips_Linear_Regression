# Tips_Linear_Regression
A simple Linear Regression demo using Python and scikit-learn. Trains a model, makes predictions, and evaluates performance using MAE, MSE, and R² Score.

📌 Linear Regression Overview

Linear Regression is one of the simplest and most commonly used machine learning algorithms. It models the relationship between one or more independent variables and a dependent variable by fitting a straight line to the data.

The model uses the equation:

𝑦
=
𝑏
0
+
𝑏
1
𝑥
y=b
0
	​

+b
1
	​

x

x: Independent variable

y: Target variable

b₀, b₁: Parameters learned by the model

📌 What This Project Does

Loads and splits the dataset into training and testing sets

Trains a LinearRegression() model from scikit-learn

Evaluates the model using MAE, MSE, and R² Score

✔ MAE (Mean Absolute Error)

Shows the average absolute difference between predictions and actual values. Closer to 0 is better.

✔ MSE (Mean Squared Error)

Measures the average squared error. Penalizes larger mistakes more heavily. Lower is better.

✔ R² Score

Indicates how well the model explains the variance in the data.

1.0 → Perfect fit

0 → No explanatory power

Negative → Worse than predicting the mean

If your R² is 1.0, it means the model fits the data perfectly — usually because the dataset is simple, small, or highly linear.

📌 What This Example Demonstrates

This project provides a simple demonstration of:

How a linear regression model works

How to train a model using scikit-learn

How to evaluate predictions with multiple error metrics

What each metric means in practice
