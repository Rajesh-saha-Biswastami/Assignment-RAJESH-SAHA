# Quant-Research-Project
This research notebook is for understanding Nifty and Bank Nifty indices volatilities as they have
significant overlap in terms of their constituents and weights. The objective is exploit the dispersion
in their volatilites as they are likely to be affected by similar market conditions and macroeconomic
factors. Pairs trading strategies are constructed in the attempts to capture any dispersion that
may occur between the volatilities of the two indices. The analysis will be performed on minute
level historical data of implied volatilities (IVs) of Bank Nifty and Nifty from Jan 1st 2021 to Jun
30th 2022.
## Deliverables
1. Build a z-score based trading system. It would use the z-scores of the spread to identify when
volatility has diverged away from the historical mean and act accordingly. The calculation of
the P/L here constitutes the base model.
2. Build a better model than the z-score trading system. Be creative in the modelling techniques
you implement.
3. Compare your proposed model with the base model with the goal of optimizing the absolute
P/L, Sharpe Ratio, and Drawdown of your strategy.

