ETL and Data Warehousing Project for Fudgemart

**Overview**
This project demonstrates an ETL pipeline and data warehousing workflow for a hypothetical shop, Fudgemart, leveraging Snowflake as the data warehouse and dbt for transformations. The goal is to analyze various business scenarios, including customer reviews, product reviews, and customer repeat-buy behavior, using Power BI for reporting.


**Features**
Data Source: CSV-based database for Fudgemart, simulating real-world data.
Data Transformation: YAML-defined rules processed using dbt.
Data Warehousing: Snowflake stores and organizes the data, enabling robust analytics.
Visualization: Power BI dashboards provide interactive and actionable insights.


**Project Structure**
Files and Directories
/dbt_project: Contains dbt project files for the ETL process.
models/: dbt models that define the transformations applied to raw data.
seeds/: Source data files in CSV format.
dbt_project.yml: Configuration file for dbt setup and project settings.
/data: Raw CSV files representing Fudgemart’s transactional and operational data.
/visualizations: Power BI dashboard file (Fudgemart_Insights.pbix) connected directly to Snowflake.
README.md: Documentation for the project.


**Workflow**
Data Extraction:
Source data is stored in CSV files, representing Fudgemart’s operational data, including customer details, product reviews, and transaction history.


**Data Transformation:**
YAML configuration defines data transformation logic.
dbt processes the transformations, applying cleaning, enrichment, and structuring steps for analytics-ready data.


**Data Loading:**
Transformed data is loaded into Snowflake tables optimized for reporting and querying.


**Visualization**:
Power BI connects directly to Snowflake for live querying and reporting.
Dashboards include KPIs, trends, and customer behavior analysis.

**Dashboard Features**
The Power BI dashboard provides actionable insights, including:
KPIs: Metrics on customer satisfaction, product performance, and revenue growth.
Customer Behavior: Analysis of repeat purchases and buying patterns.
Product Reviews: Trends in product performance based on customer feedback.
Dynamic Filters: Slicers for exploring data by time, product category, and region.

**Here are some of the screenshots of the PoweBI Visualizations:**
![image](https://github.com/user-attachments/assets/85869d7c-a1d4-4929-bcc7-8828cdf67684)
![image](https://github.com/user-attachments/assets/77a1e211-1a84-4274-b3ea-bc7ef51bb8e1)
