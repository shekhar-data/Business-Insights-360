# Business Insights 360

## Power BI Business Intelligence Project

Business Insights 360 is an interactive Power BI dashboard designed to provide a consolidated view of business performance across Finance, Sales, Marketing, Supply Chain, and Executive functions.

This project was completed as part of the **Codebasics Data Analytics Bootcamp** and focuses on applying Power BI, Power Query, DAX, and data modelling concepts to a real-world business scenario.

## Project Overview

AtliQ Hardware is a growing consumer electronics company operating across multiple markets and regions.

As the business grows, different teams need access to relevant performance metrics to understand what is happening across the organization and make better decisions.

The Business Insights 360 dashboard brings these different perspectives together into one interactive Power BI report.

## Dashboard Views

### Executive View
Provides a high-level overview of business performance, including:

- Net Sales
- Gross Margin
- Net Profit
- Forecast Accuracy
- Revenue by Division and Channel
- Market Share
- Top Products and Customers

### Finance View
Focuses on financial performance and profitability through:

- Profit & Loss analysis
- Net Sales
- Gross Margin
- Net Profit
- Year-over-Year performance
- Customer and product performance
- Unit economics

### Sales View
Analyzes customer and product performance across:

- Customer performance
- Product performance
- Performance matrix
- Region and market performance
- Unit economics

### Marketing View
Provides a marketing-focused perspective on business performance, including customer, product, and market-level analysis.

### Supply Chain View
Focuses on forecast and operational performance through:

- Forecast Accuracy
- Net Error
- Absolute Error
- Forecast Accuracy trends
- Product-level forecast performance

### Info View
Provides information about the report, data refresh process, definitions, and frequently asked questions.

## Key Business Metrics

The dashboard works with several important business metrics, including:

- Gross Sales
- Pre-Invoice Deductions
- Post-Invoice Deductions
- Net Invoice Sales
- Net Sales
- Total COGS
- Gross Margin
- Gross Margin %
- Net Profit
- Net Profit %
- Forecast Accuracy
- Net Error
- Absolute Error
- Market Share
- Revenue Contribution

## Data Model

The project uses a structured Power BI data model containing dimension, fact, and supporting tables.

### Dimension Tables

- `dim_customer`
- `dim_product`
- `dim_category`
- `dim_market`
- `dim_subzone`
- `Dim_date`
- `fiscal_year`

### Fact and Supporting Tables

- `fact_actuals_estimate`
- `fact_forecast_monthly`
- `post_invoice_deductions`
- `freight_cost`
- `manufacturing_cost`
- `Operational_Expense`
- `marketshare`
- `target_table`

Additional supporting tables are used for report navigation, dynamic reporting elements, P&L presentation, targets, and other dashboard functionality.

## Tools & Techniques

### Tools

- Power BI Desktop
- Power Query
- DAX

### Techniques Applied

- Data cleaning and transformation
- Data modelling
- Star schema
- DAX measures
- Calculated columns
- Time-based analysis
- Year-over-Year analysis
- Target vs Actual analysis
- Variance analysis
- KPI development
- Forecast accuracy analysis
- Market share analysis
- Interactive filters and slicers
- Conditional formatting
- Dynamic titles and report elements
- Dashboard navigation
- Business-focused data visualization

## Key Business Questions

The dashboard helps answer questions such as:

- How is the overall business performing?
- Which markets and regions are contributing most to revenue?
- Which customers and products are performing well or poorly?
- How are Gross Margin and Net Profit changing over time?
- Which products and customers contribute most to revenue?
- How accurate is the sales forecast?
- Where are the largest forecast errors occurring?
- How does market share change across regions and categories?
- Which areas require management attention?

## Project Outcome

The project helped transform multiple business datasets into an interactive reporting solution that provides different teams with relevant views of business performance.

The main focus was not only on building visuals, but also on understanding business metrics, structuring the data model, creating reusable DAX measures, and presenting information in a way that supports business decision-making.

## Project Structure

The repository will contain the Power BI report, dashboard screenshots, and supporting project documentation.

## Credits

This project was completed as part of the **Codebasics Data Analytics Bootcamp**.

The Business Insights 360 project was used as a guided learning project to apply Power BI, Power Query, DAX, and data modelling concepts in a practical business scenario.
