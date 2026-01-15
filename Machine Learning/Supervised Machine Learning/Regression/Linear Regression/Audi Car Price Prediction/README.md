# Audi Car Price Prediction using Linear Regression

## Overview
This project builds a **Linear Regression** model to predict the **price of Audi cars** based on vehicle specifications.  
Categorical features such as model, transmission, and fuel type are encoded numerically to make them suitable for regression.

---

## Objective
- Predict car prices using linear regression  
- Analyze the impact of vehicle specifications on price  
- Handle categorical variables through numeric encoding  
- Evaluate model performance using the R² score  

---

## Dataset
- **audi.csv**
- Features used:
  - `model`
  - `year`
  - `transmission`
  - `mileage`
  - `fuelType`
  - `tax`
  - `mpg`
  - `engineSize`
- Target variable:
  - `price`

---

## Data Preprocessing
- Encoded categorical columns:
  - `model` → numeric labels  
  - `transmission` → Automatic, Manual, Semi-Auto  
  - `fuelType` → Petrol, Diesel, Hybrid  
- Filled missing values with `0`  
- Verified dataset consistency  

---

## Methodology
- Feature and target selection  
- Train-test split (80–20)  
- Train Linear Regression model  
- Predict prices on test data  
- Evaluate performance using **R² score**

---

## Evaluation Metric
- **R² Score** for regression performance  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project demonstrates a basic regression approach for automobile price prediction and highlights the importance of preprocessing categorical data.
