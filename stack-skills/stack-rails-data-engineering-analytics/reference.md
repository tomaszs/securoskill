# Ruby on Rails: Data engineering, analytics, and BI security

Stack-specific implementation for **Ruby on Rails** (Ruby). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Warehouse access control

**Sub-topics:** Snowflake RBAC, BigQuery IAM, Row access policies, Column masks, Shared datasets

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for warehouse controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## ETL credentials

**Sub-topics:** Airflow connections, dbt profiles, Spark keys in notebooks, Rotation, CI to prod

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for etl controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

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

## PII in analytics

**Sub-topics:** Hashing vs encryption, Join keys, Re-identification, Sampling leaks, Aggregates

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for pii controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## BI and dashboards

**Sub-topics:** Embed tokens, RLS in Power BI, Export CSV, Scheduled email, Public links

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for bi controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Data lakes

**Sub-topics:** S3 path traversal, Parquet metadata, Glue catalog ACL, Lake Formation, Iceberg snapshots

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for data_lake controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Streaming analytics

**Sub-topics:** Flink state, Kafka Connect secrets, Exactly-once, Poison records, Schema registry ACL

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for streaming controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Feature stores

**Sub-topics:** Point-in-time leaks, Training-serving skew, Offline online parity, PII in features, Access audit

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for feature_store controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Notebooks and ad hoc SQL

**Sub-topics:** Shared workspaces, Output history, Git sync secrets, Cell execution order, Public nbviewer

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for notebooks controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Data contracts and quality

**Sub-topics:** Breaking schema, DQ alerts, Tampered sources, Lineage trust, SLA abuse

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for data_contracts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Third-party data feeds

**Sub-topics:** License scope, Resale restrictions, API keys shared, Poisoned feeds, Watermarking

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for third_party_data controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

## Analytics backups

**Sub-topics:** Snapshot sharing, Cross-account, Restore to dev PII, Retention, Encryption

### Do (use this in Ruby on Rails)

- Apply domain skill `security-data-engineering-analytics` requirements using rails supported APIs only.
- Use the official rails security documentation for backups controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

