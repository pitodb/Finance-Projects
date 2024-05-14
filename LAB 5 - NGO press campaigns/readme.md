# Investigating the Impact of NGO Press Campaigns on Stock Market Returns

This project aims to analyze the potential influence of NGO (Non-Governmental Organization) press campaigns on stock market returns, with a particular focus on the banking sector. By leveraging data from Sigwatch, which includes materials from thousands of NGOs matched with stock market data, the analysis explores whether NGO campaigns have a measurable impact on the performance of targeted companies.

## Analysis Steps

1. **Data Acquisition**: Obtained data from Sigwatch, which included materials from thousands of NGOs and their respective press campaigns, matched with stock market data for banks.

2. **CAPM Parameter Estimation**: Estimated rolling Capital Asset Pricing Model (CAPM) parameters over a rolling window using market returns per country and three additional factors.


3. **Cumulative Abnormal Returns (CARs) Calculation**: Computed Cumulative Abnormal Returns (CARs) around every event date, which represents the date when an NGO published news or conducted a press campaign targeting a specific bank.



4. **Statistical Testing**: Performed statistical tests to determine whether NGO campaigns had a significant impact on the targeted banks' stock returns.

## Key Findings and Conclusions

1. **Initial Overreaction**: On the event date, there was an initial overreaction or the presence of other market factors playing a role. However, within the analyzed time window, the actual returns performed below the expected level, suggesting a longer-term response.



2. **Post-Event CAR Behavior**: After the event, there was an immediate spike in CAR, reaching a peak around 5 days post-event.

<img width="543" alt="Screenshot 2024-05-13 at 21 25 13" src="https://github.com/pitodb/Finance-Projects/assets/112696408/8edb9a41-1ea0-4b54-8a76-a06c0a70ffee">

3. **Sentiment and CAR Relationship**: An ANOVA test revealed that the relationship between the sentiment of the NGO campaign and the corresponding CAR is not straightforward. Very positive news did not necessarily lead to positive stock returns.

<img width="396" alt="image" src="https://github.com/pitodb/Finance-Projects/assets/112696408/0844640a-2dfb-4e43-9bbf-32a377ffb58d">

4. **Negative News Impact**: Negative news, especially with high prominence, generally had a negative relationship with the targeted banks' CARs. However, some stocks reacted positively to negative news campaigns.
<img width="392" alt="image" src="https://github.com/pitodb/Finance-Projects/assets/112696408/8791cdf0-0a43-44dc-93de-3f2b1acc7d1b">

5. **Positive News Impact**: Positive news campaigns exhibited an inverse relationship with CARs, which is counterintuitive but in line with Krueger's 2015 research paper.

<img width="392" alt="image" src="https://github.com/pitodb/Finance-Projects/assets/112696408/fadf355f-52ba-4d0e-a489-7a406a03d5bd">

The findings of this project suggest that NGO press campaigns can have a measurable impact on stock market returns, particularly in the banking sector. While the relationship between campaign sentiment and stock performance is not straightforward, negative news campaigns with high prominence tend to have a negative effect on targeted banks' CARs. Interestingly, positive news campaigns exhibited an inverse relationship with CARs, potentially due to market expectations or other underlying factors.

<img width="262" alt="image" src="https://github.com/pitodb/Finance-Projects/assets/112696408/a59a7560-057f-4e5a-8adb-590b061ac8ba">


These insights contribute to our understanding of how non-financial factors, such as NGO campaigns, can influence stock market performance and highlight the importance of considering these external factors in investment decision-making processes.
