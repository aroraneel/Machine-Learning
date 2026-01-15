# Combined Cycle Power Plant Energy Output Prediction using Ridge Regression

## Overview
This project predicts the **energy output (PE)** of a **Combined Cycle Power Plant (CCPP)** using **Ridge Regression with Polynomial Features**.  
A complete **machine learning pipeline** is built to handle preprocessing, feature scaling, feature expansion, and model training in an efficient and reproducible way.

---

## Objective
- Predict power plant energy output based on environmental conditions  
- Handle missing values and scale features properly  
- Reduce overfitting using Ridge regularization  
- Capture non-linear relationships using polynomial features  

---

## Dataset
- **CCPP_data.csv**
- Features used:
  - `AT` – Ambient Temperature  
  - `V` – Exhaust Vacuum  
  - `AP` – Ambient Pressure  
  - `RH` – Relative Humidity  
- Target variable:
  - `PE` – Electrical Energy Output  

---

## Methodology
- Split dataset into training and testing sets (80–20)  
- Use **RidgeCV** to select the optimal regularization parameter (`alpha`)  
- Build a pipeline consisting of:
  - Median imputation for missing values  
  - Feature standardization  
  - Polynomial feature expansion (degree = 2)  
  - Ridge regression with the best alpha  
- Train the model and generate predictions  

---

## Evaluation
- **R² Score** used to evaluate regression performance  
- Scatter plot comparing actual vs predicted power output  

---

## Visualization
- Actual vs Predicted Power Output plot  
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
This project demonstrates how regularization and polynomial feature engineering can significantly improve regression performance in real-world energy prediction tasks.
