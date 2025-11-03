# Stock-Price-Prediction
Key Features:
Stock market variables: Parent Indices Data (NIFTY 50, NIFTY COMMODITIES, NIFTY INFRASTRUCTURE).
Exogenous variables: USD INR Exchange Rate, Interest Rate (Repo Rate), Crude Oil Prices, FPI Data.
Feature Engineering to create extra variables such as EMA, RSI, Log Returns, Price Change, Volume Ratio, Volatility.
Multicollinearity Check: Correlation Matrix & Variance Inflation Factor (VIF)
Time Series Cross-Validation (TSCV: 5 Fold) & time series train-test split (80:20)
Models: Linear Regression, Support Vector Regression (SVR), Random Forest Regressor, Adaboost Regressor, Gradient Boost Regressor, XGBoost Regressor, LightGBM Regressor
Conducted hyperparameter tuning and calculted MAE, MSE, % MAE for each model.
Also performed check on normality of residuals (QQ Plot), feature linearity, autocorrelation of residuals (ACF/PACF/Ljung-Box Test), heteroskedasticity (Breusch-Pagan Test).
As features had multicollinearity, so linear regression and SVR performed better than expected. Disregarding those, XGBoost performed the best (MAE: 1.37 %)
