# Kubernetes: Data engineering, analytics, and BI security

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Kubernetes)

- Use parameterized queries or ORM equivalents for every database call.

### Don't

- Do not build SQL/command strings with user input.

### Verify

- Static analysis for injection sinks.

