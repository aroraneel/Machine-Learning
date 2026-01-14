# Heart Disease Prediction Using Machine Learning

## Overview
This project explores the use of **machine learning classification techniques** to predict whether a patient has heart disease based on clinical and demographic attributes.  
It is designed as an **end-to-end data science proof of concept**, covering data exploration, model building, evaluation, and interpretation.

---

## Problem Statement
Given clinical parameters about a patient, can we predict whether or not they have **heart disease**?

This is formulated as a **binary classification problem**, where:
- `1` → Heart disease present  
- `0` → No heart disease  

---

## Dataset
- **heart.csv**
- Structured tabular dataset with medical attributes such as:
  - Age, Sex
  - Chest pain type (cp)
  - Resting blood pressure
  - Cholesterol
  - Maximum heart rate
  - Exercise-induced angina
  - ST depression, slope, number of vessels, thalassemia
- Target variable:
  - `target`

---

## Exploratory Data Analysis (EDA)
- Class balance analysis of heart disease outcomes
- Gender-wise heart disease frequency
- Age vs maximum heart rate visualization
- Chest pain type vs heart disease comparison
- Distribution plots and histograms
- Correlation matrix and heatmap to study feature relationships

EDA is used to build intuition before modeling.

---

## Machine Learning Models
The following classification models are trained and compared:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**

---

## Model Training
- Features and target separated
- Data split into training and testing sets (80/20)
- Baseline models trained and evaluated
- Model comparison based on accuracy

---

## Hyperparameter Tuning
- **KNN**: Tuned number of neighbors manually
- **Logistic Regression**: Tuned using RandomizedSearchCV and GridSearchCV
- **Random Forest**: Tuned using RandomizedSearchCV

Hyperparameter tuning improves model performance and robustness.

---

## Model Evaluation
Evaluation goes beyond accuracy and includes:
- Confusion Matrix (numeric and visual)
- Classification Report
- Precision
- Recall
- F1-score
- ROC Curve and AUC
- Cross-validation with multiple scoring metrics

These metrics provide a deeper understanding of model performance.

---

## Feature Importance
- Feature importance extracted from Logistic Regression coefficients
- Visualization of how each feature contributes to predictions
- Helps interpret which medical attributes are most influential

---

## Results & Insights
- Logistic Regression performs best among tested models
- Model achieves strong but sub-95% accuracy
- Certain features (e.g., sex, slope, chest pain) show strong influence
- Demonstrates the importance of model evaluation beyond accuracy

---

## Future Improvements
- Collect more data to improve generalization
- Experiment with advanced models such as XGBoost or CatBoost
- Perform deeper feature engineering
- Export and deploy the trained model for real-world use

---

## Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook / VS Code  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
