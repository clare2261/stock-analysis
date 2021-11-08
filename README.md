# Stock Analysis

## Overview of Project
To use VBA to quickly analyze stocks to check for volume traded and returns per year in an attempt to help Steve give investment advice.

### Results of the Stock Data
The data set included 12 stocks with pricing for trading days.  The outcome was to record the trading volume and return per year of each stock.  This data was intially processed with code that looped through the data several times to collect all the data.  To speed up the process and write more efficient code, the methodology was changed to record the data in an array so that it would only have to run through the data one time.  This was then run for the 2017 data and the 2018 data.  Screen shots are included below of the results.
![image](https://user-images.githubusercontent.com/92898919/140670833-e806ba20-037c-4402-a2af-98dc80ae0c44.png)
https://github.com/clare2261/stock-analysis/blob/main/VBA_Challenge_2017.png?raw=true

![image](https://user-images.githubusercontent.com/92898919/140670866-c78ce96a-8d23-43b9-a9e5-0f024cc705b8.png)
https://github.com/clare2261/stock-analysis/blob/main/VBA_Challenge_2018.png?raw=true

### Summary
In general, the process of refactoring the code is considered to be in-line with best practices.  By reconsidering the code and continuing to think about it, it leaves the possiblity for more eficient code.  But this iterative process can be deconstructive if taken to exhaustion and continuing to focus resources on code that already works.  In this specific example a large pro of refactoring the code was in the efficeincy gain of the new code.  By looping through the dataset only once instead of looping for the number of stocks that were to be analyzed it saved much time.  These benefits would only increase in payoff with the more stocks and more data for each analysis.  There was lost time in refactoring as the orignal code could of processed and displayed the same output though.

