# Time-Series-Behavior-and-ARIMA-Forecasting
Data preparation, time-series analysis, and examination of ARIMA behavior

---

## 📁 Project Description
This repository contains a Jupyter Notebook that analyzes time-series data and compares classical time-series behavior with ARIMA modeling.  
The notebook covers:

- Time-series visualization  
- Stationarity checks (ADF test)  
- Autocorrelation & Partial Autocorrelation analysis (ACF/PACF)  
- Differencing  
- ARIMA model selection and fitting  
- Forecasting  
- Evaluation metrics (RMSE, MAE, MAPE)

---

## 🧪 Contents
- `Time Series vs ARIMA.ipynb` — Main notebook with full analysis  
- Data preprocessing  
- Model training and comparison  
- Forecast visualization

---

## 🛠 Tools & Libraries
- pandas  
- numpy  
- matplotlib  
- statsmodels  
- sklearn  

---

## 📈 Model Performance Summary
Evaluation metrics from the final model:

- **RMSE:** *136.66*  
- **MAE:** *78.44*  
- **MAPE:** *16.16%*  

These metrics show that the ARIMA model provides a reasonable approximation, but the error levels indicate that the dataset may contain seasonality, volatility, or structural patterns not fully captured by ARIMA.

---

## 📌 Conclusion
This notebook demonstrates practical steps to build, fit, and evaluate ARIMA models, comparing raw time-series behavior with model-based forecasting.  
It can be used as a baseline for more advanced models such as SARIMA, Prophet, or LSTM.

---

## 👤 Author
Time Series Project — Data Analysis & Forecasting  
