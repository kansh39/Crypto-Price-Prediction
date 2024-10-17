This project aims to predict the future prices of cryptocurrencies using historical market data and a Long Short-Term Memory (LSTM) neural network. Leveraging the CoinGecko API, historical data for cryptocurrencies like Bitcoin is fetched and preprocessed for time-series analysis. The data is scaled and structured into sequences of past prices to serve as input for the LSTM model. After training the model, predictions are made for future prices, and the performance is evaluated using Root Mean Squared Error (RMSE). The project demonstrates how deep learning can be applied to predict trends in the volatile cryptocurrency market.
Summary of Steps:
Install libraries.
Fetch historical price data using CoinGecko API.
Visualize the data.
Preprocess the data: Scale prices and create sequences.
Build an LSTM model.
Train the model.
Evaluate the model by comparing predicted and actual prices.
