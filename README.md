#                                                                                  UK monetary policy, inflation and FTSE 100 analysis

 This project investigates the empirical relationship in the UK between inflation, bank interest rate changes and FTSE 100 monthly returns from 2005-2026.
 The analysis uses macroeconomic data with financial market data within the UK.
 Python is used to clean and merge datasets, calculate returns, visuialise trends and estimate regression models.

 ## Hypothesis
 
 H0: UK inflation and bank rate changes have no statistically significant relationship with FTSE 100 monthly returns
 
 H1: UK inflation and bank rate changes has a statistically significant negative relationship with FTSE 100 monthly returns


 ## Data sources
 1. Office for national statistics (ONS) - Uk CPI inflation
 2. Bank of England (BoE) - bank rate history
 3. Yahoo finance - FTSE 100 historical market data

 ## Tools
 1. Python
 2. Pandas
 3. NumPy
 4. Matplotlib
 5. Statsmodels
 6. Yfinance

 ## Methodology
 1. Import raw data
 2. Clean date formats and inconsistent data structures
 3. Convert FTSE 100 dailly prices to monthly
 4. Calculate yearly rolling volatility
 5. convert bank rate changes to monthly time series
 6. Merge inflation, bank rate and FTSE 100 to one dataset
 7. Analyse correlations of macroeconomic data and FTSE returns
 8. Estimate contemporaneous and one month lagged ONS regression models

 ## Key findings
1. This project found very weak correlation between uk inflation, bank rate changes and FTSE 100 returns
2. The regression produced a 0.004 R squared, this means CPI inflation and bank rate changes explained just 0.4% of variation in FTSE 100 returns
3. CPI inflation and bank rate changes were not significant predictors in FTSE 100 returns
4. The one month lagged regression produced similar results; there was an R squared of 0.007 and no significant coefficients
5. Monthly FTSE 100 peformance cannot be well explained by uk inflation and bank changes alone.

## Graphs
1. UK CPI inflation and bank rate changes over time: 
    - ![UK CPI Inflation and Bank Rate](figures/inflation_bank_rate.png)
2. FTSE 100 monthly returns: 
    - ![FTSE 100 Monthly Returns](figures/ftse_monthly_returns.png)
3. FTSE 100 rolling 12 month volatility: 
    - ![FTSE 100 Rolling Volatility](figures/ftse_rolling_volatility.png)
4. Bank rate chaneges compared to FTSE 100 returns
    - ![Bank Rate Changes vs FTSE 100 Returns](figures/bank_rate_change_vs_ftse_return.png)


## Limitations
1. The analysis identifies statistical relationships, but does not establish causation.
2. The market is not under ceretis paribus conditions, and so other factors can influence the FTSE 100 returns. 
3. Equity markets are influenced by numerous factors, including global economic conditions, investor sentiment,and geopolitical events. 
4. Financial markets also respond to expectations of future economic conditions.

## Conclusions 
The project demonstrates use of python, regression modelling, analysis, data collection, cleaning and graphing. 
Using this the project investigated Uk monetary and ionflation impact on FTSE 100 returns and identified no significant correlation. 
The methodology could be improved: such as analysing unexpected bank rate changes rather than raw data, analysing more financial decisions that may have impacted the market, finally comparing the FTSE 100 to FTSE 250, for more domestic exposure
