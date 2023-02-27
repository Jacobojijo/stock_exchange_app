# stock_exchange_app

An implementation of a a web app via which you can manage portfolios of stocks. Users can register a personal account
Not only will this tool allow the user to check real time stocks’ actual prices and portfolios’ values, it will also let the user buy and sell stocks by querying IEX(https://iexcloud.io/) for stocks’ prices.

This is implemented as follows

#REGISTRATION
the implementation of registeration in such a way that it allows a user to register for an account via a form.

Require that a user input a username, render an apology if the user’s input is blank or the username already exists.
Require that a user input a password and confirm the same, render an apology if either input is blank or the passwords do not match.

#QUOTE TAB
This allows the user to check in Real time the price of shares of a particular company before buying or selling

#BUY TAB
Requires that a user input a stock’s symbol, render an apology if the input is blank or the symbol does not exist
Require that a user input a number of shares, render an apology if the input is not a positive integer.
Upon completion, the user is redirected to the home page.

#SELL TAB
Requires that a user input a stock’s symbol, render an apology if the user fails to select a stock or if (somehow, once submitted) the user does not own any shares of that stock.
Require that a user input a number of shares, render an apology if the input is not a positive integer or if the user does not own that many shares of the stock.
Upon completion, the user is redirected to the home page.

#HISTORY TAB
Displays an HTML table summarizing all of a user’s transactions ever

#HOME 
Displays an HTML table summarizing, for the user currently logged in, which stocks the user owns, the numbers of shares owned, the current price of each stock, and the total value of each holding. Also display the user’s current cash balance along with a grand total (i.e., stocks’ total value plus cash). 

