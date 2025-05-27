# 📈 Stock Forecasting Models

This repository contains a collection of time series forecasting models applied to the **S&P 500 Index (`^GSPC`)**, built using different approaches:

- **ARIMA**: Traditional statistical model for linear trends.
- **LSTM (Long Short-Term Memory)**: Deep learning-based sequential model that captures temporal dependencies.
- **Prophet**: Facebook's additive time series forecasting model with trend, seasonality, and holidays.
- **XGBoost**: Gradient boosting framework used for regression based on engineered lag features.

---

## 📁 Notebooks Included

| Notebook         | Description |
|------------------|-------------|
| `ARIMA.ipynb`    | ARIMA-based forecast with performance metrics and directional accuracy. |
| `LSTM.ipynb`     | LSTM deep learning model using scaled sequences for prediction. |
| `Prophet.ipynb`  | Facebook Prophet with changepoint detection and trend visualization. |
| `XGBOOST.ipynb`  | Tree-based regression using lagged features and boosting. |

---

## 📊 Metrics Evaluated

Each model reports the following metrics:

- **RMSE** (Root Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **MAPE** (Mean Absolute Percentage Error)
- **Directional Accuracy**
- **R² Score**
- **Pearson Correlation**

---

## 🚀 Usage

You can run these notebooks locally or on cloud platforms like [Google Colab](https://colab.research.google.com/).

---

## 📦 Dependencies

To install the required packages:

```bash
pip install -r requirements.txt
