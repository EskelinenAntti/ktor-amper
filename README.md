# Ktor with Amper

This a sample Ktor server application using experimental Amper build tool instead of Gradle or Maven.

## How to run

In the repository root, run

```bash
./amper run
```

You can validate that the app started successfully by calling the endpoint

```bash
curl http://localhost:8080/
```

## Interesting files

### Build configuration

You can find the build configuration in [module.yaml](/module.yaml).

### Ktor application

- The Ktor application is in [src/main.kt](/src/main.kt).
- Ktor configuration and log configuration can be found under [resources/](/resources).