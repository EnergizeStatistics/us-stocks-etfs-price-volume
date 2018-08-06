# Stock Price Prediction #
This repository hosts my code that predicts US stock and ETF prices. 
## Description ##
The data used in the analysis is [provided by Kaggle user Boris Marjanovic](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs "Kaggle Huge Stock Market Dataset"). Datasets cover the full historical daily price and volume data for all US-based stocks and ETFs trading on the NYSE, NASDAQ, and NYSE MKT up to November 10, 2017; they include open, high, low, close prices, as well as volume. 

Currently I pick one stock and use recurrent neural network with long-short term memory (RNN-LSTM) to predict its daily closing price. The model performance is shown in the last plot in the notebook. 
## Future Work ##
Productionize the process to all stocks and ETFs, potentially using the `Flask` package. 
## Requirements ##
`Python`, `keras`, `sci-kit-learn` and other common analytical packages. 
