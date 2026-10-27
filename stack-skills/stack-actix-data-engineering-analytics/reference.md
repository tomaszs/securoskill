# Actix Web (Rust): Data engineering, analytics, and BI security

Stack-specific implementation for **Actix Web (Rust)** (Rust). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Actix Web (Rust))

- Use `sqlx` with `.bind()` for all dynamic values.

### Don't

- Do not format SQL with user strings.

### Verify

- cargo audit + SQLi integration tests.

