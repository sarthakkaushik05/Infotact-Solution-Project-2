# Infotact-Solution-Project-2

#  Supply Chain Analytics — Demand Forecasting & Anomaly Detection

**Infotact Technical Internship Program — Advanced Data Analytics**

---

## Executive Problem Statement

Supply chain efficiency dictates profitability for retail and manufacturing companies.
Overestimating demand leads to bloated warehouses, tied-up capital, and spoilage.
Underestimating demand leads to stockouts, lost sales, and furious customers.
Unexpected anomalies (viral trends, supplier delays) often go unnoticed in massive
datasets until the financial damage is already done.

This project builds a time-series analytics pipeline that:
- Analyzes historical sales/inventory data to **forecast future demand**
- Deploys statistical methods to **automatically detect anomalies** in the supply chain flow

## Business Objectives & KPIs

| Objective | Metric |
|---|---|
| Optimize inventory levels | Forecast accuracy — MAE, RMSE, MAPE / sMAPE |
| Catch operational issues early | Anomaly detection precision (flag real outliers, avoid "alert fatigue") |

## User Personas

| Persona | Needs | Workflow |
|---|---|---|
| **Supply Chain Manager** | Data-driven procurement scheduling | Uses the demand forecast to order the right quantity of stock for the upcoming period |
| **Operations Analyst** | Immediate notification of operational hiccups | Investigates flagged anomalies (e.g. sudden dispatch drop) |

---

## Tech Stack

- **Python**: pandas, numpy, matplotlib, seaborn

