# ⚡ Energy Forecasting Analysis

This repository contains a comprehensive analysis of electricity demand forecasting, exploring both statistical and machine learning approaches.

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-View_on_Kaggle-blue?logo=kaggle)](https://www.kaggle.com/code/jacopoferretti/time-series-forecasting-univariate-multivariate)

<img width="1966" height="1141" alt="Screenshot 2026-07-13 alle 15 25 47" src="https://github.com/user-attachments/assets/866b4464-8272-4ed5-ab1c-c2f8cba92778" />

---

## 📖 Project Overview
Developed and evaluated statistical (SARIMA), machine learning (XGBoost), and deep learning (LSTM) models for univariate and multivariate electricity demand forecasting. Compared deterministic and probabilistic forecasting approaches for risk-aware energy prediction. 

The best-performing XGBoost model achieved **2.13% MAPE** with a Durbin-Watson statistic of **1.94**, indicating highly accurate forecasts with uncorrelated residuals.

---

## 🎯 Objective

- Build forecasting models for energy consumption
- Compare deterministic vs probabilistic approaches
- Evaluate predictive uncertainty
- Generate confidence intervals from model outputs
- Compare univariate and multivariate approaches

---

## 📈 Key Insights
* **Baseline Performance:** SARIMA models established a strong statistical baseline, offering high interpretability for linear temporal dependencies.
* **Non-Linear Dynamics:** The **XGBoost** model demonstrated superior performance in capturing complex, non-linear patterns within the energy consumption data.
* **Deep Learning Potential:** **LSTM** networks proved effective in modeling long-range temporal structures, showing stability for multi-step sequences.
* **Risk Management:** Incorporating **probabilistic forecasting** and confidence intervals provided essential uncertainty estimation, which is critical for real-world grid load management.
* **Feature Importance:** The transition to a multivariate approach allowed for a better understanding of exogenous variables, significantly enhancing predictive accuracy.

---

## 🛠️ Technical Skills

- **Time Series Forecasting:** Statistical modeling, SARIMA.
- **Machine Learning:** XGBoost, Hyperparameter optimization.
- **Deep Learning:** TensorFlow / Keras (LSTM networks for sequential data).
- **Evaluation:** Deterministic vs. Probabilistic approaches, Error Analysis.

---

## 👤 Author

#### Jacopo Ferretti

Data Scientist | Machine Learning | Applied AI

Kaggle: https://www.kaggle.com/jacopoferretti

LinkedIn: https://www.linkedin.com/in/jacopo-ferretti-29b2b3293

GitHub: https://github.com/JakFerretti

---

## 📄 License

MIT License
