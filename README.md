# Netflix_Azure_DataEngineering_Project

This repository contains the implementation of a modern data lakehouse architecture using Azure services, Databricks, and Delta Lake. The project demonstrates an end-to-end data pipeline that processes data through a medallion architecture (Raw → Bronze → Silver → Gold).

**Key Technologies**<br/><br/>
**Azure Data Factory**: For orchestrating data movement from GitHub to ADLS<br/>
**Azure Data Lake Storage Gen2**: For storing data in different layers<br/>
**Databricks**: For data processing and transformation<br/>
**Delta Lake**: For reliable data storage and time travel capabilities<br/>
**Delta Live Tables**: For declarative pipeline development to the Gold layer<br/>
