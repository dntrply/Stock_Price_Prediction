# Stock_Price_Prediction
## Self contained module in just a few lines of code, predicts future prices of any company in S&P 500 using all prices of S&P tickers using sci-kit learn
### Run Note Book Predict_Stock_Prices.ipynb (other notebooks are inter-connected)
  ### 1. downloads/updates latest S&P tickers 
  ### 2. downloads prices of all S&P tickers in a folder called 'prices' for the choosen date range
  ### 3. prepares a consolidated Adj Close File with all Adj Close prices for all tickers for Machine Learning
        ### note: other columns like 'High', 'Low', 'Open' and 'Close' and its varies iterations did not improve accuracy
  ### 4. Predicts using following Sci-Kit Learn Algorithms
     Predicts using Linear Regression
     Predicts using Bayesian Ridge Regression
     Predicts using using RANSAC
     Predicts using K Nearest Neighbors Regressor
     Predicts using Gaussian Process Regression
     Predicts using Decision Tree Regressor
     Predicts using Gradient Boosting Regressor
