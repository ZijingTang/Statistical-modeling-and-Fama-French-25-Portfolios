# Statistical-modeling-and-Fama-French-25-Portfolios
Data retrieval, statistical modeling (ARCH/GARCH), financial calculations (VaR), and factor modeling.

**Retrieve the daily data on S&P500 and IBM for the period Aug 1 1990 to Aug 1 2019 from yahoo
finance.**

 Fit a ARCH(1), ARCH(2), GARCH(1,1), GARCH(2,1),TARCH(1,1,1), TARCH(2,2,1) models to the index and the stock separately and report the results.
 Find the best model for each series by the BIC criteria from the models mentioned in question (a).
 From the last observation in your sample, use the best model you find in question (b) to find the 1 day ahead 5% Value at Risk (VaR). Do this for both the single stock and the index separately. Suppose the market value of your investment in S&P500 is $100M and the market value of your investment in IBM is also $100M at the last day in your sample.

 **Fama-French 25 portfolios double sorted by size and value**
  Consider to obtain the monthly average value-weighted returns from the ’25_Portfolios_5x5’ in the Fama-French datasets. The sample period is from Jul 1963 - Sep 2019.
  Obtain the corresponding monthly market, size, and book-to-market factors in the Fama-French
datasets.
  Run the 3-factor model for the 25 portfolios to obtain alpha, the t-statistic of alpha, the coefficients
before each factor and adjusted R2.
  Calculate the risk premium predicted by the 3-factor model and the realized risk premium for each portfolio. Use two sets of risk premiums to plot a figure for evaluating the performance of the 3 factor model in the 25 portfolios under study.
