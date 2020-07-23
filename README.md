## Dictionary Rule

* `TABLE_NAME_HERE`  : Replace with your table name
* `COLUMN_NAME_HERE` : Replace with your column name


### Select all table names in specific database

``` sql
SELECT TABLE_NAME FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_SCHEMA = 'DB_NAME_HERE';
```

### Select Duplicated rows

``` sql
SELECT * FROM `TABLE_NAME_HERE` GROUP BY COLUMN_NAME_HERE HAVING COUNT(COLUMN_NAME_HERE) > 1;
```
