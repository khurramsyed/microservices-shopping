#Eureka Server
We are using Eureka Server discovery purposes.

You can create the jars using

```shell
$ mvn clean package
```

### Building Docker image

```
$ docker build . -t eureka-server
```

### Running server on docker container

```
$  docker run -p 8761:8761 eureka-server
```
