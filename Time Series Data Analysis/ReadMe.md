#S&P Index Stock Prediction
*This project is to predict Closing price from past data of S&P Index Stock data.
These are the indicators used in the model
*The average price from the past 5 days.
*The average price for the past 30 days.
*The average price for the past 365 days.
*The ratio between the average price for the past 5 days, and the average price for the past 365 days.
*The standard deviation of the price over the past 5 days.
*The standard deviation of the price over the past 365 days.
*The ratio between the standard deviation for the past 5 days, and the standard deviation for the past 365 days.
*First a linear model and RandomForest Regressor was used to learn and predict. 
*Then data was made to stationary by differencing and decomposing and time-series ARIMA model was used. 
