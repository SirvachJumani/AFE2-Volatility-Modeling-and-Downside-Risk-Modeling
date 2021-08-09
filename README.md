# AFE2-Volatility-Modeling-and-Downside-Risk-Modeling
University Trier - Applied Financial Econometrics - Project 2

# Volatility-Modeling

1. First we load the EUROSTOXX50 dataset as a modern time series object into your working environment and plot it.
2. Then Use the AIC and autocorrelation tests to find an adequate ARMA-GARCH specification up to 5 lags for the log-returns. Also consider normal as well as t-distributed residuals.
4. Check the result support the premise of volatility clustering.
5. Use a GJR-GARCH(1,1) model to check whether we have leverage effects are present in the dataset.
6. Use an EGARCH(1,1) for the same purpose whether we have leverage effects are present in the dataset. 

# Downside-Risk-Modeling

1. First the empirical distribution function of the EUROSTOXX50 logreturns.
2. Then explia whole-sample empirical VaR and ES at the 99% level.
3. Compute time-varying estimates of VaR (99%) and ES (99%) with Historical Simulation. Use data from the previous 250 trading days in each period.
4. Creating the plot of the log-returns together with the computed VaR and ES series in a time series graph.
5. Backtest your VaR estimates for violation independence as well as correct conditional and unconditional coverage.
