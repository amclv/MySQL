### Will list all the databases you have on MySQL.

```
show databases;
```

### Creates a database with the name you select.

```
CREATE DATABASE <name>;
```

### Drops or deletes a database that you selected.

```
DROP DATABASE <name>;
```

### To use a database.

```
USE <name>;
```

### To verify the database you are using.

```
SELECT database();
```

### Creating a table.

```
CREATE TABLE tablename
    (
        column_name data_type,
        column_name data_type
    );
```

### Show tables that are currently in your database.

```
SHOW TABLES;
```

### Show the columbs from the certain table.

```
SHOW COLUMNS FROM <tablename>;
```
or
```
DESC <tablename>;
```

### Deleting Tables

```
DROP TABLE <tablename>;
```

### Data Types

| Numeric Types | String Types | Date Types |
| --- | --- | --- |
| `INT` | `CHAR` | `DATE` |
| `SMALLINT` | `VARCHAR` | `DATETIME` |
| `TINYINT` | `BINARY` | |
| `MEDIUMINT` | `VARBINARY` | |
| `BIGINT` | `BLOB` | |
| `DECIMAL` | `TINYBLOB` | |
| `NUMERIC` | `MEDIUMBLOB` | |
| `FLOAT` | `LONGBLOB` | |
| `DOUBLE` | `TEXT` | |
| `BIT` | `TINYTEXT` | |
| | `MEDIUMTEXT` | |
| | `LONGTEXT` | |
| | `ENUM` | |
























