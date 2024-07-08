# Risk Based Optimization 


## Risk Based Portfolio Optimization 
### Overview

This project tests the out-of-sample performance of Markowitz Minimum Volatility, Naive Risk Parity, Risk Parity, and Maximum Diversification strategies compared to an equally weighted benchmark portfolio. The goal was to analyze the effectiveness of these strategies in reducing volatility and improving risk-adjusted returns.

### Data and Method

We selected stocks from the DAX Export, DAX Dividend and DAX ESG indices, and used five years of historical data up to December 31, 2023, to determine portfolio weights. The first semester of 2024 served as the out-of-sample testing period. We implemented the aforementioned quantitative strategies, alongside an equally weighted as benchmark, and applied covariance shrinkage to improve the estimation of the covariance matrix.

Results and Conclusion

The results demonstrated that the quantitative strategies reduced out-of-sample volatility compared to the benchmark. All strategies achieved positive Sharpe ratios in the out-of-sample period. Although covariance shrinkage had minimal impact on returns and volatility, the overall findings highlight the potential of risk-based optimization strategies in achieving better risk-adjusted performance.
