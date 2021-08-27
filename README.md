# Time Series Analysis on Store Item Demand Forecasting

### **Objective:** Predict 3 months of item sales at different stores
                                               

The dataset is provided with 4 columns:       
**date:** The date of sale    
**store:** This is the store number     
**item:** This is the item number       
**sales:** Sales made on that particular day  

### Approach:
- Visualise the Time series
- **Decomposing** into trend, seasonal, cyclical and noise components
- Analyze the **seasonality** of a Time Series: additive and multiplicative.
- Check **stationarity** of data - **Rolling Mean, ADCF Test(Augmented Dickey–Fuller test)**
- Stationarize Time series - first **differencing**
- Plot **ACF/PACF** charts and find optimal parameters
- Build Time series models according to data - **AR, MA, ARIMA, SARIMA**
- Plot Residual distribution
- Make predictions
- **MAPE,SMAPE** as evaluation metric

### References:
- https://towardsdatascience.com/what-is-time-series-decomposition-and-how-does-it-work-9b67e007ae90
- https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/
- http://www.seanabu.com/2016/03/22/time-series-seasonal-ARIMA-model-in-python/


