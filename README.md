# wolf.algo.bollinger
Bollinger Band reversion back test.  Reversion strategy is then measured against a simple buy and hold strategy and outputs performance metrics off a pyfolio 
tearsheet. 

The idea came from https://tinyurl.com/4a5fvavb.  Karthik Ram designed a strategy using different syntax and methods for setting lookback, which then 
generate different columns in pandas dataframe.  This was a unique puzzle to solve as I had to find a format and syntax to acquire the data differently. 

YFinance is a fun and flexible data source and module which allows easy compatability with other Broker API and Backtesters.  You can use simple Pandas based or matplotlib based scripts to design functions for triggering signals.  

Going forward, I will change graph output and performance charts to plotly while also figuring out how to print all output to a dashboard, either in excel or a web template hosted on css html online (cloud) template!



Modules used:

    yfinance
    pandas
    numpy
    matplotlib
    pyfolio
    os
    datetime 
    
![readmepic2](https://user-images.githubusercontent.com/29739578/211128735-9f4e59e3-ebba-43cc-991f-524dece0ca12.PNG)

#
#
#
![readmepic](https://user-images.githubusercontent.com/29739578/211128738-7103c036-0b34-4d04-a31c-44a07ab30a25.PNG)
