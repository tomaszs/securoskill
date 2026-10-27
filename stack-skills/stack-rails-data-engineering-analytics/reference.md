# Ruby on Rails: Data engineering, analytics, and BI security

Stack-specific implementation for **Ruby on Rails** (Ruby). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

