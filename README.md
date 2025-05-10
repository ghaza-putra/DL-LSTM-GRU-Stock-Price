# DL-LSTM-GRU-Stock-Price
## Background Problem
This project aims to predict the future stock prices of PT Adaro Energy Indonesia Tbk (ADRO) using deep learning models such as LSTM and LSTM+GRU, utilizing the ADRO.csv dataset containing historical stock price data. This time series data is analyzed through Exploratory Data Analysis (EDA) and feature engineering techniques like normalization and time series data creation. The developed models are then evaluated using MSE, RMSE, and R2 metrics to assess prediction accuracy, with the goal of providing insights for better investment decision-making.

Link Dataset from kaggle (https://www.kaggle.com/datasets/muamkh/ihsgstockdata/data)

## Libraries Version
- NumPy version: 2.0.2
- Pandas version: 2.2.2
- TensorFlow version: 2.18.0
- Keras version: 3.8.0
- scikit-learn version: 1.6.1

## Insight
1. **LSTM Model:** The LSTM model shows a strong alignment between predicted and actual data with an RMSE of 135.31, MAPE of 3.42%, and an R² of 0.9412, indicating high accuracy and reliability for stock price prediction.
2. **LSTM with GRU Model:** While the LSTM with GRU model still performs well, it shows slightly higher errors with an RMSE of 174.50, MAPE of 4.36%, and R² of 0.9022, but remains a strong alternative with competitive predictive performance.

## Advice
The LSTM model shows high accuracy with low error, making it a strong choice for stock price prediction. It is recommended to continue using this model and experiment with hyperparameter tuning to further improve accuracy. Meanwhile, although the LSTM with GRU model has slightly higher error rates, it still provides good results. Experimenting with different configurations, such as the number of GRU units or layers, may help improve its performance, and the combination of LSTM with GRU can offer better generalization, especially in avoiding overfitting.

#DeepLearning #Python #StockPrice #DataScience #LSTM #GRU Feel free to connect with me if you'd like to discuss anything, 
ghazaputra99@gmail.com
