# predict-stock-prices-using-time-series-analysis

df.close.rolling(3, win_type ='triang').sum()

dataframe.rolling() function provides the feature of rolling window calculations


ARIMA model, gold source --> https://www.investopedia.com/terms/a/autoregressive-integrated-moving-average-arima.asp

Takeaways:
Difference between autoregressive and moving average models:
  
  AR(1) autoregressive process, for instance, is one in which the current value is based on the immediately preceding value, while an AR(2) process is one in which the current      value is based on the previous two values. A moving average is a calculation used to analyze data points by creating a series of averages of different subsets of the full data    set to smooth out the influence of outliers --> so it can take into account trends, cycles, seasonality and other non-static types of data
