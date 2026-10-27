# Spring Boot: Server framework and runtime security

Stack-specific implementation for **Spring Boot** (Java). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in Spring Boot)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in Spring Boot)

- Enforce max query depth and complexity limits.
- Disable introspection in production unless required for trusted tools.
- Authorize each resolver field (not only top-level entry).

### Don't

- Do not expose admin-only fields on the same schema without field-level auth.
- Do not allow batch aliases to bypass rate limits.

### Verify

- Load-test GraphQL with deeply nested queries; expect rejection.

## Serverless framework adapters

**Sub-topics:** Chalice, Serverless.yml secrets, SAM templates, Cold start IAM, Local invoke creds

### Do (use this in Spring Boot)

- Map `Serverless framework adapters` controls to Spring Boot APIs documented for `security-server-framework-security`.
- Add an abuse-case test or check for `Serverless framework adapters` before merge.

### Don't

- Do not ship `Serverless framework adapters` work in Spring Boot with only happy-path tests.
- Do not disable Spring Boot security defaults to unblock `Serverless framework adapters`.

### Verify

- Peer review `Serverless framework adapters` against domain skill `security-server-framework-security`.

