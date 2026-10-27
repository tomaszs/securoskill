# Kotlin / Jetpack Compose: Data engineering, analytics, and BI security

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-data-engineering-analytics` / `reference.md`.

## Warehouse access control

**Sub-topics:** Snowflake RBAC, BigQuery IAM, Row access policies, Column masks, Shared datasets

### Platform rules (summary)

- Validate and canonicalize all inputs touching Warehouse access control; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Warehouse access control.
- Keep dependencies patched; pin versions for Warehouse access control components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Warehouse access control before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Warehouse access control paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## ETL credentials

**Sub-topics:** Airflow connections, dbt profiles, Spark keys in notebooks, Rotation, CI to prod

### Platform rules (summary)

- Validate and canonicalize all inputs touching ETL credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ETL credentials.
- Keep dependencies patched; pin versions for ETL credentials components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for ETL credentials before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for ETL credentials paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Pipeline injection

**Sub-topics:** SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Platform rules (summary)

- Validate and canonicalize all inputs touching Pipeline injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Pipeline injection.
- Keep dependencies patched; pin versions for Pipeline injection components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Pipeline injection before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Pipeline injection paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## PII in analytics

**Sub-topics:** Hashing vs encryption, Join keys, Re-identification, Sampling leaks, Aggregates

### Platform rules (summary)

- Validate and canonicalize all inputs touching PII in analytics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in analytics.
- Keep dependencies patched; pin versions for PII in analytics components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PII in analytics before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PII in analytics paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## BI and dashboards

**Sub-topics:** Embed tokens, RLS in Power BI, Export CSV, Scheduled email, Public links

### Platform rules (summary)

- Validate and canonicalize all inputs touching BI and dashboards; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to BI and dashboards.
- Keep dependencies patched; pin versions for BI and dashboards components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for BI and dashboards before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for BI and dashboards paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Data lakes

**Sub-topics:** S3 path traversal, Parquet metadata, Glue catalog ACL, Lake Formation, Iceberg snapshots

### Platform rules (summary)

- Validate and canonicalize all inputs touching Data lakes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data lakes.
- Keep dependencies patched; pin versions for Data lakes components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Data lakes before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Data lakes paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Streaming analytics

**Sub-topics:** Flink state, Kafka Connect secrets, Exactly-once, Poison records, Schema registry ACL

### Platform rules (summary)

- Validate and canonicalize all inputs touching Streaming analytics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Streaming analytics.
- Keep dependencies patched; pin versions for Streaming analytics components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Streaming analytics before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Streaming analytics paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Feature stores

**Sub-topics:** Point-in-time leaks, Training-serving skew, Offline online parity, PII in features, Access audit

### Platform rules (summary)

- Validate and canonicalize all inputs touching Feature stores; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature stores.
- Keep dependencies patched; pin versions for Feature stores components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Feature stores before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Feature stores paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Notebooks and ad hoc SQL

**Sub-topics:** Shared workspaces, Output history, Git sync secrets, Cell execution order, Public nbviewer

### Platform rules (summary)

- Validate and canonicalize all inputs touching Notebooks and ad hoc SQL; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Notebooks and ad hoc SQL.
- Keep dependencies patched; pin versions for Notebooks and ad hoc SQL components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Notebooks and ad hoc SQL before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Notebooks and ad hoc SQL paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Data contracts and quality

**Sub-topics:** Breaking schema, DQ alerts, Tampered sources, Lineage trust, SLA abuse

### Platform rules (summary)

- Validate and canonicalize all inputs touching Data contracts and quality; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data contracts and quality.
- Keep dependencies patched; pin versions for Data contracts and quality components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Data contracts and quality before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Data contracts and quality paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Third-party data feeds

**Sub-topics:** License scope, Resale restrictions, API keys shared, Poisoned feeds, Watermarking

### Platform rules (summary)

- Validate and canonicalize all inputs touching Third-party data feeds; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party data feeds.
- Keep dependencies patched; pin versions for Third-party data feeds components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Third-party data feeds before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Third-party data feeds paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

## Analytics backups

**Sub-topics:** Snapshot sharing, Cross-account, Restore to dev PII, Retention, Encryption

### Platform rules (summary)

- Validate and canonicalize all inputs touching Analytics backups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Analytics backups.
- Keep dependencies patched; pin versions for Analytics backups components.

### How to do this in Kotlin / Jetpack Compose

- Read normative rules in domain skill `security-data-engineering-analytics` / `reference.md`, then apply them using Kotlin / Jetpack Compose APIs and deployment model.
- Prefer framework-maintained security features in Kotlin / Jetpack Compose over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Analytics backups before merge.
- Pin Kotlin / Jetpack Compose dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Analytics backups paths in Kotlin / Jetpack Compose.
- Run SAST/dependency scan configured for Mobile.

