# Medical Insurance Cost Prediction using Lasso Regression

## Overview
This project predicts **medical insurance charges** using **Lasso Regression with Polynomial Features**.  
Lasso regression is used to perform **regularization and feature selection**, helping reduce overfitting while identifying the most influential factors affecting insurance costs.

A complete **machine learning pipeline** is implemented to ensure clean preprocessing and reproducible modeling.

---

## Objective
- Predict medical insurance charges accurately  
- Handle categorical and missing data effectively  
- Apply Lasso regularization to control model complexity  
- Capture non-linear relationships using polynomial features  

---

## Dataset
- **insurance.csv**
- Features used:
  - `age`
  - `sex`
  - `bmi`
  - `children`
  - `smoker`
  - `region`
- Target variable:
  - `charges`

---

## Data Preprocessing
- Encoded categorical variables into numeric values  
- Filled missing values using median imputation  
- Ensured dataset consistency before training  

---

## Methodology
- Split data into training and testing sets (80–20)  
- Selected optimal regularization strength using **LassoCV**  
- Built a pipeline consisting of:
  - Median imputation  
  - Feature standardization  
  - Polynomial feature expansion (degree = 2)  
  - Lasso Regression with optimal alpha  
- Generated predictions on unseen test data  

---

## Evaluation
- **R² Score** used to measure regression performance  
- Scatter plot comparing actual vs predicted insurance charges  

---

## Visualization
- Actual vs Predicted Medical Charges plot  
- Reference line representing perfect prediction  

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
This project demonstrates how Lasso regression helps control overfitting and highlights the importance of regularization in real-world regression problems.
