Task : Begin by defining economic regimes based on inflation or growth trends. Try to find the optimal hedge for the S&P 500 depending on which economic regime you are in. The hedges will be a mix of gold and US treasuries. 

Result: Portfolio optimisation in two ways:

Hedged portfolio by minimising portfolio volatility vs. S&P 500
![image](https://github.com/user-attachments/assets/a3458c6d-46de-46a3-bdba-aeb9343e762a)

Performance Metrics: {'Sortino Ratio': -0.489, 'Maximum Drawdown': 0.254}


Hedged portfolio by minimising maximum drawdown vs. S&P 500
![image](https://github.com/user-attachments/assets/39e448ca-fd11-443a-9d75-1eac416beb94)

Performance Metrics: {'Sortino Ratio': -1.185, 'Maximum Drawdown': 0.177}

Caveat: I forgot to adjust Gold and US 10Y Bond prices according to US Spot Rate Index data. Might obtain more accurate results upon discounting.
