# HRMIS Backend

Backend starter for the HRMIS diploma project at Astana IT University.

## Technology stack
- Java 21
- Spring Boot 3.5.x
- Spring Web
- Spring Data JPA
- PostgreSQL
- Bean Validation

## Current status
This repository contains the initial backend structure and a health endpoint. Employee and KPI modules are planned next.

## Run locally
1. Install JDK 21 and Maven.
2. Create a PostgreSQL database named `hrmis`.
3. Set environment variables if needed:
   - `DB_URL` (default: `jdbc:postgresql://localhost:5432/hrmis`)
   - `DB_USERNAME` (default: `postgres`)
   - `DB_PASSWORD` (default: `postgres`)
4. Run:
   ```bash
   mvn spring-boot:run
   ```
5. Check `GET http://localhost:8080/api/health`.

Do not commit real passwords or secret keys.
