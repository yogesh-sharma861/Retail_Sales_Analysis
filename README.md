
# Retail Sales Analysis

**Retail Sales & Profit Analysis (Project 1)** — an end-to-end analysis of retail sales and profitability from January 2009 to December 2012, built with **Excel** (data cleaning) and **Power BI** (dashboard).

## Overview

The dataset has 8,399 order lines (5,496 unique orders). Total sales are **14.92M** and total profit is **1.52M**, a profit margin of **10.2%**. The average discount is **4.97%** and total shipping cost is **107.83K**.

## Repository Contents

| File | Description |
|---|---|
| `Retail_Clean_Data_project1.xlsx` | Cleaned dataset (8,399 rows × 24 columns) |
| `Retail_Sales_Dashboard.pbix` | Power BI dashboard file (open in Power BI Desktop) |
| `Retail_sales_dashboard.pdf` | Power BI dashboard export |

## Data Cleaning

- Fixed mixed date formats (day and month were swapped in some rows).
- Filled 63 blank Product Base Margin values with the sub-category median (flagged in the `Margin Imputed` column).
- Corrected the region spelling "Prarie" to "Prairie".
- No duplicate rows were found.

## Key Insights

- **Top region:** West has the highest sales (3.60M), followed by Ontario (3.06M) and Prairie (2.84M). Nunavut is the lowest.
- **Top category:** Technology is the most profitable category (886K). Furniture has high sales (5.18M) but only 117K profit, a very low margin.
- **Top product:** Global Troy Executive Leather Low-Back Tilter has the highest revenue (276K).
- **Top customer segment:** Corporate gives the most profit (599.75K, 39.41% of total profit).
- **Sales trend:** January 2009 is the peak month (516K) and June 2011 is the lowest (198K). Yearly sales fell from 4.21M (2009) to 3.55M (2010) and 3.44M (2011), then recovered to 3.72M in 2012.
- **Loss-making areas:** Tables and Bookcases lose money, which pulls down the Furniture category.

## Answers to Project Questions

1. **Highest sales region:** West, with sales of 3.60M.
2. **Most profitable category:** Technology, with a profit of 886K.
3. **Highest revenue product:** Global Troy Executive Leather Low-Back Tilter, with sales of 276K.
4. **Highest profit customer segment:** Corporate, with a profit of 599.75K (39.41% of total profit).
5. **Monthly sales trend:** Sales were highest in January 2009 (516K) and lowest in June 2011 (198K). Sales fell after 2009 and partly recovered in 2012.

## Recommendation

Focus on Technology and Corporate customers for growth, and review discounts and shipping cost on Furniture, where many order lines lose money.

## Tools

Microsoft Excel · Power BI Desktop




