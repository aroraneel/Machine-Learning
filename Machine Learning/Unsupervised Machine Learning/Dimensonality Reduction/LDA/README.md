# Wine Dataset Visualization using Linear Discriminant Analysis (LDA)

## Overview
This project demonstrates **Linear Discriminant Analysis (LDA)** applied to the Wine dataset to reduce dimensionality while **maximizing class separability**.  
LDA is a supervised dimensionality reduction technique that uses class labels to find the most discriminative feature space.

---

## Objective
- Standardize wine feature data  
- Apply LDA for dimensionality reduction  
- Visualize class separation in a 2D space  

---

## Dataset
- **Wine Dataset** (from `sklearn.datasets`)
- Contains chemical analysis of wines grown in the same region
- Target variable:
  - Three distinct wine classes

---

## Methodology
- Standardized features using **StandardScaler**
- Applied **Linear Discriminant Analysis (LDA)** with 2 components
- Examined explained variance ratio
- Visualized transformed data using a 2D scatter plot

---

## Results
- LDA effectively reduced the feature space to two dimensions
- Clear separation observed between different wine classes
- Shows the strength of LDA for supervised dimensionality reduction

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
This project focuses on visualization and understanding class separation using LDA rather than predictive modeling.
