# Impact of News Headlines on Stock Prices: A Sentiment Analysis Project

## Project Objective

This project aims to examine the relationship between the stock prices of certain companies listed on Borsa Istanbul and the sentiment analysis of news headlines published about these companies. The main goal of the project is to observe how positive and negative news affect stock prices.

## Limitations

- This project was conducted with limited data, a small number of companies, and within a restricted time frame.
- To obtain conclusive results, similar analyses need to be conducted with a larger dataset, more companies, and over longer periods.
- News headlines alone are not a definitive predictor of stock prices; they can be more valuable when used alongside other parameters.

## Techniques and Steps Used

### 1. Data Collection

The datasets used in the project are as follows:
- **News Headlines**: News headlines about the companies and their publication dates.
- **Stock Prices**: Daily closing prices of the companies over a specified period.

News headlines were collected from TradingView, while stock prices were sourced from Yahoo Finance.

### 2. Data Preprocessing

Data preprocessing steps included:
- **Conversion to Datetime Format**: Converting the dates of news headlines and stock prices to datetime format.
- **Timezone Adjustment**: Removing timezone discrepancies from the dates.

### 3. Sentiment Analysis

Sentiment analysis of news headlines was conducted using Hugging Face's "distilbert-base-uncased-finetuned-sst-2-english" model. Each news headline was classified as positive, negative, or neutral based on the sentiment analysis results.

### 4. Impact Analysis

To analyze the impact of positive and negative news on stock prices, the following steps were taken:
- Comparing the stock prices one day before and one day after the news headline date.
- Calculating the price change and classifying it as positive or negative.
- Calculating the positive impact rate of positive sentiment and the negative impact rate of negative sentiment.

### 5. Visualization of Results

Bar charts were created to show the impact of positive and negative news headlines on stock prices. These charts demonstrated that positive news did not have the expected positive impact on stock prices, while negative news had a significant negative impact.

## Results

### Impact of Negative News
- Negative news headlines were observed to have a negative impact on stock prices.
- The negative impact rate of negative sentiment was calculated as 100%.

### Impact of Positive News
- Positive news headlines did not have the expected positive impact on stock prices.
- The positive impact rate of positive sentiment was calculated as 0%.

### Comments and Evaluation
- Negative news was observed to negatively affect stock prices as expected.
- Positive news did not create the expected positive impact on stock prices, possibly due to other overshadowing factors or the market not reacting to the positive news.
- During the relevant time period, it was observed that negative news for the studied companies, especially during downtrend periods of the company prices, produced effective results.

## Conclusion and Recommendations

This project provides an analysis based on a limited dataset and a small number of companies. Similar analyses need to be conducted with a larger dataset and more companies. News headlines alone may not be a definitive predictor of stock prices, but they can be a valuable parameter when combined with other factors.

### Recommendations for Future Work

- **More Data and Companies**: Analyses can be conducted with a larger dataset and more companies.
- **Detailed Sentiment Analysis**: The tone and content of the news can be analyzed in more detail to improve sentiment analysis.
- **Economic and Market Data**: Including other macroeconomic factors and market data can lead to more comprehensive analyses.
- **Time Series Models**: Deeper forecasts can be made using time series analyses (ARIMA, LSTM).
- **Machine Learning Models**: Different machine learning models (Random Forest, Gradient Boosting) can be used for analysis.

This project serves as an important step in examining the impact of news on stock prices and can provide a foundation for more comprehensive analyses.
