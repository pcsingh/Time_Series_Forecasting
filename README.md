# Time_Series_Forecasting

Solar radiation is an important source for electricity generation. For effective utilization, it is important to precisely know the irradiance amount at different time horizons: minutes, hours, and days. Depending on the horizon, two main classes of methods can be used to forecast the solar radiation: statistical time series forecasting methods for short to midterm horizons and numerical weather prediction methods for medium- to long-term horizons.

- In this project, we have to forecast the future solar irradiance (watt per meter square) values using ClimaCell API Data and real weather station data from a solar plant.

On [ClimaCell Data](https://github.com/pcsingh/Time_Series_Forecasting/blob/main/notebook/climacell_data_model.ipynb), I have shown a variation of irradiance with time and used some algorithms or model such as Multilayer Perceptron (MLP), Stacked LSTM, Gated Recurrent Units (GRU), and Bidirectional LSTM. Also, check the stationarity property of time series using the Duckey Fuller test and show the future irradiance values using the Bidirectional LSTM model.

On [Weather station Data](https://github.com/pcsingh/Time_Series_Forecasting/blob/main/notebook/weather_data_model.ipynb), I have used ARIMA, SARIMA, and LSTM algorithms and show their performances. From them, LSTM performs well, which can be used for future prediction of Solar Irradiance value.

Performance metrics used are R2, Root mean square error (RMSE), and Normalized RMSE.

Same approach can be used for stock price prediction, company sales prediction, etc.
