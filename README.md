# Introduction
This repo contains Databricks Notebook and Power BI report which helps to analyze Popular Movies in IMDB. It is based on data from following sources:
* [IMDb Datasets](https://datasets.imdbws.com/)
* [IMDB](https://www.imdb.com/) web-scapping for getting Top/Popular movies
* [Box Office Mojo](https://www.boxofficemojo.com) web-scapping for getting BOX Office details of few movies.

# IMDB ELT Databricks
The notebook does the ELT process in Databricks. It can be executed in [Databricks Community Edition](https://docs.databricks.com/getting-started/community-edition.html).

# IMDB Popular Movie Analysis
This contains the Power BI visualization based on the gold view in Databricks. Pass the Databricks Cluster ID and Workspace ID (found in URL) as parameter values for refreshing the report, after the notebook is executed in Databricks. The final report is also available [here](https://app.powerbi.com/view?r=eyJrIjoiZTllYjVkN2ItZDI2MS00N2VjLThhYTEtN2M5ZGVkYzNjODA2IiwidCI6IjgxNDQwMDExLTVhZTQtNDhmNy1hY2YwLTg2ZjBkNWQ2YTFlMiJ9).