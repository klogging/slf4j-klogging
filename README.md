# slf4j-klogging

## The code for this library is now [here](https://github.com/klogging/klogging/tree/main/slf4j-klogging) and this repository is archived 

A simple [SLF4J](https://www.slf4j.org) binding to use with Klogging.

For more details, please see [the Klogging SLF4J documentation](https://klogging.io/docs/java/slf4j)
and [using Klogging with Spring Boot via SLF4J](https://klogging.io/docs/java/spring-boot).

## Quick start

Specify this library as the dependency. Gradle:

```kotlin
    implementation("io.klogging:slf4j-klogging:0.5.0")
```

Maven:

```xml
<dependencies>
    <dependency>
        <groupId>io.klogging</groupId>
        <artifactId>slf4j-klogging</artifactId>
        <version>0.5.0</version>
    </dependency>
</dependencies>
```

This binding does not currently support Markers.
