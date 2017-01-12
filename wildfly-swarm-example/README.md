# WildFly Swarm Example

The application can be started by

```
mvn wildfly-swarm:run
```

or it can be first packaged by

```
mvn package
```

and then started anywhere by

```
java -jar wildfly-swarm-example-swarm.jar
```

Once running, you can try to access the following URL

```
http://localhost:8080/rest/hello
```
