📈 **Stock Market Price Prediction**



📌 **Overview**

This project predicts stock market trends using ARIMA (AutoRegressive Integrated Moving Average) and LSTM (Long Short-Term Memory) models. By leveraging historical stock data, we aim to forecast future stock prices and analyze market trends.

🔍 **Dataset**

We use Yahoo Finance data via the yfinance API. The dataset includes:

**Date**: Trading date

Open, High, Low, Close: Daily stock prices

**Volume**: Number of shares traded

📥 **Fetching Data**

We retrieve stock data for a given company (e.g., Apple - AAPL) from 2010 to 2024 using yfinance.

🚀 **Project Workflow**

1️⃣ Download historical stock data using Yahoo Finance API
2️⃣ Visualize trends in stock price movements
3️⃣ Train ARIMA for traditional time series forecasting
4️⃣ Train LSTM for deep learning-based prediction
5️⃣ Evaluate model performance using RMSE (Root Mean Squared Error)
6️⃣ Compare actual vs predicted stock prices

🛠 **Requirements**

**Install dependencies using**:

pip install yfinance pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow

📊 **Model Implementation**

🔹 ARIMA (AutoRegressive Integrated Moving Average)

Uses past stock prices to predict future trends

Best for short-term forecasting

Evaluated using RMSE

🔹 LSTM (Long Short-Term Memory)

A type of Recurrent Neural Network (RNN)

Captures long-term dependencies in stock prices

Uses 60 days of past stock data for predictions

Evaluated using RMSE

📈 **Results & Insights**

**ARIMA RMSE**: Measures statistical forecasting accuracy

**LSTM RMSE**: Evaluates deep learning-based trend predictions

Comparison of actual vs predicted prices in visual plots

🎯 **Key Takeaways**

✅ ARIMA works well for short-term stock price forecasting 📉
✅ LSTM captures complex stock patterns for long-term trends 📊
✅ Data preprocessing & feature engineering improve accuracy 🔍

💡 **Want to contribute? Feel free to fork, star ⭐, and raise issues!**
🔗 **Connect with me**: https://www.linkedin.com/in/poorvi-shrivastava-4a34a9256/
