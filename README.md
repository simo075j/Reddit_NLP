# Understanding Reddit investing communities('Wallstreetbets', 'stocks, 'investing' etc.) with webscraping, yfinance and NLP.
The power of social media has recently drawn alot of attention in the media and investment world. Some of the most popular finance/investment subreddits such as 'wallstreetbets', 'stocks', 'investing' and 'stockmarket' accumulate upwards of 15 million users. Understanding what's going on in this world is almost impossible as an outside investor, BUT with some automation every outsider has a chance.


This program scrapes and analyses any investing/stock related subreddits, to gain a basic understanding on whats being discussed, the general sentiment and overall financial metrics of mentioned stocks.
The application uses Vader SentimentIntensityAnalyzer to calculate ticker compound values with the incorporation of custom reddit "slang" words related to stocks and investing.
The script furthermore takes a deeper dive into some of the most mentioned stocks using the Yahoo finance API 'yfinance'. This includes:
* Visualizations of closing prices over various timeperiods
* Most recent recommendations from top institutions (Goldman sachs, Morgan Stanley, etc.)
* An insight into the top institutional shareholders
* Company descriptions, industry of operation, moving averages, short ratios, market capitalization and much more.


**Example output**

![](reddit_treemap.png)

![](Reddit_sentiment.png)

![](ticker_prices.png)
