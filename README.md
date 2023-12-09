This project is to predict stock price on a daily basis and recommend BUY, HOLD, SELL decisions.

Approaches include Moving Average, ARIMA, Prophet and LSTM models. In terms of performance, ARIMA and Prophet can only learn the upward trend but not the seasonality of the price pattern. 
On the other hand, LSTM model using 5 prior days' prices to predict the next price outperforms other models with MAPE score of ~0.012, 
meaning the average difference between the predicted price and the actual value is only 1.2%. It is predicted that the given stock should be bought on Feb 1st and sold on Mar 3rd, 
gaining a return of **>$21**/stock after being held for 30 days. 
