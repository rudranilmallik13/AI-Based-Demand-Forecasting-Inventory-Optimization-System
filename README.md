🚀 AI Demand Forecasting & Inventory Optimization System

An end-to-end data science project that forecasts retail demand using ARIMA, Prophet, and LSTM, compares models visually, and recommends optimal inventory levels to reduce stockouts and overstock.

🎯 Why This Project Matters

Retail businesses lose money due to:

Overstock → high holding cost

Stockouts → lost sales

This project solves the problem using data-driven demand forecasting + inventory planning.

🧠 What I Built (End-to-End)

✔ Synthetic retail dataset (1800+ rows)
✔ Exploratory Data Analysis (EDA)
✔ Demand forecasting using 3 models
✔ Model comparison using graphs + MAE
✔ Inventory optimization logic (reorder point)

📊 Models Used
Model	Purpose
ARIMA	Baseline statistical forecasting
Prophet	Trend & seasonality modeling
LSTM	Deep learning for complex patterns

📌 Result: LSTM achieved the lowest MAE.

📈 Key Visual Analysis

Actual vs Predicted demand (for all models)

Error comparison bar chart

Model performance interpretation

Visual analysis clearly shows LSTM outperforming ARIMA and Prophet in accuracy.

📦 Inventory Optimization Logic

Based on forecasted demand:

Lead Time = 5 days

Safety Stock = 20%

Reorder Point Formula:

Reorder Point = (Average Daily Demand × Lead Time) + Safety Stock


📌 Final output tells whether stock should be reordered or not.

🛠 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Statsmodels (ARIMA)

Prophet

TensorFlow / Keras (LSTM)
