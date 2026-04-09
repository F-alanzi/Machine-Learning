# 📊 Machine Learning - Lab 6  
### Bias-Variance Tradeoff & Model Evaluation

This lab focuses on understanding one of the most important concepts in machine learning: the **bias-variance tradeoff**. Through simulation and experimentation, we analyze how different models perform under varying levels of noise and complexity.

---

## 📌 Objectives

- Understand the relationship between **bias**, **variance**, and **noise**
- Simulate a data-generating process
- Train machine learning models to approximate the underlying function
- Evaluate model performance using **Mean Squared Error (MSE)**
- Decompose error into:
  - Bias
  - Variance
  - Irreducible error (noise)

---

## 🧠 Key Concepts

### 🔹 Bias
Error due to overly simplistic assumptions in the model.

### 🔹 Variance
Error due to sensitivity to fluctuations in the training data.

### 🔹 Noise
Irreducible error inherent in the data generation process.

### 🔹 Mean Squared Error (MSE)
Used to measure model performance:

\[
MSE = Bias^2 + Variance + Noise
\]

---

## ⚙️ Methodology

### 1. Simulated Data Generation
We define a synthetic function:

\[
Y = f(X) + \epsilon
\]

- \( f(X) \): true underlying function  
- \( \epsilon \): random noise (normally distributed)

### 2. Model Training
- Fit polynomial regression models of varying complexity
- Train models on generated datasets

### 3. Repeated Experiments
- Run simulations multiple times (e.g., 1000 iterations)
- Store predictions for analysis

### 4. Evaluation
- Compute average predictions
- Calculate MSE
- Analyze bias and variance components

---

## 📈 Results & Observations

- **Low-complexity models** → high bias, low variance  
- **High-complexity models** → low bias, high variance  
- Optimal performance occurs at a balance between the two  

Noise introduces unavoidable error, even with the best model.

---

## 🛠️ Technologies Used

- Python / R (depending on implementation)
- Common libraries:
  - `numpy`, `pandas`
  - `matplotlib` / `ggplot2`
  - `scikit-learn` (if Python)

---

