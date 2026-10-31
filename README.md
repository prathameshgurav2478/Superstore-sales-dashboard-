# Superstore Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyzes sales and profit performance of a retail superstore across customer segments, product categories, regions and time.

![Dashboard Preview](dashboard_preview.png)

## Project Overview

This project turns raw order-level data into a single-page dashboard that helps answer common business questions:

- How much revenue is the business generating, and where does it come from?
- Which product categories and customer segments drive the most sales?
- How does profit change over time (year and quarter) for each category?
- Which states and regions perform best?

## Dataset

- **Source:** Sample Superstore dataset (Excel)
- **Sheets:** `Orders`, `Returns`, `Users`
- **Orders table:** 9,426 rows and 24 columns (customer, segment, product category, region, state, order and ship dates, discount, sales, profit, etc.)
- **Time period:** January 2010 – December 2013
- **Total sales:** ~8.95M

## Dashboard Features

| Visual | Purpose |
|---|---|
| KPI card | Total sales (8.95M) at a glance |
| Clustered column chart | Sales by customer segment and product category |
| Donut chart | Sales share by customer segment |
| Line chart | Profit by year, quarter and product category |
| Filled map | State-wise sales across the United States |
| 100% stacked bar chart | Sales contribution by product category |
| Slicers | Filter by Year and Product Category |

## Key Insights

- **Technology** is the top-selling category (~3.51M), followed by Furniture (~3.18M) and Office Supplies (~2.26M).
- The largest customer segment contributes about **36.5%** of total sales.
- Profit fluctuates noticeably by quarter across all three categories.
- Sales are concentrated in a few high-performing states, visible on the map.

## Tools Used

- **Power BI Desktop**: data modeling, visuals, slicers and formatting
- **Microsoft Excel**: source data

## How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the **Year** and **Product Category** slicers to explore the data.
4. Click any chart element to cross-filter the other visuals.

## Repository Structure

```
├── Sample_Superstore.xlsx      # Source dataset
├── Sales_Dashboard.pbix        # Power BI dashboard file
├── dashboard_preview.png       # Dashboard screenshot
└── README.md
```

## What I Learned

- Cleaning and loading data into Power BI and building relationships between tables
- Choosing the right chart type for each business question
- Using slicers and cross-filtering for interactive analysis
- Designing a clean, readable dashboard layout
