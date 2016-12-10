# dropwizard-sample
A sample/skeleton to serve as a starting off point for a new dropwizard service.

## Build and Run Locally
Building and running a basic dropwizard service as a JAR file.
We will be using maven-jar-plugin and maven-shade-plugin to construct a jar file with our required dependencies.
* http://www.dropwizard.io/1.0.5/docs/getting-started.html#running-your-application
```
mvn package
java -jar target/hello-world-0.0.1-SNAPSHOT.jar server hello-world.yml
```
