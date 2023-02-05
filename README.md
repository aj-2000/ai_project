#Sales Forecast
A sales forecasting tool that allows the user to put a link to a sales dataset, then the user can predict the future sales based on previous sales data, which can be beneficial in many ways. This feature uses the AMIRA Time series, analysis Model.

- Features:
  - Any CSV Dataset with the first column as Dates and the second column as Numerical values (sales) is supported.
  - Users can optimise the forecasting model by using different values of "p" and "q". "p" and "q" are parameters of the ARIMA(p,d,q) equation. This model assumes the value of "d" to be 1.
  - Displays various model accuracy metrics such as Root Mean Squared Error(RMSE), Mean Absolute Percentage Error(MAPE), and Residual Sum Of Squares(RSS) Value.
  - Tells whether the given data is stationary or not using Dickey-Fuller Test.
  - Shows model accuracy by showing a visual comparison between actual and predicted values.
  - Applicable for both stationary and non-stationary datasets.
