# VAR Analysis on Sales Data 1

# Introduction:
The following report outlines the steps taken to analyze a time series data of three products, to check whether they are stationary, and to diagnose a VAR model for forecasting. The data was analyzed using Python programming language, and the results were visualized using various Python libraries.

## Data:
The data consists of three products, and the data set is not stationary.


## Results:

* The visually checked data was not stationary.
* After performing the ADF test, it was concluded that the data was not stationary.
* First-order differencing was applied to make the data stationary.
* The optimal order for the VAR model was determined to be 1.
* The VAR model was estimated.
* The residuals of the VAR model passed the test for whiteness.
* The VAR model was found to be stable.
* The roots of the characteristic polynomial were within the unit circle.
* The test for Granger causality was conducted, and the results showed that there was causality among the variables
* Impulse response analyses, cumulative effect plots, long-run effect plots, and forecast error variance decomposition (FEVD) plots were also produced.

## Conclusion:
In conclusion, the data set was analyzed to check whether the data was stationary, and the VAR model was diagnosed for forecasting. The results showed that the data set was not stationary, but it was made stationary after applying first-order differencing. The VAR model was found to be suitable for forecasting, and the model's residuals were found to be white, stable, and causal. Impulse response analyses, cumulative effect plots, long-run effect plots, and FEVD plots were produced to help in forecasting the data.



# Arima Analysis on Sales Data 2

## Introduction:
In this report, we analyze the sales data of a company using time series analysis techniques. Our main objective is to build a model that can forecast future sales with a reasonable level of accuracy.

## Check for Stationarity
We first check if the data is stationary, a necessary condition for ARIMA models. We plot the rolling mean and standard deviation of the sales data over a 12-month period and visually check for stationarity. We then perform the Augmented Dickey-Fuller (ADF) test to confirm the stationarity of the data.

## Determine ARIMA Order
We use the my_plot function to plot the autocorrelation and partial autocorrelation of the sales data. This helps us determine the order of the ARIMA model. We then fit the ARIMA model with the determined order and get a summary of the model.

## Configuring ARIMA Model
We check for the significance of the AR and MA coefficients by looking at their p-values. We then rebuild the model without the non-significant MA terms.

## Review Assumptions
We test if the residuals are white noise by performing the Ljung-Box Q-test. We also check if the residuals are normally distributed using a histogram and a Q-Q plot.

## Fit Analysis
We compare the AIC and BIC of the models to determine which one has a better fit. We then plot the residuals to check for autocorrelation and partial autocorrelation.

## Conclusion:
We have successfully built an ARIMA model that can forecast sales data with a reasonable level of accuracy. We have also checked the assumptions of the model and ensured that the residuals are white noise and normally distributed. This model can be used to make predictions about future sales data and help the company make informed decisions.
