# Diamond Price Prediction using Lasso Regression

## Overview
This project focuses on predicting **diamond prices** using **Lasso Regression with Polynomial Features**.  
Lasso regression is used to control model complexity through **L1 regularization**, which helps in feature selection and improves generalization on high-dimensional data.

A complete **machine learning pipeline** is implemented for clean preprocessing and modeling.

---

## Objective
- Predict diamond prices based on physical and quality attributes  
- Encode categorical diamond characteristics numerically  
- Apply Lasso regularization to reduce overfitting  
- Capture non-linear relationships using polynomial features  

---

## Dataset
- **diamonds.csv**
- Features used:
  - `carat`
  - `cut`
  - `color`
  - `clarity`
  - `depth`
  - `table`
  - `x`, `y`, `z`
- Target variable:
  - `price`

---

## Data Preprocessing
- Converted categorical features (`cut`, `color`, `clarity`) into numeric form  
- Handled missing values using median imputation  
- Standardized features for better convergence  
- Prepared data using a unified pipeline  

---

## Methodology
- Split data into training and testing sets (80–20)  
- Selected optimal regularization parameter using **LassoCV**  
- Built a pipeline with:
  - Median imputation  
  - Feature scaling  
  - Polynomial feature expansion (degree = 2)  
  - Lasso Regression with best alpha  
- Generated predictions on test data  

---

## Evaluation
- **R² Score** used to evaluate regression performance  
- Scatter plot comparing actual vs predicted diamond prices  

---

## Visualization
- Actual vs Predicted Diamond Price plot  
- Reference line indicating perfect predictions  

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
This project demonstrates how Lasso regression is effective for feature-rich regression problems and highlights the importance of regularization in price prediction tasks.
