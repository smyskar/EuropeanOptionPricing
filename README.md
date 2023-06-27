# EuropeanOptionPricing

Pricing of European basket options through Principal Component Analysis (PCA)

In this project, we focus on the task of pricing a European basket option, which comes with a payoff defined as max(avg(s1, s2, ..., s10), 0). Here, each S1 through S10 represents an individual stock price. 

Techniques such as Cholesky decomposition and Geometric Brownian motion are employed for generating correlated stock prices. The 95% Value at Risk (VaR) is computed accordingly.

To streamline this process, we leverage Principal Component Analysis (PCA) to reduce the dimensionality of the correlation matrix. After the application of PCA, the option price and VaR are recalculated.
