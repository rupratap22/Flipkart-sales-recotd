# Flipkart Sales Dashboard 📊

An interactive sales analytics dashboard built to explore Flipkart sales performance across product categories, quantities sold, customer ratings, and time periods.

## 📌 Project Overview

This project analyzes a Flipkart sales dataset and presents key performance indicators (KPIs) and visual summaries in a dashboard. The goal is to make sales patterns easier to understand and identify areas for further investigation.

## 🎯 Objectives

- Track key sales and quantity metrics.
- Compare sales performance across product categories.
- Understand the contribution of different quantities sold to total sales.
- Explore trends by year, quarter, and month.
- Identify data-quality questions to investigate before forecasting.

## 📈 Dashboard Highlights

The dashboard includes KPI cards and charts for category, product, quantity, and time-based analysis.

### Key Performance Indicators

| Metric | Value shown in report |
|---|---:|
| Total sales | ₹75.21M |
| Quantity sold | Approximately 3K units |
| Customer ratings recorded | Approximately 1K |
| Sum of listed price | ₹24.52M |
| Sales records | Approximately 1K |

> **Note:** The source dashboard screenshot and report display some differently aggregated values. The figures above follow the accompanying PDF report; validate them against the underlying dataset before using them for formal reporting.

### Category Performance

Sales are spread across five categories:

| Category | Sales |
|---|---:|
| Electronics | ₹17.31M |
| Clothing | ₹15.11M |
| Books | ₹14.79M |
| Beauty | ₹14.68M |
| Home & Kitchen | ₹13.33M |

- **Electronics** is the leading category, contributing approximately **23.01%** of reported total sales.
- **Home & Kitchen** has the lowest reported category sales, at approximately **₹13.33M**.
- The relatively distributed category mix suggests there may be opportunities to grow more than one category.

### Quantity-Based Sales

The report shows the following sales contribution by quantity sold:

| Quantity sold | Sales |
|---:|---:|
| 1 | ₹20.79M |
| 2 | ₹15.35M |
| 3 | ₹26.08M |
| 4 | ₹8.01M |
| 5 | ₹4.99M |

- Orders with a quantity of **3** contribute the largest share: approximately **₹26.08M (34.67%)**.
- Quantities **4 and 5 combined** contribute approximately **₹13.00M (17.28%)**.
- Investigate product mix, pricing, and order characteristics to understand why quantity-3 orders contribute the most sales.

### Time-Based Trends

- The report's year view shows quantity sold at approximately **3K in 2024** and near zero in **2025**, based on the displayed chart scale.
- The monthly view shows a late-year spike, with **December at approximately 10 units** on the displayed scale.
- These patterns should be treated as signals to validate—not confirmed business trends—until date filters and year completeness are checked.

## 💡 Key Insights & Recommendations

1. **Protect the leading category:** Review what is driving Electronics sales and identify opportunities to grow other categories, particularly Home & Kitchen.
2. **Investigate quantity-3 orders:** Examine products, prices, and order patterns associated with the highest sales contribution.
3. **Validate the time series:** Check date filters, missing records, and 2025 data completeness before drawing conclusions or forecasting.
4. **Review the December spike:** Confirm whether the spike reflects real demand, incomplete monthly data, or a reporting/filtering issue.
5. **Verify dashboard aggregations:** Reconcile KPI cards and chart totals with the underlying data before using results in business decisions.

## 🧰 Tools & Technologies

- **Power BI** — dashboard and data visualization *(based on the dashboard interface shown)*
- **Dataset analysis** — category, quantity, rating, price, and time-based summaries
- **GitHub Markdown** — project documentation

> Update this section if you used additional tools, such as Excel, SQL, Python, or Power Query.

## 🗂️ Repository Structure

A suggested structure for publishing this project:

```text
flipkart-sales-dashboard/
├── README.md
├── dashboard/
│   └── flipkart-sales-dashboard.png
├── report/
│   └── Flipkart-sales-performance-at-a-glance.pdf
└── data/
    └── README.md
```

Add your actual files to the matching folders, or adjust this structure to match your repository. Do not upload confidential or restricted customer data.

## 🚀 How to Use

1. Clone or download this repository.
2. Open the dashboard image and PDF report to review the analysis.
3. If the editable dashboard file and source dataset are included, open them in the relevant application and refresh the data as needed.
4. Validate the metrics against the source data before using them in reports or forecasts.

## ⚠️ Data Notes & Limitations

- Figures are based on the supplied dashboard and accompanying PDF report.
- Some chart values are approximate readings from displayed axes.
- The screenshot and report may use different aggregations or filters; reconcile totals with the source data.
- The apparent decline in 2025 and the December spike require validation.
- No causal conclusions should be drawn from these charts alone.

## 🔮 Future Improvements

- Add slicers for category, product, year, and month.
- Include profit, discount, and order-level metrics if those fields are available.
- Add year-over-year and month-over-month comparisons.
- Validate data types, missing values, duplicate records, and filter context.
- Create a documented data-cleaning and refresh workflow.

## 👤 Author

**Your Name**  
Add your GitHub profile or portfolio link here.

## 📄 License

Add a license if you intend to distribute this project publicly. If the dataset has usage restrictions, follow its original terms.
