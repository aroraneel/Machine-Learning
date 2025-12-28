# Diabetes Progression Prediction Using Ridge Regression

## Overview
This project applies **Ridge Regression** to predict **disease progression in diabetes patients** using clinical and physiological measurements.  
It demonstrates a complete **regression workflow**, from data loading to model evaluation and visualization.

---

## Objective
- Predict diabetes disease progression based on medical features  
- Apply Ridge Regression to handle multicollinearity  
- Evaluate model performance using the **R² score**  

---

## Dataset
- **Diabetes Dataset** (from `sklearn.datasets`)
- A standard benchmark dataset for regression tasks

### Features Used
- Age (`age`)
- Sex (`sex`)
- Body Mass Index (`bmi`)
- Blood Pressure (`bp`)
- Serum measurements (`s1`, `s2`, `s3`, `s4`, `s5`, `s6`)

### Target Variable
- `target` → Quantitative measure of diabetes disease progression

---

## Machine Learning Model
- **Ridge Regression**
  - Uses **L2 regularization**
  - Reduces overfitting and stabilizes coefficient estimates
- Model parameter:
  - `alpha = 1.0`

---

## Training Process
- Dataset split into training and testing sets (80/20)
- Model trained on training data
- Predictions generated on unseen test data

---

## Model Evaluation
- **R² Score (Coefficient of Determination)** used to measure performance
- Scatter plot of **Actual vs Predicted** values
- Reference diagonal line represents perfect prediction

---

## Results
- Ridge Regression provides stable and consistent predictions
- Regularization improves generalization on unseen data
- Visualization highlights prediction accuracy and error spread

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

## Notes
This README provides a brief overview of the project structure and methodology.
