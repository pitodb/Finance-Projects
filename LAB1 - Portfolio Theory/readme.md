# PC LAB 1 - Testing Portfolio Theory

This project explores the application of Modern Portfolio Theory (MPT) to a portfolio of eight US stocks. The analysis includes data exploration, calculation of stock returns, correlation analysis, simulation of random portfolios, and the identification of the tangency portfolio along with its performance during the sample period.

## Data

The dataset used in this analysis consists of daily stock prices for the following eight US companies:

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/ce4e3bd8-e42e-49d1-b93d-b90829b2ccdb)

## Analysis

The following steps were performed in the analysis:

1. **Data Exploration**: Explored the stock price data to gain insights into the characteristics of the individual stocks.

2. **Normalization and Return Calculation**: Normalized the stock prices and computed the daily stock returns for each company.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/689d5653-3bf3-4ad4-acf4-3f74e91fbbc2)

3. **Correlation Analysis**: Calculated the correlation matrix for the stock returns and visualized it using a heatmap to identify potential diversification opportunities.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/0603b222-e13b-4f1f-84e0-b461f09e9ef0)


4. **Portfolio Simulation**: Simulated 1000 portfolios with random weights, computed the returns, variance, and Sharpe ratio for each portfolio.

5. **Tangency Portfolio**: Identified the tangency portfolio, which represents the portfolio with the highest Sharpe ratio along the efficient frontier.

6. **Efficient Frontier**: Defined a function to draw the efficient frontier, which represents the set of portfolios that provide the highest expected return for a given level of risk (variance).

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/22e93eca-2667-42b9-b554-4e0698f57b34)


## Results and Limitations

The analysis demonstrates the application of Modern Portfolio Theory and the identification of the tangency portfolio. However, it is important to note that this approach has several limitations:

- It may not be an accurate prediction tool, as Markowitz's original goal was not to predict future returns.
- Equal-weighted (EW) portfolios often outperform Markowitz portfolios in practice (Kolm et al., 2014).
- High transaction costs associated with rebalancing the portfolio can reduce its effectiveness.
- The assumption of normality in the returns distribution may not hold true in practice.
- Determining the appropriate sample period for estimating mean and variance can be challenging.
- Many Markowitz portfolios may exclude a large number of stocks in practice.
- The use of variance as a measure of risk is criticized, as it treats upside and downside risk equally, ignoring the potential for rare but significant declines.

Despite these limitations, the analysis provides valuable insights into the principles of Modern Portfolio Theory and serves as a starting point for further exploration and refinement of portfolio optimization techniques.

## References

Kolm, P. N., Tütüncü, R., & Fabozzi, F. J. (2014). 60 Years of portfolio optimization: Practical challenges and current trends. European Journal of Operational Research, 234(2), 356-371.
