# Introduction

## Creating a database
- Follow the commands below to create a database

```sql
CREATE DATABASE database_name;  
```

## Navigate into a specific database

```sql
\c database_name;

```
The command above allows you to navigate into a specific database

To check the tables in a specific database, use the command below.

```sql
\dt
```

## Drop a database

```sql
DROP DATABASE database_name;
```

## Create a table

```sql
CREATE TABLE table_name (
    column_name1 datatype,
    column_name2 datatype,
    column_name3 datatype,
    column_name4 datatype,
    column_name5 datatype,
    column_name6 datatype,
    column_name7 datatype,
    column_name8 datatype,
    column_name9 datatype,
    column_name10 datatype
);
```

## Drop a table

```sql
DROP TABLE table_name;
```

## Insert data into a table

```sql
INSERT INTO table_name (column_name1, column_name2, column_name3, column_name4, column_name5, column_name6, column_name7, column_name8, column_name9, column_name10)
VALUES (value1, value2, value3, value4, value5, value6, value7, value8, value9, value10);
``` 

## Select data from a table

```sql
SELECT column_name1, column_name2, column_name3, column_name4, column_name5, column_name6, column_name7, column_name8, column_name9, column_name10
FROM table_name;
```

## Update data in a table

```sql
UPDATE table_name
SET column_name = new_value
WHERE condition;
```
## View all the values in a table;
This will display all the values in the table

```sql
SELECT * FROM table_name;
```

## Delete data from a table

```sql
DELETE FROM table_name
WHERE condition;
```
