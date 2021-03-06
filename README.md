# stocks-analysis

## Overview of Project

The purpose of this analysis is to develop a program to help Steve analyze vast amounts of stock data as quickly and efficiently as possible. Specifically we created a program to pull specific information from 12 stocks yearly data in 2017 and 2018.

## Results 

We found that 11 of the 12 stocks saw their value increase in 2017 compared to 2 stocks in 2018. More specifically, ENPH saw an increase of 129.52% and 81.92% in 2017 and 2018 respectively with a total return of 417.55% in two years. While I wouldn't recommend using past performance to determine future performance of a stock. But it could be one of many indicators Steve uses to determine which stocks to invest in the future.

The original script would perform the analysis in 1.73 seconds and 1.43 seconds for 2017 and 2018 respectively. While the refactored script would perform the analysis in 0.24 seconds and 0.32 seconds for 2017 and 2018 respectively. 

![2017 Stock Analysis](Resources/VBA_Challenge_2017.png)

![2018 Stock Analysis](Resources/VBA_Challenge_2018.png)

## Summary

### 1. What are the advantages or disadvantages of refactoring code?

Clearly the refactored script is significantly faster, anywhere from 4 to 7 times faster. So when running this program to examine stocks over more years and thousands of more stocks it can make a significant difference in the time of analysis. Using the refactored data would save Steve a lot of time. The only disadvantage I can see is that the script is a bit more complicated to write than the original script. So it can take a little bit more time to write the initial script.

### 2. How do these pros and cons apply to refactoring the original VBA script?

For a small data set like the one for 2017 and 2018, it would be more efficient use of time to use the original VBA script. Spending a significant amount of time to save a few seconds in an analysis isn't an efficient use of time. Unfortunately if we wanted to use it for future data sets that are larger we would then have to make the necessary refactoring changes.
