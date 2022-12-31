# IMDB ELT Databricks
The notebook does the ELT process in Databricks, which downloads the IMDB and BOX Office data from csv's as well as web scapping and build the final gold table. It can be executed in [Databricks Community Edition](https://docs.databricks.com/getting-started/community-edition.html).

# IMDB Popular Movie Analysis
This contains the Power BI visualization based on the gold table in Databricks. Pass the Databricks Cluster ID and Workspace ID (found in URL) as parameter values for refreshing.