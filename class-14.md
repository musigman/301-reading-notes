# Reading Day: 09.23.20
## Database Normalization
Database normalization is a process used to organize a database into tables and columns. A table should be about a specific topic and supporting topics. 

By limiting a table to one purpose, you reduce the number of duplicate data contained within your database. And this eliminates issues from modifications of the database.

Database modifications uses some established rules. As tables satisfy normalization form, they become less prone to database modification anomalies and more focused toward a sole purpose or topic.

## The Reasons for Normalization
There are 3 main reasons to normalize a database:
1. **Minimize Duplicate Data**
1. **Minimize or Avoid Data Modifications Issues**
1. **Simplify Queries**

## Data Duplication
Duplicated data in the database presents two problems:
1. **Increased Storage and Decreased Performance**
1. **More difficult to maintain data changes**

## Definitions
There are three common forms of database normalization: *1st, 2nd, and 3rd normal form. The forms are progressive, so for a table to qualify for 3rd normal form, it must first satisfy the rules for 2nd normal form and must adhere to 1st normal form.

- **First Normal Form** - Information is stored in a relational table with each column containing atomic values with no repeating groups of columns.

- **Second Normal Form** - Table is in first normal form and all the columns depend on the table's primary key.

- **Third Normal Form** - Table is in second normal form and all columns are not transitively dependent on the primary key.


[<== Back to Table of Contents](index.md)