# FinancialMarketPrediction-TimeSeriesAnalysis-MinorProject

This research project is focused on making a regression-based Price Prediction of stocks using various statistical and machine-learning models. The target variable for the prediction was the stock's closing price, and the study focused on the Indian financial markets. The data was gathered over 25 years using the YFinance API from Yahoo Finance.

The implementation of the project involved testing the accuracy of various statistical models such as Linear Regression, AR(Auto-regressive), MA(Moving Average), ARMA (Auto-regressive moving average), ARIMA(Autoregressive Integrated moving average), and LSTM(Long-Short Term Memory). The models were tested using python and the accuracy of the models was evaluated using the R Square (coefficient of determination) and the Mean Squared Error (MSE) is calculated for checking the residual error. The stock selected for the implementation was ‘BHARATFORGE’.

The purpose of the research was to analyze the data set using data mining techniques and to predict future trends using machine learning algorithms. The first step involved extracting and pre-processing the data to ensure its accuracy and consistency. Next, feature selection was performed to identify the most relevant features for the analysis. A descriptive analysis was conducted to understand the characteristics of the data and formulate hypotheses for testing.

Overall, this research project demonstrated the potential of machine learning algorithms in predicting stock prices and the importance of pre-processing and feature selection in obtaining accurate results.

## What is Stock Market Prediction

Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a suggests that stock prices reflect all currently available information and any prices changes that are not base on newly revealed information this are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to again future prices information.

## What is Time Series Analysis

A time series is a series of data points indexed in timeorder. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data. Example of time series are heights of ocean tides, counts of sunspots and the daily closing value of the Dow Jones Industrial Average. Time Series Analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the ise of a model to predict future values based on previously observed values. While regression analysis is often employed in such a way as to test theories that the current vales of one or more independent time series affect the current value of another time series , this type of analysis of time series is not called “time series analysis”, which focuses on comparing vales of a single time series or multiple dependent time series at different points in time. 

## Flowchart

![image](https://user-images.githubusercontent.com/73190244/222461411-6c815775-7673-4233-9f74-303630e4bafb.png)

## Comparative Analysis

![image](https://user-images.githubusercontent.com/73190244/222462752-b2e5f472-82e1-4db8-a26b-04f536bdbe4d.png)

## Conclusion

Time series models are powerful tools for the analysis of stock price data and prediction. The linear regression model is a simple and widely used method for time series analysis, while the AR, MA, ARMA, ARIMA, and LSTM models offer more advanced capabilities for dealing with non-linear and non-stationary data. However, it is important to note that the choice of model will depend on the specific data set. For example, if the data is known to be non-linear, an ARIMA or LSTM model may be more appropriate. On the other hand, if the data is linear, a linear regression model may be sufficient. Additionally, it is important to be aware of the limitations of each model and to interpret the results with caution. For example, the LSTM model may be sensitive to the values in the data so scaling/normalization is done for dealing with that condition, while the ARIMA model may not be able to capture long-term patterns in the data and data must be stationary for implementing the ARMA and ARIMA models. Combining the strengths of different models makes it possible to build a hybrid model that can effectively capture both linear and non-linear relationships in the data.


