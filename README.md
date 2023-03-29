# Data Engineering Capstone Project

## Overview
The purpose of this data engineering capstone project is to give a chance to combine what I've learned throughout the program.

In this project, I defined the scope and data for the project; work with four datasets to complete the project. The main dataset include data on immigration to the United States, and supplementary datasets will include data on airport codes, U.S. city demographics, and temperature data.

## Project Summary
In this project data gathered from four datasets with different sources for analysing US immigration data in a simple star schema. The main aim is to provide analytics to answer business questions which can be analyze and provide insight into the pattern of immigration. The analysis questions can be answered based on the data model using simple joins. Spark was used for the ETL pipeline and The final data is stored in parquet files for analysis.

## Project Datasets:

- I94 Immigration Data: This data comes from the US National Tourism and Trade Office. 
- World Temperature Data: This dataset came from Kaggle.
- U.S. City Demographic Data: This data comes from OpenSoft.
- Airport Code Table: This is a simple table of airport codes and corresponding cities.

## Project Data Model
The chosen data model was the star schema, That model was the chosen one because it allows great performance, and it also allows users to write simple queries joining the fact and dimension tables in order to achieve the analytical dataset they need and perform BI solutions.

![the data model](https://github.com/israahamdy/DataEngineering-Capstone-Project/blob/main/capstone%20data%20model.jpg)
