# PostgreSQL

## Commands

- Enter to postgres console as user
```
psql -h [hostname] -d [database_name] -p [port] -U [user] --> exmaple: psql -h localhost -d test -p 5432 -U postgresql_user
```

### Inside of psql console
- Get list of all users
```
\du
```