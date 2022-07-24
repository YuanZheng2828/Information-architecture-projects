# IA-final

In recent years, day trading has become increasingly popular with people watching the markets in their free time, whether this is people trying to make a little bit of money on the side of whatever their regular job is or students trying to make some money to cover expenses. With the rise of different platforms like Robinhood for the stock market and Coinbase for cryptocurrency, investing has become more popular and accessible than ever. 

As popular as day trading is, the average trader doesn’t have access to the resources and investment tools that large hedge funds and banks have access to. The purpose of this application is to give the average person access to some of that information that can help them in their mission to grow their investments. 

There are three components being offered to the user that they may not have had access to before through other platforms. 

-  First, is a basic analysis of daily movements of the prices of select stocks including the opening price, closing price, daily high, daily low, and volume traded per day. This data is being taken directly from alphavantage.co, a website dedicated to providing data on stocks, through a live API.
-  The second component is a machine learning algorithm to try and predict this information. The data that the algorithm is being based off of also comes through alphavantage.co via another API so that there is consistency in the metrics being provided. 
-  The component, which perhaps is the most unique tool to the average day trader, is a sentiment analysis of selecting stocks so that predictions could be made off of the trends of a company’s sentiment score going forward. This is also accomplished using a live API through finviz.com, a leading stock screening website. All of this information will be able to help day trader’s maximize their investments without having to go through large financial institutions that they may not be able to afford.
