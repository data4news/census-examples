# census-examples

This repo contains examples of how to access US Census data.

* [tidycensus-example.ipynb](tidycensus-example.ipynb) and *   [tidycensus-example.qmd](tidycensus-example.qmd) show how to access US Census data using the `tidycensus` package in R. It covers obtaining an API key, retrieving data, and creating maps. Qmd stand for Quarto Markdown (which is similar to jupyter notebook but more native to R).

*   [census-example.ipynb](census-example.ipynb) shows how to access US Census data using the `census` package in Python. Same idea, different package from the above tidycensus example.

*   [census-geocode.ipynb](census-geocode.ipynb) - This notebook shows how to geocode addresses using the US Census Geocoder API and the `censusgeocode` package in Python. It helps you place **latitude/longitude data** into the context of census geography.

*   [census-spatial-joins.ipynb](census-spatial-joins.ipynb) - This notebook shows how to perform spatial joins between census tracts and other geospatial datasets using GeoPandas. It includes examples of different types of spatial joins and how to analyze the results.
