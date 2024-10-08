# Olympic-Data-Analytics
Overview

The "Olympic Data Analysis" project is designed to provide insights and visualizations of historical Olympic Games data. The project leverages various Azure cloud services to create a scalable and efficient data pipeline for ingesting, processing, and analyzing data.

Project Architecture

![image](https://github.com/user-attachments/assets/8ec565c3-49bf-4b2d-a9ad-73d835fd4a24)

- Data Ingestion: Azure Data Factory is used to ingest raw Olympic data from a GitHub repository into Azure Data Lake Gen 2.
- Data Processing: PySpark on Azure Databricks is employed to transform and clean the data, making it ready for analysis.
- Data Storage: The cleaned data is stored back in Azure Data Lake Gen 2 for further processing and querying.
- Data Querying: Azure Synapse Analytics is used to query the processed data, enabling fast and efficient retrieval of insights.
- Data Visualization: Power BI is used to create dashboards and visualizations, offering an intuitive way to explore the results of the analysis.

Features

- Data Ingestion: Automated data ingestion pipeline using Azure Data Factory.
- Data Transformation: Data cleaning and transformation using PySpark, including handling missing values, normalization, and aggregation.
- Data Storage: Scalable and secure storage of transformed data in Azure Data Lake Gen 2.
- Data Querying: Fast querying capabilities with Azure Synapse Analytics for detailed insights.
- Visualization: Interactive dashboards in Power BI for exploring historical Olympic data.

Tools & Technologies

- Azure Data Factory: For orchestrating data ingestion and ETL workflows.
- Azure Databricks (PySpark): For large-scale data processing and transformation.
- Azure Data Lake Gen 2: For secure and scalable data storage.
- Azure Synapse Analytics: For querying and analyzing large datasets.
- Power BI: For creating interactive visualizations and dashboards.

DashBoard

![image](https://github.com/user-attachments/assets/2faa68f7-dd7c-4aeb-bcd2-b4ed062f233c)


1. Distribution of Medals by Gender
2. Country of Medals-->i)sort by count of Medal
		           ii) conditional formatting
3. Distribution of Medals among Top 10 Players
4. Distribution of Medals by Sports (top 20)
5. Distribution of Medals by Season and Country 
6. Count of Medals by Age
7. Count of Name by Year and Gender.
