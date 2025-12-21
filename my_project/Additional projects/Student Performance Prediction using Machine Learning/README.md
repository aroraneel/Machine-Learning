# Student Performance Prediction Using Machine Learning

## Overview
This project analyzes a **Student Performance dataset** to predict whether a student will **Pass or Fail** based on academic and behavioral factors.  
Multiple machine learning models are trained and compared to evaluate their effectiveness in student performance classification.

---

## Objective
To build and compare machine learning models that classify student performance (Pass/Fail) using:
- Hours Studied  
- Previous Scores  
- Extracurricular Activities  
- Sleep Hours  
- Sample Question Papers Practiced  

---

## Dataset
- **Student_Performance.csv**
- Target variable:
  - `Pass (1)` → Performance Index ≥ 60  
  - `Fail (0)` → Performance Index < 60  

---

## Data Preprocessing
- Converted **Extracurricular Activities** to binary values (Yes → 1, No → 0)
- Transformed **Performance Index** into a binary result (Pass/Fail)
- Selected relevant features for model training

---

## Visualization
- Scatter plot comparing **Hours Studied vs Previous Scores**
- Points colored by student result (Pass/Fail)

---

## Machine Learning Models Used
- K-Nearest Neighbors (KNN)  
- Logistic Regression  
- Naive Bayes (GaussianNB)  

---

## Model Evaluation
Models are evaluated using:
- Accuracy Score  
- Confusion Matrix  

A train–test split (80/20) with stratification ensures balanced evaluation.

---

## Key Findings
- All three models successfully classify student performance
- Logistic Regression and Naive Bayes provide strong baseline results
- Feature-based patterns such as study hours and prior scores strongly influence outcomes

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## Conclusion
This project demonstrates how machine learning can be applied to educational data to predict student outcomes.  
The comparison of multiple classifiers provides insights into model behavior and performance for binary classification tasks.

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This README provides a brief overview of the project structure and methodology.

