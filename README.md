# Linear-Regression-Scratch

📌 Project Overview

This project implements Linear Regression from scratch using Python and Gradient Descent — without relying on machine learning libraries like scikit-learn.

Dataset: (x, y) points (scatter plot).

Goal: Fit the best line 
𝑦
=
𝑚
𝑥
+
𝑏
y=mx+b that minimizes error.

Method: Gradient Descent optimization.

Output: Fitted line plotted alongside data points.

⚙️ How It Works

Initialize slope m and intercept b as 0.

Define a learning rate (L) and number of iterations (epochs).

Use gradient descent to iteratively update m and b.

After training, plot the best-fit line.

🧮 Math Behind Linear Regression

We want to fit a line:

𝑦
=
𝑚
𝑥
+
𝑏
y=mx+b
1. Error Function (MSE)

We use Mean Squared Error (MSE) to measure how good our line is:

MSE
(
𝑚
,
𝑏
)
=
1
𝑛
∑
𝑖
=
1
𝑛
(
𝑦
𝑖
−
(
𝑚
𝑥
𝑖
+
𝑏
)
)
2
MSE(m,b)=
n
1
	​

i=1
∑
n
	​

(y
i
	​

−(mx
i
	​

+b))
2
2. Gradients

To minimize error, we compute derivatives:

For slope 
𝑚
m:

∂
∂
𝑚
MSE
(
𝑚
,
𝑏
)
=
−
2
𝑛
∑
𝑖
=
1
𝑛
𝑥
𝑖
⋅
(
𝑦
𝑖
−
(
𝑚
𝑥
𝑖
+
𝑏
)
)
∂m
∂
	​

MSE(m,b)=
n
−2
	​

i=1
∑
n
	​

x
i
	​

⋅(y
i
	​

−(mx
i
	​

+b))

For intercept 
𝑏
b:

∂
∂
𝑏
MSE
(
𝑚
,
𝑏
)
=
−
2
𝑛
∑
𝑖
=
1
𝑛
(
𝑦
𝑖
−
(
𝑚
𝑥
𝑖
+
𝑏
)
)
∂b
∂
	​

MSE(m,b)=
n
−2
	​

i=1
∑
n
	​

(y
i
	​

−(mx
i
	​

+b))
3. Update Rules

Using gradient descent, update 
𝑚
m and 
𝑏
b:

𝑚
←
𝑚
−
𝐿
⋅
∂
∂
𝑚
MSE
m←m−L⋅
∂m
∂
	​

MSE
𝑏
←
𝑏
−
𝐿
⋅
∂
∂
𝑏
MSE
b←b−L⋅
∂b
∂
	​

MSE

Where L = learning rate.
