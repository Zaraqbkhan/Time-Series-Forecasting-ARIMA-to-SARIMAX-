# 🍫 Daily Revenue Forecasting for a ChocoBar Company (Time Series)

This project focuses on forecasting the daily revenue of a ChocoBar company using ARIMA, SARIMA, and SARIMAX models. The analysis is conducted in Python, comparing model performance to determine the most accurate and robust approach.

## 🔧 Tools & Libraries Used

- Python (Jupyter Notebook)
- Pandas
- Statsmodels
- Matplotlib / Seaborn
- scikit-learn (for evaluation)

## 📊 Models Used

- ARIMA – for trend modeling (non-seasonal)
- SARIMA – for trend + seasonality
- SARIMAX – incorporates exogenous factors (discount & coupon rates)

## ✅ Best Model: SARIMAX

**SARIMAX outperforms ARIMA and SARIMA** by including promotional variables (`discount_rate` and `coupon_rate`) as exogenous inputs. This results in:

- Lower MAE,RMSE,MAPE values
- Better ability to capture spikes and dips driven by promotions
- More realistic forecasting during marketing campaigns

## 📁 Files Included

- `revenue_forecasting.ipynb` – Full analysis and model comparison
- `data_description.txt` – Description of dataset columns
- `insights.md` – Summary of findings and model performance

## 📈 Use Case

Forecasting revenue helps the business plan inventory, staffing, and promotions more effectively — especially around high-discount or high-coupon periods.
#
