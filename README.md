# adventureworks-sql-financial-analysis
SQL analysis of AdventureWorks financial performance to identify high-revenue and high-ROI markets.
# AdventureWorks Financial Performance Analysis (SQL)

## Project Overview
In this project, I act as a data analyst at AdventureWorks. The finance director wants to understand which markets generate the highest revenue and profitability in order to guide future marketing investments.

Using SQL, I analyze sales transactions, products, territories, and marketing campaign data to evaluate financial performance across different countries.

## Business Questions
The analysis focuses on answering two key questions:

1. Which countries generate the most revenue?
2. Which markets are the most profitable after considering marketing expenses?

## Dataset
The analysis uses a subset of the AdventureWorks dataset with the following tables:

- **ventas_2017** – sales transactions for 2017
- **productos** – product catalog including cost and price
- **productos_categorias** – product category hierarchy
- **clientes** – customer information
- **territorios** – country and continent mapping
- **campanas** – marketing spending by territory

## Tools
- SQL
- Relational databases
- Data cleaning and transformation
- Financial KPI analysis

## Key Metrics
The following financial metrics were calculated:

- Revenue
- Cost
- Gross Profit
- Profit Margin
- Marketing ROI

## Methodology
1. Explored the relational schema and identified relationships between tables.
2. Joined sales, product, and territory data using SQL.
3. Cleaned and prepared the data (handling NULL values and data types).
4. Calculated financial KPIs such as revenue, profit, and ROI.
5. Validated results using quality checks.

## Key Insights
The analysis identifies which markets generate the highest revenue and which territories provide the strongest return on marketing investment.

## Dashboard

Below is a preview of the financial analysis dashboard created for this project.

![AdventureWorks Dashboard](dashboard_preview.png)

You can also download the full dashboard here:

[Download Dashboard](Financial_Dashboard.pdf)

## Author
Juanita Pinzón
