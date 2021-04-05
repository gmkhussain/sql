# Sql

### Convert Unix timestamp into human readable date using MySQL

```js
SELECT
  FROM_UNIXTIME(timestamp, '%Y %D %M %H:%i:%s') 
FROM 
  db.table_name;
```
