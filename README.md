Bitcoin Price Prediction using ARIMA Model
This project aims to predict the price of Bitcoin using the ARIMA (AutoRegressive Integrated Moving Average) model. 
The ARIMA model is a popular statistical method for time series forecasting, especially useful for datasets that show evidence of non-stationarity.

The ARIMA model combines three components:

AutoRegressive (AR) part: Involves regressing the variable on its own lagged (i.e., prior period) values.
Integrated (I) part: Involves differencing the observations to make the time series stationary.
Moving Average (MA) part: Involves modeling the error term as a linear combination of error terms occurring contemporaneously and at various times in the past.
The model is specified as ARIMA(p,d,q), where:

p: Number of lag observations included in the model (lag order).
d: Number of times that the raw observations are differenced (degree of differencing).
q: Size of the moving average window (order of moving average).
