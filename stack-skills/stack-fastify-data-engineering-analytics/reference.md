# Fastify: Data engineering, analytics, and BI security

Stack-specific implementation for **Fastify** (Node.js server). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

