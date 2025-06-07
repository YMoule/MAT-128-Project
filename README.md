# MAT-128-Project
Stock Predictions on MAAGA Companies using LSTM and Linear Prediction

## Dataset
We used the dataset from https://www.kaggle.com/datasets/nikhil1e9/netflix-stock-price

## EDA
The EDA file provides exploratory data analysis and graphs for the dataset.

## Models
In this repository, there is one linear regression model file including graphs and evaluation of the linear regression mode as well as prediction of future prices. The linear regression model has the best performance overall. 

The LSTM file includes the intial creation of the LSTM model structure and hyperparamter tuning for both the weekly and daily LSTM models. 

LSTM_Final_Days has the best performing LSTM model trained on days and includes model evaluation and prediction of future prices. This model is saved as a .pth file to reintialize the model with the exact same weights. 

LSTM_Final_Weeks has the best performing LSTM model trained on weeks and includes model evaluation and prediction of future prices. 

The New_norm_tech file includes a linear regression model created by training on the difference between today's and yesterdays stock prices rather than the stock prices themselves. It predicts future stock prices as well. 
