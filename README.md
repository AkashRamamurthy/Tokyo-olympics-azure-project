# Azure End-to-End Data Engineering Project Tokyo Olympics
This project demonstrates an end-to-end data engineering pipeline built using various Azure services. The goal was to create a streamlined workflow for extracting, transforming, and loading data (ETL) from an API, performing transformations, and ultimately visualizing insights using Azure Synapse Analytics. The project serves as a practical, hands-on demonstration of Azure's capabilities in the data engineering space.

##Project Overview:
In this project, I extracted data from an API using Azure Data Factory, loaded the raw data into Azure Data Lake Storage, transformed the data using Azure Databricks (leveraging Apache Spark), and then loaded the cleaned data into a transformed data lake. Finally, I used Azure Synapse Analytics to run SQL queries and visualize the insights.

##Data Source:
The dataset used was sourced from Kaggle's 2021 Tokyo Olympics data, containing information about over 11,000 athletes, 47 disciplines, and 743 teams. The raw data files included information on athletes, coaches, medals, and teams, all converted into CSV format for easier processing.

## Technologies Used:
### Azure Data Factory for data integration and creating pipelines.
### Azure Data Lake Storage Gen2 for storing raw and transformed data.
### Azure Databricks for performing data transformations using Apache Spark.
### Azure Synapse Analytics for SQL-based data analysis and visualization.
### Apache Spark for efficient data transformation and processing.
### Azure Key Vault for securely storing credentials and secrets.

## Steps Involved:
#### Data Ingestion: Using Azure Data Factory to copy data from various sources (GitHub, CSV, HTTP) into Azure Data Lake Storage.
#### Data Transformation: Using Apache Spark in Azure Databricks to clean and transform the data, preparing it for analysis.
#### Data Storage: Storing transformed data in Azure Data Lake Gen2.
#### Data Analysis: Running SQL queries and performing analytics using Azure Synapse Analytics.
#### Visualization: Using tools like Tableau to visualize the insights from the data and create dashboards.

## Key Learnings:
Throughout this project, I gained valuable hands-on experience working with various Azure cloud services and integrating them into a cohesive data engineering pipeline. The project allowed me to explore best practices for building scalable and secure data pipelines in Azure, especially when dealing with real-world datasets.

## Future Enhancements:
Automating the pipeline for real-time data processing.
Integrating Power BI for advanced visualizations and real-time dashboarding.
Extending the project by incorporating machine learning models using Azure Machine Learning.

## Conclusion:
This project is exciting opportunity to explore the power of Azure's cloud-based tools in the context of a large-scale data engineering workflow. I encourage anyone interested in cloud data engineering to explore this project, try out the steps, and enhance the pipeline based on their specific use cases.
