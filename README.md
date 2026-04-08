Business-Sales-Forecasting

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

Daily sales data from multiple stores and product families.

Time period: 2013–2014

Main file used:

train.csv
🛠️ Tools & Technologies
Python
Google Colab
Pandas
NumPy
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

Used Moving Average forecasting as a comparison benchmark.

Machine Learning Model

Implemented Random Forest Regressor

Used time-based features to capture patterns
Improved forecast accuracy compared to baseline
Model Evaluation

Evaluation metric used:

Mean Absolute Error (MAE)

Machine learning model showed lower error compared to baseline forecasting.

Visualization

Created plots for:

Past vs Actual vs Predicted Sales
30-day future sales forecast
📈 Results

Baseline Model MAE: ~121,596

Machine Learning Model MAE: ~108,582

Improvement:
The ML model captures weekly patterns and sales trends more effectively.

Future Forecast

Predicted average daily sales for next 30 days

≈ 580,000 – 600,000

Trend shows stable demand with small weekly variations.

💡 Business Insights

The forecasting model helps businesses:

Plan inventory levels more efficiently
Prepare staffing requirements
Reduce risk of overstocking or stockouts
Improve financial and operational planning
📂 Project Structure
Business-Sales-Forecasting
│
├── Machine_Learning_Task_1_(2026).ipynb
├── README.md
└── data
    └── train.csv
🚀 How to Run
Clone the repository
git clone <repository-link>
Open the notebook in Google Colab or Jupyter Notebook
Upload the dataset
Run all cells step by step
🔗 Acknowledgement

Dataset source:

Kaggle – Store Sales Time Series Forecasting

📢 Author

Created by Vindhya Verma
Machine Learning – 2026
