# AI Financial Market Impact Analysis using Linear Regression

## Overview
This project applies **Linear Regression** to analyze the relationship between **AI-related financial metrics** and company representation in a synthetic financial market dataset.  
The focus is on understanding how investment and revenue indicators relate to market impact signals.

---

## Objective
- Analyze AI financial indicators using linear regression  
- Explore relationships between R&D spending, AI revenue, and stock impact  
- Evaluate model performance using the R² metric  

---

## Dataset
- **ai_financial_market_daily_realistic_synthetic.csv**
- Categorical columns:
  - `Company` (encoded numerically)
- Numerical features used:
  - `R&D_Spending_USD_Mn`
  - `AI_Revenue_USD_Mn`
  - `AI_Revenue_Growth_%`
  - `Stock_Impact_%`

---

## Data Preprocessing
- Dropped non-numeric and irrelevant columns (`Date`, `Event`)  
- Encoded company names into numeric values  
- Removed missing values  

---

## Methodology
- Feature and target selection  
- Train-test split (80–20)  
- Model training using Linear Regression  
- Prediction on test data  
- Evaluation using **R² score**

---

## Evaluation Metric
- **R² Score** to measure model fit  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project demonstrates linear regression applied to financial indicators and highlights preprocessing steps required for mixed-type datasets.
