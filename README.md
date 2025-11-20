# Simple_Maven_SonarQube_CICD 

This repository is a streamlined Java project that demonstrates continuous integration using Maven and SonarQube. It automates code compilation, testing, and quality analysis through a CI/CD pipeline. Ideal for beginners, it showcases best practices in build automation, static code analysis for maintainable and testable Java application.
For reference: 
[Build a Java app with Maven](https://jenkins.io/doc/tutorials/build-a-java-app-with-maven/)

The repository contains a simple Java application which outputs the string "Hello world!" and is accompanied by a couple of unit tests to check that the
main application works as expected. The results of these tests are saved to a JUnit XML report.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline) and the `jenkins/scripts` subdirectory
contains a shell script with commands that are executed when Jenkins processes the "Deliver" stage of your Pipeline.
