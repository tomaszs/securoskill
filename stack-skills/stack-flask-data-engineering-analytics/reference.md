# Flask: Data engineering, analytics, and BI security

Stack-specific implementation for **Flask** (Python). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Flask)

- Use SQLAlchemy ORM or `cursor.execute('... WHERE id=?', (id,))` with DB-API params.

### Don't

- Do not use f-strings in `db.session.execute(f'...')`.

### Verify

- pytest with SQLi payloads on search endpoints.

