# superstore-sales-profit-analysis
Tableau coursework analyzing Superstore sales, profit, and order quantities across three visualizations.
## Tableau Visualizations

1. [Annual Profit by Product Category](https://public.tableau.com/views/Homework1_1_17586193693580/Sheet1)
   A stacked area chart showing how Furniture, Office Supplies, and Technology
   contributed to total profit each year.

2. [Sales, Profit, and Quantity Summary](https://public.tableau.com/views/Homework1_2_17586193343080/Sheet2)
   A text table summarizing total sales, total profit, and total units sold.

3. [Annual Sales and Profit Trends](https://public.tableau.com/views/Homework1_17586192438430/Sheet3)
   A line chart comparing annual sales and profit on a shared axis.

## Tableau Functions and Techniques

- **Aggregation:** `SUM([Sales])`, `SUM([Profit])`, and `SUM([Quantity])`
  summarize transaction-level measures.
- **Date grouping:** `YEAR([Order Date])` groups orders by calendar year
  for the trend charts.
- **Measure Names and Measure Values:** Tableau's built-in fields display
  multiple measures together in the summary table and the trend chart.
- **Category breakdown:** `Category` splits the stacked area chart into
  Furniture, Office Supplies, and Technology.

## Data Source

[Superstore dataset used in the assignment](https://github.com/ogut77/University/blob/main/Superstore.xls)
