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
 
### Step 1: Data Collection
Source: Yahoo Finance (yfinance library)<br>
Data Collected: Date, Open, High, Low, Close, Volume, Adjusted Close<br>

### Step 2: Data Preprocessing
•	Handling missing values<br>
•	Feature engineering (e.g., moving averages, daily returns)<br>
•	Data transformation (scaling, normalization)<br>

### Step 3: Exploratory Data Analysis (EDA)
•	Stock price trend visualization (line charts)<br>
•	Daily returns analysis (histograms)<br>
•	Moving average analysis (SMA, EMA)<br>
•	Volatility analysis (Bollinger Bands)<br>

### Step 4: Predictive Modeling
•	Traditional Models: ARIMA (AutoRegressive Integrated Moving Average)<br>
•	Deep Learning Models: LSTM (Long Short-Term Memory), Facebook Prophet<br>
•	Model evaluation: RMSE, MAPE, and accuracy scores<br>

## **Insights & Observations**

•	Stock price trends show cyclic behavior with seasonal highs and lows.<br>
•	Moving Averages (SMA, EMA) help in identifying trends and support/resistance levels.<br>
•	High volatility observed during earnings announcements and macroeconomic events.<br>
•	Daily returns are normally distributed but contain outliers during market crashes.<br>
•	Machine learning models predict trends well, but long-term forecasts require more data.<br>

## **Final Conclusions**

•	Stock prices are influenced by macroeconomic factors, earnings reports, and investor sentiment.<br>
•	Moving averages and Bollinger Bands help in decision-making for trading.<br>
•	Predicting short-term trends is feasible, but long-term predictions are uncertain due to market randomness.<br>
•	A dashboard can enhance visualization and allow dynamic exploration of market trends.<br>
