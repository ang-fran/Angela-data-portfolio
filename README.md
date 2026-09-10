# Angela-Frances Ibhade — Data Portfolio

**MSc Statistics · Brock University (2026)**  
Specializing in time series econometrics, regime-switching models, and applied data analytics.  
Open to credit risk, data analytics, data scientist, and quantitative research roles.

📍 St. Catharines, ON &nbsp;|&nbsp; [GitHub](https://github.com/ang-fran) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/angela-frances-ibhade-717372192/)

---

## About

I'm a statistician and aspiring data analyst with deep expertise in time series modeling and a growing
track record applying quantitative methods to real-world problems in finance and credit risk.

My graduate research focuses on regime-switching time series models - specifically their
application to macroeconomic forecasting and mortgage delinquency prediction in Canada.
Alongside thesis work, I've built production-oriented projects in SQL, Power BI, and Python,
and developed an R package implementing a novel Markov-Switching VAR estimator.

I bring together rigorous statistical foundations, hands-on programming in R, Python, SQL,
and SAS, and the ability to communicate technical findings clearly to non-technical audiences.

---

## Featured Projects

### End-to-End Credit Risk Analytics Pipeline
**SQL · Power BI · Python · Scikit-learn · XGBoost · SHAP**

A two-part project analyzing 2.2M+ Lending Club loan records from business intelligence
through to predictive modeling and explainability.

**Part 1 — Credit Risk Scorecard Dashboard** ([Repo link](https://github.com/ang-fran/credit-risk-scorecard))  
Built a 3-layer SQL data pipeline (raw → staging → mart), engineered 6 borrower risk
features, and designed a 3-page interactive Power BI dashboard covering portfolio KPIs,
borrower risk segmentation, and vintage default curves (2007–2018).

Key findings: Grade G borrowers default at 12× the rate of Grade A; debt consolidation
accounts for 59% of loan volume; 2007 pre-crisis vintages peak at ~48% default rate for
high-risk grades.

**Part 2 — Credit Default Prediction Model** ([Repo link](https://github.com/ang-fran/credit-default-prediction))  
Extended the same dataset into a full ML pipeline — comparing Logistic Regression, Random
Forest, and XGBoost on 266K resolved loans. Applied SMOTE to handle class imbalance and
used SHAP to explain individual predictions.

Key results: XGBoost AUC 0.71, KS statistic 0.30 — meeting the industry threshold for an
acceptable credit scorecard. SHAP waterfall analysis traced one borrower's predicted
default probability from a 2.9% base rate to 81.1%, driven by Grade F, a 26.99% interest
rate, and renter status.

> SQL pipeline → Business dashboard → Predictive model → Explainability

---

### Thesis Research: Macroeconomic Drivers of Mortgage Delinquency in Canada
**R · Regime-Switching Models · Time Series Econometrics**

MSc thesis investigating the relationship between macroeconomic variables (interest rates,
unemployment, GDP) and Canadian mortgage delinquency rates. Compares stationary ARIMAX
and VAR baselines against Markov-switching alternatives to capture structural breaks and
economic regime changes. Ongoing — targeting defense in 2026.

[Repo link](https://github.com/ang-fran/thesis-research)

---

### MSM-VAR: R Package for Markov-Switching Mean-Adjusted VAR Models
**R Package Development · EM Algorithm · Multivariate Time Series**

Authored an R package implementing the Markov-Switching Mean-Adjusted VAR (MSM-VAR)
model from scratch. Features state-dependent means, autoregressive coefficients, and
covariance matrices estimated via an exact EM algorithm with Hamilton filter-smoother.
Applicable to both simulated and real macroeconomic datasets. Currently under active
development.

[Repo link](https://github.com/ang-fran/MSMAHVAR)

---

### Mixed-Lag Markov-Switching Autoregressive Models
**R · Simulation · Regime Detection**

Simulation study and empirical analysis of mixed-lag MS-AR and MS-VAR models developed
as part of thesis research. Evaluates identification, estimation accuracy, and regime
recovery under varying data-generating processes.

[Repo link](https://github.com/ang-fran/mixed-ms-ar-var)

---

### AR & ARIMA Simulation Framework
**R · Diagnostic Testing · Statistical Computing**

Structured simulation of AR(1), AR(2), and ARIMA models across varying parameter spaces,
with full diagnostic suites (ACF/PACF, residual tests, information criteria). Built as a
teaching and research reference tool during my TA appointment at Brock.

[Repo link](https://github.com/ang-fran/ar-arima-simulation)

---

### VAR & VECM Simulation
**R · Cointegration · Multivariate Modeling**

Simulation and analysis of vector autoregressive (VAR) and vector error correction (VECM)
models, covering estimation, impulse response analysis, and cointegration testing.

[Repo link](https://github.com/ang-fran/var-vec-simulation)

---

## Additional Projects

| Project | Methods | Link |
|---|---|---|
| EEG-Based Prediction of Visual Working Memory | Classification, signal processing | [Repo](https://github.com/ang-fran/EEG_Research_Project) |
| Technology Adoption Growth Modeling | Diffusion models, nonlinear regression | [Repo](https://github.com/ang-fran/Spread-of-Technology-Project) |
| Forecasting Hypoxia in the Gulf of St. Lawrence | Environmental time series, forecasting | [Repo](https://github.com/ang-fran/Hypoxia_Project) |

---

## Technical Skills

**Languages:** R, Python, SQL, SAS  
**Analytics & BI:** Power BI, Excel  
**Machine Learning:** Logistic Regression, Random Forest, XGBoost, SMOTE, SHAP  
**Time Series:** AR/ARIMA, VAR, VECM, Markov-Switching models (MS-AR, MSMAH-VAR)  
**Estimation:** Maximum likelihood, EM algorithm, Hamilton filter & smoother  

---

*Each repository is self-contained with documentation covering methodology, implementation, and results interpretation.*
