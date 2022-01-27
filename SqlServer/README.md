# What is SQL server?
Microsoft SQL Server is a relational database management system developed by Microsoft. 

As a database server, it is a software product with the primary function of storing and retrieving data as requested 
by other software applications—which may run either on the same computer or on another computer across a network.

# How can I start?

Jus execute the command bellow to run the container and connect with credentials to `sa` user.

```bash
$ docker-compose -f "SqlServer/mssql-docker-compose.yml" up -d
```

Default user is `sa` and the `password` you must change on composer file on `SA_PASSWORD` key.

# Done!
Now you can connect on your prefered tool!

Other common [tools](https://docs.microsoft.com/en-us/sql/linux/quickstart-install-connect-docker?view=sql-server-ver15&pivots=cs1-bash#connectexternal) to connect to SQL Server include:

- Visual Studio Code
- SQL Server Management Studio (SSMS) on Windows
- Azure Data Studio
- mssql-cli (Preview)
- PowerShell Core
