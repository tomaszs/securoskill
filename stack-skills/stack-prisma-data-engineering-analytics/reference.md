# Prisma: Data engineering, analytics, and BI security

Stack-specific implementation for **Prisma** (ORM / data access). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

