# Student Performance Prediction Using Machine Learning

## Overview
This project focuses on predicting whether a student will **Pass or Fail** based on academic and behavioral factors.  
Multiple machine learning classification models are implemented and compared to evaluate their effectiveness.

---

## Objective
- Predict student performance (Pass / Fail)
- Analyze the impact of study habits and activities on results
- Compare multiple classification algorithms

---

## Dataset
**Student Performance Dataset**

Features used:
- Hours Studied  
- Previous Scores  
- Extracurricular Activities  
- Sleep Hours  
- Sample Question Papers Practiced  

Target variable:
- `Result`  
  - Pass (1) → Performance Index ≥ 60  
  - Fail (0) → Performance Index < 60  

---

## Data Preprocessing
- Converted *Extracurricular Activities* to binary values (Yes → 1, No → 0)
- Converted *Performance Index* into Pass/Fail labels
- Selected relevant input features
- Applied an 80–20 train-test split with stratification

---

## Visualization
- Scatter plot of **Hours Studied vs Previous Scores**
- Points colored by Pass/Fail outcome
- Helps visualize the relationship between study effort and performance

---

## Machine Learning Models
The following models are trained and evaluated:
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Naive Bayes (GaussianNB)**

---

## Model Evaluation
Each model is evaluated using:
- Accuracy Score  
- Confusion Matrix  

This allows comparison of classification performance across models.

---

## Results
- All three models successfully classify student outcomes
- Performance varies based on model assumptions and feature sensitivity
- Demonstrates practical use of classification algorithms in education analytics

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook / VS Code  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
