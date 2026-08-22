# Taboola Home Assignment

This repository contains my Java solution to a Taboola home assignment. It includes two independent exercises:

- **Invoice parser** — reads fixed-width, seven-segment ASCII digits and converts each entry into a nine-digit value.
- **Concurrent word counter** — reads multiple text files in parallel and aggregates case-insensitive word counts.

## Tech stack

- Java 17
- Gradle
- JUnit 5
- Lombok

## Run the tests

```bash
./gradlew test
```

On Windows:

```powershell
.\gradlew.bat test
```

## Run the examples

The entry points are:

- `com.taboola.invoice.InvoiceParser`
- `com.taboola.wordcounter.WordsCounter`

Sample inputs are under `src/main/resources`; test fixtures are under `src/test/resources`.

## Project context

This code was created specifically as a Taboola take-home assignment and is preserved here as a portfolio and learning project.
