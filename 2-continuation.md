## 1. Order By keyword
 The command below allows you to order the data in a table by a specific column.
```sql
SELECT * FROM table_name
ORDER BY column_name;
```

### ASC keyword
Use together with ORDER BY keyword  to sort the data in Ascending order.

```sql
SELECT * FROM table_name    
ORDER BY column_name ASC;
```
### DESC keyword
Use together with ORDER BY keyword  to sort the data in Descending order.

```sql
SELECT * FROM table_name
ORDER BY  column_name DESC;
```

## 2. Distinct keyword

The command below allows you to display DISTINCT values in a table.
This display the values in a certain column without repetition.

```sql
SELECT DISTINCT column_name FROM table_name;
```

## 3. WHERE CLAUSE & AND;

The ```WHERE``` keyword allows you to filter data based on a condition.

```sql
SELECT * FROM table_name
WHERE condition;
```
### Example

```sql
SELECT * FROM person
WHERE first_name = 'Brian';
```
This will display the data in the table where the first name is equal to Brian.


```sql
SELECT * FROM person
WHERE first_name = 'Brian' AND last_name = 'Smith';
```
This will display the data in the table where the first name is equal to Brian and the last name is equal to Smith

