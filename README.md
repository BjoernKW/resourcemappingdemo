# resourcemappingdemo

Demo for using [PathResourceResolver](https://docs.spring.io/spring/docs/current/javadoc-api/org/springframework/web/servlet/resource/PathResourceResolver.html)
for resolving [Angular](https://angular.io) *HTML5 pushState* paths when loading an Angular client from a static resources folder within a
[Spring Boot](https://spring.io/projects/spring-boot) application.

## Running the example 

In order to try out the example please run these commands:

```
$ cd client
$ ng build --prod
$ cd ..
$ mvn clean install
$ java -jar target/resourcemappingdemo-0.0.1-SNAPSHOT.jar
```

Alternatively, you can use this command instead of the two last ones above:

```
mvn spring-boot:run
```

Once the application is running go to [http://localhost:8080/nested], which maps to a component served by an Angular route.

## Built With

* [Spring Boot](https://spring.io/projects/spring-boot)
* [Angular](https://angular.io)

## Authors

* **[Björn Wilmsmann](https://bjoernkw.com)**

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

## Acknowledgments

* [Michel Palourdio](https://github.com/mpalourdio) for his
[SpringBootAngularHTML5](https://github.com/mpalourdio/SpringBootAngularHTML5) example this example was built on.
