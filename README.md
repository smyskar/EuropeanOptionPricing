# EuropeanOptionPricing
European option pricing using Principal Component analysis (PCA)

In this project we try to price European basket option which has payoff of max(avg(s1,s2,...,s10),0). Here S1,.., S10 are the stock prices.

We generate stock price using Geometric Brownian motion. We also calculate the 95% VaR.

We then use PCA to reduce the dimension of the correlation matrix, and recalculate the option price and VaR
