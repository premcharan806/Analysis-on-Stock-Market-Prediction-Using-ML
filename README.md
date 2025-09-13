# Analysis-on-Stock-Market-Prediction-Using-ML
1. Overview

This project applies machine learning regression algorithms to predict stock market portfolio opening values.
The dataset contains 516 instances with 18 financial features, including:

Stock indices

Commodities

Cryptocurrencies

Bond yields

Currency exchange rates

2. Objective

The main goals of this project are to:

Analyze financial data to study price trends and correlations.

Predict PortfolioOpen values based on other financial metrics.

Identify the best-performing machine learning model for accurate forecasting.

3. Dataset

Instances: 516

Features: 18

Target Variable: PortfolioOpen

4. Best Model

Among all tested models:

Bagging Regressor achieved the highest accuracy with:

R² = 0.9622

MAPE = 0.0108

Other strong performers included: Random Forest, Gradient Boosting, and XGBoost.

Bagging was the most reliable across all data splits.

5. Key Results

Bagging and Random Forest were the most reliable models.

Ensemble methods consistently outperformed simpler models (e.g., Linear Regression, KNN).

Data preprocessing (handling missing values, resolving multicollinearity) significantly improved model stability and accuracy.

6. Future Scope

Potential improvements include:

Incorporating macroeconomic indicators (GDP, inflation, interest rates).

Using advanced time-series models such as LSTM and GRU.

Applying hyperparameter tuning and feature engineering for better performance.

7. Business Impact

Accurate forecasting of portfolio opening values strengthens investment strategies.

Supports better risk management and decision-making.

A hybrid approach combining ensemble methods with neural networks can ensure robust portfolio prediction.
