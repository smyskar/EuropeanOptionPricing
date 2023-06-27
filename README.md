# EuropeanOptionPricing

## Application of Principal Component Analysis (PCA) in European Option Pricing

This project is an exploration into the pricing of a European basket option. The payoff of this option is max(avg(s1,s2,..,s10),0).

To model the behaviour of these stock prices and their correlations, I applied methodologies such as Cholesky decomposition and Geometric Brownian motion. A computation of the 95% Value at Risk (VaR) is also carried out.

Further, I utilized Principal Component Analysis (PCA) to reduce the dimensionality of the correlation matrix of stock prices. After applying PCA, both the option price and the VaR are recalculated to reflect this dimensional reduction.

In a separate strategy, I manually divided the stocks into three distinct categories through visual analysis. This approach offers an alternative view of the data, demonstrating the flexibility of the financial modeling techniques used in this project.
