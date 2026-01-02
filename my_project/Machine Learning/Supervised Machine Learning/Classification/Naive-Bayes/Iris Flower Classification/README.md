# Iris Flower Classification Using Naive Bayes

## Overview
This project applies the **Gaussian Naive Bayes** algorithm to classify iris flowers into different species based on their physical measurements.  
It demonstrates a complete **supervised machine learning workflow**, including data loading, preprocessing, model training, and evaluation.

---

## Objective
- Classify iris flowers into species using Naive Bayes  
- Understand probabilistic classification on structured data  
- Evaluate model performance using accuracy and confusion matrix  

---

## Dataset
- **Iris.csv**
- Features used:
  - Id  
  - SepalLengthCm  
  - SepalWidthCm  
  - PetalLengthCm  
  - PetalWidthCm  
- Target variable:
  - `Species` (Iris-setosa, Iris-versicolor, Iris-virginica)

---

## Data Preparation
- Loaded dataset using Pandas
- Inspected data structure and class distribution
- Selected relevant numeric features
- Split data into training (80%) and testing (20%) sets

---

## Machine Learning Model
- **Algorithm:** Gaussian Naive Bayes
- Assumes features follow a normal distribution
- Suitable for multi-class classification problems

---

## Model Evaluation
The model is evaluated using:
- Accuracy score  
- Confusion matrix  
- Classification report  
- Confusion matrix visualization using `ConfusionMatrixDisplay`

---

## Results
- Gaussian Naive Bayes successfully classifies iris species
- High accuracy achieved on the test dataset
- Confusion matrix visualization helps interpret class-wise predictions

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
