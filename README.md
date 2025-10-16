# Fresh Peaches — Sales Forecasting & Analytics

This repository contains data cleaning, analysis, and time series forecasting work for Fresh Peaches, a direct-to-consumer startup specializing in eco-friendly home care products. The goal of this project is to transform raw 12-month sales data into actionable insights and predictive models to guide inventory and marketing decisions.

## Project Overview

Objectives:
- Clean and unify historical transaction data across SKUs (≈30+ products, ~7K units distributed)
- Compute descriptive metrics such as MoM sales growth, AOV, bundle frequency, and top customers by spend
- Build reproducible forecasting pipelines using Prophet and SARIMA
- Compare model performance using MAPE, RMSE, and pseudo-R²
- Visualize results and export key insights for leadership reports

## Methods & Tools

| Task | Approach |
|:--|:--|
| Data Cleaning | Pandas & SQL-style deduplication by (customer_id, order_id, title), NULL detection, type casting |
| Exploratory Analysis | Group-by aggregations, SKU-level MoM/YoY trends, seasonality visualization |
| Forecasting Models | Prophet (with retail-holiday regressors), SARIMA/SARIMAX, Auto-ARIMA baselines |
| Evaluation Metrics | MAPE, RMSE, pseudo-R² |
| Visualization | Matplotlib, Seaborn, and Jupyter inline charts |
| Documentation | Jupyter Notebooks + CSV exports for reproducibility |

## Repository Structure
