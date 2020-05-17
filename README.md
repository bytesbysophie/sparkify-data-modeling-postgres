# Data Modeling & ETL for the Music Streaming Service Sparkify

## Table of Contents
1. [Installation](#Installation)
2. [Project Motivation and Description](#Project-Motivation)
3. [File Descriptions](#File-Descriptions)
4. [Authors and Acknowledgements](#Authors-Acknowledgements)

## Installation <a name="Installation"></a>
Following libraries must be installed for running the notebook locally:

    - pandas
    - psycopg2

Additionally, a local postgres installation is needed with the following setup (alternatively you can change the connection details in create_tables.py to match your existing setup):

    - host: 127.0.0.1
    - dbname: studentdb
    - user=student
    - password=student

## Project Motivation and Description <a name="Project-Motivation"></a>

This project aims to model log data and set up an ETL process for the fictional music streaming service Sparkify using PySpark.
In more detail, the analytics team should get enabled to understand what songs users are listening to.

For this project a small subset of the user log data has been provided.

The key parts of the project are:
* Creating a data base schema 
* Building an ETL pipeline to insert data into the schema and make it available for analysis

## File Descriptions <a name="File-Descriptions"></a>

* data/: Directoty for the provided log data subset and corresponding song data 
* create_tables.py: This script creates the database as well as all tables that have been defined in sql_queries.py
* etl.ipynb: Here, the etl process is desigend step by step as a prototype for the final pipeline
* etl.py: Implementation of etl pipeline
* sql_queries.py: This script contains all SQL statements needed for creating tables and inserting data
* test.ipynb: With this notebook, the result of the etl process can be tested

## Authors and Acknowledgements <a name="Authors-Acknowledgements"></a>
This project has been implemented as part of the Udacity Data Scientist Nanodegree program. The data has been provided by Udacity accordingly as well as the project structure/ file templates.
