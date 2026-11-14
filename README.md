# BrightLearn - Sales Case Study | Exploratory Data Analysis & Financial Modeling

## Project Overview
This repository contains the exploratory data analysis (EDA), financial feature engineering, promotional analysis, and business insights for the BrightLearn Sales Case Study. Utilizing **Python, pandas, NumPy, and Plotly** within a **Databricks** environment, this project audits historical sales performance, evaluates pricing strategies, and calculates Price Elasticity of Demand (PED) across distinct promotional periods.

---

## Key Analytical Steps & Methodology

1. **Data Cleaning & Audit:**
   * Inspected dataset structure (`df.info()`), checked for null values (`df.isnull().sum()`), and verified data integrity against duplicate rows.
2. **Financial Feature Engineering:**
   * Derived key operational and financial metrics, including **Unit Price**, **Gross Profit**, **Gross Profit %**, and **Gross Profit Per Unit**.
   * Standardized and rounded financial figures to two decimal places for professional reporting and presentation.
3. **Pricing & Profitability Analysis:**
   * Established a normal baseline average unit price of **R37.07**.
   * Tracked daily and monthly fluctuations in gross profit margins (ranging from **-14.85% to 14.41%**) and gross profit per unit (**-R4.96 to R6.08**).
4. **Promotional & Elasticity Analysis:**
   * Isolated **three distinct promotional periods** to measure consumer responsiveness.
   * Calculated **Price Elasticity of Demand (PED)**, uncovering highly elastic demand ($\text{PED} < -1$, ranging between **-6.90 and -10.52**).

---

## Key Findings & Business Insights

* **Total Performance:** The business generated **R186.91 million in total sales** across **5,279,872 units sold**. However, total Cost of Sales reached **R194.03 million**, resulting in an overall **gross loss of R7.12 million**.
* **Volume vs. Profitability Trade-off:** While promotional discounts (approx. 17%–19% price cuts) successfully more than doubled daily unit sales volume due to high elasticity, they resulted in negative average gross profit percentages during those windows.
* **Strategic Recommendation:** Management must treat promotions as strategic loss-leaders designed to drive store traffic and clear inventory, while re-evaluating baseline pricing and Cost of Sales structures to ensure sustainable gross profitability.

---

## Repository Structure
* `Sales Case Study.ipynb` – Main Databricks notebook containing all code, calculations, and markdown interpretations.
* `presentation.pdf` – Final project presentation detailing visual summaries and strategic recommendations.

---

## Tech Stack & Libraries
* **Environment:** Databricks / Google Colab / Python
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Visualization:** `plotly.express`, `matplotlib`, `seaborn`
