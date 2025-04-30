# DS 2002: Data Science Systems Project 1 Midterm 
Data Engineering project demonstrating the Extract, Transform, and Load (ETL) process with the sakila database 

### Repository Contents 
Project1-Midterm.ipynb
* Jupyter Notebook containing all code used to populate the data mart

actor.json, address.json
* Files read in locally

category.json, city.json
* Files set as collections in MongoDB sakila database (collection names = city, category), and then read in

sakila-schema.sql, sakila-data.sql, sakila-drop-tables.sql, sakila_date_dim.sql 
* Files used to create sakila schema (sakila-schema.sql), populate sakila tables (sakila-data.sql), drop tables read in locally or from MongoDB (sakila-drop-tables.sql), and create sakila date dimension table in new data warehouse (sakila_date_dim.sql)
  
