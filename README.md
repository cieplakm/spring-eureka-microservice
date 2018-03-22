# Spring Boot + Eureka

### Services run

For first instance:

```
java -jar target\my-service-0.0.1-SNAPSHOT.jar --server.port=8090 --service.instance.name=instance_1
```

For second instance:

```
java -jar target\my-service-0.0.1-SNAPSHOT.jar --server.port=8091 --service.instance.name=instance_2
````