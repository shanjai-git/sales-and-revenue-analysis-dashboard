# Sales & Revenue Analysis Dashboard
**Internship Task 1 - Data Science / Business Analytics Domain**

## Objective
Import sales data, clean it, visualize KPIs (total sales, revenue trends, top-performing products), and build an interactive dashboard with charts and filters for business analysis.

## Dataset
Synthetic order-level sales data — 1,200 orders across 5 categories, 4 regions, 3 sales channels, and 6 sales reps, over calendar year 2025.

## Key KPIs
| KPI | Value |
|---|---|
| Total Revenue | Rs 1,20,83,335 |
| Total Orders | 1,200 |
| Total Units Sold | 4,788 |
| Average Order Value | Rs 10,069 |

## Key Insights
- A small set of products (Bluetooth Speaker, Wireless Earbuds, Non-stick Pan Set, USB-C Cable, Vacuum Cleaner) drives a disproportionate share of revenue.
- **Online** is the largest sales channel (51.8% of revenue), ahead of Retail Store (25.8%) and Marketplace (22.4%).
- Electronics and Home & Kitchen lead category revenue; North region leads by region.
- Heavier discounts don't proportionally increase order volume — worth re-examining the discounting strategy.

## Files
| File | Description |
|---|---|
| `sales_raw_dataset.csv` | Raw dataset (1,210 rows, with intentional duplicates and missing values) |
| `sales_cleaned_dataset.csv` | Cleaned dataset after processing (1,200 rows) |
| `Sales_Revenue_Analysis.ipynb` | Full executed notebook — cleaning, KPIs, trends, top products, channel mix |
| `Sales_Revenue_Report.html` | Static HTML export of the notebook |
| `sales_dashboard.html` | **Interactive dashboard** — KPI cards, filters (category/region/channel), 5 live charts |
| `Final_Report_Sales.docx` | Formal written report |

## How to view the dashboard
The interactive dashboard (`sales_dashboard.html`) is a self-contained HTML file — no server or installation needed:
1. Download `sales_dashboard.html` from this repo.
2. Double-click it (or right-click → Open with → your browser).
3. Use the Category/Region/Channel filters to explore the data live.

A live hosted version is also available here: **[Interactive Dashboard](https://claude.ai/artifact/7YTDJZSxu77eHNwDeuYUxe)**

## Tools
Python · Pandas · Matplotlib · Seaborn · Chart.js (for the interactive dashboard) · Jupyter Notebook

---
*Submitted as part of a Data Science / Business Analytics internship task — Sales & Revenue Analysis Dashboard.*
