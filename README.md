# Stock-Price-Prediction

![Project Image](C:\Users\urvas\OneDrive\Desktop\stock_price.jpg)

## Data Analytics Hackathon Project

This repository contains my data analytics project for a Kaggle hackathon, where I focused on stock price prediction for the 'Close' and 'Strategy' columns using the 'Open' and 'Volume' features.

**Leaderboard Ranking:** I'm proud to share that I achieved the 32nd position out of 274 participants on the Kaggle leaderboard for this hackathon.

## Project Overview

In this hackathon, I aimed to predict stock prices and develop a strategy (Hold, Buy, or Sell) based on historical data. I used the following techniques and models:

### Stock Price Prediction - 'Close' Column
- **Linear Regression:** I used linear regression as my final model for predicting the 'Close' price of stocks. Although I experimented with ARIMA initially, it didn't perform as well as linear regression. You can find the ARIMA code in the repository as well.

### Strategy Prediction
- **Ensemble Learning:** To predict the 'Strategy' (Hold, Buy, or Sell), I leveraged ensemble learning techniques.
- **XGBoost:** I employed the XGBoost model as one of the ensemble base models.
- **Soft Voting:** The final prediction for the strategy was made using soft voting among the ensemble models.

## Getting Started

To run the code and reproduce the results, follow these steps:

1. Clone this repository to your local machine.
2. Navigate and open the Kaggle notebook for step-by-step analysis.
3. Review the code and comments to understand the data preprocessing and modeling process.
4. Execute the notebooks to generate predictions for the 'Close' and 'Strategy' columns.

Happy coding!
