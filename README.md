# 📊 Policy Impact Analysis: Plastic Waste Reduction (Palu City)

## 📌 Overview

This project evaluates the effectiveness of a plastic waste reduction policy in Palu City using advanced time series analysis. The study applies intervention analysis to measure the real impact of policy implementation on waste volume.

## 🎯 Objectives

* Assess the impact of Mayoral Regulation No. 40/2021
* Identify structural changes in waste trends
* Provide data-driven policy evaluation

## 🛠 Tools & Technologies

* SAS (Time Series Analysis)
* Seasonal ARIMA (SARIMA)
* Intervention Analysis (Box-Tiao Model)

## 📈 Methodology

* Time series modeling using SARIMA
* Intervention modeling with step function
* Model selection based on AIC and accuracy metrics
* Residual diagnostics and validation

## 📊 Key Findings

* Best model: SARIMA(0,1,1)(1,1,1)₁₂ with intervention
* Model accuracy: MAPE = **1.13%**
* Policy impact is statistically significant (p < 0.05)

⚠️ **Unexpected Insight:**

* Waste volume increased by **+170.40 tons/month (~2.91%) after policy implementation**
* Suggests improved waste collection/reporting rather than actual increase in waste generation

## 💼 Policy Implications

* Policy evaluation must consider data recording improvements
* Waste increase does not necessarily indicate policy failure
* Supports evidence-based environmental decision making

## 📂 Project Structure

* `report/` → Full thesis document
* `code/` → SAS scripts
* `README.md` → Project summary

## 🚀 Future Improvements

* Convert model to Python (statsmodels)
* Build interactive dashboard
* Include external variables (population, economy)

## 👤 Author

Jeremy Filippo Gabriel Givary
Bachelor of Statistics – ITS
