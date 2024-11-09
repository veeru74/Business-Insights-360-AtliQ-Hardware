# Business-Insights-360-AtliQ-Hardware

## Project Overview
AtliQ Hardware, experiencing rapid growth, has implemented Power BI analytics to drive data-based decisions across finance, sales, marketing, and supply chain. This project is AtliQ's first venture into analytics, designed to provide valuable insights to compete effectively and guide stakeholders' decision-making.

I worked on this project by following the [Codebasics Power BI Course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project), which provided comprehensive training and practical experience.



## Tech Stack
- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for performance optimization)
- **Project Charter File**


## Key Power BI Techniques Learned
- **Initial Project Planning**: Defined objectives, metrics, and timelines based on stakeholder input.
- **Data Modeling**: Structured using a Snowflake schema to optimize performance.
- **DAX Calculations**: Created calculated columns and measures with functions like `CALCULATE()`, `DIVIDE()`, `FILTER()`, `SWITCH()`.
- **Interactive Visuals**: Used Bookmarks, buttons for navigation, and dynamic titles.
- **Data Validation and Error Prevention**: Leveraged data validation techniques and conditional formatting for enhanced accuracy.
- **Automation and Collaboration**: Published to Power BI Services, with auto-refresh using personal gateway, Power BI App creation, and workspace management.



## Business and Domain Knowledge Applied
- **Finance**: Gross Price, Net Sales, Gross Margin, Net Profit.
- **Sales and Marketing**: Market segmentation, YTD/YTG metrics, retail and distributor performance.
- **Supply Chain**: COGS, inventory tracking, forecasting for improved customer satisfaction.
- **Executive View**: provide overall insights to stakeholders




## Data Overview
Understanding the datasets was key to efficient analysis. Data was reviewed for accurate model design, helping avoid performance issues.

### Dataset Tables and Structures
- **Dimension Tables**:
  - `dim_customer`: Contains 27 markets, 75 customers, two platforms (Brick & Mortar, E-commerce), and three channels (Retailer, Direct, Distributors).
  - `dim_market`: Geographical data covering 7 sub-zones in regions like APAC, EU, LATAM.
  - `dim_product`: Product details, including categories and types (e.g., Notebook, Desktop).
  
- **Fact Tables**:
  - `fact_forecast_monthly`: Forecasted demand data to enhance satisfaction and reduce warehouse costs.
  - `fact_sales_monthly`: Sales data, formatted similarly to the forecast table.

- **Cost Tables**:
  - `freight_cost`, `gross_price`, `manufacturing_cost`, `pre_invoice_deductions`, `post_invoice_deductions`: Detailing costs and deductions per market, product code, and year.



## Data Import and Modeling
Data was imported from MySQL, with a Snowflake schema for optimal performance. Following good modeling practices ensured a reliable foundation for visuals.
