# Retail Sales & Profitability Analysis | Power BI

**An interactive business intelligence project analyzing retail sales, profitability, customer performance, product trends, discount strategies, and shipping operations.**

## 1. Project Overview

This project uses Microsoft Power BI to transform retail transaction data into an interactive business intelligence solution that supports data-driven decision-making.

The report explores sales performance, profitability, customer and product contributions, discount patterns, and order-to-shipment processing time. It presents these areas through six interactive dashboards designed to help users investigate business performance from multiple perspectives.

The project demonstrates practical data analytics skills in data preparation, data modeling, DAX calculations, KPI development, dashboard design, and business performance analysis.

## 2. Business Objectives

The key objectives of this project are to:

- Monitor overall sales, profit, order volume, and profit margin.
- Analyze sales trends and changes in performance over time.
- Compare product categories and sub-categories.
- Evaluate customer and customer segment contributions to sales and profitability.
- Investigate the relationship between discounts and profitability.
- Examine order-to-shipment processing time.
- Develop interactive dashboards that make business performance easier to understand.
- Identify areas requiring further business investigation.

## 3. Data Source

- **Dataset:** Superstore Sales Dataset
- **Source:** [Kaggle — Superstore Dataset Final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **File:** `data/Superstore Sales Dataset.csv`
- **Format:** CSV

The dataset contains retail order information relating to customers, products, sales, quantities, discounts, profits, geographical regions, and shipping.

The dataset was imported into Power BI and prepared for analysis. Power Query transformations, data modeling, DAX measures, and calculated columns were used to support the analytical requirements.

**Attribution:** Credit for the original dataset belongs to its respective creator and source. This project focuses on the data preparation, analytical calculations, data modeling, dashboard development, and business analysis.


## 4. Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Interactive dashboards and business intelligence reporting |
| Power Query | Data cleaning and transformation |
| DAX | Measures, calculated columns, and analytical calculations |
| Data Modeling | Relationships between tables and analytical model development |
| CSV | Source data format |
| GitHub | Project documentation, version control, and portfolio presentation |

## 5. Dashboard Gallery

This project contains six dashboards, each focusing on a different aspect of retail business performance.

### 5.1 Executive Overview

Provides a high-level summary of business performance through key performance indicators and summary visualizations.

**Key analytical areas:**
- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Monthly sales trends
- Sales by product category
- Profit by customer segment
- Profit by category
- Key operational insights

![Executive Overview Dashboard](screenshots/Executive-Overview.png)

### 5.2 Trends & Products Analysis

Explores sales trends over time and compares product performance to identify patterns and potential opportunities.

**Key analytical areas:**
- Sales trends over time
- Product category comparisons
- Product and sub-category performance
- Identification of strong and weak product areas

![Trends and Products Analysis](screenshots/Trend-products-Analysis.png)

### 5.3 Customer & Segment Analysis

Evaluates how different customer segments contribute to sales and profitability.

**Key analytical areas:**
- Customer segment comparisons
- Sales and profit contributions
- Segment-level performance
- Customer purchasing patterns

![Customer and Segment Analysis](screenshots/Customer-Segment-Analysis.png)

### 5.4 Customer Performance

Focuses on individual customer performance and their contribution to business results.

**Key analytical areas:**
- Customer sales performance
- Customer profitability
- Customer contribution to overall results
- Identification of high-value customers

![Customer Performance](screenshots/Customer-Performance.png)

### 5.5 Discount & Profitability Analysis

Investigates discounting patterns and their relationship with sales and profitability.

**Key analytical areas:**
- Profitability across discount levels
- Sales and profit comparisons
- Identification of potentially unprofitable discount patterns
- Opportunities for further pricing strategy investigation

![Discount and Profitability Analysis](screenshots/Discount-Profitability-Analysis.png)

### 5.6 Operations & Shipping Performance

Examines order-to-shipment processing time using the available order and ship dates.

**Key analytical areas:**
- Average order-to-ship processing time
- Orders taking more than four days between order and shipment
- Shipping-related operational comparisons
- Indicators of potential processing inefficiencies

![Operations and Shipping Performance](screenshots/Operations-Shipping-Performance.png)

**Data limitation:** The dataset contains order dates and ship dates but does not provide actual delivery dates or promised delivery dates. Therefore, this analysis measures the time between order placement and shipment; it does not independently establish whether an order was delivered late.

## 6. Key Performance Indicators

The project uses measures and calculations to support business performance analysis.

| KPI | Purpose |
|---|---|
| Total Sales | Measures total sales revenue |
| Total Profit | Measures total recorded profit |
| Total Orders | Counts distinct orders |
| Total Customers | Counts distinct customers |
| Average Order Value | Measures sales value per order |
| Profit Margin | Measures profit relative to sales |
| Total Quantity | Measures total quantity sold |
| Sales per Customer | Measures average sales per customer |
| Orders per Customer | Measures average orders per customer |
| Average Order-to-Ship Time | Measures average days between order placement and shipment |

Additional measures support year-over-year comparisons, customer profitability analysis, and shipping-related analysis.

## 7. Data Preparation & Modeling

The project followed a structured analytics workflow:

1. **Data import:** Imported the source CSV dataset into Power BI Desktop.
2. **Data inspection:** Reviewed available columns and data types.
3. **Data preparation:** Used Power Query to clean and transform data as required.
4. **Date modeling:** Created a date table to support time-based analysis.
5. **Relationship development:** Connected the date table to the retail dataset using the order date.
6. **DAX development:** Created measures and calculated columns to support KPIs and analytical requirements.
7. **Visualization:** Designed dashboards using KPI cards, charts, filters, and supporting insights.
8. **Business analysis:** Used the resulting dashboards to explore performance patterns and potential areas for further investigation.

## 8. DAX Measures & Calculations

Examples of measures and calculations developed for this project include:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Average Order Value
- Profit Margin
- Total Quantity
- Sales per Customer
- Orders per Customer
- Customer Profit Margin
- Previous-Year Sales
- Sales Growth Percentage
- Previous-Year Quantity
- Quantity Growth Percentage
- Shipping Days
- Average Order-to-Ship Time
- Orders Shipped After Four Days

Distinct-count calculations are used where appropriate for orders and customers. Additional measures support profitability, customer analysis, and time-based comparisons.

## 9. Interactivity & User Experience

The report uses interactive filters and visual interactions to allow users to explore performance from different perspectives.

Depending on the dashboard, users can analyze results by dimensions such as:

- Year
- Region
- Customer Segment
- Product Category
- Other available fields in the dataset

A consistent visual design and navigation approach helps users move between report pages and investigate specific business questions.

## 10. Key Business Questions

This project supports the investigation of questions such as:

1. How are sales and profits changing over time?
2. Which product categories contribute most to sales and profit?
3. Which customer segments contribute most to profitability?
4. Which customers generate substantial sales or profit?
5. How do discount levels relate to profitability?
6. How long does it typically take for orders to be shipped after placement?
7. Which products, customer groups, or operational areas may require further investigation?

The answers depend on the data and report filter selections. Patterns observed in the report should be interpreted in context and should not automatically be treated as proof of causation.

## 11. Repository Structure

The GitHub repository is organized as follows:

```text
Retail-Sales-Profitability-PowerBI/
│
├── Power-bi/
│   ├── README.md
│   └── Retail_Sales_Profitability_Business_Performance.pbix
│
├── data/
│   ├── README.md
│   └── Superstore Sales Dataset.csv
│
├── screenshots/
│   ├── Customer-Performance.png
│   ├── Customer-Segment-Analysis.png
│   ├── Discount-Profitability-Analysis.png
│   ├── Executive-Overview.png
│   ├── Operations-Shipping-Performance.png
│   ├── Trend-products-Analysis.png
│   └── README.md
│
└── README.md
```


## 12. How to Explore the Project

1. Open the Power BI report in `Power-bi/` using Microsoft Power BI Desktop.
2. Start with the Executive Overview dashboard.
3. Navigate through the remaining dashboard pages.
4. Use the available filters and visual interactions to explore different business dimensions.
5. Review the images in `screenshots/` for a quick preview of the report.
6. Refer to the source dataset in `data/`, subject to its licensing and usage terms.

## 13. Skills Demonstrated

This project demonstrates practical skills in:

- Data cleaning and transformation
- Power Query
- Data modeling and relationships
- DAX measures and calculated columns
- KPI development
- Time-based analysis
- Sales and profitability analysis
- Customer and product performance analysis
- Discount analysis
- Shipping operations analysis
- Interactive dashboard development
- Data visualization and storytelling
- Business intelligence reporting
- GitHub documentation and project organization

## 14. Business Value

The report provides a foundation for monitoring business performance, investigating sales and profitability patterns, comparing customer and product results, and examining order-to-shipment processing time.

These analyses can support further investigation into pricing decisions, product performance, customer contribution, and operational efficiency. Business actions should be based on validated findings and the wider business context.

## 15. Author

**Joseph Njoroge**

Aspiring Data Analyst | Business Intelligence Enthusiast

This project forms part of my data analytics portfolio and demonstrates my ability to prepare data, develop analytical calculations, design interactive dashboards, and communicate business performance through data visualization.

**Areas of interest:** Data Analytics, Business Intelligence, Sales Analytics, Customer Analytics, and Business Performance Reporting.

---

Thank you for exploring this project. Feedback and suggestions for improvement are welcome.
