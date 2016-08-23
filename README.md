# StockWatcher

## Objective 
The objective of StockWatcher is to watch Canada's stock index via INDEXTSI:OSPTX.
Using Google or Yahoo Finance, StockWatcher will store the stock open and close values
of INDEXTSI:OSPTX. Using these values, StockWatcher will predict whether or not a
market crash may or may not happen.

There are two patterns that StockWatcher can watch for:

* 2008 crash
* 2000 crash

More search needs to be done for these crashes.

## To do List (In order of execution)

* Write out the exact patterns for 2008 and 2000 crash
    * Sept 19, 2008 - 12 912.99
    * Sept 26, 2008 - 12 126.00 (-6.09%)
    * Oct  03, 2008 - 10 803.35 (-10.91%)
    * Oct  10, 2008 - 9 065.16  (-16.01%)
    * Need to grab averages now for open and close, fastest way is to start tracking them now!
* Figure out if there are more crashes (use US Index?)
    * NYSE recession was similar to TSX
* Figure out how to use Google or Yahoo's API
    * http://finance.google.com/finance/info?client=ig&q=INDEXTSI:OSPTX
* Design the API reader
* Figure out how to store the data (local database?)
* Track daily data to analyze with the above notes
* Design the algorithmn
* Test!
* Figure out whether to use schedule task or service to make this constantly run at the right times


## Do if bored

* Figure out threshold on API requests
