# Big Data Sales Analysis using PySpark

## Project Overview
This project focuses on analyzing large-scale sales data using PySpark to demonstrate scalable data processing and business-oriented analysis. The objective is to identify sales and profit trends across regions and product categories, and convert data findings into actionable business insights.

## Business Problem
Organizations generate massive amounts of sales data, but raw data alone does not help decision-making. The key business challenge is to understand:
- Which regions contribute the most to sales and profit
- Which product categories drive profitability
- Which areas cause revenue leakage or low margins

This project addresses these questions using Big Data processing techniques.

## Dataset Description
The dataset used is a Superstore sales dataset containing transactional sales records. Key attributes include:
- Order Date
- Region
- Category and Sub-Category
- Sales
- Profit

The dataset is large enough to justify the use of PySpark for scalable analysis.

## Tools & Technologies
- Python  
- PySpark  
- Apache Spark  
- Jupyter Notebook  
- VS Code  

## Project Workflow
- **Phase 0: Environment Setup**  
  Python version management, PySpark installation, Java configuration, and Spark session setup.

- **Phase 1: Data Understanding**  
  Data loading, schema inspection, column analysis, and null checks.

- **Phase 2: Data Cleaning & Preparation**  
  Column selection, date parsing, and creation of an analysis-ready dataset.

- **Phase 3: Big Data Processing**  
  Aggregations and transformations including:
  - Overall sales and profit
  - Region-wise analysis
  - Category and sub-category performance
  - Region–category combinations
  - Ranking top-performing segments

- **Phase 4: Business Insights**  
  Interpretation of analytical results to derive meaningful business conclusions.

## Key Business Insights
- The **West and East regions** are the strongest contributors to both sales and profit.
- **Technology** is the most profitable category and acts as the primary growth driver.
- **Office Supplies** performs well in sales volume but generates slightly lower profit than Technology.
- **Furniture** consistently shows low or negative profitability, indicating the need for pricing, cost, or logistics optimization.
- Other regions contribute moderately but do not significantly impact strategic decision-making.

## Conclusion
This project demonstrates how PySpark can be used to efficiently analyze large datasets and extract valuable business insights. By identifying high-performing regions and categories, as well as underperforming areas, businesses can make data-driven decisions to improve profitability and optimize growth strategies.
