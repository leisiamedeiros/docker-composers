# What is Nexus?

Nexus Repository OSS is an open source repository that supports many artifact formats, including Docker, Java™, and npm. 

With the Nexus tool integration, pipelines in your toolchain can publish and retrieve versioned apps and their dependencies 
by using central repositories that are accessible from other environments.

# How can I start?

Jus execute the command bellow and go to the adress on your browser `http://localhost:8081/`

```bash
$ docker-compose -f nexus-docker-compose.yml up -d
```

Default user is `admin` and the uniquely generated password can be found in the `admin.password` file inside the volume. 


# How to use
**Configuring Internal Nexus Repository on Your Local Machine**

## Prerequisites

Install the nuget.exe CLI by downloading it from [nuget.org](https://www.nuget.org/downloads), saving that .exe file 
to a suitable folder, and adding that folder to your PATH environment variable.

## Adding Source

```bash 
nuget sources Add -Name NugetLocalHost -Source http://localhost:8081/repository/nuget-hosted/ -username developer -password <pwd>
```

## Done!
Now you can install the package that's available on `http://localhost:8081/#browse/search/nuget`

For example:

```bash
dotnet add package PackageName --version 0.0.1
```