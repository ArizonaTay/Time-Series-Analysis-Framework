# VAR Analysis on Sales Data

# Introduction:
The following report outlines the steps taken to analyze a time series data of three products, to check whether they are stationary, and to diagnose a VAR model for forecasting. The data was analyzed using Python programming language, and the results were visualized using various Python libraries.

## Data:
The data consists of three products, and the data set is not stationary.


## Results:

The visually checked data was not stationary.
After performing the ADF test, it was concluded that the data was not stationary.
First-order differencing was applied to make the data stationary.
The optimal order for the VAR model was determined to be 1.
The VAR model was estimated.
The residuals of the VAR model passed the test for whiteness.
The VAR model was found to be stable.
The roots of the characteristic polynomial were within the unit circle.
The test for Granger causality was conducted, and the results showed that there was causality among the variables.
Impulse response analyses, cumulative effect plots, long-run effect plots, and forecast error variance decomposition (FEVD) plots were also produced.

## Conclusion:
In conclusion, the data set was analyzed to check whether the data was stationary, and the VAR model was diagnosed for forecasting. The results showed that the data set was not stationary, but it was made stationary after applying first-order differencing. The VAR model was found to be suitable for forecasting, and the model's residuals were found to be white, stable, and causal. Impulse response analyses, cumulative effect plots, long-run effect plots, and FEVD plots were produced to help in forecasting the data.
