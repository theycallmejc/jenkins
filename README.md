# Currency Exchange Service: Jenkins Pipeline Example

A small Java/Spring Boot currency-exchange service built with Maven, paired with a minimal Jenkins Pipeline example.

## Project contents

- `src/main/` contains the service source.
- `pom.xml` defines the Maven/Spring Boot project.
- `Jenkinsfile` shows `Build` and `Test` stages.

## Run locally

Install a compatible JDK and Maven, then run:

```bash
mvn test
mvn spring-boot:run
```

## Pipeline status

The current `Jenkinsfile` only prints the stage names; it does not invoke Maven or run automated tests. Add those commands before treating this pipeline as a CI quality gate.