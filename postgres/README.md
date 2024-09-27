# PostgreSQL and pgAdmin image

connect database:

```commandline
psql -h <HOSTNAME> -p <PORT> -U <USERNAME> -d <DATABASENAME>
```

e.g.:

```commandline
psql -h localhost -p 5432 -U admin -d database
```

`host.docker.internal` - host name for pgAdmin to connect local db