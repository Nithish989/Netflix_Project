# Netflix End-to-End Azure Data Engineering Project

## Overview
Built a metadata-driven data engineering pipeline for Netflix dataset using 
Delta Live Tables and Unity Catalog on Azure Databricks.

## Architecture

<img width="1639" height="960" alt="image" src="https://github.com/user-attachments/assets/ed3fc42a-aed3-4fe1-8d79-c750ff91324f" />





## Tech Stack
- Azure Data Factory (ADF) — metadata-driven dynamic pipeline
- Azure Data Lake Storage Gen2 (ADLS) — Bronze, Silver, Gold containers
- Azure Databricks — Auto Loader and Delta Live Tables (DLT)
- Unity Catalog — centralized data governance and security
- Delta Lake — incremental data processing

## What I Built
- Dynamic ADF pipeline using Web, Validation, ForEach, and Copy activities
- Auto Loader for incremental data ingestion into Bronze layer
- Delta Live Tables for scalable Silver and Gold layer processing
- Unity Catalog metastore for data governance

## Screenshots
### ADF Pipeline


<img width="931" height="476" alt="image" src="https://github.com/user-attachments/assets/f6509068-eb68-46b2-b83e-10d639b86ad2" />




### Unity Catalog Metastore



<img width="986" height="529" alt="image" src="https://github.com/user-attachments/assets/00c24d33-3c83-46fd-8072-3616fa7a8903" />



### Azure Resources

<img width="1054" height="484" alt="image" src="https://github.com/user-attachments/assets/8ec10669-b2d5-4a11-9354-77e437ce2ed9" />

