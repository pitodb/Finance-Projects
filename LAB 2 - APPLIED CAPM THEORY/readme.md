# PC LAB 2 - APPLIED CAPM THEORY

This project aims to apply the Capital Asset Pricing Model (CAPM) theory to real-world financial data. The analysis involves web scraping market data, computing CAPM parameters (alpha and beta) through ordinary least squares (OLS) regression, calculating error terms, forming a portfolio of risky assets, and testing the validity of the CAPM theory.

## Data Collection

The market data used in this analysis was obtained through web scraping using the Yahoo Finance API. This allowed for the collection of up-to-date financial data from various sources.

## Analysis

The following steps were performed in the analysis:

1. **Web Scraping Market Data**: Utilized the Yahoo Finance API to gather relevant market data for the analysis.

2. **Computing CAPM Parameters**: Computed the CAPM parameters, alpha and beta, for individual assets using ordinary least squares (OLS) regression.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/b71fb186-64d3-4f4b-a3d6-bfcf0da762e5)

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/9e939ad0-3571-4405-b16c-888b56f65fb7)


3. **Error Term Calculation**: Calculated the error terms between the observed returns and the predicted returns based on the CAPM model.
![image](https://github.com/pitodb/Finance-Projects/assets/112696408/aa0925f2-8fa2-4ef4-8928-042d060d1076)


4. **Portfolio Formation**: Selected four risky assets and formed an equally weighted portfolio.
![image](https://github.com/pitodb/Finance-Projects/assets/112696408/e67ecd4d-d540-4179-88e7-5463b8b642bf)


5. **Portfolio Return Estimation**: Estimated the portfolio return based on the CAPM parameters (alpha and beta) obtained from the individual asset analysis.
![image](https://github.com/pitodb/Finance-Projects/assets/112696408/d090fc53-3c7e-4e13-8059-f9f0821d6c95)



6. **CAPM Theory Testing**: Tested the validity of the CAPM theory by comparing the predicted returns with the actual observed returns for the formed portfolio.
![image](https://github.com/pitodb/Finance-Projects/assets/112696408/de05c807-400f-4c3a-af94-52cf70371ed6)



## Considerations

When testing the CAPM theory with large-scale real financial data, it is important to consider the following factors:

- **Market Inefficiencies**: Financial markets may not always operate efficiently, violating one of the key assumptions of the CAPM theory. Market inefficiencies can arise due to factors such as information asymmetry, investor behavior, and market frictions.

- **Transaction Costs**: The CAPM theory assumes frictionless markets, but in reality, transaction costs (e.g., brokerage fees, bid-ask spreads) can impact the realized returns and portfolio performance.

- **Borrowing at the Risk-Free Rate**: The CAPM theory assumes that investors can borrow and lend at the risk-free rate, which may not always be feasible in practice.

- **Model Assumptions**: The CAPM theory relies on several simplifying assumptions, such as the normality of returns, which may not hold true in real-world scenarios.

While the CAPM theory can provide useful insights and a framework for understanding the relationship between risk and expected returns, its predictions may not always align perfectly with the complex realities of financial markets. Therefore, it is essential to interpret the results cautiously and consider the limitations and assumptions of the model when applying it to real-world data.

Despite these limitations, the analysis conducted in this project offers valuable practical experience in working with financial data, implementing the CAPM theory, and evaluating its applicability in real-world scenarios.
