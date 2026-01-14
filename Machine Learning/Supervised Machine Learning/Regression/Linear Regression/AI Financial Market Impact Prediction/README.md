# AI Financial Market Impact Prediction using Linear Regression

## Overview
This project uses **Linear Regression** to analyze how AI-related business factors influence stock market performance.  
The model predicts **Stock Impact (%)** based on company-level AI investment and revenue metrics.

---

## Objective
- Understand the relationship between AI spending and stock impact  
- Apply linear regression on financial data  
- Evaluate model performance using R² score  

---

## Dataset
- **Synthetic financial market dataset**
- Features used:
  - `R&D_Spending_USD_Mn`
  - `AI_Revenue_USD_Mn`
  - `AI_Revenue_Growth_%`
- Target:
  - `Stock_Impact_%`
- Date column removed during preprocessing

---

## Methodology
- Data preprocessing using Pandas  
- Train-test split (70% train, 30% test)  
- Model training using Scikit-learn’s Linear Regression  
- Performance evaluation using R² score  

---

## Evaluation Metric
- **R² Score** to measure regression accuracy  

---

## Tools Used
- Python  
- Pandas  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | AI & Machine Learning  

---

## Notes
This project demonstrates a simple regression-based approach to study AI-driven financial market impact.
