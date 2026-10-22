# Truck Delay Classification

The primary objective of this project is to create an end-to-end machine learning pipeline for truck delay classification.

## Overview
The project addresses a critical challenge faced by the logistics industry. Delayed truck shipments not only result in increased operational costs but also impact customer satisfaction. Timely delivery of goods is essential to meet customer expectations and maintain the competitiveness of logistics companies. By accurately predicting truck delays, logistics companies can:
- Improve operational efficiency by allocating resources more effectively
- Enhance customer satisfaction by providing more reliable delivery schedules
- Optimize route planning to reduce delays caused by traffic or adverse weather conditions
- Reduce costs associated with delayed shipments, such as penalties or compensation to customers

## Data
The project involves the following data tables:

- City Weather: Weather data for various cities
- Routes: Information about truck routes, including origin, destination, distance, and travel time
- Drivers: Details about truck drivers, including names and experience
- Routes Weather: Weather conditions specific to each route
- Trucks: Information about the trucks used in logistics operations
- Traffic: Traffic-related data
- Truck Schedule: Schedules and timing information for trucks

_Data is not included in this repository._

## Approach
- Introduction to End-to-End Pipelines: ○ Understanding the fundamental concepts and importance of end-to-end pipelines
- Database Setup: ○ Creating AWS RDS instances for MySQL and PostgreSQL ○ Setting up MySQL Workbench and pgAdmin4 for database management
- Data Analysis: ○ Performing data analysis using SQL on MySQL Workbench and pgAdmin4
- AWS SageMaker Setup
- Exploratory Data Analysis (EDA): ○ Conducting exploratory data analysis to understand essential features and the dataset's characteristics
- Feature Store:

○ Understanding the concept of a feature store and its significance in machine learning projects ○ Understanding how Hopsworks works to facilitate project creation and feature group management

- Data Retrieval from Feature Stores
- Fetching data from feature stores for further analysis
- Data Preprocessing and Feature Engineering
- Data Storage: ○ Storing the final engineered features in the feature store for easy access and consistency

Code Folder Overview:

Once you unzip the code.zip file, you can find the following folders:

Here is a brief information on the folders:
1. Data
2. Notebook
3. References
4. SQL Commands
1. The data folder contains database backup files in both MySQL and PostgreSQL formats. These files can be used to restore a database. It also contains training data files in CSV format and data description.
2. The notebook folder contains the original ipython notebook as in the lectures. Note that this notebook contains code as well as observation and other information as per videos.
3. The reference folder contains a README.md file, which contains documentation and instructions, and a requirements.txt file has all the required libraries with respective versions and solution methodology of the project.
4. The SQL commands folder contains MySQL and PostgreSQL analysis scripts.

## Tech stack
➔ Language: Python, SQL ➔ Libraries: NumPy, Pandas, PyMySQL , Psycopg2, Matplotlib, Seaborn ➔ Data Storage: PostgreSQL,MySQL, AWS RDS, Hopsworks ➔ Data Visual Tool(SQL): MySQL Workbench, Pgadmin4 ➔ Feature Store: Hopsworks ➔ Cloud Platform: AWS Sagemaker

## How to run
```bash
pip install -r end-to-end-1/References/requirements.txt
```
Notebooks: [`Truck_Delay_Classification.ipynb`](end-to-end-1/Notebook/Truck_Delay_Classification.ipynb)

## Project structure
```
.gitignore
README.md
end-to-end-1/
  Notebook/
    Truck_Delay_Classification.ipynb
  References/
    requirements.txt
  SQL Commands/
    truck-delay-mysql.sql
    truck-delay-postgres.sql
```

## Credits
Based on a ProjectPro guided project.
