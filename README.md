# Sql

### Convert Unix timestamp into human readable date using MySQL

```js
SELECT
  FROM_UNIXTIME(timestamp, '%Y %D %M %H:%i:%s') 
FROM 
  db.table_name;
```



### Compare 2 tables and display using MySQL

```js
SELECT 
	 *
FROM 
    db.table1
    JOIN db.table2
    ON db.table2.ID = db.table1.user_id
```
