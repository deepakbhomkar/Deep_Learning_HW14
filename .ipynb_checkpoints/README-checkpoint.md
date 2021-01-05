# Deep_Learning_HW14
Homework 14 Deep Learning

# Stock Predictor Using Closing prices and Fear & Greed Index for Bitcoin

## Step 1 (FNG Model)
Build and train a custom LSTM RNN that uses a 10 day window of Bitcoin fear and greed index values to predict the 11th day closing price.

## Step 2 (Closing Price Model)
Build and train a custom LSTM RNN that uses a 10 day window of Bitcoin Closing prices values to predict the 11th day closing price.

Based on the above models, the Closing Price model tracks the Real and Predicted values better over time as seen by the plots below.


![LSTM FNG Model](Instructions/Images/LSTM_FNG_Model.png)

![LSTM FNG Model](Instructions/Images/LSTM_Closing_Price_Model.png)

The model with the lower loss performance was the LSTM Closing Prices Stock Predictor which showed a loss of 0.0265 when compared to the LSTM FNG Stock Predictor that showed a 0.0810. 
