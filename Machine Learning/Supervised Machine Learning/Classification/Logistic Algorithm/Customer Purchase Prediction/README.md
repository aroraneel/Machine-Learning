# Customer Purchase Prediction using Logistic Regression

## Overview
This project demonstrates how **Logistic Regression** can be used to predict whether a customer will make a purchase based on their **Age** and **Time Spent on a Website**.  
It also illustrates how to evaluate a classification model using the **ROC Curve** and **AUC score**.

---

## Objective
- Analyze customer behavior data
- Build a binary classification model to predict purchase status
- Visualize customer patterns using scatter plots
- Evaluate model performance using ROC and AUC

---

## Dataset
- **customer_purchase_data.csv**
- Features used:
  - `Age`
  - `TimeSpentOnWebsite`
- Target variable:
  - `PurchaseStatus` (0 = No Purchase, 1 = Purchase)

---

## Data Exploration & Visualization
- Scatter plot of **Age vs Time Spent on Website**
- Visualization helps identify patterns related to purchase behavior

---

## Model Development
- **Algorithm:** Logistic Regression
- Input features: Age, TimeSpentOnWebsite
- Data split:
  - Training set: 90%
  - Test set: 10%

---

## Model Evaluation
The model is evaluated using:
- Accuracy score
- ROC Curve (Receiver Operating Characteristic)
- AUC Score (Area Under the Curve)

These metrics help assess how well the model distinguishes between purchasing and non-purchasing customers.

---

## Results
- Logistic Regression successfully classifies customer purchase behavior
- ROC curve visualization shows model performance beyond accuracy
- AUC score provides a quantitative measure of classification quality

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
