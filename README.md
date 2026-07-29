# Retail Sales and Customer Insights

An end-to-end retail analytics case study using Python, SQL, Excel, and Power BI to turn transaction data into customer and sales insights.

## Business questions

- Which customers contribute the most value?
- How do revenue and order activity change over time?
- Which customer segments are loyal, at risk, or recently acquired?
- What do cohorts reveal about retention?
- What patterns may be useful for near-term sales planning?

## Analysis workflow

1. Profile and clean transaction and response data.
2. Query and validate the relational dataset with SQL.
3. Analyze sales trends and high-value customers in Python.
4. Build RFM segments and customer cohorts.
5. Explore churn and time-series patterns.
6. Present the results in Excel and Power BI dashboards.

## Tools

- Python: Pandas, NumPy, SciPy, Matplotlib, Seaborn, and Plotly
- SQL: preparation, validation, and business queries
- Excel: analysis and dashboarding
- Power BI: data modeling, measures, and interactive reporting

## Repository guide

| Artifact | Purpose |
| --- | --- |
| [Analysis notebook](<Sales Data Analysis and Reporting for a Retail Chain.ipynb>) | Cleaning, exploration, segmentation, cohorts, churn, and trends |
| [SQL queries](Fnal_Retail_db_Qureies.sql) | Database setup and analytical queries |
| `sales_data.pbix` | Power BI report |
| `sales_data.pbit` | Reusable Power BI template |
| `Retail_data.xlsx` | Excel analysis workbook |
| `Internship_studio_project_Presentation1.pptx` | Project presentation |

The source CSV files used by the notebook and reports are included in the repository.

## Run the notebook

```bash
git clone https://github.com/AyushUprety/retail-sales-insights.git
cd retail-sales-insights
jupyter notebook "Sales Data Analysis and Reporting for a Retail Chain.ipynb"
```

## Notes

This is a portfolio case study built from a fixed dataset. Forecasts and customer labels should be validated against current business definitions and production data before operational use.
