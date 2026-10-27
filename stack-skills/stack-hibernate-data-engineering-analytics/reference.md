# Hibernate / JPA: Data engineering, analytics, and BI security

Stack-specific implementation for **Hibernate / JPA** (ORM / data access). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Hibernate / JPA)

- Use Spring Data JPA repositories and derived queries.
- Use `@Query` with named parameters `:email` bound via `@Param`.
- Use `JdbcTemplate` with `?` placeholders.

### Don't

- Do not concatenate user input into JPQL/SQL strings in `@Query`.
- Do not enable unsafe SpEL in query bindings.
- Do not expose `/actuator/env` or `/actuator/heapdump` in production.

### Verify

- OWASP Dependency-Check + SQLi tests on repository custom queries.

