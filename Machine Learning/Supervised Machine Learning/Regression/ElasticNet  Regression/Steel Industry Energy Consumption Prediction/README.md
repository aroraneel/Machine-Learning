# Steel Industry Energy Consumption Prediction using ElasticNet Regression

## Overview
This project predicts **energy consumption (Usage_kWh)** in the steel industry using **ElasticNet Regression with Polynomial Features**.  
ElasticNet combines L1 and L2 regularization, making it effective for datasets with correlated energy and power-related features.

A machine learning **pipeline** is used to streamline preprocessing, feature engineering, and model training.

---

## Objective
- Predict industrial energy usage based on electrical and environmental factors  
- Handle correlated features using ElasticNet regularization  
- Reduce overfitting while capturing non-linear patterns  

---

## Dataset
- **Steel_industry_data.csv**
- Features used:
  - `Lagging_Current_Reactive.Power_kVarh`
  - `Leading_Current_Reactive_Power_kVarh`
  - `CO2(tCO2)`
  - `Lagging_Current_Power_Factor`
  - `Leading_Current_Power_Factor`
  - `NSM`
- Target variable:
  - `Usage_kWh`

---

## Data Preprocessing
- Removed non-numeric categorical columns  
- Handled missing values using median imputation  
- Standardized features for stable training  

---

## Methodology
- Train-test split (80–20)  
- Optimal regularization strength selected using **ElasticNetCV**  
- Pipeline steps:
  - Median imputation  
  - Feature scaling  
  - Polynomial feature expansion (degree = 2)  
  - ElasticNet regression with best alpha  
- Generated predictions on test data  

---

## Evaluation
- **R² Score** used to measure model performance  
- Scatter plot comparing actual vs predicted energy usage  

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
This project highlights the effectiveness of ElasticNet regression for industrial energy prediction and demonstrates how regularization improves model generalization on real-world datasets.
