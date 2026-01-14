# Banknote Authentication using Decision Tree Regression

## Overview
This project applies a **Decision Tree Regressor** to the Banknote Authentication dataset to understand how tree-based regression models learn patterns from numerical features. The focus is on model training, visualization, evaluation, and hyperparameter tuning.

---

## Objective
- Build a Decision Tree Regression model  
- Analyze model depth and performance  
- Visualize the decision tree structure  
- Evaluate using R² and Mean Squared Error  
- Improve performance using GridSearchCV  

---

## Dataset
- **BankNote_Authentication.csv**
- Features:
  - `variance`
  - `skewness`
  - `curtosis`
  - `entropy`
- Target:
  - `class`

---

## Methodology
- Load and explore the dataset  
- Check shape, statistics, and missing values  
- Split data into training and testing sets  
- Train a Decision Tree Regressor (`max_depth = 3`)  
- Visualize the regression tree  
- Evaluate using:
  - R² Score
  - Train & Test Mean Squared Error  
- Apply **cost complexity pruning**  
- Tune hyperparameters using **GridSearchCV**  

---

## Evaluation Metrics
- R² Score  
- Mean Squared Error (Train & Test)  

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
This project demonstrates decision tree regression, pruning techniques, and hyperparameter optimization for improving model generalization.
