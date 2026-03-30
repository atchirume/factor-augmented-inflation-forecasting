# Factor-Augmented Inflation Forecasting Framework

A central bank–grade inflation nowcasting and forecasting system developed by **Chirume Admire Tarisirayi**.

This framework integrates advanced econometric modelling, machine learning, and macroeconomic factor analysis to produce robust, policy-relevant inflation forecasts for Zimbabwe and comparable economies.

## Key Features

- **PCA-Based Factor Extraction**  
  Dimensionality reduction of macroeconomic indicators into interpretable economic factors.

- **Multi-Model Forecasting Engine**  
  Combines Elastic Net, Random Forest, Support Vector Regression (SVR), and XGBoost for enhanced predictive accuracy.

- **Inflation Nowcasting**  
  Incorporates high-frequency indicators to estimate current-period inflation dynamics.

- **Scenario Analysis Engine**  
  Simulates policy and external shocks (exchange rate, liquidity, fiscal impulse) and evaluates their impact on inflation.

- **Regime Classification Framework**  
  Classifies inflation into regimes aligned with SADC macroeconomic convergence targets.

- **Interactive Dashboard (Streamlit)**  
  Real-time visualisation of forecasts, factor contributions, and risk scenarios.

## Live Application

https://factor-augmented-inflation-nowcasting-and-forecasting.streamlit.app/

## Methodological Framework

The system is based on a **Factor-Augmented Model**, where inflation is driven by latent macroeconomic factors derived from observable indicators:

\[
\pi_t = \alpha + \beta F_t + \varepsilon_t
\]

Where:
- \( \pi_t \): Inflation  
- \( F_t \): Extracted macroeconomic factors (via PCA)  
- \( \beta \): Factor loadings  
- \( \varepsilon_t \): Error term  

## Applications

- Central banks and monetary authorities  
- National statistical agencies  
- Economic research institutions  
- Financial sector risk and policy analysis  

## Author

**Admire Tarisirayi Chirume**  
Director of Macroeconomic Statistics  
Economist | Data Scientist | Data Engineer| Developer  

## Keywords

Inflation Forecasting • Nowcasting • Econometrics • Machine Learning • PCA • Central Banking • Macroeconomic Modelling • Zimbabwe • SADC
