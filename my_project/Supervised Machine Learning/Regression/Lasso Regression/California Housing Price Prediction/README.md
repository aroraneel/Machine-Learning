# California Housing Price Prediction Using Lasso Regression

## Overview
This project demonstrates a **regression-based machine learning approach** to predict **median house prices** using the California Housing dataset.  
It focuses on applying **Lasso Regression** to understand prediction performance and regularization effects on structured numerical data.

---

## Objective
- Predict median house values based on geographic and socio-economic features  
- Apply Lasso Regression for regression and feature regularization  
- Evaluate model performance using the **R² score**  

---

## Dataset
- **California Housing Dataset** (from `sklearn.datasets`)
- Widely used benchmark dataset for regression problems

### Features Used
- Median Income (`MedInc`)
- House Age (`HouseAge`)
- Average Rooms (`AveRooms`)
- Average Bedrooms (`AveBedrms`)
- Population
- Average Occupancy (`AveOccup`)
- Latitude
- Longitude

### Target Variable
- `target` → Median house value

---

## Machine Learning Model
- **Lasso Regression**
  - Uses **L1 regularization**
  - Helps reduce model complexity and perform implicit feature selection
- Model parameter:
  - `alpha = 0.1`

---

## Training Process
- Dataset split into training and testing sets (80/20)
- Model trained on training data
- Predictions generated on unseen test data

---

## Model Evaluation
- **R² Score (Coefficient of Determination)** used to measure performance
- Scatter plot of **Actual vs Predicted house values**
- Reference diagonal line represents perfect prediction

---

## Results
- Lasso Regression provides a reasonable prediction of house prices
- Regularization helps control overfitting
- Visualization highlights prediction accuracy and deviation

---

## Tools & Technologies
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
