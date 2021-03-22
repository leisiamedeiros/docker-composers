# Docker composers
This is where we can save our docker composers to use when we want!

You can use this composers to help you developement on localhost with all this without needing to install the 
application on your machine, you just need [Docker](https://www.docker.com/get-started) and [Docker-Compose](https://docs.docker.com/compose/)

# Applications

- **Nexus**
![nexus](Nexus/nexus.png)

- **Elastic**  
WIP

- **Kibana**  
WIP

- **Sql Server**
![sqlserver](SqlServer/sqlserver.png)

- **Postgres with Adminer**
![psqlandadminer](Postgres/postgres-adminer.png)

- **RavenDb**
![ravenDb](RavenDb/ravendb.png)


# Contribute
Fell free to contribute just forking this repository and sending a pull request with a docker compose from any 
application to help us to developer.

You must create a folder with this structure:

```bash
FolderAppName
├── appname-docker-compose.yml
├── help.md
├── appName.png
```

You can see the [Nexus](Nexus) folder to get an example.

There's a `help-Template.md` to help you when you go to write about the app.