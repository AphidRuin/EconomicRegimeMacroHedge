Task : Begin by defining economic regimes based on inflation or growth trends. Try to find the optimal hedge for the S&P 500 depending on which economic regime you are in. The hedges will be a mix of gold and US treasuries. 

Result: Portfolio optimisation in two ways:

Hedged portfolio by minimising portfolio volatility vs. S&P 500
![image](https://github.com/user-attachments/assets/a3458c6d-46de-46a3-bdba-aeb9343e762a)

Performance Metrics: {'Sortino Ratio': -0.489, 'Maximum Drawdown': 0.254}


Hedged portfolio by minimising maximum drawdown vs. S&P 500
![image](https://github.com/user-attachments/assets/39e448ca-fd11-443a-9d75-1eac416beb94)

Performance Metrics: {'Sortino Ratio': -1.185, 'Maximum Drawdown': 0.177}

Caveat: 
- Train-test split not performed, hence results are overfitted.
- Could use rate of change of GDP & CPI instead of the indices themselves.
- Economic regimes are defined arbitarily (GDP = 2.0, CPI = 2.0) when mean/median could be used.
- Maximum drawdown are calculated every three months, hence might not be accurate when encountering black-swan events.
