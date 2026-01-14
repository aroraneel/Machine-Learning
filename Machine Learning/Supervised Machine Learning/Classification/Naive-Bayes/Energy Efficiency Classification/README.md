# Energy Efficiency Classification Using Naive Bayes

## Overview
This project applies the **Gaussian Naive Bayes** algorithm to classify building energy efficiency based on architectural and design features.  
The goal is to categorize buildings into **Low, Medium, or High Cooling Load** classes using supervised machine learning.

---

## Objective
- Predict cooling load categories of buildings  
- Apply probabilistic classification using Naive Bayes  
- Convert a continuous target variable into categorical classes  
- Evaluate model performance using accuracy and confusion matrix  

---

## Dataset
- **energy_efficiency_data.csv**
- Features used:
  - Relative_Compactness  
  - Surface_Area  
  - Wall_Area  
  - Roof_Area  
  - Overall_Height  
  - Orientation  
  - Glazing_Area  
  - Glazing_Area_Distribution  
- Target variable:
  - `Cooling_Load` (binned into **Low**, **Medium**, **High**)

---

## Data Preparation
- Loaded dataset using Pandas
- Inspected data structure and feature types
- Converted continuous **Cooling_Load** into three categorical classes using binning
- Selected relevant numerical features
- Split data into training (80%) and testing (20%) sets

---

## Machine Learning Model
- **Algorithm:** Gaussian Naive Bayes
- Suitable for multi-class classification problems
- Assumes features follow a normal distribution

---

## Model Evaluation
The model is evaluated using:
- Accuracy score  
- Confusion matrix  
- Confusion matrix visualization using `ConfusionMatrixDisplay`

---

## Results
- Naive Bayes successfully classifies energy efficiency levels
- Accuracy score reflects model effectiveness on unseen data
- Confusion matrix provides insight into class-wise predictions

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
