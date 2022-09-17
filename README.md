# Time-series-analysis-and-forecasting-files
In this repository, I have shared project files in time-series analysis and forecasting domain.

Project 1: time-series-analysis-methods - This file contains methods and techniques that are used in time-series forecasting and analysis.

Project 2: stock-price-analysis-and-forecasting - In this project I have analysed TOP 10 most traded S&P 500 stocks and built models to forecast future values.


-------------

# Stock price analysis and forecasting

## Background
Time series forecasting is parhaps one of the most common type of machine learning techniques used in real-world scenarios. `time-sereis forecsting refers to predicting future values from historical data by statical analysis of trends and patterns from certain time-series data.` it falls under unsupervised learning category but called as a self-supervised learning or supervised learning technique. time-series data can be much complex to find patterns out of it, this is because irregular component of time series. time-series data is widely used and analysed in finance industry to measure the performace of stocks. this noteboook consists of stock price analysis and forecasting models that are can be leveraged in stock price analysis and forecasting.

## Objectives and tasks
- Prepare S%P 500 stocks data to find TOP 10 most traded stocks
- Analyse stock data to find best performing stocks and recommend which stocks to buy
- Conduct statistical hypothesis test to prove daily return stock hyppthesis
- Build forecasting models to find forecast future values of stock ticker 'FB' and 'AAPL'

## Approch and techniques
- Used for loops and dataframe filtering to find TOP 10 traded stocks
- Analysed top 10 stocks to find average trade volume, growth of stocks
- Did comprative anaalysis of 7 tech stocks 
- 1 sample t-test to prove hypothesis of daily return being 0%
- technical analysis using moving average method and candle stick charts
- Built forecasting models using FB's Prophet module and also using Auto-ARIMA models.

## Learnings from this project
1. Learned how to comprehensively analyze stock price data to find relevant insights
2. technical analysis of stocks using comparative analysis, moving average and candlestick charts
3. time-series forecast modelling using auto-ARIMA models, evaluation metric RMSE, non-stationarity of time-series and ACF/PACF plots

## Tools/technologies used
- Python
- fbprophet
- pmdarima
- matplotlib
- pandas
- plotly
- statsmodels
- mplfinance 
