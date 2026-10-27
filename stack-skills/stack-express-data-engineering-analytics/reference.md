# Express.js: Data engineering, analytics, and BI security

Stack-specific implementation for **Express.js** (Node.js server). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Express.js)

- Use `pg` / `mysql2` placeholders: `pool.query('SELECT * FROM users WHERE id = $1', [id])`.
- Prefer Prisma or another ORM with parameterized APIs when using Express.

### Don't

- Do not use template literals to embed `req.query` / `req.body` fields into SQL.
- Do not use `eval` or `Function` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

