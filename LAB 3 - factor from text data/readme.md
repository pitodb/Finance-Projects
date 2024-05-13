# Sentiment Analysis and Media Attention in Stock Markets

This project focuses on analyzing sentiment and media attention in the stock market using natural language processing techniques and exploring their potential relationship with stock returns. The analysis involves text analysis on Twitter data related to stocks, sentiment analysis using pre-trained models like BERT and FinBERT, and investigating the correlation between media attention and excess stock returns.

## Analysis Steps

1. Performed text analysis on Twitter data related to stocks, including calculating the number of words per tweet, analyzing the distribution of the number of words per tweet, and computing the average sentiment.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/3b3c1813-a238-4489-8e46-375a8849645b)


2. Created word clouds to visualize the most frequently used words based on sentiment (positive, negative, or neutral).

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/460c6fec-2130-4053-adae-38ef8761cc69)

3. Conducted sentiment analysis on the Twitter data by tokenizing the text, padding sequences, splitting the data into training and testing sets, and utilizing pre-trained models like BERT and FinBERT.


4. Trained a recurrent neural network (RNN) and a long short-term memory (LSTM) model to predict the sentiment of tweets based on the preprocessed data.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/6f4bd108-09ca-402f-80a5-5fd2e84299f2)

5. Measured media attention by analyzing the correlation between the ratio of positive to negative tweets for each stock and its excess return.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/b31ffc57-11b3-4780-96fd-6b094c0e0f28)

## Results and Considerations

The analysis revealed that the media attention, measured by the ratio of positive to negative tweets for each stock, does not appear to be correlated with the realized annual returns of the stocks. High values of media attention were observed for both high and low annual returns, suggesting no clear relationship between the two variables.

To assess the potential significance of the media attention factor, its correlation with beta was analyzed. The results showed no correlation between the media attention factor and beta. Therefore, media attention (the ratio of positive to negative tweets for each stock) could be considered a plausible candidate for a relevant factor.

However, further investigation revealed no correlation between the media attention factor and alpha (excess return). This lack of correlation implies that the media attention factor is unable to predict future stock returns effectively, rendering it less useful as a significant factor in this context.

Additionally, it is important to note that in this analysis, there were few significant values for alpha (excess return), as the majority of the corresponding p-values were high. This means that the null hypothesis of alpha being equal to zero could not be rejected. Even if a correlation between the media attention factor and alpha were found, caution should be exercised regarding the goodness of the factor due to the lack of significant alpha values.

Overall, while the sentiment analysis and media attention measurement provide interesting insights, the lack of correlation with excess returns and the limited significance of alpha values suggest that the media attention factor may not be a reliable predictor of future stock returns in this specific analysis.

![image](https://github.com/pitodb/Finance-Projects/assets/112696408/9f567523-1084-4c09-b90f-4ad0a3b997eb)
