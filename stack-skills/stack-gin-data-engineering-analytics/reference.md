# Gin (Go): Data engineering, analytics, and BI security

Stack-specific implementation for **Gin (Go)** (Go). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Gin (Go))

- Use `db.QueryRowContext(ctx, 'SELECT ... WHERE id = $1', id)`.

### Don't

- Do not fmt.Sprintf user input into SQL.

### Verify

- gosec G201/G202 in CI.

