---
title: "💰: A Financial Investigation into Stocks Portfolio Optimization"
excerpt: "The project explores using machine-learning techniques—specifically Nested Cluster Optimization (NCO)—to build stock portfolios more effectively than the classic Mean-Variance Optimization (MVO) approach."
collection: portfolio
mydate: 2025-07-07
---
Date: Jan 2025 - April 2025

The project is about how machine learning, specifically the Nested Clustered Optimization (NCO) method, can improve stock portfolio optimization compared to the traditional Markowitz Mean-Variance Optimization (MVO).

1. Formulated research questions to explore when higher-risk investments are preferable, what factors define a “good” investment, and how clustering helps diversification.

2. Collected market data using Yahoo Finance and conducted exploratory data analysis (EDA) to understand asset behaviors.

3. Implemented the NCO algorithm step by step, including denoising covariance matrices, converting to correlation matrices, clustering with the ONC algorithm, and computing intra- and inter-cluster weights for optimal allocation.

4. Benchmarked NCO against MVO by constructing minimum variance and maximum Sharpe ratio portfolios using both methods, running simulated experiments under different market conditions (normal, high correlation, high volatility, negative returns) with multiple repetitions to assess performance robustness.

5. Evaluated results, finding that NCO generally produced higher Sharpe ratios and lower RMSEs in challenging or high-dimensional situations, indicating better real-world stability.

6. Developed a user-friendly website to let investors input their chosen stocks and risk preferences to receive optimized portfolio recommendations using NCO.
   
[Link to the Project](https://github.com/qingruili/PORTFOLIO-OPTIMIZATION)
