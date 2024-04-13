# Build a Data Pipeline with abt, Airflow and Snowflake

This repositories demonstrates a data pipeline for data transformation, scheduling, and analysis using dbt, Apache Airflow and Snowflake.

Tutorial Link: https://quickstarts.snowflake.com/guide/data_engineering_with_apache_airflow

## Overview

1. Environment Setup:
    - Utilize Astro CLI and Docker to create Apache Airflow environment for workflow orchestration.
2. Data Storage:
    - Create a database and tables in Snowflake to store the data.
3. Data Transformation:
    - Set up dbt project to define data models that generate Snowflake views for data analysis.
4. Workflow Orchestration:
    - Integrate the dbt project with Airflow using Cosmos's dbtDAG.
    - Incorporate Snowpark into Airflow's DAG for data retrieval and analysis
5. Data Seeding and Analysis:
    - dbtDAG seeds data from CSV files into designated Snowflake tables and create Snowflake views for data analysis.
    - Perform a simple analysis with Snowpark DAG

## Challenges and Solutions
There is an issue with this tutorial where the version of Airflow used in this tutorial has an incompatibility issue with pendulum package. This issue can be resolved by upgrade to a higher Airflow version. (ref: https://stackoverflow.com/questions/77703615/pendulum-tz-timezoneutc-typeerror-module-object-is-not-callable)


## Learning Outcomes
With this tutorial, I gain a solid understandif of the ETL process with dbt, Airflow and Snowflake. It gives me an opportunity to explore various data engineering tools and techniques valuable for aspiring data engineers.




    
