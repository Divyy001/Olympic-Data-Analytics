# Olympic-Data-Analytics
Overview

The "Olympic Data Analysis" project is designed to provide insights and visualizations of historical Olympic Games data. The project leverages various Azure cloud services to create a scalable and efficient data pipeline for ingesting, processing, and analyzing data.
Project Architecture

    Data Ingestion: Azure Data Factory is used to ingest raw Olympic data from a GitHub repository into Azure Data Lake Gen 2.
    Data Processing: PySpark on Azure Databricks is employed to transform and clean the data, making it ready for analysis.
    Data Storage: The cleaned data is stored back in Azure Data Lake Gen 2 for further processing and querying.
    Data Querying: Azure Synapse Analytics is used to query the processed data, enabling fast and efficient retrieval of insights.
    Data Visualization: Power BI is used to create dashboards and visualizations, offering an intuitive way to explore the results of the analysis.

Features

    Data Ingestion: Automated data ingestion pipeline using Azure Data Factory.
    Data Transformation: Data cleaning and transformation using PySpark, including handling missing values, normalization, and aggregation.
    Data Storage: Scalable and secure storage of transformed data in Azure Data Lake Gen 2.
    Data Querying: Fast querying capabilities with Azure Synapse Analytics for detailed insights.
    Visualization: Interactive dashboards in Power BI for exploring historical Olympic data.

Tools & Technologies

    Azure Data Factory: For orchestrating data ingestion and ETL workflows.
    Azure Databricks (PySpark): For large-scale data processing and transformation.
    Azure Data Lake Gen 2: For secure and scalable data storage.
    Azure Synapse Analytics: For querying and analyzing large datasets.
    Power BI: For creating interactive visualizations and dashboards.
