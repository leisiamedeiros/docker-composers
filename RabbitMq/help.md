# What is [RabbitMQ](https://www.rabbitmq.com/)  ?

RabbitMQ is open source message broker software (sometimes called message-oriented middleware) that implements 
the Advanced Message Queuing Protocol (AMQP).

# How can I start?

Jus execute the command bellow to run the container.

```bash
$ docker-compose -f "RabbitMq/rabbit-docker-compose.yml" up -d
```

# Done!

Access the default host:port `http://localhost:15672/` and login with the default `guest` user and password.