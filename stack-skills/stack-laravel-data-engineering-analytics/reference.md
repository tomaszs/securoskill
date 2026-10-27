# Laravel: Data engineering, analytics, and BI security

Stack-specific implementation for **Laravel** (PHP). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Laravel)

- Use Eloquent or `DB::select('... where id = ?', [$id])`.

### Don't

- Do not use `DB::raw()` with interpolated user strings.

### Verify

- Laravel security checker packages in CI.

