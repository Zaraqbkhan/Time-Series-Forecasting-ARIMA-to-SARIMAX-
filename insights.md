# 📊 Forecasting Insights – Daily Revenue Prediction

This project explored three time series forecasting models (ARIMA, SARIMA, SARIMAX) to predict daily revenue for a ChocoBar company.

## 🔍 Key Findings

- Revenue is influenced not just by time trends and seasonality, but also by **discounts and coupon usage**.
- **ARIMA** performed poorly due to lack of seasonality modeling.
- **SARIMA** improved results by modeling weekly/monthly seasonal patterns.
- **SARIMAX** delivered the best accuracy by incorporating external variables (exogenous regressors).

## 📈 SARIMAX Benefits

- Captures promotion-driven revenue fluctuations
- Lowest AIC and RMSE values among all models
- Strong alignment with observed business behavior (e.g. coupon weeks = spikes)

## 🧠 Conclusion

SARIMAX is recommended for daily revenue forecasting due to its ability to model both time-based seasonality and promotion-driven variability.
