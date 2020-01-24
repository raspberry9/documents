## Postgresql

### Installation

#### Ubuntu

```
sudo apt update
sudo apt install postgresql postgresql-contrib
```

### Console

#### Run

```
sudo -u postgres psql
```

#### Commands

```
\q - exit console
\conninfo - show current connection information
\d - show all tables and relations
\dt - show all tables and relations without sqeuences
```

### Add user

```
sudo -u postgres createuser --interactive
```

### Create a database

```
sudo -u postgres createdb mydb
```

### Client

- [SQLPro for Postgres](https://apps.apple.com/kr/app/sqlpro-for-postgres/id976140091?mt=12)
