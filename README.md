# Quarkus demo: Hibernate Reactive with Panache and RESTEasy Reactive

Reproducer for [@Lob doesn't work with MSSQL](https://github.com/eclipse-vertx/vertx-sql-client/issues/1200).

The base project comes from the [Hibernate Reactive with Panache quickstart](https://github.com/quarkusio/quarkus-quickstarts/tree/main/hibernate-reactive-panache-quickstart)

Steps to reproduce the error (check the testcase in FruitsEndpointTest):
```
./mvnw quarkus:dev
```
and then press `r` for resuming testing.

Or by creating a new fruit with a post request:
```
http POST localhost:8080/fruits name=Pear
```

Link to [HTTPie](https://github.com/httpie/httpie)



