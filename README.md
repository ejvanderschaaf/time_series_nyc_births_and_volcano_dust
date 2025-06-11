# Introduction

The typical goal of time series analysis is to use data points gathered at regular intervals to predict future values. Methods such as decomposition can be used to determine the underlying structure of the data. Single moving average or exponential smoothing can help reduce noise. ARIMA is a popular model for time series analysis which incorporates autoregression, differencing, and moving average.

This report will decompose time series data concerning births in NYC from 1946 - 1959. Then another dataset concerning the presence of volcanic ash in the northern hemisphere will be analyzed. An ARIMA model will be fit and used to forecast. These forecasted values will be evaluated against known values.

![image](https://github.com/user-attachments/assets/b316fbee-e7e9-4737-b800-02825319d3a5)
__Figure 1.__ Decomposition of NYC births time series data

![image](https://github.com/user-attachments/assets/e2c1a310-c950-4fca-9fdf-3e0c7f563eda)
__Figure 2.__ Time series plot of seasonally adjusted NYC births data

![image](https://github.com/user-attachments/assets/ce06239c-f432-4c2e-a79c-243a69ac369e)
__Figure 3.__ Volcanic dust level predictions, 1960 - 1970
