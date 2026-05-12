# Revenue Forecasting for Resort Operations

Overview:
This project builds a forecasting system for resort revenue using Python and time-series models. It analyzes hotel, ski, and golf departments to improve demand prediction and operational planning.

Business Problem
Resort revenue is highly seasonal:
- Ski: winter-driven spikes  
- Hotel: stable year-round revenue  
- Golf: moderate seasonal variation  

Traditional planning methods fail to capture these patterns accurately.
Dataset
- Daily operational revenue data (2025)
- Departments: Hotel, Ski, Golf
- Features include date, revenue, and aggregated monthly values
- Data has been anonymized

 Methods
- Exploratory Data Analysis (EDA)
- Feature engineering (lags, rolling averages, calendar features)
- Forecasting models:
  - Moving Average
  - Exponential Smoothing
  - ARIMA
  - Regression model
  - Hierarchical forecasting

Key Result
| Model | MAE | RMSE |
|------|------|------|
| Regression | **Best performance** |
| ARIMA | Moderate |
| Moving Average | Baseline |
| Exponential Smoothing | Weakest |

Regression performed best during high-demand seasonal peaks.

Key Insight
- Ski drives winter peaks
- Hotel is the most stable revenue source
- Strong seasonality exists across all departments
- Regression handles volatility better than time-series models

Tools
Python, SQL, Excel, Jupyter Notebook

Outcome
A practical forecasting framework for revenue planning, staffing, and seasonal demand management in resort operations.
