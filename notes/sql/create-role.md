# CREATE ROLE

> It is used to create a role. A role can is a entity that
> can be a users, or a group of users.


## Create a User
```sql
CREATE USER dev WITH PASSWORD '1234';

-- the command above is equivalent
CREATE ROLE dev LOGIN WITH PASSWORD '1234';
```
