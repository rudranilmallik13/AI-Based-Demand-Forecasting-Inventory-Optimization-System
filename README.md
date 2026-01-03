# 🚀 AI Demand Forecasting & Inventory Optimization System

An **end-to-end data science project** that forecasts retail demand using **ARIMA, Prophet, and LSTM**, compares model performance visually, and recommends **optimal inventory levels** to reduce **stockouts and overstock**.

---

## 🎯 Problem Statement

Retail businesses often lose money due to:

- ❌ **Overstock** → High holding and storage costs  
- ❌ **Stockouts** → Lost sales and poor customer experience  

This project solves the problem using **data-driven demand forecasting** combined with **inventory optimization logic**.

---

## 🧠 What This Project Does (End-to-End)

✔ Generates a **synthetic retail dataset (1800+ rows)**  
✔ Performs **Exploratory Data Analysis (EDA)**  
✔ Forecasts demand using **three models**  
✔ Compares models using **visual graphs + MAE**  
✔ Applies **inventory optimization logic**  
✔ Provides a clear **reorder / no-reorder decision**

---

## 📊 Dataset Details

- **Type**: Synthetic retail sales data  
- **Rows**: 1800+  
- **Includes**:
  - Date
  - Demand values
  - Trend
  - Seasonality
  - Noise  

The dataset closely mimics **real-world retail demand patterns**.

---

## 📈 Forecasting Models Used

| Model   | Purpose |
|--------|--------|
| **ARIMA** | Baseline statistical time-series forecasting |
| **Prophet** | Captures trend and seasonality |
| **LSTM** | Deep learning model for complex patterns |

---

## 📌 Model Comparison & Results

- 📉 Actual vs Predicted demand plots for all models  
- 📊 MAE comparison bar chart  
- 🧠 Performance interpretation  

### ✅ Final Result
**LSTM achieved the lowest MAE**, outperforming ARIMA and Prophet in forecasting accuracy.

---

## 📦 Inventory Optimization Logic

Inventory decisions are based on **forecasted demand**.

**Assumptions:**
- Lead Time = **5 days**
- Safety Stock = **20%**

### 📐 Reorder Point Formula

Reorder Point = (Average Daily Demand × Lead Time) + Safety Stock


### 📌 Final Output
- Indicates whether **inventory should be reordered or not**
- Helps minimize **stockouts and overstock losses**

---

## 🛠 Tech Stack

- **Programming**: Python  
- **Data Handling**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn  
- **Time Series**: Statsmodels (ARIMA), Prophet  
- **Deep Learning**: TensorFlow / Keras (LSTM)



