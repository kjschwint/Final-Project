# Final Project
Web Scraping Financial Information

Final Project Summary	Kevin J. Schwint

Tools Used:

Platform:	Jupyter Notebook ver. 6.4.8

Python Packages:
requests	BeautifulSoup from bs4
pandas	Path from pathlib
numpy	TextBlob from textblob
seaborn	NaiveBayesAnalyzer from textblob.sentiments 
datetime	WordCloud from wordcloud 
yfinance	candlestick_ohlc from mplfinance.original_flavor 
matplotlib.pyplot	matplotlib.dates

Questions Asked:

Buy, Hold or Sell based on Technical Analysis of a stock (e.g., AAPL)?
How well is the stock correlated with other stocks?
Based on price movement and trading volume, is the trend positive or negative (momentum indicator)?
Based on the Candlestick Patterns of the stock, is the trend positive or negative (technical analysis)?
Based on 20-day, 50-day and 200-day moving averages, is the trend positive or negative?
What is current Sentiment for the stock?
Is your portfolio sufficiently diversified?

Insights Discovered:

The Trend is your friend!
Stocks in the same industry are more correlated than other stocks.
Some stocks are more correlated with interest rates/other stocks than others.
Charts still need human interpretation. (Perhaps ChatGPT can interpret better.)

Recommendations:

Technical Analysis be an effective way of selecting stocks, and deciding when to buy and when to sell.
Technical Analysis can identify trends, confirm breakouts, and spot reversals.
Technical Analysis should be used to supplement Fundamental Analysis.

Future Work:

Incorporate variable time offsets to maximize correlation between stocks (leading/lagging indicators).
Automate the process so that the program will automatically screen many stocks and determine maximum correlation at the optimum lead time.
Incorporate other economic parameters (e.g., interest rates, GNP/GDP, trade balances, unemployment rate, inflation rate, etc.) into model.  
