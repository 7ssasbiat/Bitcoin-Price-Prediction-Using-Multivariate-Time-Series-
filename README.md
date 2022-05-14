# Bitcoin-Price-Prediction-Using-Multivariate-Time-Series-
BITCOIN PRICE FORCASTING USING VAR,VARMA AND VARMA with AUTO-ARIMA
In this project, we are going to choose the best model beteween the following multivariate time series models : VAR,VARMA AND VARMA with AUTO-ARIMA to forcast bitcoin price.

Why MTS?

Multivariate Time Series consist of more than one time-dependent variable and each variable depends not only on its past values but also has some dependency on other variables.

Bitcoin’s movements show now a high correlation with those of Nasdaq index and S&P500. That's why we will validate if there is a real causality relation between them so we can use multivariate time series models for forecasting.

After studying the causality beteween the three time series, we found out that both S&P500 and NASDAQ series are causing the evolution of Bitcoin. Then we built VAR,VARMA and VARMA with AUTO-ARIMA and compared performances. We conclude that the best model is VARMA with auto-ARIMA since it has the least bitcoin price forcasting error.
![This is an image](https://github.com/7ssasbiat/Bitcoin-Price-Prediction-Using-Multivariate-Time-Series-/blob/main/Actual%20VS%20Forcast.png)


