Tax Regression – End-to-End Cloud-Based Machine Learning System
🧾 Project Overview

Tax_regresssion_project_regression is a full-stack, end-to-end data analytics and machine learning project that integrates cloud data storage, web application development, machine learning modeling, real-time prediction, and business intelligence visualization.

The system collects tax-related data through a Node.js web application (HTML/CSS), stores it securely in MongoDB Atlas (cloud), processes and models the data using multiple regression and ensemble ML techniques with Optuna optimization, and visualizes insights through a Power BI dashboard connected directly to the cloud database.

🔗 End-to-End Architecture
HTML / CSS UI
      ↓
Node.js (Express API)
      ↓
MongoDB Atlas (Cloud Database)
      ↓
Machine Learning Pipeline (Python)
      ↓
Streamlit Prediction App
      ↓
Power BI Dashboard (Live Data)

🗄️ Cloud Data Storage (MongoDB Atlas)

MongoDB Atlas used as cloud-hosted NoSQL database

Data stored in structured JSON format

Handles:

User-submitted tax data

Historical tax records

Model input datasets

Secure connection via MongoDB URI

Scalable and production-ready cloud solution

🌐 Web Application (HTML, CSS, Node.js)

Frontend built using HTML & CSS

Backend API built with Node.js (Express)

Features:

Data entry forms for tax information

Server-side validation

REST API endpoints

MongoDB CRUD operations

Acts as the primary data ingestion layer

🧠 Machine Learning System
🔹 Models Implemented

Linear Regression

Ridge Regression

Lasso Regression

ElasticNet

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

XGBoost / LightGBM (optional)

🔹 Ensemble Learning

Voting Regressor

Bagging Regressor

Stacking Regressor

Random Forest (bagging-based)

Gradient Boosting (boosting-based)

🔹 Hyperparameter Optimization

Optuna used for:

Automated hyperparameter tuning

Bayesian optimization

Cross-validation-based selection

Improves model accuracy and generalization

📈 Model Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

Cross-validation performance comparison

🖥️ Streamlit ML Application

Interactive Streamlit web app

Features:

Load data from MongoDB cloud

Upload CSV files

Select ML model dynamically

Generate real-time tax predictions

Visualize prediction results

Serves as the ML deployment layer

📊 Power BI Dashboard (Live Analytics)

Power BI connected directly to MongoDB Atlas

Live / scheduled refresh enabled

Dashboards include:

Tax trend analysis

Revenue distribution

Model prediction summaries

KPI metrics

Enables business intelligence & decision making
