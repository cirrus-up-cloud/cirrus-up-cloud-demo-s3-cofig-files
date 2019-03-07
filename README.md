# README #

### What is this repository for? ###

* Demo RESTful web service using Java & Spring Boot that reads configuration properties from S3.
* It's a demo for [Spring S3 Property Loader](https://github.com/cirrus-up-cloud/spring-s3-properties-loader) library.

### How do I get set up? ###

* Compile with maven -> mvn package
* Run the jar -> java -Daws.accessKey=<> -Daws.secretKey=<> -Ds3.config.bucket=<> -Ds3.config.filename=<> target/cirrus-up-cloud-demo-s3-config-files-1.0.jar
