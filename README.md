# Traffic-and-Next-Day-prediction-stock-Project
1)Downloads historical data from Yahoo Finance (`yfinance`)
2)Cleans columns and builds features (Open–Close, High–Low, % changes)
3) Splits data in **time order** (no shuffling)
4) Trains a **LightGBM** regression model
5) Evaluates with **RMSE**
6) Plots Actual vs Predicted and **Feature Importance**
7) Predicts the **next-day close** from the latest row
