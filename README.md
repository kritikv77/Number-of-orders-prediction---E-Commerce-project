# Number-of-orders-prediction---E-Commerce-project
Predicts daily e-commerce order volumes using historical data with machine learning models (Linear Regression, Random Forest, XGBoost). Includes data preprocessing, feature engineering, EDA, and forecast visualizations.
Number of Orders Prediction – E-commerce Dataset
📌 Overview

This project predicts daily order counts for an e-commerce platform using historical order data. The goal is to help businesses forecast demand, optimize inventory, and improve resource planning. Machine learning models capture trends, seasonality, and user behavior to generate accurate predictions.

📂 Dataset

Source: Instacart Online Grocery Basket Analysis Dataset

Dataset includes:

Orders: Daily order history for each user.

Products: Product IDs, categories, and pricing information.

Users: Optional user behavior and activity data.

Aggregated to daily order counts for prediction purposes.

🔎 Key Work Done

Data Preprocessing: Handled missing values, encoded categorical features, and normalized numerical features.

Exploratory Data Analysis (EDA): Studied order trends, seasonality, and correlations between features.

Feature Engineering: Created features such as day of the week, month, moving averages, and lag variables.

Model Building: Trained multiple regression models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Evaluation: Used RMSE, MAE, and R² to compare model performance.

Visualization: Plotted actual vs predicted orders over time and feature correlations.

📊 Results & Insights

Daily order trends show clear seasonality with peaks during weekends and holidays.

Moving averages and lag features significantly improve prediction accuracy.

Model performance:

Random Forest and XGBoost outperform Linear Regression in capturing complex patterns.

Forecasts can guide inventory management, marketing campaigns, and staffing decisions.

🛠 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
