# Brazil-COVID-Predictions

Currently implements Facebook's Prophet model, the HoltWinters model, and the auto ARIMA model to try and predict the accumulated COVID Cases and deaths in Brazilian states based off of past dates. Currently, it trains with Brazilian data up until June 15 and then compares its predictions with the reported data from June 16th - June 29th. It runs MAD, MAPE, and RMSE analysis to analyze the effectiveness of 
each model in predicting cases across Brazil and its diverse states. Hopefully this can be used to assist the officials in their response to this crisis.
