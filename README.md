# Stock Market Volatility and News Sentiment Analysis

This project explores whether sentiment extracted from financial news headlines can serve as a meaningful predictor of stock market volatility. Specifically, we analyze Apple Inc. (AAPL) stock data alongside daily Reddit news headlines using natural language processing and time series modeling techniques.

## Key Concepts
- Time series modeling with GARCH(1,1)
- Sentiment analysis using the Bing lexicon
- Financial volatility visualization
- News sentiment correlation with daily returns

## Data Sources
- AAPL Stock Data: [Yahoo Finance](https://finance.yahoo.com/quote/AAPL)
- News Headlines: [Reddit News on Kaggle](https://www.kaggle.com/datasets/therohk/million-headlines)

## Structure
- `data/`: Raw datasets
- `code/`: R Markdown files for sentiment scoring, modeling, and plotting
- `output/`: Final technical report

## Tools Used
- R (`tidyverse`, `tidytext`, `rugarch`, `ggplot2`)
- Natural Language Processing
- Financial Econometrics

## Highlights
- Built sentiment scores from Reddit headlines using `bing` lexicon
- Modeled volatility with GARCH(1,1) to capture market risk dynamics
- Visualized alignment between sentiment and return spikes

## Report
View the full analysis here: [`Stock-Market-Volatility-and-News-Sentiment-Analysis.pdf`](./output/Stock-Market-Volatility-and-News-Sentiment-Analysis.pdf)

---
