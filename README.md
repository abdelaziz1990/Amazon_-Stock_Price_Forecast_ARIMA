   # Amazon_-Stock_Price_Forecast_ARIMA
# Introduction : 
 The Stock Market, as we know, is volatile in nature and the prediction of the same is a cumbersome task. In this work the Amazon stock price are predict With ARIMA model.
 the results from this work lead to a conclusion that ARIMA can be used to predict stock prices for a short period.
 # Project Steps :
  1. Data loading
  2. EDA
  3. Data Stasionarity (ADF, KPSS TESTS and Differencing Method)
  4. Auto-Regressive Integrated Moving Average (ARIMA)
# Data : 
The Data was uploaded from Yahoo finance, from 2012 to 2022, the Data shape is [2537 rows x 6 columns]
# ARIMA :
A famous and widely used forecasting method for time-series prediction is the AutoRegressive Integrated Moving Average (ARIMA) model. ARIMA models are capable of capturing a suite of different standard temporal structures in time-series data.
AR: < Auto Regressive > means that the model uses the dependent relationship between an observation and some predefined number of lagged observations (also known as “time lag” or “lag”).
I:< Integrated > means that the model employs differencing of raw observations (e.g. it subtracts an observation from an observation at the previous time step) in order to make the time-series stationary.MA:
MA: < Moving Average > means that the model exploits the relationship between the residual error and the observations.
# Forcast: 
Once we build The ARIMA Model we forcast the 2012 Year, then we can compare between the actual and the forcast results.
We can see  the Forcaste of 30 Days, short periode..
# Conclusion:
The stationarity issue affect the forecast result, so we need to improve this point. 
We must use Machine learning Model prediction and then compare with ARIMA forecast.


