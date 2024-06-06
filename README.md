# The Impact of News Headlines on Stock Prices: A Sentiment Analysis Project

## Project Objective

This project aims to examine the relationship between stock prices of certain companies listed on Borsa Istanbul and the sentiment analysis of news headlines related to these companies. The main goal of the project is to observe how positive and negative news affect stock prices.

## Limitations

- This project was conducted with limited data, a small number of companies, and within a limited time frame.
- To obtain a conclusive result, similar analyses need to be conducted with a larger dataset, more companies, and over longer periods.
- News headlines alone are not definitive in predicting stock prices; they can be a valuable parameter when used in conjunction with other factors.

## Techniques and Steps Used

### 1. Data Collection

The datasets used in the project include:
- **News Headlines**: News headlines related to the companies and their dates.
- **Stock Prices**: Daily closing prices of the companies over a specific time period.

News headlines were collected from TradingView, and stock prices were collected from Yahoo Finance.

### 2. Data Preprocessing

The data preprocessing steps included:
- **Conversion to Datetime Format**: Converting the dates of the news headlines and stock prices to datetime format.
- **Timezone Adjustment**: Adjusting for timezone differences.

### 3. Sentiment Analysis

Sentiment analysis of the news headlines was conducted using Hugging Face's "distilbert-base-uncased-finetuned-sst-2-english" model. Each news headline was analyzed and classified as positive, negative, or neutral.

### 4. Impact Analysis

To analyze the impact of positive and negative news on stock prices, the following steps were followed:
- Comparing the stock prices one day before and one day after the news headline date.
- Calculating the price change and classifying it as positive or negative.
- Calculating the positive impact rate of positive sentiment and the negative impact rate of negative sentiment.

### 5. Visualization of Results

Bar charts were created to show the effects of positive and negative news headlines on stock prices. These charts indicated that positive news did not show the expected positive impact on stock prices, while negative news had a significant negative impact on stock prices.

## Results

### Impact of Negative News
- Negative news headlines were observed to have a negative impact on stock prices.
- The negative impact rate of negative sentiment was calculated to be 100%.

### Impact of Positive News
- Positive news headlines did not have the expected positive impact on stock prices.
- The positive impact rate of positive sentiment was calculated to be 0%.

### Comments and Evaluation
- Negative news was observed to negatively affect stock prices as expected.
- Positive news did not create the expected positive impact on stock prices, possibly due to other factors overshadowing this effect or the market not reacting to positive news.

## Conclusion and Recommendations

This project is an analysis conducted with a limited dataset and a small number of companies. Similar analyses need to be conducted with a larger dataset and more companies. News headlines may not be definitive in predicting stock prices alone; however, they can be valuable when used with other parameters.

### Recommendations for Future Work

- **More Data and Companies**: Conduct analyses with a larger dataset and more companies.
- **Detailed Sentiment Analysis**: Improve sentiment analysis by analyzing the tone and content of the news in more detail.
- **Economic and Market Data**: Include other macroeconomic factors and market data for a more comprehensive analysis.
- **Time Series Models**: Use time series analyses (ARIMA, LSTM) for deeper predictions.
- **Machine Learning Models**: Use different machine learning models (Random Forest, Gradient Boosting) for analysis.

This project is an important step in examining the impact of news on stock prices and can serve as a basis for more comprehensive analyses.
