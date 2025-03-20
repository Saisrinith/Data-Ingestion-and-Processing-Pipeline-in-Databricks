# Data-Ingestion-and-Processing-Pipeline-in-Databricks
This Azure Data Factory pipeline automates data validation and processing. It starts when a new file is detected in the Azure Blob Storage landing folder. A Databricks notebook then validates the file against a schema in Azure SQL. If the data passes validation, it moves to the staging folder; if not, it goes to the rejected folder for review. The pipeline ensures efficient data handling and quality control, leveraging Databricks for processing and Azure SQL for schema management.

![image](https://github.com/user-attachments/assets/429792a1-7fe0-4c66-87ad-1aa506bef03f)
