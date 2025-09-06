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

We want to fit a line:<br>

<img width="255" height="69" alt="image" src="https://github.com/user-attachments/assets/394621b0-9769-4d1e-ae01-ff903cde4d2d" />

1. Error Function (MSE)

We use Mean Squared Error (MSE) to measure how good our line is:<br>

<img width="437" height="116" alt="image" src="https://github.com/user-attachments/assets/640a4d6b-0d2f-4409-ae8a-6668bd5ddb05" />

2. Gradients

To minimize error, we compute derivatives:

For slope m:<br>
<img width="548" height="130" alt="image" src="https://github.com/user-attachments/assets/a89556e7-f9c3-4b9e-9a4f-4e99e9fcc4d5" />

For intercept b:<br>
<img width="499" height="123" alt="image" src="https://github.com/user-attachments/assets/c59e6eee-9b5c-4b07-9a4f-b1e6a316eaef" />

3. Update Rules

Using gradient descent, update m and b:<br>
<img width="345" height="151" alt="image" src="https://github.com/user-attachments/assets/5ebcb7b0-a05a-4f96-a4b8-1872928bb69e" />

Where L is the learning rate.




