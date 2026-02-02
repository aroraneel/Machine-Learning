# Breast Cancer Data Visualization using PCA

## Overview
This project applies **Principal Component Analysis (PCA)** to the Breast Cancer dataset to reduce high-dimensional data into **two principal components** for visualization and pattern analysis.

---

## Objective
- Standardize breast cancer features  
- Reduce dimensionality using PCA  
- Visualize class separation between malignant and benign tumors  

---

## Dataset
- **Breast Cancer Wisconsin Dataset** (from `sklearn.datasets`)
- Contains numerical features describing cell nuclei characteristics
- Target classes:
  - `0` → Malignant  
  - `1` → Benign  

---

## Methodology
- Standardized features using **StandardScaler**
- Applied **PCA with 2 components**
- Analyzed explained variance
- Visualized transformed data using a 2D scatter plot

---

## Results
- PCA successfully reduced dimensions while preserving key variance
- Clear visual separation observed between malignant and benign classes
- Demonstrates PCA’s effectiveness for exploratory data analysis

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project focuses on dimensionality reduction and visualization rather than classification performance.
