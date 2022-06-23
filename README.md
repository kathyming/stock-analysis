# stock-analysis

## Overview
The purpose of this analysis was to look at volume and returns for stocks during different years given daily stock prices and volumes.

## Results
By running the script for 2017 and 2018 it was obvious that 2017 was a much better year for the stock market.  Of the 12 stocks analyzed, only one had a negative return for the year.  2018, however, only had two stocks which had a positive year.

After writing the original code, the time to run the analysis was about 7 seconds.  Refactoring the code greatly decreased the time - to less than a second!

## Summary
The advantages of refactoring the code are definitely the time saving for the time for the code to run.  Obviously, this is a very small example and an easy analysis, but if a system was computing large amounts of data the efficiency of the code would be very desireable.  The disadvantages of refactoring the code is I ended up breaking the code for a time.  So, I went form working code  to debugging.  So, the old addage of "it ain't broke, don't fix it" definitely applied.  

The advantages of refactoring the VBA script in particular was that it would be more easily expanded if more stocks were added to the spreadsheet.  By using an index and not hard coding the numbers, the code is more flexible.  
