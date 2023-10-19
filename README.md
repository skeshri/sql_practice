# sql_practice
### Find the schema of a table:
Query
```
select column_name, data_type
from INFORMATION_SCHEMA.COLUMNS
where TABLE_NAME='table_name'
```
