
# [Class 03: Data Modeling](/README.md

## [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

## [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

## [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

<hr>

# nosql vs sql

- ## What type of database is the best fit for the complex query intensive environment?
    - Sql databases are a good fit for complex query environment
- ## What type of database is the best fit for hierarchical data storage?
    - noSql databases are a better for hierarchical data storage since it stores data as key value pairs.
- ## Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
    - Sql databases are vertically scalable so you manage increasing load by adding more cpu, ram , storage on a single server. in a noSql database it scales horizontally so you just need to add another server. 
# sql modeling techniques

- ## Among data tables, what is a one-to-many relationship and how do we “relate” them?
    - where an entry in one table is related to many in another table. we relate them by connecting lines between tables to show relationship.
- ## Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
    - create a diagram 
- ## Explain the difference between a primary and foreign key.
    - primary keys uniquely identify each row in a table. 
    - foreign keys match primary keys in another table

# sql vs nosql

- ## How do we treat keywords and parameters differently in SQL syntax?
  - single quotes 

- ## Define normalization within the context of schemas and data.
  - modeling data so no table has any redundant data. 

- ## Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
  - one-to-one: one record from one table matches one record from another, uniquely.
  - one-to-many: one record from one table matches many records in another.
  - many-to-many: many records from one table matches many records from another table. 