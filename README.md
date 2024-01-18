# Yelp-Dataset-ETL-and-Analysis

This project focuses on extracting insights from the Yelp academic dataset to support opening a new restaurant business.

##Technical Approach
1. The Yelp dataset JSON files were accessed via Kaggle notebooks for this project.
2. The JSON data was loaded into pandas dataframes within the Kaggle notebook for exploration and analysis.
3. An Azure MySQL server was provisioned to hold the transformed Yelp data.
4. The Kaggle notebook contains SQL code and sqlalchemy to connect to the Azure MySQL instance.
5. Pandas dataframes were used to transform the JSON data into a structure matching the MySQL schema.
6. The structured data was then loaded into the Azure MySQL database from the Jupyter notebook using sqlalchemy.
7. Further data exploration and visualization was done in the Kaggle notebook using pandas, matplotlib, seaborn and SQL queries.
8. The Jupyter notebook documents the process of extracting the JSON, designing the MySQL schema, ETL logic, and analysis.

##Learnings
Through this project, I gained experience with:

1. Handling semi-structured JSON data and developing ETL processes.
2. Designing relational database schemas and configuring metadata.
3. Using pandas, sqlalchemy, and other Python libraries for data wrangling.
4. Creating visualizations with matplotlib and seaborn for exploratory analysis.
5. Communicating data-driven insights to support business strategy and decision making.
