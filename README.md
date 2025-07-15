# Customer-Churn-Predictions-ML
This project focuses on predicting customer churn using classification algorithms. The objective is to help businesses identify customers at risk of leaving and take proactive steps to retain them.
Project Objective
To develop a machine learning model that accurately predicts whether a customer will churn based on behavioral and service-related data. The goal is to uncover key churn drivers and provide actionable insights to improve customer retention strategies.

Data Preprocessing and Analysis


Performed exploratory data analysis (EDA) to understand customer behavior and identify patterns related to churn.

Conducted data cleaning and feature engineering to prepare the dataset for modeling.

Visualized churn trends and feature distributions using Seaborn and Matplotlib.

Created new features from existing variables to improve model performance.

Model Development


Algorithms used: Logistic Regression, Random Forest, and XGBoost.

Hyperparameter tuning was applied to optimize model performance.

Evaluated model outputs using key classification metrics:

Precision

Recall

F1-score

Classification report

Results and Insights


The XGBoost model performed the best with an accuracy of approximately 79 percent.

Key churn indicators included service type, customer tenure, support calls, and billing patterns.

The model provides valuable insights into which customer segments are more likely to churn, enabling targeted retention strategies.

Project Structure


Churn_Prediction_Model.ipynb: Jupyter notebook with full code and analysis

data/: Contains the customer churn dataset

visuals/: Contains graphs and plots generated during EDA



Tools and Technologies


Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
