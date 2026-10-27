# Rules reference: Data engineering, analytics, and BI security

ETL, warehouses, lakes, and reporting pipelines.

## Warehouse access control

Sub-topics: Snowflake RBAC, BigQuery IAM, Row access policies, Column masks, Shared datasets

### Do

- Validate and canonicalize all inputs touching Warehouse access control; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Warehouse access control.
- Keep dependencies patched; pin versions for Warehouse access control components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Warehouse access control in Warehouse access control as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Warehouse access control (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Warehouse access control.

### Design

- Apply least privilege and defense in depth for Warehouse access control.
- Prefer established patterns and libraries over custom crypto or auth for Warehouse access control.
- Fail closed: deny by default when Warehouse access control cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Warehouse access control; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Warehouse access control.
- Keep dependencies patched; pin versions for Warehouse access control components.

### Verification

- Add automated tests and SAST/DAST coverage for Warehouse access control paths.
- Run dependency and secret scanning on every change touching Warehouse access control.
- Perform targeted manual tests (abuse cases) for Warehouse access control.

### Operations

- Log security-relevant events for Warehouse access control without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Warehouse access control.
- Review access and configuration for Warehouse access control on a regular cadence.

## ETL credentials

Sub-topics: Airflow connections, dbt profiles, Spark keys in notebooks, Rotation, CI to prod

### Do

- Validate and canonicalize all inputs touching ETL credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ETL credentials.
- Keep dependencies patched; pin versions for ETL credentials components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat ETL credentials in ETL credentials as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for ETL credentials (Data engineering, analytics, and BI security).
- Require security review for material changes affecting ETL credentials.

### Design

- Apply least privilege and defense in depth for ETL credentials.
- Prefer established patterns and libraries over custom crypto or auth for ETL credentials.
- Fail closed: deny by default when ETL credentials cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching ETL credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ETL credentials.
- Keep dependencies patched; pin versions for ETL credentials components.

### Verification

- Add automated tests and SAST/DAST coverage for ETL credentials paths.
- Run dependency and secret scanning on every change touching ETL credentials.
- Perform targeted manual tests (abuse cases) for ETL credentials.

### Operations

- Log security-relevant events for ETL credentials without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in ETL credentials.
- Review access and configuration for ETL credentials on a regular cadence.

## Pipeline injection

Sub-topics: SQL in dbt, Dynamic partitions, User-supplied SQL, Jinja in queries, UDF sandbox

### Do

- Validate and canonicalize all inputs touching Pipeline injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Pipeline injection.
- Keep dependencies patched; pin versions for Pipeline injection components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Pipeline injection in Pipeline injection as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Pipeline injection (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Pipeline injection.

### Design

- Apply least privilege and defense in depth for Pipeline injection.
- Prefer established patterns and libraries over custom crypto or auth for Pipeline injection.
- Fail closed: deny by default when Pipeline injection cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Pipeline injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Pipeline injection.
- Keep dependencies patched; pin versions for Pipeline injection components.

### Verification

- Add automated tests and SAST/DAST coverage for Pipeline injection paths.
- Run dependency and secret scanning on every change touching Pipeline injection.
- Perform targeted manual tests (abuse cases) for Pipeline injection.

### Operations

- Log security-relevant events for Pipeline injection without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Pipeline injection.
- Review access and configuration for Pipeline injection on a regular cadence.

## PII in analytics

Sub-topics: Hashing vs encryption, Join keys, Re-identification, Sampling leaks, Aggregates

### Do

- Validate and canonicalize all inputs touching PII in analytics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in analytics.
- Keep dependencies patched; pin versions for PII in analytics components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat PII in analytics in PII in analytics as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PII in analytics (Data engineering, analytics, and BI security).
- Require security review for material changes affecting PII in analytics.

### Design

- Apply least privilege and defense in depth for PII in analytics.
- Prefer established patterns and libraries over custom crypto or auth for PII in analytics.
- Fail closed: deny by default when PII in analytics cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PII in analytics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in analytics.
- Keep dependencies patched; pin versions for PII in analytics components.

### Verification

- Add automated tests and SAST/DAST coverage for PII in analytics paths.
- Run dependency and secret scanning on every change touching PII in analytics.
- Perform targeted manual tests (abuse cases) for PII in analytics.

### Operations

- Log security-relevant events for PII in analytics without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PII in analytics.
- Review access and configuration for PII in analytics on a regular cadence.

## BI and dashboards

Sub-topics: Embed tokens, RLS in Power BI, Export CSV, Scheduled email, Public links

### Do

- Validate and canonicalize all inputs touching BI and dashboards; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to BI and dashboards.
- Keep dependencies patched; pin versions for BI and dashboards components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat BI and dashboards in BI and dashboards as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for BI and dashboards (Data engineering, analytics, and BI security).
- Require security review for material changes affecting BI and dashboards.

### Design

- Apply least privilege and defense in depth for BI and dashboards.
- Prefer established patterns and libraries over custom crypto or auth for BI and dashboards.
- Fail closed: deny by default when BI and dashboards cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching BI and dashboards; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to BI and dashboards.
- Keep dependencies patched; pin versions for BI and dashboards components.

### Verification

- Add automated tests and SAST/DAST coverage for BI and dashboards paths.
- Run dependency and secret scanning on every change touching BI and dashboards.
- Perform targeted manual tests (abuse cases) for BI and dashboards.

### Operations

- Log security-relevant events for BI and dashboards without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in BI and dashboards.
- Review access and configuration for BI and dashboards on a regular cadence.

## Data lakes

Sub-topics: S3 path traversal, Parquet metadata, Glue catalog ACL, Lake Formation, Iceberg snapshots

### Do

- Validate and canonicalize all inputs touching Data lakes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data lakes.
- Keep dependencies patched; pin versions for Data lakes components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Data lakes in Data lakes as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Data lakes (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Data lakes.

### Design

- Apply least privilege and defense in depth for Data lakes.
- Prefer established patterns and libraries over custom crypto or auth for Data lakes.
- Fail closed: deny by default when Data lakes cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Data lakes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data lakes.
- Keep dependencies patched; pin versions for Data lakes components.

### Verification

- Add automated tests and SAST/DAST coverage for Data lakes paths.
- Run dependency and secret scanning on every change touching Data lakes.
- Perform targeted manual tests (abuse cases) for Data lakes.

### Operations

- Log security-relevant events for Data lakes without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Data lakes.
- Review access and configuration for Data lakes on a regular cadence.

## Streaming analytics

Sub-topics: Flink state, Kafka Connect secrets, Exactly-once, Poison records, Schema registry ACL

### Do

- Validate and canonicalize all inputs touching Streaming analytics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Streaming analytics.
- Keep dependencies patched; pin versions for Streaming analytics components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Streaming analytics in Streaming analytics as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Streaming analytics (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Streaming analytics.

### Design

- Apply least privilege and defense in depth for Streaming analytics.
- Prefer established patterns and libraries over custom crypto or auth for Streaming analytics.
- Fail closed: deny by default when Streaming analytics cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Streaming analytics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Streaming analytics.
- Keep dependencies patched; pin versions for Streaming analytics components.

### Verification

- Add automated tests and SAST/DAST coverage for Streaming analytics paths.
- Run dependency and secret scanning on every change touching Streaming analytics.
- Perform targeted manual tests (abuse cases) for Streaming analytics.

### Operations

- Log security-relevant events for Streaming analytics without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Streaming analytics.
- Review access and configuration for Streaming analytics on a regular cadence.

## Feature stores

Sub-topics: Point-in-time leaks, Training-serving skew, Offline online parity, PII in features, Access audit

### Do

- Validate and canonicalize all inputs touching Feature stores; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature stores.
- Keep dependencies patched; pin versions for Feature stores components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Feature stores in Feature stores as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Feature stores (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Feature stores.

### Design

- Apply least privilege and defense in depth for Feature stores.
- Prefer established patterns and libraries over custom crypto or auth for Feature stores.
- Fail closed: deny by default when Feature stores cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Feature stores; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature stores.
- Keep dependencies patched; pin versions for Feature stores components.

### Verification

- Add automated tests and SAST/DAST coverage for Feature stores paths.
- Run dependency and secret scanning on every change touching Feature stores.
- Perform targeted manual tests (abuse cases) for Feature stores.

### Operations

- Log security-relevant events for Feature stores without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Feature stores.
- Review access and configuration for Feature stores on a regular cadence.

## Notebooks and ad hoc SQL

Sub-topics: Shared workspaces, Output history, Git sync secrets, Cell execution order, Public nbviewer

### Do

- Validate and canonicalize all inputs touching Notebooks and ad hoc SQL; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Notebooks and ad hoc SQL.
- Keep dependencies patched; pin versions for Notebooks and ad hoc SQL components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Notebooks and ad hoc SQL in Notebooks and ad hoc SQL as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Notebooks and ad hoc SQL (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Notebooks and ad hoc SQL.

### Design

- Apply least privilege and defense in depth for Notebooks and ad hoc SQL.
- Prefer established patterns and libraries over custom crypto or auth for Notebooks and ad hoc SQL.
- Fail closed: deny by default when Notebooks and ad hoc SQL cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Notebooks and ad hoc SQL; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Notebooks and ad hoc SQL.
- Keep dependencies patched; pin versions for Notebooks and ad hoc SQL components.

### Verification

- Add automated tests and SAST/DAST coverage for Notebooks and ad hoc SQL paths.
- Run dependency and secret scanning on every change touching Notebooks and ad hoc SQL.
- Perform targeted manual tests (abuse cases) for Notebooks and ad hoc SQL.

### Operations

- Log security-relevant events for Notebooks and ad hoc SQL without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Notebooks and ad hoc SQL.
- Review access and configuration for Notebooks and ad hoc SQL on a regular cadence.

## Data contracts and quality

Sub-topics: Breaking schema, DQ alerts, Tampered sources, Lineage trust, SLA abuse

### Do

- Validate and canonicalize all inputs touching Data contracts and quality; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data contracts and quality.
- Keep dependencies patched; pin versions for Data contracts and quality components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Data contracts and quality in Data contracts and quality as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Data contracts and quality (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Data contracts and quality.

### Design

- Apply least privilege and defense in depth for Data contracts and quality.
- Prefer established patterns and libraries over custom crypto or auth for Data contracts and quality.
- Fail closed: deny by default when Data contracts and quality cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Data contracts and quality; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data contracts and quality.
- Keep dependencies patched; pin versions for Data contracts and quality components.

### Verification

- Add automated tests and SAST/DAST coverage for Data contracts and quality paths.
- Run dependency and secret scanning on every change touching Data contracts and quality.
- Perform targeted manual tests (abuse cases) for Data contracts and quality.

### Operations

- Log security-relevant events for Data contracts and quality without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Data contracts and quality.
- Review access and configuration for Data contracts and quality on a regular cadence.

## Third-party data feeds

Sub-topics: License scope, Resale restrictions, API keys shared, Poisoned feeds, Watermarking

### Do

- Validate and canonicalize all inputs touching Third-party data feeds; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party data feeds.
- Keep dependencies patched; pin versions for Third-party data feeds components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Third-party data feeds in Third-party data feeds as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Third-party data feeds (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Third-party data feeds.

### Design

- Apply least privilege and defense in depth for Third-party data feeds.
- Prefer established patterns and libraries over custom crypto or auth for Third-party data feeds.
- Fail closed: deny by default when Third-party data feeds cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Third-party data feeds; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party data feeds.
- Keep dependencies patched; pin versions for Third-party data feeds components.

### Verification

- Add automated tests and SAST/DAST coverage for Third-party data feeds paths.
- Run dependency and secret scanning on every change touching Third-party data feeds.
- Perform targeted manual tests (abuse cases) for Third-party data feeds.

### Operations

- Log security-relevant events for Third-party data feeds without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Third-party data feeds.
- Review access and configuration for Third-party data feeds on a regular cadence.

## Analytics backups

Sub-topics: Snapshot sharing, Cross-account, Restore to dev PII, Retention, Encryption

### Do

- Validate and canonicalize all inputs touching Analytics backups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Analytics backups.
- Keep dependencies patched; pin versions for Analytics backups components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Analytics backups in Analytics backups as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Analytics backups (Data engineering, analytics, and BI security).
- Require security review for material changes affecting Analytics backups.

### Design

- Apply least privilege and defense in depth for Analytics backups.
- Prefer established patterns and libraries over custom crypto or auth for Analytics backups.
- Fail closed: deny by default when Analytics backups cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Analytics backups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Analytics backups.
- Keep dependencies patched; pin versions for Analytics backups components.

### Verification

- Add automated tests and SAST/DAST coverage for Analytics backups paths.
- Run dependency and secret scanning on every change touching Analytics backups.
- Perform targeted manual tests (abuse cases) for Analytics backups.

### Operations

- Log security-relevant events for Analytics backups without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Analytics backups.
- Review access and configuration for Analytics backups on a regular cadence.

