# Docker composers

> RUN YOUR SERVICES ON LOCALHOST WITH JUST [Docker](https://www.docker.com/get-started) and [Docker-Compose](https://docs.docker.com/compose/)

#### You can use this composers to help your daily developement with your services on localhost without needing to install it!!

### Composers List
- [RabbitMQ](#rabbitmq)
- [Mongodb with MongoExpress](#mongodb-with-mongo-express)
- [Redis with RedisInsight](#redis-with-redisinsight)
- [ElasticSearch and Kibana](#elasticsearch-and-kibana)
- [RavenDb](#ravendb)
- [Sql Server](#sql-server)
- [MySQL with Adminer](#mysql-with-adminer)
- [Postgres with Adminer](#postgres-with-adminer)
- [Nexus](#nexus)

# Applications

### RabbitMQ
![rabbitmq](RabbitMq/rabbitmq.png)
[help-rabbitmq](RabbitMq/README.md)

### Mongodb with Mongo-Express
![mongodb](Mongodb/mongodb-mongoexpress.png)
[help-mongo](Mongodb/README.md)

### Redis with RedisInsight
![rediswithinsight](Redis/redis.png)
[help-redis](Redis/README.md)

### ElasticSearch and Kibana
![elastickibana](ElasticKibana/kibana.png)
[help-elastickibana](ElasticKibana/README.md)

### RavenDb
![ravenDb](RavenDb/ravendb.png)
[help-raven](RavenDb/README.md)

### Sql Server
![sqlserver](SqlServer/sqlserver.png)
[help-sqlserver](SqlServer/README.md)

### Postgres with Adminer
![psqlandadminer](Postgres/postgres-adminer.png)
[help-psql](Postgres/README.md)

### MySQL with Adminer
![mysqlandadminer](MySQL/mysql-adminer.png)
[help-mysql](MySQL/README.md)

### Nexus
![nexus](Nexus/nexus.png)
[help-nexus](Nexus/README.md)


# Contribute
Fell free to contribute just forking this repository and sending a pull request with a docker compose from any 
application to help us to developer.

You must create a folder with this structure:

```bash
FolderAppName
├── appname-docker-compose.yml
├── README.md
├── appName.png
```

You can see the [Nexus](Nexus) folder to get an example.

There's a `help-Template.md` to help you when you go to write about the app.
