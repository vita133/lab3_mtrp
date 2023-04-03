# Simple Kotlin server

This is a simple project for the third laboratory assignment on containerization.
This project is written in [Kotlin](https://kotlinlang.org/) programming language and uses [Ktor](https://ktor.io/) framework.

## How to run
To compile this project, you need to have [JDK](https://www.oracle.com/cis/java/technologies/downloads/) and [Gradle](https://gradle.org/)

Build the project with the following command:
```cmd
./gradlew build
```
When you have the project built, you can run project:
```cmd
java -jar build/libs/ktor-docker-sample.jar
```
The server will start on http://localhost:8081