# Robinhood-Watchlist-Stock-History
Download stock quote history from AlphaVantage for all the symbols in your Robinhood Default Watchlist to csv files. There is one file per symbol.

Open dl_quotes.py

Update: 
1. Your free AlphaVantage API key
2. Your Robinhood email
3. Your Robinhood password
4. Your path to where to place the csv files.

# When symbols fail
If symbols fail, you can re-run the code and download only the list of failed symbols. The list is provided by the code. You'll have to copy/paste the list, and comment/uncomment several lines. Detailed instructions are in the code.

# Example of the csv file (ALLY)
date,1. open,2. high,3. low,4. close,5. volume 
2020-01-31,32.2,32.325,31.85,32.03,3968506.0 
2020-01-30,31.74,32.495,31.69,32.45,4338968.0 

