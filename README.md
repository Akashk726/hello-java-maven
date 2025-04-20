# Hello Java Maven - Jenkins Build
This repository contains a simple Java application built using Maven in a Jenkins Freestyle job as part of Task 8.

## Contents
- `src/main/java/HelloWorld.java`: Java application code.
- `pom.xml`: Maven configuration file.
- `build_success.png`: Screenshot of successful Jenkins build console output.

## Steps Performed
1. Created a Java application with a Maven `pom.xml`.
2. Set up Jenkins using Docker and configured JDK and Maven.
3. Created a Freestyle project in Jenkins to build the application.
4. Configured the job to use Maven with goals `clean package`.
5. Ran the build and verified `BUILD SUCCESS` in the console output.
6. Captured a screenshot of the console output.
