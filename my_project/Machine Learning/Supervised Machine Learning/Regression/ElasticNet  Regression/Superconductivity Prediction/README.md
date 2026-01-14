# Superconductivity Prediction Using Elastic Net Regression

## Overview
This project uses **machine learning regression** to predict the **critical temperature of superconductors** based on their chemical and physical properties.  
It demonstrates an end-to-end **regression workflow** using the Superconductivity dataset from OpenML.

---

## Objective
To predict the **critical temperature (`critical_temp`)** of superconducting materials using numerical material descriptors.

This is formulated as a **regression problem**.

---

## Dataset
- **Source:** OpenML – *Superconductivity Dataset*
- Loaded using `fetch_openml`
- Contains a large number of **material composition and physical features**
- Target variable:
  - `critical_temp` (continuous value)

---

## Features
The model uses multiple numerical features, including:
- Atomic mass statistics
- Atomic radius statistics
- Density-related features
- Electron affinity
- Fusion heat
- Thermal conductivity
- Valence-related properties

All features are numeric and suitable for regression.

---

## Machine Learning Model
- **Elastic Net Regression**
  - Combines **Lasso (L1)** and **Ridge (L2)** regularization
  - Helps handle multicollinearity and feature selection
- Model configuration:
  - `alpha = 0.1`

---

## Training Process
- Dataset split into training and testing sets (80/20)
- Model trained on training data
- Predictions generated on test data

---

## Evaluation Metric
- **R² Score (Coefficient of Determination)**
  - Measures how well predictions explain variance in target values
- Visualization:
  - Scatter plot of **Actual vs Predicted** values
  - Reference line for perfect prediction

---

## Results
- The model provides a reasonable fit for predicting critical temperature
- Elastic Net helps manage high-dimensional feature space
- Visualization highlights prediction accuracy and error spread

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
