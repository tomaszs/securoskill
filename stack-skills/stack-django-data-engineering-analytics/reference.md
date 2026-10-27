# Django: Data engineering, analytics, and BI security

Stack-specific implementation for **Django** (Python). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Django)

- Use Django ORM: `User.objects.filter(email=email)` with no raw SQL.
- For raw SQL: `Model.objects.raw('SELECT * FROM u WHERE id = %s', [user_id])` or `cursor.execute(sql, params)`.
- Enable query logging in staging only; never log bound secret values.

### Don't

- Do not use f-strings or `.format()` to build SQL in views, managers, or signals.
- Do not use `extra()` / `RawSQL` with user-controlled fragments.
- Do not concatenate `WHERE` clauses from query string filters.

### Verify

- Add tests that malicious `filter` query params do not alter SQL structure.

