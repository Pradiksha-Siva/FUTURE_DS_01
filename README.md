# FUTURE_DS_01 — Business Sales Performance Analytics

**Internship:** Future Interns — Data Science & Analytics
**Task:** Task 1 of 3

## What this task is about
Analyze business sales data to find revenue trends, top-selling products, high-value categories, and how different regions are performing, then turn that into insights and recommendations a business could actually act on.

## Files in this folder
- `data/raw_sales_data.csv` — raw order-level sales data (Jan 2024 – Dec 2025)
- `task1_sales_analysis.ipynb` — full analysis notebook (cleaning, EDA, charts, insights)
- `task1_sales_analysis.html` — the same notebook exported to HTML, in case you just want to view it without opening Jupyter
- `task1_sales_dashboard.xlsx` — Excel dashboard with summary KPIs, monthly trend, top products, category and regional breakdowns, all with native charts
- `*.png` — chart images exported from the notebook

## Tools used
Python (pandas, matplotlib) for the analysis and Excel (openpyxl) for the dashboard.

## Approach
1. Loaded the raw data and checked it for the usual issues in a live export — duplicate rows, inconsistent text casing, missing region values, a few zero-quantity glitches.
2. Cleaned it up (deduped, standardised categories, dropped the quantity glitches, filled missing regions as "Unknown" instead of dropping them).
3. Looked at overall revenue trend by month, top products by revenue, category-level performance (revenue, orders, AOV), and regional performance.
4. Pulled out the 5 clearest insights and turned each into a specific recommendation rather than a generic statement.

## Key takeaways
- Festive season (Oct–Nov) is the biggest demand driver — revenue is roughly 35-40% above the yearly average in that window.
- Electronics is the top revenue category, driven by a high average order value rather than order volume.
- South region leads on total revenue, but it's a volume story — its AOV isn't the highest.
- May–June is a consistent soft period worth targeting with a planned clearance push.

Full write-up with charts is in the notebook.
