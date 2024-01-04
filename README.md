# Azure-Warehousing-Application
Azure Application, accessible in the Azure Marketplace.
The application automatically deploys a Data Warehousing architechture via ARM template. 
it includes a template for a Userinterface for inserting parameters.

Components:
Logical Microsoft SQL-Server
Microsofts famous AdventureWorks Database as an example for a operational Database
SQL Database for the Datawarehouse
finished Implementation of an Azure Data Factory with an automatic ETL-Process between these two databases, performing a Full-load of the Data warehouse

Automatic Processes:
1. Deployment of the SQL Server
2. Deployment of the SQL Databases
3. data loading for operatinal and analytical database via Azure data Factory







