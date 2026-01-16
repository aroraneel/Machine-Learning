# Superconductivity Critical Temperature Prediction using ElasticNet Regression

## Overview
This project predicts the **critical temperature (`critical_temp`) of superconducting materials** using **ElasticNet Regression with Polynomial Features**.  
ElasticNet combines **L1 (Lasso)** and **L2 (Ridge)** regularization, making it well-suited for **high-dimensional scientific datasets** with correlated features.

A complete **machine learning pipeline** is used for preprocessing, feature engineering, and model training.

---

## Objective
- Predict superconducting critical temperature from material properties  
- Handle high-dimensional and correlated features effectively  
- Reduce overfitting using ElasticNet regularization  
- Capture non-linear relationships using polynomial features  

---

## Dataset
- **Superconduct Dataset** (via OpenML)
- Features:
  - Atomic, electronic, thermal, and valence-related properties  
  - Includes statistical descriptors such as mean, weighted mean, entropy, range, and standard deviation  
- Target variable:
  - `critical_temp`

---

## Data Preprocessing
- Checked and handled missing values using **median imputation**  
- Standardized features for stable optimization  
- Used polynomial feature expansion (degree = 2)  

---

## Methodology
- Train-test split (80–20)  
- Optimal regularization parameter selected using **ElasticNetCV**  
- Built a pipeline with:
  - Median imputation  
  - Feature scaling  
  - Polynomial feature generation  
  - ElasticNet regression with best alpha  
- Generated predictions on unseen test data  

---

## Evaluation
- **R² Score** used to evaluate regression performance  
- Scatter plot comparing actual vs predicted critical temperatures  

---

## Visualization
- Actual vs Predicted Critical Temperature plot  
- Reference line indicating perfect prediction  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project demonstrates the effectiveness of ElasticNet regression for complex, high-dimensional scientific datasets and highlights the importance of regularization in materials science prediction tasks.
