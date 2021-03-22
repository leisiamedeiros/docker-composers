# What is Nexus?

Nexus Repository OSS is an open source repository that supports many artifact formats, including Docker, Java™, and npm. 

With the Nexus tool integration, pipelines in your toolchain can publish and retrieve versioned apps and their dependencies 
by using central repositories that are accessible from other environments.

# How can I start?

Just execute the command bellow and go to the adress on your browser `http://localhost:8081/`

```bash
$ docker-compose -f "Nexus/nexus-docker-compose.yml" up -d
```

Default user is `admin` and the uniquely generated password can be found in the `admin.password` file inside the volume. 

# Done!
Now you can configure your sources as you wish!
