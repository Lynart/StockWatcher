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
* Figure out if there are more crashes (use US Index?)
* Figure out how to use Google or Yahoo's API
* Design the API reader
* Figure out how to store the data (local database?)
* Design the algorithmn
* Test!
* Figure out whether to use schedule task or service to make this constantly run at the right times


## Do if bored

* Figure out threshold on API requests