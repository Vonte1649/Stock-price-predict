# Stock-price-predict

This program predicts stock prices using LSTM (Long Short-Term Memory) neural networks. The data is fetched using the yfinance library which connects to Yahoo Finance.

Steps Taken to Create this Project
Data Collection: Used the yfinance library to fetch historical stock prices from Yahoo Finance.
Data Preprocessing: The fetched data was scaled using MinMaxScaler from scikit-learn to transform the stock prices to a range of 0 to 1.
Model Building: Built an LSTM (Long Short-Term Memory) model using tensorflow. This model takes the past 60 days of stock prices to predict the next day's closing price.
Model Training: The LSTM model was trained on the historical stock data.
Testing and Prediction: After training, the model was tested on more recent data to predict stock prices and compare them with actual prices.
Visualization: Used matplotlib to visualize the actual vs. predicted stock prices.


Libraries Used
numpy: For numerical operations and data manipulation.
pandas: For handling and analyzing structured data.
matplotlib: For plotting and visualizing data.
yfinance: For fetching stock data from Yahoo Finance.
tensorflow: For building and training the LSTM neural network model.
scikit-learn: For data preprocessing using MinMaxScaler.


How to Run
Ensure you have the required libraries installed:

pip install numpy matplotlib pandas yfinance tensorflow scikit-learn
Run the main.py:

python main.py


Tested Stocks
The program has been tested for the following stocks:

Tesla (TSLA) image

JP Morgan (JPM) image

Apple (AAPL) image


Disclaimer
Do not use it to make investment decisions. The stock market is unpredictable and influenced by numerous factors outside the scope of this program.
