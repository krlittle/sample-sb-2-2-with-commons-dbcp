# sample-sb-2-2-with-commons-dbcp

Saves and lists reminders on a pooled data source.

## Stack

- Spring Boot 2.2.4.RELEASE
- Java 8
- Gradle 6.0.1
- Commons DBCP 1.2.2

## Build

```
./gradlew build
```

## Run

```
./gradlew bootRun
```

```
curl -X POST 'localhost:8080/reminders?message=call%20mom'
curl localhost:8080/reminders
```
