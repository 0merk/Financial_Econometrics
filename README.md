# Financial Econometrics Projects

This repository showcases two projects focused on financial econometric modeling. These projects were completed as part of a course at Peter the Great St. Petersburg Polytechnic University.

## Project 1: Univariate Time Series Analysis - Forecasting NVIDIA Share Prices

### Objective
Forecast NVIDIA's weekly share prices using econometric modeling techniques.

### Methodology
- **Stationarity Tests:** Applied Augmented Dickey-Fuller (ADF) and KPSS tests to evaluate stationarity. Log differencing was used to transform the non-stationary series.
- **Seasonal Decomposition:** Decomposed the series into trend, seasonality, and noise using an additive model.
- **Model Selection:** Explored ARMA and ARIMA models, leveraging ACF and PACF plots for lag determination. Models were optimized based on AIC, BIC, and HQIC scores.
- **Findings:**
  - ARIMA (0,0,0) was the best-fit model, revealing that past values and residuals had no significant impact on future stock prices.
  - Suggested further analysis of external factors influencing stock price movements.

### Tools Used
- Python: `Pandas`, `Statsmodels`, `Matplotlib`

---

## Project 2: Multivariate Time Series Analysis - U.S. Macroeconomic Indicators

### Objective
Analyze and forecast the relationship between U.S. GDP Growth Rate and Unemployment Rate.

### Methodology
- **Stationarity Tests:** Conducted ADF tests to confirm stationarity after differencing.
- **Causality Analysis:** Used Granger Causality tests to establish bidirectional causality between unemployment and GDP growth.
- **Modeling Approach:**
  - Developed a Vector Autoregressive (VAR) model with lag selection based on informational criteria.
  - Conducted impulse response analysis to evaluate dynamic relationships between variables.
  - Generated 20-step forecasts for both unemployment and GDP growth.
- **Findings:**
  - Strong interdependence observed between the two variables.
  - Recommended the inclusion of additional external economic factors for enhanced forecasting accuracy.

### Tools Used
- Python: `Statsmodels`, `Matplotlib`, `Pandas`
