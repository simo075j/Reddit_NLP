# Wallstreetbets analyisis with webscraping, NLP and SQL
With all the talk in the media about the impact of wallstreetbets, i thought it would be fun to get an insight into what is actually going on in this massive community.
My interest for doing this project really caught on fire after my silver stocks skyrocketed due to interest from reddit forums such as wallstreet bets.

The program uses Vader SentimentIntensityAnalyzer to calculate ticker compound values with the incorporation of custom reddit "slang" words related to stocks and investing.
The program can be used to scrape and analyse any investing/stock related subreddits, to gain a basic understanding on whats being discussed in a live feed.
The script furthermore takes the most discussed tickers and looks up their price using the yfinance API.

for ref https://www.youtube.com/watch?v=CJAdCLZaISw&ab_channel=PartTimeLarry

Use a stock tick list to compare output
![](reddit_treemap.png)

![](Reddit_sentiment.png)

![](ticker_prices.png)

Using pushift to get an understanding on what is being talked about in terms of stock tickers on the forum daily
Get a hold of a NYSE + NASDAQ stock ticker api or downloadable file
