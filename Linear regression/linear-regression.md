# Linear Regression

## What it is
A **supervised learning** algorithm used to predict **continuous values** by fitting a straight line to data.

\[
y = wx + b
\]

---

## Objective
Minimize **Mean Squared Error (MSE)** between predicted and true values.

J(w,b) = \frac{1}{m}\sum_{i=1}^{m} \big( w x_i + b - y_i \big)^2
---

## How it works
- Initialize weights
- Predict output
- Compute error
- Update parameters using **Gradient Descent**
- Repeat until convergence

---

## Key assumptions
- Linear relationship
- Low noise
- No extreme outliers

---

## Pros
- Simple and fast  
- Easy to interpret  
- Strong baseline model  

---

## Cons
- Fails on non-linear data  
- Sensitive to outliers  

---

## Applications
- Trend analysis  
- Forecasting  
- System calibration  

---

## Files
- `linear_regression_from_scratch.ipynb`
- `linear_regression_sklearn.ipynb`