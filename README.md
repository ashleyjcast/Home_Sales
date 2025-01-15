# Home_Sales
Module 22 Challenge 

##Home Sales Analysis with PySpark

## Overview

This project uses PySpark and SparkSQL to analyze home sales data, leveraging Spark's distributed computing capabilities to calculate key metrics. The assignment includes working with temporary views, caching, partitioning data, and optimizing query runtimes.

## Project Steps

# Data Preparation:

- Import the home_sales_revised.csv dataset into a Spark DataFrame.

- Create a temporary SQL view from the DataFrame.

# Key Queries:

- Calculate the average price of four-bedroom houses sold each year.

- Determine the average price of homes with three bedrooms and three bathrooms for each year they were built.

- Find the average price of homes with three bedrooms, three bathrooms, two floors, and at least 2,000 square feet for each year they were built.

- Compute the average price of homes per "view" rating with an average price ≥ $350,000 and record the runtime.

# Optimization:

- Cache the temporary table and rerun the query to compare runtime with and without caching.

- Partition the data by date_built and store it in Parquet format.

- Create a temporary table from the partitioned data and rerun the query.

- Uncache the table and verify that it has been uncached.

# Tools and Technologies

- PySpark: For data processing and querying.

- SparkSQL: To perform SQL-like queries on the data.

- Google Colab: Development environment.

