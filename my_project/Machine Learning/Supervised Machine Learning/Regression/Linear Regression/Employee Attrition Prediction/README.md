# Employee Attrition Prediction using Linear Regression

## Overview
This project uses **Linear Regression** to analyze employee data and predict whether an employee is likely to **leave the company or not** based on numerical features.

The focus is on understanding the relationship between employee attributes and attrition using a simple regression model.

---

## Objective
- Predict employee attrition (`LeaveOrNot`)
- Understand how factors like age, experience, and payment tier affect attrition
- Apply basic regression workflow using Scikit-learn

---

## Dataset
- **Employee dataset** loaded from CSV
- Categorical columns removed:
  - Education
  - City
  - Gender
  - EverBenched
- Features used:
  - JoiningYear  
  - PaymentTier  
  - Age  
  - ExperienceInCurrentDomain  
- Target:
  - `LeaveOrNot`

---

## Methodology
- Data preprocessing by dropping categorical columns  
- Train-test split (70% training, 30% testing)  
- Model trained using `LinearRegression`  
- Performance evaluated using **R² score**

---

## Evaluation
- Metric used: **R² Score**
- Measures how well the independent variables explain employee attrition

---

## Tools Used
- Python  
- Pandas  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | AI & Machine Learning  

---

## Notes
This project is for academic and learning purposes to understand regression-based prediction.
