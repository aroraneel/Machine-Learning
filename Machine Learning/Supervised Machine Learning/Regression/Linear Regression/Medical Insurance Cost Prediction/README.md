# Medical Insurance Cost Prediction using Linear Regression

## Overview
This project uses **Linear Regression** to predict **medical insurance charges** based on individual demographic and health-related factors.  
Categorical variables are encoded numerically, and the model performance is evaluated using the **R² score**.

---

## Objective
- Predict insurance charges using linear regression  
- Understand the impact of demographic and lifestyle features  
- Evaluate model performance on unseen data  

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
- Converted categorical variables into numeric form:
  - `sex`: male → 1, female → 0  
  - `smoker`: yes → 1, no → 0  
  - `region`: encoded into integer categories  

---

## Methodology
- Load and preprocess the dataset  
- Select relevant features and target variable  
- Split data into training and testing sets (70–30)  
- Train a Linear Regression model  
- Make predictions on test data  
- Evaluate performance using **R² score**

---

## Evaluation Metric
- **R² Score** to measure how well the model explains variance in insurance charges  

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
This project provides a simple yet effective example of applying linear regression to a real-world healthcare cost prediction problem.
