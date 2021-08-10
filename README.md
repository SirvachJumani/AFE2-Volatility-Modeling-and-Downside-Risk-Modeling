# AFE2-Volatility-Modeling-and-Downside-Risk-Modeling
University Trier - Applied Financial Econometrics - Project 2


# Summary for Volatility Modeling: 
In the time-series 5 weekdays data of Euro stock close exchange price, firstly cleaning and manipulating the dataset and then first using AIC and autocorrelation to find the best ARMA GARCH model for up to five lags for the log-returns. Afterward, check the volatility clustering in the dataset. Finally generates the GJR-GARCH and EGARCH model to check the leverage effect is present or not in the Euro stock data set.

# Task done in Volatility Modeling

1. First we load the EUROSTOXX50 dataset as a modern time series object into your working environment and plot it.
2. Then Use the AIC and autocorrelation tests to find an adequate ARMA-GARCH specification up to 5 lags for the log-returns. Also consider normal as well as t-distributed residuals.
4. Check the result support the premise of volatility clustering.
5. Use a GJR-GARCH(1,1) model to check whether we have leverage effects are present in the dataset.
6. Use an EGARCH(1,1) for the same purpose whether we have leverage effects are present in the dataset. 

# Summary for Downside Risk Modeling
Description for Downside Risk Modeling: Using the same dataset of Euro stock. firstly compute the empirical distribution for the historical simulation at Value at Risk (VaR) (99%) and Expected Shortfall (ES) (99%), moreover create GARCH combination models with Normal distribution, Student t distribution, Normal GJR-GARCH distribution, and Student GJR-GARCH distribution to check which model performs better in term of the correct conditional and unconditional coverage by Backtest of Value at Risk (VaR).

# Task done in Downside Risk Modeling

1. First the empirical distribution function of the EUROSTOXX50 logreturns.
2. Then explia whole-sample empirical VaR and ES at the 99% level.
3. Compute time-varying estimates of VaR (99%) and ES (99%) with Historical Simulation. Use data from the previous 250 trading days in each period.
4. Creating the plot of the log-returns together with the computed VaR and ES series in a time series graph.
5. Backtest your VaR estimates for violation independence as well as correct conditional and unconditional coverage.



