# SQLAlchemy: Data engineering, analytics, and BI security

Stack-specific implementation for **SQLAlchemy** (ORM / data access). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Warehouse access control

**Sub-topics:** Snowflake RBAC, BigQuery IAM, Row access policies, Column masks, Shared datasets

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## ETL credentials

**Sub-topics:** Airflow connections, dbt profiles, Spark keys in notebooks, Rotation, CI to prod

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## PII in analytics

**Sub-topics:** Hashing vs encryption, Join keys, Re-identification, Sampling leaks, Aggregates

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## BI and dashboards

**Sub-topics:** Embed tokens, RLS in Power BI, Export CSV, Scheduled email, Public links

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Data lakes

**Sub-topics:** S3 path traversal, Parquet metadata, Glue catalog ACL, Lake Formation, Iceberg snapshots

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Streaming analytics

**Sub-topics:** Flink state, Kafka Connect secrets, Exactly-once, Poison records, Schema registry ACL

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Feature stores

**Sub-topics:** Point-in-time leaks, Training-serving skew, Offline online parity, PII in features, Access audit

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Notebooks and ad hoc SQL

**Sub-topics:** Shared workspaces, Output history, Git sync secrets, Cell execution order, Public nbviewer

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Data contracts and quality

**Sub-topics:** Breaking schema, DQ alerts, Tampered sources, Lineage trust, SLA abuse

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Third-party data feeds

**Sub-topics:** License scope, Resale restrictions, API keys shared, Poisoned feeds, Watermarking

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

## Analytics backups

**Sub-topics:** Snapshot sharing, Cross-account, Restore to dev PII, Retention, Encryption

### Do (use this in SQLAlchemy)

- SQLAlchemy is not the primary enforcement point for `data-engineering-analytics`; load stack skill `security-data-engineering-analytics` when you touch that layer.
- Keep SQLAlchemy configuration aligned with requirements from `security-data-engineering-analytics` (domain reference.md).

### Don't

- Do not duplicate `data-engineering-analytics` controls only in SQLAlchemy config while leaving security-data-engineering-analytics misconfigured.
- Do not assume SQLAlchemy defaults satisfy `security-data-engineering-analytics` without verification.

### Verify

- Integration test the full path: SQLAlchemy plus the system covered by `security-data-engineering-analytics`.

