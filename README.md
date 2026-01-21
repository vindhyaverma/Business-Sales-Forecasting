# Business-Sales-Forecasting
Sales & Demand Forecasting using Machine Learning
📌 Project Overview

This project focuses on sales and demand forecasting using historical retail data.
It demonstrates how Machine Learning can help businesses predict future sales and make better planning decisions.

The project was completed as Machine Learning Task 1 (2026) under Future Interns.

🎯 Business Problem

Businesses need accurate sales forecasts to:

Plan inventory

Manage cash flow

Prepare staffing

Avoid overstocking or losses

This project builds a forecasting system that predicts future daily sales using past data.

📊 Dataset

Store Sales – Time Series Forecasting (Kaggle)

Daily sales data from multiple stores and product families

Time period: 2013–2014

Main file used:

train.csv

🛠️ Tools & Technologies

Python

Google Colab

Pandas, NumPy

Scikit-learn

Matplotlib

🔧 Project Workflow

Data Loading & Cleaning

Handled missing values

Converted date columns

Removed unnecessary columns

Feature Engineering

Created time-based features:

Year

Month

Day

Day of week

Week of year

Baseline Model

Moving Average forecasting

Used as a comparison benchmark

Machine Learning Model

Random Forest Regressor

Used time features to capture patterns

Improved forecast accuracy compared to baseline

Model Evaluation

Mean Absolute Error (MAE)

ML model reduced error vs baseline

Visualization

Past vs actual vs predicted sales

30-day future sales forecast

📈 Results

Baseline MAE: ~121,596

ML Model MAE: ~108,582

Improvement: ML model captures weekly patterns and trends better

Future Forecast

Predicted average daily sales for next 30 days:
≈ 580,000 – 600,000

Trend: Stable with small weekly variations

💡 Business Insights

The forecast helps businesses plan inventory and staffing for the next month

Reduces risk of overstocking or missed sales

Supports better financial and operational planning

📂 Project Structure
├── Machine_Learning_Task_1_(2026).ipynb
├── README.md
└── data/
    └── train.csv

🚀 How to Run

Clone the repository

Open the notebook in Google Colab or Jupyter

Upload the dataset

Run all cells step-by-step

🔗 Acknowledgement

Dataset: Kaggle – Store Sales Time Series Forecasting

Task by: Future Interns

📢 Author

Created by Vindhya Verma
Machine Learning Intern – 2026
