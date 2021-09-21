# What is [Redis](https://redis.io/) and [RedisInsight](https://redis.com/redis-enterprise/redis-insight/) ?

- Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker.
- RedisInsight is a desktop manager that provides an intuitive and efficient GUI for Redis, allowing you to interact 
with your databases and manage your data

# How can I start?

Jus execute the command bellow to run the containers.

```bash
$ docker-compose -f "Redis/redis-docker-compose.yml" up -d
```
# Done!

Now you can go to the adress on your browser `http://localhost:8001/`, to login insert the rediscache credentials 
`host` (you can insert the service name on composer `rediscache`), `port` and `name` to connect to our service.