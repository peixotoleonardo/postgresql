# DROP DATABASE

> Remove a database. Only owner of database, or a **superuser** can drop it.

```sql
-- if database not exists, only log notice about it.
DROP DATABASE IF EXISTS test;

-- if database not exists, there is an error 
DROP DATABASE test;
```

If there are users connected on database, use `FORCE`.

```sql
DROP DATABASE IF EXISTS test WITH(FORCE);
```
