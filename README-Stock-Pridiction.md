Short-Term Stock Price Prediction (AAPL)

Task Objective
The objective of this task was to predict the **next day’s closing price** of Apple Inc. (AAPL) stock using historical market data. The goal was to build regression models that capture short-term trends based on features available from the previous trading day.

Dataset Used
Historical stock market data for AAPL was retrieved from **Yahoo Finance** using the `yfinance` Python library. The dataset included the following daily features:
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

For modeling, the features **Open, High, Low, and Volume** were used to predict the **next day’s Close price**.

Models Applied
Two regression models were implemented:
1. Linear Regression (LR): a baseline model for trend prediction.
2. Random Forest Regressor (RF): an ensemble model to capture non-linear relationships.

Key Results and Findings
-Linear Regression achieved a score of 0.9909, demonstrating excellent predictive capability.  
-Random Forest achieved a score of 0.9899, performing slightly below LR.  
-Both models effectively captured the overall price trend, while minor deviations occurred on volatile days.  
-Price features (Open, High, Low) were the most influential, with Volume providing confirmation of movement strength.  
- The analysis shows that historical OHLCV data provides meaningful signals for short-term next-day closing price prediction, suitable for trend analysis and decision support.
