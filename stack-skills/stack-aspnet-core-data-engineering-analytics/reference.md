# ASP.NET Core: Data engineering, analytics, and BI security

Stack-specific implementation for **ASP.NET Core** (.NET). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in ASP.NET Core)

- Use EF Core LINQ; parameters are automatic.
- Use `FromSqlInterpolated` only when necessary; prefer LINQ.
- Use Dapper with anonymous objects for parameters.

### Don't

- Do not use `FromSqlRaw` with string concatenation from request data.
- Do not build dynamic SQL for column names without allowlists.

### Verify

- Roslyn analyzers + integration tests on filter APIs.

