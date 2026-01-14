# Linear Regression from Scratch using Gradient Descent (1D)

## Overview
This project demonstrates **Linear Regression from scratch** using **Gradient Descent** without relying on Scikit-learn.  
The goal is to understand how slope and intercept are learned iteratively and how error reduces during training.

Synthetic data is used to clearly visualize learning behavior and optimization.

---

## Objective
- Implement linear regression manually
- Understand gradient descent updates
- Visualize error reduction and parameter learning
- Evaluate model performance using regression metrics

---

## Dataset
- **Synthetic dataset** generated using NumPy
- Feature:
  - `X_Feature`
- Target:
  - `Y_Target` (linear relation with noise)

---

## Methodology
- Initialize slope and intercept to zero  
- Train using **batch gradient descent**  
- Track:
  - Mean Squared Error (MSE)
  - Slope and intercept values  
- Split data into train and test sets (70/30)

---

## Evaluation Metrics
- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)

---

## Visualization
- Data with true regression line  
- Error vs iterations plot  
- Slope & intercept learning curves  
- Prediction vs actual plot  
- 3D visualization of regression line  
- Gradient descent animation  

---

## Tools Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  

---

## Author
**Neel Arora**  
BCA Undergraduate | AI & Machine Learning  

---

## Notes
This project is designed for learning and visualization purposes to build strong fundamentals in linear regression.
