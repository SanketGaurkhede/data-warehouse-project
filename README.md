Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture
<img width="1543" height="800" alt="image" src="https://github.com/user-attachments/assets/93ed77b9-3bdb-4c2d-8409-ff40f4d9ac2b" />


Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
📖 Project Overview
This project involves:

Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
Data Modeling: Developing fact and dimension tables optimized for analytical queries.
Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

SQL Development
Data Architect
Data Engineering
ETL Pipeline Developer
Data Modeling
Data Analytics

🚀 Project Requirements
Building the Data Warehouse (Data Engineering)
Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues prior to analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
BI: Analytics & Reporting (Data Analysis)
Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                    # Raw datasets used for the project
│
├── docs/                        # Project documentation and architecture details
│   ├── etl.drawio               # ETL techniques and methods
│   ├── data_architecture.drawio # Project architecture
│   ├── data_catalog.md          # Dataset catalog and metadata
│   ├── data_flow.drawio         # Data flow diagram
│   ├── data_models.drawio       # Data models / star schema
│   └── naming-conventions.md    # Naming standards
│
├── scripts/                     # SQL scripts for ETL and transformations
│   ├── bronze/                  # Extract and load raw data
│   ├── silver/                  # Clean and transform data
│   └── gold/                    # Create analytical models
│
├── tests/                       # Data quality and test scripts
│
├── README.md                    # Project overview and instructions
├── LICENSE                      # License information
├── .gitignore                   # Files ignored by Git
└── requirements.txt             # Project dependencies
```

🔐 License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

🌟 About Me

Hi there! I'm **Sanket Gaurkhede**, an IT professional, **AWS DevOps Engineer, and Data Engineer** with hands-on experience in cloud infrastructure, automation, and data engineering.

I'm passionate about building scalable and reliable data solutions and continuously expanding my skills in **SQL, Python, AWS, Data Engineering, Data Warehousing, ETL, and Cloud Technologies**.

Through my projects, I enjoy working with technologies such as **SQL Server, AWS, Terraform, Docker, Git, and Data Engineering tools** while following industry best practices for data architecture, ETL pipelines, data modeling, and analytics.

🚀 Areas of Interest

- Data Engineering
- SQL & Data Warehousing
- ETL & Data Pipelines
- AWS Cloud
- Data Modeling & Analytics
- Infrastructure as Code
- DevOps & Cloud Automation

📫 Let's Connect

I'm always interested in learning, collaborating, and connecting with professionals in **Cloud, Data Engineering, and Analytics**.
