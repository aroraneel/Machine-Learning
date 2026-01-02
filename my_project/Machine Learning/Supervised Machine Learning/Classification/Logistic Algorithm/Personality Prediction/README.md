# Personality Prediction Using Logistic Regression

## Overview
This project demonstrates a **binary classification task** using **Logistic Regression** to predict a person’s personality type based on behavioral features.  
The analysis includes data preprocessing, visualization, model training, and evaluation using **ROC Curve** and **AUC score**.

---

## Objective
- Predict personality type using behavioral indicators  
- Apply Logistic Regression for classification  
- Visualize feature relationships  
- Evaluate model performance using ROC and AUC  

---

## Dataset
- **personality_dataset.csv**
- Features used:
  - `Time_spent_Alone`
  - `Social_event_attendance`
- Target variable:
  - `Personality` (label-encoded using `LabelEncoder`)

---

## Data Preprocessing
- Loaded dataset using Pandas
- Converted categorical **Personality** labels into numeric form using **Label Encoding**
- Selected relevant features for model training
- Split data into training (70%) and testing (30%) sets

---

## Visualization
- Scatter plot of **Time Spent Alone vs Social Event Attendance**
- Helps visualize behavioral separation between personality classes
- ROC Curve plotted to evaluate classification performance

---

## Machine Learning Model
- **Algorithm:** Logistic Regression
- Input features:
  - Time_spent_Alone
  - Social_event_attendance

---

## Model Evaluation
The model is evaluated using:
- Accuracy score
- ROC Curve
- AUC Score (Area Under the Curve)

These metrics provide insight into how well the model distinguishes between personality classes.

---

## Results
- Logistic Regression successfully classifies personality types
- ROC curve shows model performance beyond accuracy
- AUC score provides a robust measure of classification quality

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
