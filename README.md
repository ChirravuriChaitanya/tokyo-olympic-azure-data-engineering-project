# tokyo-olympic-azure-data-engineering-project
tokyo-olympic-azure-data-engineering-project


Extracting Tokyo_Olympic Data from Kaggle


-  Push the dataset into Github repo
-  Create Resource group in Azure fron ADF, Databricks, Data Lake(Storage Account) and Synapse
-  In ADF, create pipelines for each table to extract data from github repo url configuring HTTP self-hosted runtime integration and load in the Data Lake 
-  After successful extraction of data from the github repo, using Databricks ,configuring , mounting datalake on databricks implemented required transformations using Pyspark
-  Then, stored the transformed and cleaned data in the data lake.
-   Now, connected Synapse to the Databricks and stored as tables to perform SQL queries and automatically visualize the graphs and charts.