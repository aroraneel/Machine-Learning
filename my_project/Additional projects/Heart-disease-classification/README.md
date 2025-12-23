# Predicting Heart Disease Using Machine Learning

## Overview
This project focuses on **predicting the presence of heart disease** using machine learning techniques.  
It is an **end-to-end data science and machine learning proof of concept**, covering data exploration, model building, evaluation, and interpretation using a clinical heart disease dataset.

---

## Objectives
- Perform exploratory data analysis (EDA) to understand patient health data  
- Build and compare multiple machine learning classification models  
- Tune model hyperparameters to improve performance  
- Evaluate models using metrics beyond accuracy  
- Identify key features contributing to heart disease prediction  

---

## Dataset
- **Heart Disease Dataset (`heart.csv`)**
- Contains clinical attributes such as age, sex, chest pain type, heart rate, cholesterol, and more
- Target variable:
  - `1` → Heart disease present  
  - `0` → No heart disease  

---

## Project Workflow
The notebook follows a structured machine learning framework:

1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature and target separation  
4. Train–test split  
5. Model training and comparison  
6. Hyperparameter tuning  
7. Model evaluation  
8. Feature importance analysis  

---

## Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

The models are compared using accuracy, and the best-performing model is further optimized.

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- ROC Curve & AUC  
- Cross-validation scores  

These metrics provide a comprehensive view of model performance beyond simple accuracy.

---

## Key Findings
- Logistic Regression performed best among tested models  
- Hyperparameter tuning improved model performance  
- Several features (e.g., sex, slope, chest pain type) strongly influence predictions  
- The final model achieved strong performance but did not reach the 95% target accuracy  

---

## Tools & Technologies
- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Conclusion
This project demonstrates a complete machine learning workflow for a healthcare classification problem.  
While the accuracy target was not fully met, the analysis provides valuable insights into model behavior, feature importance, and next steps for improvement.

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This README provides a brief overview of the project structure and methodology.

