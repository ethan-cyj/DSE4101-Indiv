# DSE4101 Individual Project: Bitcoin Volatility Forecasting

## Overview

This project investigates the application of Markov Regime-Switching (MRS) models combined with Heterogeneous AutoRegressive (HAR) and Random Forest (RF) approaches to forecast Bitcoin volatility. The research aims to compare single-regime and two-regime models to determine which provides superior predictive accuracy and practical value in risk management and trading strategies.

## Project Goals

* Evaluate the effectiveness of regime-switching models in forecasting Bitcoin volatility.
* Compare HAR and Random Forest models under single and multi-regime conditions.
* Identify key predictive features influencing Bitcoin volatility across different market regimes.

## Author

* **Ethan Cheung Yu Jeng** ([ethan-cyj](https://github.com/ethan-cyj))

## Repository Structure

* `report.pdf`: [View Project Report](https://github.com/ethan-cyj/DSE4101-Indiv/blob/main/DSE4101%20Indiv%20Report.pdf)
* Project presentation materials (if available) will be included.

## Key Findings

* The two-regime HAR model significantly outperforms single-regime HAR and Random Forest models, especially during high volatility periods.
* Regime-specific modeling effectively adapts feature importance dynamically, enhancing predictive performance and interpretability.
* Feature analysis highlights daily volatility, trading volume, and market sentiment as critical predictors in high volatility regimes, while long-term indicators such as monthly volatility and macroeconomic data dominate in calmer periods.

## Implications

* **Risk Management:** Enhanced forecasting accuracy can significantly improve financial risk metrics like Value-at-Risk and Expected Shortfall.
* **Trading Strategies:** The developed models offer better-informed market entry and exit strategies, particularly beneficial during high volatility conditions.
* **Academic Contributions:** Advances volatility forecasting literature by demonstrating the efficacy of regime-switching models in cryptocurrency markets.

## References

All detailed citations, methodological discussions, and statistical analyses are available in the [Project Report](https://github.com/ethan-cyj/DSE4101-Indiv/blob/main/DSE4101%20Indiv%20Report.pdf).

---

**This project was conducted as part of the DSE4101 Capstone in Data Science and Economics course at the National University of Singapore.**
