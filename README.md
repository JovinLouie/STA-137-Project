# Predicting Breast Cancer Subtypes Using Gene Expression Profiles - STA 141C Final Project

By Jovin Louie, Jenny Xu, Keai Zhang, Peter Xie\
Professor Xiucai Ding\
STA 137: Applied Time Series Analysis\
Spring Quarter 2025 - UC Davis

---

We conducted a full time series analysis of annual GDP and Imports data using the ARIMA framework.
The project began with exploratory visualization and log-transformation to stabilize variance. We
evaluated stationarity using ACF/PACF plots and the Augmented Dickey-Fuller test. For each series,
multiple ARIMA models were fit and compared based on information criteria and diagnostic plots.
Forecasts were generated for the next four years, with 95% confidence intervals. The GDP series was
best modeled using an ARIMA(2,1,0), while Imports was fit with ARIMA(0,1,1). All analysis was
performed in R with clear justification and interpretation of modeling choices.

## Abstract

Abstract This project analyzes and forecasts the GDP and Imports time series of the Central African
Republic from 1960 to 2017. After visual inspection and log transformation to address
non-stationarity, we applied ARIMA modeling to each series. We assessed model fit through AIC, BIC,
residual diagnostics, and compared forecast performance. The final selected ARIMA models provide
insight into the economic trends and enable informed predictions for future GDP and Imports.

## References

- Mercereau, B. (2004). Political Instability and Growth: The Central African Republic.
  https://papers.ssrn.com/sol3/papers.cfm?abstract_id=878903
- World Bank Group. (2023a). GDP (current US$)—Central African Republic. World Bank Group.
  https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=CF
- World Bank Group. (2023b). Imports of goods and services (% of GDP)—Central African Republic.
  World Bank Group. https://data.worldbank.org/indicator/NE.IMP.GNFS.ZS?locations=CF
- World Trade Organization. (2013). Annex 4 Central African Republic (No. WT/TPR/S/285). World Trade
  Organization. https://www.wto.org/english/tratop_e/tpr_e/s285-03_e.pdf
