# CREATE TABLE

> It is used to create a table on a database.

```sql
CREATE TABLE actors (
    id SERIAL PRIMARY KEY,
    first_name VARCHAR(150) NOT NULL,
    last_name VARCHAR(150) NOT NULL,
    gender CHAR(1) NOT NULL,
    date_of_birth DATE NOT NULL,
    created_at DATE NOT NULL,
    updated_at DATE
)
``