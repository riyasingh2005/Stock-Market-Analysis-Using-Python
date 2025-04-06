# Stock-Market-Analysis-Using-Python

This project involves analyzing historical stock market data, extracting key insights using visualization tools, and predicting future trends using machine learning techniques.

## **Project Objective**

The objective of this project is to:<br>
•	Perform exploratory data analysis (EDA) on stock market data.<br>
•	Identify trends, volatility, and price patterns over time.<br>
•	Visualize key metrics such as daily returns, moving averages, and volatility.<br>
•	Use machine learning models (e.g., ARIMA, LSTM, Prophet) to forecast stock prices.<br>
•	Build a dashboard to present insights and predictions interactively.<br>

## **Research Questions**

1.	What are the historical trends in stock price movements?
2.	How do moving averages (SMA, EMA) indicate potential buying/selling opportunities?
3.	What is the daily return distribution, and how volatile is the stock?
4.	What are the significant bullish and bearish trends?
5.	Can machine learning models predict future stock prices accurately?
6.	How can a dashboard help visualize stock market trends and forecast performance?

## **Data Collection & Process**
 
Step 1: Data Collection
Source: Yahoo Finance (yfinance library)
Data Collected:
Date, Open, High, Low, Close, Volume, Adjusted Close

Step 2: Data Preprocessing
•	Handling missing values
•	Feature engineering (e.g., moving averages, daily returns)
•	Data transformation (scaling, normalization)

Step 3: Exploratory Data Analysis (EDA)
•	Stock price trend visualization (line charts)
•	Daily returns analysis (histograms)
•	Moving average analysis (SMA, EMA)
•	Volatility analysis (Bollinger Bands)

Step 4: Predictive Modeling
•	Traditional Models: ARIMA (AutoRegressive Integrated Moving Average)
•	Deep Learning Models: LSTM (Long Short-Term Memory), Facebook Prophet
•	Model evaluation: RMSE, MAPE, and accuracy scores

## **Insights & Observations**

•	Stock price trends show cyclic behavior with seasonal highs and lows.
•	Moving Averages (SMA, EMA) help in identifying trends and support/resistance levels.
•	High volatility observed during earnings announcements and macroeconomic events.
•	Daily returns are normally distributed but contain outliers during market crashes.
•	Machine learning models predict trends well, but long-term forecasts require more data.

## **Final Conclusions**

•	Stock prices are influenced by macroeconomic factors, earnings reports, and investor sentiment.
•	Moving averages and Bollinger Bands help in decision-making for trading.
•	Predicting short-term trends is feasible, but long-term predictions are uncertain due to market randomness.
•	A dashboard can enhance visualization and allow dynamic exploration of market trends.
