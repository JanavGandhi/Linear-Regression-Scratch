# Linear-Regression-Scratch

📌 Project Overview

This project implements Linear Regression from scratch using Python and Gradient Descent — without relying on machine learning libraries like scikit-learn.

Dataset: (x, y) points (scatter plot).

Goal: Fit the best line 
𝑦 = 𝑚𝑥+𝑏
that minimizes error.

Method: Gradient Descent optimization.

Output: Fitted line plotted alongside data points.

⚙️ How It Works

Initialize slope m and intercept b as 0.

Define a learning rate (L) and number of iterations (epochs).

Use gradient descent to iteratively update m and b.

After training, plot the best-fit line.


🧮 Math Behind Linear Regression

We want to fit a line:

<img width="255" height="69" alt="image" src="https://github.com/user-attachments/assets/394621b0-9769-4d1e-ae01-ff903cde4d2d" />

1. Error Function (MSE)

We use Mean Squared Error (MSE) to measure how good our line is:
MSE(m,b)=n1​i=1∑n​(yi​−(mxi​+b))2
