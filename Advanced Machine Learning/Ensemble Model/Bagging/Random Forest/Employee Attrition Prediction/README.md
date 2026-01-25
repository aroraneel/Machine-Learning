# Employee Attrition Prediction using Random Forest

## Overview
This project analyzes **employee attrition** and builds a **Random Forest classification model** to predict whether an employee is likely to leave the organization.  
It covers the complete machine learning workflow, including data exploration, feature engineering, model training, evaluation, and hyperparameter tuning.

---

## Objective
- Understand key factors influencing employee attrition  
- Perform exploratory data analysis (EDA) and visualization  
- Build a robust classification model using Random Forest  
- Evaluate model performance using multiple metrics  
- Improve performance through cross-validation and hyperparameter tuning  

---

## Dataset
- **Dataset01-Employee_Attrition.csv**
- Target variable:
  - `left` (0 = Stayed, 1 = Left)
- Features include:
  - Satisfaction level, last evaluation
  - Number of projects, average monthly hours
  - Time spent in company
  - Work accident, promotion in last 5 years
  - Department, salary, and other HR-related attributes

---

## Data Preprocessing
- Removed duplicate records  
- Checked and handled missing values  
- Exploratory analysis using:
  - Bar charts
  - Histograms
  - Box plots  
- Encoded categorical features (`salary`, `Department`) using Label Encoding  
- Applied **StandardScaler** for feature scaling  

---

## Methodology
- Split data into training and testing sets (80–20)  
- Trained a **Random Forest Classifier**  
- Evaluated model using:
  - Confusion Matrix
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Classification Report  
- Analyzed **feature importance** to identify key drivers of attrition  

---

## Model Evaluation
- Confusion matrix visualization using heatmap  
- Cross-validation (K=5) to ensure model stability  
- Feature importance analysis to interpret model behavior  

---

## Hyperparameter Tuning
- Used **GridSearchCV** to tune:
  - `n_estimators`
  - `max_features`  
- Built a new optimized Random Forest model  
- Re-evaluated performance using cross-validation  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project demonstrates an end-to-end machine learning pipeline for HR analytics and highlights how ensemble models like Random Forest can effectively handle real-world classification problems.
