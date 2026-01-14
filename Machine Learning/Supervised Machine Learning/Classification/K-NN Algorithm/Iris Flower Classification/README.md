# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Overview
This project demonstrates a **basic machine learning classification task** using the well-known **Iris dataset**.  
The goal is to classify iris flowers into three species based on their physical measurements using the **K-Nearest Neighbors (KNN)** algorithm.

---

## Objective
- Explore the Iris dataset and understand its features
- Visualize relationships between features
- Train a KNN classifier to predict flower species
- Evaluate model performance using standard classification metrics

---

## Dataset
- **Iris Dataset** (from `sklearn.datasets`)
- Features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- Target classes:
  - Setosa
  - Versicolor
  - Virginica

---

## Data Preparation
- Loaded dataset using `load_iris()`
- Converted data into a Pandas DataFrame
- Added target labels and corresponding flower names
- Split data into training and testing sets (80/20)

---

## Visualization
- Scatter plots to visualize:
  - Sepal length vs Sepal width
  - Petal length vs Petal width
- Confusion matrix visualized using a heatmap

---

## Machine Learning Model
- **Algorithm:** K-Nearest Neighbors (KNN)
- **Number of Neighbors:** 3
- Model trained using Scikit-learn

---

## Model Evaluation
The model is evaluated using:
- Accuracy score
- Confusion matrix
- Classification report (Precision, Recall, F1-score)

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

