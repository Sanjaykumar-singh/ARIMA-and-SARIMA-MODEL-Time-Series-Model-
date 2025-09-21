# ARIMA-and-SARIMA-MODEL-Time-Series-Model-
# 📈 Time Series Forecasting of Stock Prices using ARIMA and SARIMA  

## 📌 Project Overview  
This project applies **ARIMA (Auto-Regressive Integrated Moving Average)** and **SARIMA (Seasonal ARIMA)** models to stock price data for forecasting.  
The primary dataset used is IBM stock closing prices, but the approach is general and can be applied to any financial time series.  

---

## 📂 Dataset  
- **Source:** Historical stock prices (CSV or via `yfinance`).  
- **Key Columns:**  
  - `Date` → trading date  
  - `Close` → stock closing price  

---

## ⚙️ Methodology  
1. Load and preprocess stock price dataset.  
2. Perform **stationarity check** (ADF test).  
3. Visualize **ACF/PACF** plots to identify ARIMA parameters.  
4. Fit **ARIMA** and **SARIMA** models.  
5. Forecast future stock prices and validate results.  
6. Evaluate using metrics like **RMSE** and **MAE**.  

---

## 📊 Observations  
- Stock prices show **clear non-stationarity** with long-term trends and volatility.  
- Differencing and seasonal adjustments (SARIMA) stabilize the series for forecasting.  
- Forecasts capture **short-term patterns well**, though long-term predictions are less reliable due to volatility.  

---
