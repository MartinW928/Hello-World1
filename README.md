# Calculate Profitability and Risk of different investments using the Sharpe Ratio 
When evaluating whether to invest in assets, you must not only look at how much money you can make but also how much risk you take. The Sharpe Ratio, developed by Nobel Laureate William Sharpe about 50 years ago, did exactly this: it compares the return on investment with the return on alternative investments and compares the relative return with investment risk Associate to return. In this tutorial, you will use pandas to apply Sharpe ratios to actual financial data.

**Sharp Ratio**

Let us understand the Sharpe ratio by calculating the Sharpe ratio of the stocks of the two tech giants Facebook and Amazon. As a benchmark, we will use the S&P 500 to measure the performance of the top 500 US stocks. When we use a stock index instead of a risk-free rate, the result is called the information ratio, which is used to measure the return of active portfolio management because it can tell you how much return a portfolio manager can get at a given risk unit relative to Put your money into low-cost index funds.

Before comparing investments in Facebook or Amazon with the index of the 500 largest companies in the United States, let's visualize the data so that we can better understand what we are dealing with.
![](images/Daily Prices.png)

Let's also take a closer look at the value of the S&P 500, our benchmark.


The Sharpe ratio uses the difference in return between the two investment opportunities under consideration.
However, our data shows the historical value of each investment, not the return. To calculate revenue, we need to calculate the percentage change in value from one day to the next. We will also look at summary statistics because when we calculate the Sharpe Ratio, these will become our input.
