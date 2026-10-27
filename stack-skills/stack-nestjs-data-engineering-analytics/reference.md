# NestJS: Data engineering, analytics, and BI security

Stack-specific implementation for **NestJS** (Node.js server). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in NestJS)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

