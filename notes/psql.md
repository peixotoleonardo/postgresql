# PSQL

> It is a utility used to interact with PostgreSQL from the terminal.


## Connect

```bash
# try connect localhost:5432 with user on database db_name
psql -h 127.0.0.1 \ 
    -p 5432 \
    -U user \
    -W \
    -d db_name 
```

## Helpers

- `\q` exit from psql
- `\l` list databases
- `\dt` list tables
- `\dg` list roles
- `\password` safely change the password later
- `\c` can be used to switch to another database, or other connection
- `\d table_name` shows table schema
- `\e` open a editor that is used to write a query,
  when the file is saved it is executed