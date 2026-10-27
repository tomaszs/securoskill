# MongoDB: Data engineering, analytics, and BI security

Stack-specific implementation for **MongoDB** (Database). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Warehouse access control

**Sub-topics:** Snowflake RBAC, BigQuery IAM, Row access policies, Column masks, Shared datasets

### Do (use this in MongoDB)

- Map `Warehouse access control` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Warehouse access control` before merge.

### Don't

- Do not ship `Warehouse access control` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Warehouse access control`.

### Verify

- Peer review `Warehouse access control` against domain skill `security-data-engineering-analytics`.

## ETL credentials

**Sub-topics:** Airflow connections, dbt profiles, Spark keys in notebooks, Rotation, CI to prod

### Do (use this in MongoDB)

- Map `ETL credentials` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `ETL credentials` before merge.

### Don't

- Do not ship `ETL credentials` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `ETL credentials`.

### Verify

- Peer review `ETL credentials` against domain skill `security-data-engineering-analytics`.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do (use this in MongoDB)

- Use typed filters with BSON builders; validate ObjectId strings before queries.

### Don't

- Do not use `$where` with JavaScript from user input.
- Do not pass raw user objects into query operators without schema validation.

### Verify

- Test NoSQL injection payloads on REST filters.

## PII in analytics

**Sub-topics:** Hashing vs encryption, Join keys, Re-identification, Sampling leaks, Aggregates

### Do (use this in MongoDB)

- Map `PII in analytics` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `PII in analytics` before merge.

### Don't

- Do not ship `PII in analytics` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `PII in analytics`.

### Verify

- Peer review `PII in analytics` against domain skill `security-data-engineering-analytics`.

## BI and dashboards

**Sub-topics:** Embed tokens, RLS in Power BI, Export CSV, Scheduled email, Public links

### Do (use this in MongoDB)

- Map `BI and dashboards` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `BI and dashboards` before merge.

### Don't

- Do not ship `BI and dashboards` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `BI and dashboards`.

### Verify

- Peer review `BI and dashboards` against domain skill `security-data-engineering-analytics`.

## Data lakes

**Sub-topics:** S3 path traversal, Parquet metadata, Glue catalog ACL, Lake Formation, Iceberg snapshots

### Do (use this in MongoDB)

- Map `Data lakes` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Data lakes` before merge.

### Don't

- Do not ship `Data lakes` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Data lakes`.

### Verify

- Peer review `Data lakes` against domain skill `security-data-engineering-analytics`.

## Streaming analytics

**Sub-topics:** Flink state, Kafka Connect secrets, Exactly-once, Poison records, Schema registry ACL

### Do (use this in MongoDB)

- Map `Streaming analytics` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Streaming analytics` before merge.

### Don't

- Do not ship `Streaming analytics` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Streaming analytics`.

### Verify

- Peer review `Streaming analytics` against domain skill `security-data-engineering-analytics`.

## Feature stores

**Sub-topics:** Point-in-time leaks, Training-serving skew, Offline online parity, PII in features, Access audit

### Do (use this in MongoDB)

- Map `Feature stores` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Feature stores` before merge.

### Don't

- Do not ship `Feature stores` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Feature stores`.

### Verify

- Peer review `Feature stores` against domain skill `security-data-engineering-analytics`.

## Notebooks and ad hoc SQL

**Sub-topics:** Shared workspaces, Output history, Git sync secrets, Cell execution order, Public nbviewer

### Do (use this in MongoDB)

- Map `Notebooks and ad hoc SQL` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Notebooks and ad hoc SQL` before merge.

### Don't

- Do not ship `Notebooks and ad hoc SQL` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Notebooks and ad hoc SQL`.

### Verify

- Peer review `Notebooks and ad hoc SQL` against domain skill `security-data-engineering-analytics`.

## Data contracts and quality

**Sub-topics:** Breaking schema, DQ alerts, Tampered sources, Lineage trust, SLA abuse

### Do (use this in MongoDB)

- Map `Data contracts and quality` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Data contracts and quality` before merge.

### Don't

- Do not ship `Data contracts and quality` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Data contracts and quality`.

### Verify

- Peer review `Data contracts and quality` against domain skill `security-data-engineering-analytics`.

## Third-party data feeds

**Sub-topics:** License scope, Resale restrictions, API keys shared, Poisoned feeds, Watermarking

### Do (use this in MongoDB)

- Map `Third-party data feeds` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Third-party data feeds` before merge.

### Don't

- Do not ship `Third-party data feeds` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Third-party data feeds`.

### Verify

- Peer review `Third-party data feeds` against domain skill `security-data-engineering-analytics`.

## Analytics backups

**Sub-topics:** Snapshot sharing, Cross-account, Restore to dev PII, Retention, Encryption

### Do (use this in MongoDB)

- Map `Analytics backups` controls to MongoDB APIs documented for `security-data-engineering-analytics`.
- Add an abuse-case test or check for `Analytics backups` before merge.

### Don't

- Do not ship `Analytics backups` work in MongoDB with only happy-path tests.
- Do not disable MongoDB security defaults to unblock `Analytics backups`.

### Verify

- Peer review `Analytics backups` against domain skill `security-data-engineering-analytics`.

