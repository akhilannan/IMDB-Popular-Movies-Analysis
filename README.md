# Introduction
This repository contains a Databricks Notebook and a Power BI report that help you analyze the popularity of movies on IMDB. The analysis is based on the following data sources:
* [IMDb Datasets](https://datasets.imdbws.com/), which provide various information about movies, such as ratings, genres, cast, crew, etc.
* [IMDB](https://www.imdb.com/) website, which is scraped to obtain the list of top and popular movies according to different criteria, such as user ratings, votes, etc.
* [Box Office Mojo](https://www.boxofficemojo.com) website, which is scraped to obtain the overall box office details of some movies.

# IMDB ELT Databricks
The notebook performs the extract, load and transform (ELT) process on the data sources. It can be executed in [Databricks Community Edition](https://docs.databricks.com/getting-started/community-edition.html).

# IMDB Popular Movie Analysis
This report visualizes the results of the analysis based on the gold view in Databricks. To refresh the report, you need to pass the Databricks Cluster ID and Workspace ID (found in the URL) as parameter values after running the notebook in Databricks. The final report is also available [here](https://app.powerbi.com/view?r=eyJrIjoiZTllYjVkN2ItZDI2MS00N2VjLThhYTEtN2M5ZGVkYzNjODA2IiwidCI6IjgxNDQwMDExLTVhZTQtNDhmNy1hY2YwLTg2ZjBkNWQ2YTFlMiJ9).