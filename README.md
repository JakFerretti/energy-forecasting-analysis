# ⚡ Energy Forecasting Analysis

This repository contains a comprehensive analysis of electricity demand forecasting, exploring both statistical and machine learning approaches.

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-View_on_Kaggle-blue?logo=kaggle)](https://www.kaggle.com/code/jacopoferretti/time-series-forecasting-univariate-multivariate)

<div align="center">
<img width="700" alt="Screenshot 2026-07-13 alle 15 25 47" src="https://github.com/user-attachments/assets/866b4464-8272-4ed5-ab1c-c2f8cba92778" />
</div>

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
* **Non-Linear Dynamics:** The **XGBoost** model demonstrated superior performance in capturing complex, non-linear patterns within the energy data.
* **Deep Learning Potential:** **LSTM** networks proved effective in modeling long-range temporal dependencies.
* **Scalability of Forecasting:** The multivariate approach proved critical for extending the scope beyond individual consumer metrics, enabling robust predictions for **total network energy load**.
* **Risk Management:** The use of **probabilistic forecasting** and confidence intervals provided essential uncertainty estimation, a key requirement for real-world load management.

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
