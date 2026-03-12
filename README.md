# Crypto Market Sentiment vs Bitcoin Price Movement

## Project Overview
This project explores whether cryptocurrency news sentiment is associated with short-term Bitcoin price movement.

The analysis combines cryptocurrency news headlines with Bitcoin historical price data to examine how sentiment trends relate to market behavior.

## Tools Used
- Python
- Pandas
- Matplotlib
- TextBlob
- yfinance
- Jupyter Notebook

## Data Sources
- Bitcoin historical market data
- Cryptocurrency news headlines dataset (~11,000 rows)

## Methodology
1. Data cleaning and preprocessing
2. Sentiment analysis of news headlines
3. Aggregation of daily sentiment scores
4. Merging sentiment data with Bitcoin price data
5. Exploratory analysis and visualization

## Key Findings
- News sentiment was generally mildly positive during the observation period.
- Sentiment fluctuated frequently due to the fast-moving nature of cryptocurrency markets.
- Sentiment showed weak correlation with same-day Bitcoin returns.
- Positive sentiment days tended to have higher average returns compared to negative sentiment days.

## Project Structure

crypto-market-sentiment-analysis  
│  
├── crypto_sentiment_analysis.ipynb  
├── btc_sentiment_analysis.csv  
├── data  
│   └── crypto_news.csv  
