
# Port Authority Bus Terminal – Passenger Demand Analysis

### Business Analytics | Regression Modeling | Predictive Analytics

## 📌 Project Overview

This project focuses on analyzing historical passenger data from the Port Authority Bus Terminal to understand passenger demand patterns, identify key demand drivers, and support future transportation capacity planning.

The collaborative project integrates data analysis, forecasting, regression modeling, and clustering using multiple analytical tools.

## 🎯 Business Objectives

- Analyze historical passenger demand across bus carriers.
- Identify factors influencing passenger volumes.
- Compare different predictive modeling approaches.
- Support future passenger demand and terminal capacity planning for 2026–2030.

## 👩‍💻 My Contribution

**Excel Regression Analysis & Exploratory Data Analysis**

My primary responsibility was developing and evaluating Excel-based regression models.

- Prepared the regression dataset with carrier and monthly dummy variables.
- Cleaned incomplete observations and prepared model inputs.
- Developed three multiple linear regression models.
- Compared regression performance using R², Adjusted R², RMSE, MAE, and MAPE.
- Created carrier-wise and monthly exploratory data analysis (EDA) pivot tables.
- Interpreted regression coefficients to identify important passenger demand drivers.

## 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Data Analysis ToolPak
- Multiple Linear Regression
- Pivot Tables
- Exploratory Data Analysis (EDA)
- Dummy Variable Encoding
- Data Cleaning

## 📊 Regression Models

Three regression models were developed and compared:

| Model | Description |
|---|---|
| Model 1 – Basic | Bus departures, previous-week passengers, and year |
| Model 2 – Carrier | Basic model with carrier dummy variables |
| Model 3 – Monthly | Basic model with monthly dummy variables |

## 📈 Key Results

The Carrier Regression Model achieved the best test performance among the three Excel regression models.

| Evaluation Metric | Result |
|---|---:|
| R² | 0.9946 |
| Adjusted R² | 0.9945 |
| Test RMSE | 1,248 |
| Test MAPE | 14.4% |

Additional findings:

- Previous-week passenger volume was a strong predictor of current demand.
- Bus departures showed a positive association with passenger volume.
- Passenger demand varied considerably across carriers.
- Monthly dummy variables provided limited additional explanatory value after accounting for previous-week demand.

## 💡 Business Insights

The analysis can help transportation planners:

- Understand passenger demand differences across carriers.
- Evaluate the relationship between bus departures and passenger volumes.
- Support carrier-level service planning.
- Make more informed transportation capacity decisions.

## ⚠️ Limitations

- Regression coefficients indicate associations, not necessarily causation.
- The model produced negative predictions for some smaller-carrier observations.
- Differences in carrier sizes influence overall model performance.
- Further analysis could explore separate models for smaller carriers.

## 👥 Project Context

**Course:** BANL 6430 – Business Analytics  
**Institution:** University of New Haven  
**Project:** Port Authority Bus Terminal Passenger Predictions  
**Project Type:** Collaborative Academic Project

This repository documents my individual contribution to the Excel regression and exploratory data analysis components of the larger group project.

---

*Turning data into meaningful business insights through analytical thinking and problem-solving.*
Collaborative academic project – BANL 6430, University of New Haven.

My documented contribution focuses on Excel regression modeling and exploratory data analysis.
