# Blinkit Grocery Sales Analysis | Excel Dashboard

An interactive Excel dashboard that shows which items, outlets and locations drive sales in a Blinkit grocery dataset.

<img width="2200" height="1700" alt="blinkit-sales-analysis-excel-dashboard" src="https://github.com/user-attachments/assets/74d7b88c-dea8-4065-9b7c-19840db25eb1" />


## Project Overview
- **Dataset:** 8,523 item records, 13 columns (item type, fat content, outlet size/type/location, establishment year, visibility, weight, sales, rating)
- **Tools:** Microsoft Excel (Excel Table, 10 pivot tables, slicers, GETPIVOTDATA KPIs, 8 charts)
- **Goal:** Find which items, outlets and locations drive sales, and where the opportunities are

## Data Cleaning
- Fat content had 5 inconsistent labels (Low Fat, low fat, LF, Regular, reg)
- Standardized them into 2 categories (Low Fat, Regular) using Find & Replace with "Match entire cell contents"
- After refreshing all pivots, totals reconcile to about $1.2M

## Key KPIs
| Metric | Value |
|---|---|
| Total sales | ~$1.2M |
| Avg sales per item | ~$141 |
| Total items | 8,523 |
| Avg rating | 3.97 / 5 |

## Key Insights
- Low Fat items drive about 65% of sales ($776K vs $425K Regular)
- Fruits & Vegetables ($178K) and Snack Foods ($175K) lead item categories
- Tier 3 locations generate the most sales (39%)
- Medium outlets lead by size (42%)
- Supermarket Type1 makes up about 65% of sales, but average sales per item are nearly the same across outlet types ($140–$142), so it leads on volume, not value per item

## Recommendations
- Expand stock in top categories and Tier 3 locations
- Investigate why Seafood and Breakfast underperform
- Focus on value per item, not just volume
- Review older outlets

## How to Use the Dashboard
GitHub only shows a static preview of Excel files, so the slicers and charts won't work in the browser. To use the interactive dashboard:
1. Download `BlinkIT_Grocery_Data_Excel.xlsx` from this repo.
2. Open it in Microsoft Excel and go to the **Dashboard** sheet.
3. Use the slicers on the left to filter by outlet size, outlet location and item type.

## Author
**Shivam Raut** | [GitHub](https://github.com/shivamraut747-ux) | [LinkedIn](https://www.linkedin.com/in/shivam-raut-9a9986376/)
