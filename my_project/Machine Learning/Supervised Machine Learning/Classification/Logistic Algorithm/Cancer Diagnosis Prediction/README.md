# Cancer Diagnosis Prediction Using Logistic Regression

## Overview
This project demonstrates a **binary classification problem** using **Logistic Regression** to predict cancer diagnosis based on basic health and lifestyle features.  
The notebook covers data visualization, model training, and evaluation using **ROC Curve** and **AUC score**.

---

## Objective
- Predict cancer diagnosis using selected features  
- Apply Logistic Regression for medical classification  
- Visualize relationships between variables  
- Evaluate model performance using ROC and AUC metrics  

---

## Dataset
- **The_Cancer_data_1500_V2.csv**
- Features used:
  - `Age`
  - `PhysicalActivity`
- Target variable:
  - `Diagnosis` (binary outcome)

---

## Data Exploration & Visualization
- Scatter plot of **Age vs Physical Activity**, colored by diagnosis
- Helps understand how age and activity relate to cancer diagnosis

---

## Model Development
- **Algorithm:** Logistic Regression
- Input features:
  - Age
  - PhysicalActivity
- Data split:
  - Training set: 60%
  - Test set: 40%

---

## Model Evaluation
The model is evaluated using:
- Accuracy score
- ROC Curve (Receiver Operating Characteristic)
- AUC Score (Area Under the Curve)

These metrics help assess classification performance beyond simple accuracy.

---

## Results
- Logistic Regression successfully predicts cancer diagnosis
- ROC curve shows separation between positive and negative classes
- AUC score indicates the model’s ability to distinguish outcomes

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
