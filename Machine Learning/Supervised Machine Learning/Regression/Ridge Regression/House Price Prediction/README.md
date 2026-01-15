# House Price Prediction using Ridge Regression with Polynomial Features

## Overview
This project implements **Ridge Regression** with **Polynomial Features** to predict house prices using the **HousingData** dataset.  
A machine learning **pipeline** is used to handle missing values, feature scaling, feature expansion, and model training in a clean and reproducible way.

---

## Objective
- Predict median house prices (`MEDV`) using regression  
- Handle missing values and feature scaling efficiently  
- Reduce overfitting using Ridge regularization  
- Improve model capacity using polynomial features  

---

## Dataset
- **HousingData.csv**
- Features used:
  - `CRIM`, `ZN`, `INDUS`, `CHAS`, `NOX`, `RM`, `AGE`, `DIS`,
    `RAD`, `TAX`, `PTRATIO`, `B`, `LSTAT`
- Target variable:
  - `MEDV` (Median house price)

---

## Methodology
- Split data into training and testing sets (80–20)  
- Select optimal Ridge regularization parameter using **RidgeCV**  
- Build a pipeline consisting of:
  - Median imputation for missing values  
  - Feature standardization  
  - Polynomial feature expansion (degree = 2)  
  - Ridge regression with optimal alpha  
- Train the model and generate predictions  

---

## Evaluation
- **R² Score** used to measure model performance  
- Scatter plot of actual vs predicted house prices to visualize accuracy  

---

## Visualization
- Actual vs Predicted price comparison plot  
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
This project demonstrates the effective use of pipelines and regularization techniques to build robust regression models for real-world datasets.
