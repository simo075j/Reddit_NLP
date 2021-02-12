# Reddit investing communities(Wallstreetbets) analyisis with webscraping, yfinance and NLP
With all the talk in the media about the impact of wallstreetbets, i thought it would be fun to get an insight into what is actually going on in this massive community.
My interest for doing this project really caught on fire after my silver stocks skyrocketed due to interest from reddit forums such as wallstreet bets.

The program can be used to scrape and analyse any investing/stock related subreddits, to gain a basic understanding on whats being discussed in a live feed. (i.e /wallstreetbets, /investing, /stocks)
The program uses Vader SentimentIntensityAnalyzer to calculate ticker compound values with the incorporation of custom reddit "slang" words related to stocks and investing.
The script furthermore takes the most discussed tickers and look up their current price using the yfinance API.

for ref https://www.youtube.com/watch?v=CJAdCLZaISw&ab_channel=PartTimeLarry

**Example output**

![](reddit_treemap.png)

![](Reddit_sentiment.png)

![](ticker_prices.png)


*With reference to Github user asad70*
