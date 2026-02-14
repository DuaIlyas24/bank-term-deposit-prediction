# bank-term-deposit-prediction
Task 1: Term Deposit Subscription Prediction (Bank Marketing)

Author: Dua Ilyas

📌 Objective

Predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign using historical marketing data.

🗂 Dataset

Bank Marketing Dataset from the UCI Machine Learning Repository.

Features include:

age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome, y (target)

🧰 Tools & Libraries

Python: pandas, numpy, scikit-learn, matplotlib, seaborn, shap

Machine Learning Models: Logistic Regression, Random Forest

Model Interpretation: SHAP for explainable AI

🔹 Approach

Data Loading & Preprocessing:

Loaded dataset and handled categorical features via encoding.

Checked for missing or inconsistent data.

Exploratory Data Analysis (EDA):

Visualized target distribution and important features.

Generated plots to understand customer characteristics and correlations.

Model Building:

Split data into training and testing sets.

Trained Logistic Regression and Random Forest models.

Evaluation:

Evaluated models using Accuracy, F1-Score, Confusion Matrix, and ROC Curve.

Used SHAP to interpret predictions and identify important features.

📊 Visualizations

Target Distribution

Confusion Matrix

ROC Curve

Feature Importance with SHAP

✅ Results

Model performance metrics (Accuracy, F1-Score)

Insights from SHAP analysis on key customer features influencing subscription

🔗 GitHub Repository
https://github.com/DuaIlyas24/bank-term-deposit-prediction

