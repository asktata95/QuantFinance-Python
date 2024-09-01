# VaR Estimation and Backtesting-Python
Quant Finance Projects 

In this repo we explore various models to estimate the Value at Risk (VaR) for a portfolio of selected stocks and backtest these models to measure their accuracy.

A good model for estimating Value at Risk (VaR) should have several key characteristics to ensure that it provides accurate, reliable, and meaningful risk assessments. These characteristics include:

1. Accuracy and Calibration: The model should accurately capture historical losses at the specified confidence level. Backtesting, where past data is used to test the model, is crucial to ensure accuracy. The model must be well-calibrated to reflect the actual risk exposures and market conditions. Regular updates and recalibrations are necessary as market conditions change.
2. Robustness: The model should perform well under different market conditions, including during periods of high volatility, crises, and in calm markets. The model should be capable of handling extreme scenarios, ensuring that it does not underestimate risk during market turmoil.
3. Simplicity and Interpretability: A good VaR model should be simple enough for stakeholders to understand its outputs and underlying assumptions, yet sophisticated enough to capture key risk factors. The assumptions, methodology, and limitations of the model should be transparent, allowing users to understand how the results are derived.
4. Comprehensive Risk Coverage: The model should include all relevant market risk factors, such as interest rates, exchange rates, commodity prices, and equity prices, depending on the portfolio. Additionally, it should account for the correlations between different assets and how diversification affects the overall portfolio risk.
5. Scenario Analysis and Stress Testing: The model should be able to evaluate VaR under various hypothetical scenarios, providing insights into how different market conditions might impact the portfolio. It should incorporate stress testing to assess the impact of extreme but plausible market conditions.
6. Backtesting and Validation: Regular backtesting is essential to compare the model’s predictions against actual historical outcomes, ensuring the model remains accurate over time. The model should undergo rigorous validation, including out-of-sample testing, to confirm its reliability and accuracy.

These characteristics ensure that the VaR model is not only theoretically sound but also practical and effective in real-world risk management applications.

We will use the following models to estimate VaR, grouped into three main categories:
a. Parametric Models - This approach assume that the returns follow a particular underlying distribution and the VaR is calculated using various approaches: 
                        1. Standard Deviation - A basic measure of volatility
                        2. Exponetially Weighted Moving Average (EWMA) - A volatility model that gives higher weights to recent observations
                        3. GARCH Models - GARCH with Normal Distribution (no leverage), GARCH with Generalized Error Distribution (GED and no leverage), GJR-GARCH with Normal Distribution (leverage), GJR-GARCH
                                          with GED (leverage)
                                          
b. Historical Simulation - A non-parametric approach using historical data.

c. Monte Carlo Simulation - A simulation-based approach for VaR calculation.




