# patient stream analytics
An End-to-End Real-Time Healthcare Data Pipeline using Azure Event Hubs, Databricks, Delta Lake, and Synapse Analytics

Tech Stack: Azure Event Hubs Azure Databricks (PySpark) Azure Data Factory (orchestration) Azure Synapse Analytics Power BI (visualization)

WorkFlow: --> Real-time data streaming with Azure Event Hubs + Kafka --> Ingestion & transformations with Databricks + PySpark --> Implementing the Medallion Architecture (Bronze, Silver, Gold) --> Schema evolution in Delta Lake --> SCD Type 2 handling in Gold layer --> Building a Star Schema (Fact & Dimension tables) --> Loading data into Azure Synapse SQL Pool --> Connecting Power BI for reporting
