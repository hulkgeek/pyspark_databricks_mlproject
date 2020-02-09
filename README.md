## Exercise Overview
In this exercise we will play with Spark Datasets & Dataframes, some Spark SQL, and build a couple of binary classifiaction models using Spark ML (with some MLlib too).

The set up and approach will not be too dissimilar to the standard type of approach you might do in Sklearn. Spark has matured to the stage now where for 90% of what you need to do (when analysing tabular data) should be possible with Spark dataframes, SQL, and ML libraries. This is where this exercise is mainly trying to focus.

Feel free to adapt this exercise to play with other datasets readily availabe in the Databricks enviornment (they are listed in a cell below).

## Getting Started
To get started you will need to create and attach a databricks spark cluster to this notebook. This notebook was developed on a cluster created with:

- Databricks Runtime Version 4.0 (includes Apache Spark 2.3.0, Scala 2.11)
- Python Version 3

## Dataset at Databricks
dbfs:/databricks-datasets/adult/adult.data
