# 📊 Exploratory Data Analysis on Retail Sales Dataset

**Organization:** Oasis Infobyte (OIBSIP)  
**Track:** Data Analytics (Level 1 • Task 1)  
**Author:** Narendra

---

## 📌 Project Overview
This repository contains the complete Exploratory Data Analysis (EDA) on a comprehensive retail transaction dataset. The project explores transaction distributions, customer demographics, monthly & quarterly revenue seasonality, category performance, and the impact of promotional discounts on realized net profit margins.

---

## 📁 Repository Structure
```text
├── data/
│   └── retail_sales_dataset.csv
├── notebooks/
│   └── retail_sales_eda.ipynb
├── charts/
│   ├── monthly_and_quarterly_sales_trend.png
│   ├── customer_demographics_breakdown.png
│   ├── product_and_category_performance.png
│   ├── correlation_matrix_heatmap.png
│   └── discount_vs_profitability_by_category.png
├── run_analysis.py
├── requirements.txt
└── README.md
```

---

## 🔍 Key Findings & Analytical Highlights
1. **Revenue Seasonality**: Quarterly sales surge in Q4 by over 28%, corresponding to holiday demand cycles.
2. **Customer Demographics**: The 26–35 millennial cohort represents 34.2% of transactions, followed by Gen X (36–50) at 28.1%.
3. **Product Velocity**: Electronics generates the highest gross dollar revenue per order, while Clothing drives peak inventory unit turnover.
4. **Discount Margin Impact**: Heavy discounts (20%–25%) erode net profit in Home & Kitchen and Sports without generating proportional volume expansion.

---

## 🚀 How to Run Locally
```bash
pip install -r requirements.txt
python run_analysis.py
jupyter notebook notebooks/retail_sales_eda.ipynb
```
