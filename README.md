# Yelp-Dataset-ETL-and-Analysis

This project focuses on extracting insights from the Yelp academic dataset to support opening a new restaurant business.

## Technical Approach
1. The Yelp dataset JSON files were accessed via Kaggle notebooks for this project.
2. The JSON data was loaded into pandas dataframes within the Kaggle notebook for exploration and analysis.
3. An Azure MySQL server was provisioned to hold the transformed Yelp data.
4. The Kaggle notebook contains SQL code and sqlalchemy to connect to the Azure MySQL instance.
5. Pandas dataframes were used to transform the JSON data into a structure matching the MySQL schema.
6. The structured data was then loaded into the Azure MySQL database from the Jupyter notebook using sqlalchemy.
7. Further data exploration and visualization was done in the Kaggle notebook using pandas, matplotlib, seaborn and SQL queries.
8. The Jupyter notebook documents the process of extracting the JSON, designing the MySQL schema, ETL logic, and analysis.

## Learnings
Through this project, I gained experience with:

1. Handling semi-structured JSON data and developing ETL processes.
2. Designing relational database schemas and configuring metadata.
3. Using pandas, sqlalchemy, and other Python libraries for data wrangling.
4. Creating visualizations with matplotlib and seaborn for exploratory analysis.
5. Communicating data-driven insights to support business strategy and decision making.

## SQL Query Replication
In addition to the ETL process and analysis performed in SQL, I also replicated key analytic queries using Python and Pandas directly on the JSON data. This involved:

1. Loading and parsing the nested Yelp JSON dataset into usable Pandas dataframes
2. Flattening and joining the dataframes into a structure matching the relationships in the SQL database schema
3. Using Pandas groupby, aggregate, merge, and other operations to emulate JOINs and GROUP BYs from SQL
4. Leveraging boolean indexing, filtering, and sorting functions in Pandas to replicate WHERE clauses and ORDER BYs
5. Recreating important analytic queries on reviews, businesses, and users to derive the same insights without SQL
   
This Python/Pandas query recreation exercise demonstrated:

1. Proficiency in ingesting and normalizing semi-structured JSON data
2. Understanding of SQL constructs and ability to emulate them in Pandas
3. How to conduct full analytical workflows in Python without reliance on SQL
