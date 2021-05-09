# logbook-gelf-benchmark

### Running the benchmark

Update the version of the `logback-gelf` dependency in the pom.xml and then run:
```
$ mvn clean install
$ java -Xmx8G -jar target/benchmarks.jar -prof gc
```
