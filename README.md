# Samsung Stock Price Prediction

## Introduction

Using the Kaggle [Samsung Stock](https://www.kaggle.com/datasets/ranugadisansagamage/samsung-stocks) dataset, I will be predicting the closing stock price of Samsung using a Recurrent Neural Network (RNN). I will be using the Long Short-Term Memory (LSTM) architecture for the RNN. The different models will be evaluated using the Root Mean Squared Error (RMSE) metric. I have created a Vanilla LSTM, Stacked LSTM, Bidirectional LSTM with a very low validation loss.

## Outcome

The best model created a prediction for the next 30 days (starting from 2022-05-24), which is saved inside the "predictions.csv" file.

## Setup

To run this project locally you will need to run the following commands:

```bash
git clone https://github.com/Detopall/samsung-stock-price-prediction.git
cd samsung-stock-price-prediction
pipenv install
pipenv shell
```
