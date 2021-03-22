# What is Postgres and Adminer?

- [PostgreSQL](https://hub.docker.com/_/postgres), often simply "Postgres", is an object-relational database management 
system (ORDBMS) with an emphasis on extensibility and standards-compliance.

- [Adminer](https://hub.docker.com/_/adminer) (formerly phpMinAdmin) is a full-featured database management tool. 

# How can I start?

Just execute the command bellow and go to the adress on your browser `http://localhost:8080/`

```bash
$ docker-compose -f "Postgres/postgres-docker-compose.yml" up -d
```

# Done!

Go to http://localhost:8080/ on your browser and connect with `pgsql` service name and credentials on composer file.