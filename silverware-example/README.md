# SilverWare Example

The application can be started by

```
mvn exec:run
```

or it can be first packaged by

```
mvn package
```

and then started anywhere by

```
java -jar silverware-example.jar
```

Keep in mind that you need to copy `lib` folder as well if you want to run the application from some other location.

Once running, you can try to access the following URL

```
http://localhost:8080/silverware/rest/hello
```
