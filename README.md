# Loan-Default-Prediction
Loan Default Prediction using Logistic Regression and Random Forest with Python and Scikit-learn.

# Loan Default Prediction 

## Overview
This project uses Machine Learning classification models to predict whether a customer is likely to default on a loan based on financial and employment-related information. The project includes data preprocessing, model training, performance evaluation, and feature importance analysis.

## Dataset
The dataset was obtained from Kaggle and contains customer financial information with the following features:
* Index
* Employed
* Bank Balance
* Annual Salary

**Target Variable**
* Defaulted?

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Machine Learning Workflow
* Loaded and explored the dataset.
* Performed data cleaning and handled missing values.
* Encoded categorical features where required.
* Selected features and target variable.
* Split the dataset into training and testing sets.
* Trained Logistic Regression and Random Forest Classifier models.
* Evaluated model performance using Accuracy, Precision, Recall, ROC-AUC, and Confusion Matrix.
* Analyzed feature importance using the Random Forest model.
* Predicted loan default for new customer data.

## Models Used
* Logistic Regression
* Random Forest Classifier

## Evaluation Metrics
* Accuracy
* Precision
* Recall
* ROC-AUC Score
* Confusion Matrix

## Project Structure
Loan-Default-Prediction/
│── Default_Fin.csv
│── loan_default_prediction.py
│── README.md


## Dataset Source
This project uses a dataset obtained from **Kaggle** for educational and machine learning practice purposes.

## Future Improvements
* Hyperparameter tuning for improved model performance.
* Compare additional classification algorithms such as XGBoost and Gradient Boosting.
* Deploy the model as a web application using Streamlit.


