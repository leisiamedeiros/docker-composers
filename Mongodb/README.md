# What is MongoDB and MongoExpress?

- [MongoDB](https://hub.docker.com/_/mongo) is a free and open-source cross-platform document-oriented database program. 

- [MongoExpress](https://hub.docker.com/_/mongo-express) is a Web-based MongoDB admin interface written with Node.js, Express and Bootstrap3

# How can I start?

Just execute the command bellow:

```bash
$ docker-compose -f "Mongodb/mongodb-docker-compose.yml" up -d
```

# Done!

Go to `http://localhost:8081/` on your browser.

If you whant to change your [theme](https://codemirror.net/demo/theme.html#dracula) just change 
the value of `ME_CONFIG_OPTIONS_EDITORTHEME` variable in the composer file.

If you like, you can use only the inline values with `ME_CONFIG_MONGODB_URL: mongodb://mongoadmin:secret@mongodb:27017/` data on mongo-express service.
