# AI-Driven Portfolio Optimization and Performance Evaluation

This project explores the use of machine learning techniques for predicting stock returns and constructing an AI-driven portfolio. The analysis involves exploring the correlation between changes in returns and trading volumes, applying ridge regression models with various valuation matrices, and incorporating additional features such as market returns and lagged variables. Furthermore, the performance of more complex models like neural networks and decision trees is evaluated. Ultimately, an AI-driven portfolio is constructed by selecting assets with the highest predicted returns, and its performance is compared against randomly weighted portfolios, accounting for trading fees.

## Analysis Steps

1. **Correlation Analysis**: Explored the correlation between changes in returns and trading volumes to gain insights into potential relationships.

2. **Ridge Regression Model**: Implemented a ridge regression model and explored different valuation matrices to improve the model's performance.

3. **Model Enhancements**: Improved the model by including the return of the market and incorporating additional lagged variables as predictors.

4. **Complex Models**: Explored the performance of more complex machine learning models, such as neural networks and decision trees, for predicting stock returns.

5. **AI-Driven Portfolio Construction**: Constructed an AI-driven portfolio by selecting four assets with the highest predicted returns each day, based on the trained models.

6. **Performance Evaluation**: Compared the performance of the AI-driven portfolio against 1000 randomly weighted portfolios, taking into account a 3% trading fee for each transaction.

