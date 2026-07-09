# Superstore Sales Analysis

**Tools:** Python · SQL (SQLite) · pandas · matplotlib · seaborn  
**Dataset:** 9,994 retail orders across 4 regions and 3 categories

## Project Overview
End-to-end sales analysis using SQL for querying and root cause investigation,
and Python for data cleaning, feature engineering and visualization.

## Key Findings
- West region leads in both sales ($725K) and profit margin (14.94%)
- Central region has the worst profit margin (7.92%) despite ranking 3rd in sales
- 99% of loss-making orders carry above-average discounts — discounting is the #1 profit killer
- Furniture has disproportionately low profit relative to its sales volume
- Monthly sales show seasonal cyclicality with a modest upward trend

## Files
| File | Description |
|------|-------------|
| `superstore_analysis.ipynb` | Full Python analysis with charts and findings |
| `superstore.db` | SQLite database with all SQL queries |
| `superstore.csv` | Raw dataset (9,994 orders) |

## Skills Demonstrated
- SQL querying — SELECT, GROUP BY, JOINs, CASE WHEN, Subqueries, CTEs
- Data exploration and cleaning with pandas
- Derived column creation and datetime handling
- Root cause analysis through cross-dimensional investigation
- Data visualization with matplotlib and seaborn
