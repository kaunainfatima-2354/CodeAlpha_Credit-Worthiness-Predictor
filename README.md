# CodeAlpha_Credit-Worthiness-Predictor
This project focuses on building a Credit Scoring Model that predicts whether an individual is creditworthy based on their financial and personal attributes.

The entire workflow is implemented in a Jupyter Notebook (Credit_Scoring_Model.ipynb) and demonstrates a complete machine-learning pipeline from preprocessing to prediction.
The goal is to automate creditworthiness evaluation using a supervised classification model.

1. Task: Credit Scoring Model
Objective: Predict an individual's creditworthiness using past financial data.
Approach: Use classification algorithms like Logistic Regression, Decision Trees, or Random Forest.
Key Features:
● Feature engineering from financial history.
● Model accuracy assessment using metrics like Precision, Recall, F1-Score, ROC-AUC.
● Dataset could include: income, debts, payment history, etc.

2. Features
Cleans and encodes categorical + numerical data
Trains a Random Forest Classifier
Optimizes parameters using RandomizedSearchCV
Evaluates model accuracy
Provides a function for real-time creditworthiness prediction

3. Tools Used:
Python
Pandas 
Scikit-learn
Jupyter Notebook

5. Result:
A tuned Random Forest model that predicts whether a user is creditworthy with improved accuracy.
