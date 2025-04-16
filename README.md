# Assignment2BAN6440
Module 2 Assignment:  Constructing a Supervised Machine Learning Model
## Credit Risk Prediction Model – Finance Sector (Equity Bank)

## Overview

This project presents a supervised machine learning model developed to predict credit risk at Equity Bank. The goal is to help the bank identify potential loan defaults using a classification algorithm based on a made up dataset of 300 records.

## Steps Followed

### 1. **Data Collection**
- Created a dataset of 300 records representing loan applicants and their characteristics.

### 2. **Data Preprocessing**
- Handled missing values and duplicates.
- Normalized numeric features.
- Split data into training  and testing sets.

### 3. **Model Selection**
- Chose Classification as algorith and Logistic Regression** with `class_weight='balanced'` due to the imbalanced nature of default cases.

### 4. **Model Training**
- Trained the model using the training set.

### 5. **Model Optimization**
- Used **GridSearchCV** to tune hyperparameters such as `C`, `solver`, and `penalty`.
- Ensured the model generalizes well to unseen data.

### 6. **Model Testing**
- Evaluated performance using:
  - Accuracy
  - Classification report
  - Confusion matrix
  - Visualization with heatmaps

---

## Model Performance

- Accuracy: 43.33%
- Model showed improved precision and recall after optimization and class balancing.
- Effective in identifying high-risk (default) cases.

---

## Files Included

- `credit_risk_prediction.ipynb`: Jupyter Notebook containing full code.
- `equty_credit_risk_data.csv`: CSV document 
- `README.md`: This file.
---


## Libraries Used

- `pandas`, `numpy` – Data manipulation
- `scikit-learn` – Model building and evaluation
- `seaborn`, `matplotlib` – Data visualization
- `imblearn` – SMOTE for handling class imbalance
---
## Reference 

- Shreya Singh. (2023). Model Optimization in Python: Enhancing Model Performance. Medium. https://medium.com/@jscvcds/model-optimization-in-python-enhancing-model-performance-1b78dbf4c8b9
- Data Camp. (2024). Classification in Machine Learning: An Introduction. Data Camp. https://www.datacamp.com/blog/classification-machine-learning


