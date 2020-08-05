# Brazil-COVID-Predictions

Currently implements Facebook's Prophet model, the Holt-Winters model, and the ARIMA model to predict the accumulated COVID-19 cases and deaths in Brazilian states based on historical data. Currently, it trains with Brazilian data up until June 15th, 2020, and then compares its predictions with the reported data from June 16th to June 29th, 2020. It runs MAD, MAPE, and RMSE to analyze each model's accuracy in predicting cases across Brazil and its diverse states. Hopefully, this can be used to assist government officials in their response to this crisis.
