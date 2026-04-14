#Heart Disease Prediction System (Logistic Regression)

This project is a beginner-friendly implementation of a Heart Disease Prediction System using Python and Logistic Regression. It leverages healthcare data to predict whether a person is at risk of heart disease based on key medical attributes.

Project Overview:

The system analyzes patient health data such as age, sex, cholesterol levels, and other clinical features to classify individuals as healthy or at risk of heart disease. It demonstrates a complete machine learning workflow, making it ideal for beginners in healthcare analytics.

Key Features:
Exploratory Data Analysis (EDA)
Data preprocessing and feature selection
Train-test data splitting
Model training using Logistic Regression
Model evaluation with accuracy score
Custom input prediction system

How It WorksL:
Data Exploration & Analysis
Understand dataset structure
Check for missing values
Interpret target variable (0 = Healthy, 1 = At Risk)
Data Preprocessing
Separate features (X) and target (y)
Split dataset into training and testing sets
Model Building
Train a Logistic Regression model using scikit-learn
Model Evaluation
Predict on test data
Evaluate using accuracy score (~85%)
Predictive System
Input custom patient data
Output prediction: Healthy or At Risk (Consult Doctor)

Example:
Input: Patient health metrics (age, cholesterol, etc.)
Output: Prediction → Healthy or At Risk

Technologies Used:
Python
Pandas
NumPy
Scikit-learn

Future Improvements:
Use advanced models (Random Forest, XGBoost)
Improve accuracy with feature engineering
Deploy as a web app (Streamlit / Flask)
Add visualization dashboard for insights
