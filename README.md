# Predicting_Volatility_GARCH_vs_XGBoost
<a id='abs'></a>
## Abstract
In this project, the Generalized Autoregressive Conditional Heteroskedasticity (GARCH) and a XGBoost Machine Learning model have been used to predict the volatility of Repsol's stock. GARCH is a widely-used statistical model for forecasting the variance of financial time series, and is particularly useful for modeling the volatility of stocks. Using historical data on Repsol's stock, we fitted a GARCH model and use it to make short-term rolling forecasts of the stock's volatility. We also compared the performance of our GARCH model to other more general Machine Learning model, XGBoost. Our results show that the XGBoost model is able to accurately predict the rolling monthly volatility of Repsol's stock and outperforms the GARCH model in out-of-sample forecasting. This project demonstrates the usefulness of Machine Learning for forecasting the volatility of stocks and highlights the importance of considering the time-varying nature of volatility in quantitative financial analysis.

<center>
<img src="https://1000marcas.net/wp-content/uploads/2020/11/Repsol-Logo.png" alt="image_description" width="500"/>
    </center>

Repsol is a Spanish energy company that engages in the exploration, development, production, and marketing of oil, natural gas, and other energy products. It is one of the largest energy companies in Spain and has operations in more than 30 countries around the world. Repsol is also involved in the development of renewable energy sources, such as wind power and solar energy.
<br/><br/>
Training period: 2002-10-28 to 2021-10-28 (5018 Trading Days) 
<br/><br/>
Test period for forecasting (The model has never seen this data): 2021-10-28 to 2022-10-28 (251 Trading Days)
<br/><br/>
Predictions are done on a rolling basis, predicting monthly (22 trading days) volatility day by day
<br/><br/>

## Tools

The Generalized Autoregressive Conditional Heteroscedasticity (GARCH) model is a statistical model used to describe the time-varying variance of financial time series data. It is commonly used to model the volatility of financial returns, and can be used to make predictions about future volatility, in this case we use the one from the "arch" module.
<br/><br/>



The Extreme Gradient Boosting (XGBoost) model is a powerful machine learning algorithm used for classification and regression tasks. It is an implementation of gradient boosting that is optimized for speed and performance. XGBoost is a popular choice among data scientists because it provides a high level of accuracy while also being efficient and easy to use. It works by creating a series of decision trees and combining their predictions through an ensemble model. The algorithm can handle a variety of data types, including numerical, categorical, and missing values.
