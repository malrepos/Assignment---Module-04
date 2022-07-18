# Assignment---Module-04

There are quite a few essential concepts raised throughout this assignment. Although there are functions that calculate these concepts, and thereby abstract away the idea and the math, it is important that these concepts are understood in order to make sense of the results.

Here are the major concepts from this assignment:

* Daily Returns
* Cumulative Returns
* Standard Deviation
* Rolling Statistics
* Correlation
* Covariance
* Variance
* Beta
* Exponentially Weighted Moving Average (ewm)
* Sharpe Ratio

I will try to define each concept and give examples of the function(s) used in Pandas.

### Daily Returns

A daily return of a stock compares the previous day's closing price with today's closing price, and turning that difference into a percentage. If this percentage is positive then the stock has grown in value, if negative the stock has declined in value. By calculating the daily returns as a percentage we can compare stocks and portfolios on an equal footing.

When using Pandas we can use the .pct_change() function on a Data Frame without having to do the calculations ourselves.

### Cumulative Returns

### Standard Deviation