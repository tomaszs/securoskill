# Rules reference: Data protection and databases

RDBMS, NoSQL, warehouses, backups, and encryption at rest.

## Relational databases

Sub-topics: PostgreSQL, MySQL, Migrations, Threat modeling and trust boundaries (Relational databases), Abuse cases and adversarial testing (Relational databases)

### Do

- Validate and canonicalize all inputs touching Relational databases; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Relational databases.
- Keep dependencies patched; pin versions for Relational databases components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Relational databases in Relational databases as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Relational databases (Data protection and databases).
- Require security review for material changes affecting Relational databases.

### Design

- Apply least privilege and defense in depth for Relational databases.
- Prefer established patterns and libraries over custom crypto or auth for Relational databases.
- Fail closed: deny by default when Relational databases cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Relational databases; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Relational databases.
- Keep dependencies patched; pin versions for Relational databases components.

### Verification

- Add automated tests and SAST/DAST coverage for Relational databases paths.
- Run dependency and secret scanning on every change touching Relational databases.
- Perform targeted manual tests (abuse cases) for Relational databases.

### Operations

- Log security-relevant events for Relational databases without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Relational databases.
- Review access and configuration for Relational databases on a regular cadence.

## NoSQL stores

Sub-topics: MongoDB, DynamoDB, Redis, Threat modeling and trust boundaries (NoSQL stores), Abuse cases and adversarial testing (NoSQL stores)

### Do

- Validate and canonicalize all inputs touching NoSQL stores; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NoSQL stores.
- Keep dependencies patched; pin versions for NoSQL stores components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat NoSQL stores in NoSQL stores as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for NoSQL stores (Data protection and databases).
- Require security review for material changes affecting NoSQL stores.

### Design

- Apply least privilege and defense in depth for NoSQL stores.
- Prefer established patterns and libraries over custom crypto or auth for NoSQL stores.
- Fail closed: deny by default when NoSQL stores cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching NoSQL stores; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NoSQL stores.
- Keep dependencies patched; pin versions for NoSQL stores components.

### Verification

- Add automated tests and SAST/DAST coverage for NoSQL stores paths.
- Run dependency and secret scanning on every change touching NoSQL stores.
- Perform targeted manual tests (abuse cases) for NoSQL stores.

### Operations

- Log security-relevant events for NoSQL stores without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in NoSQL stores.
- Review access and configuration for NoSQL stores on a regular cadence.

## ORM and query builders

Sub-topics: N+1, Raw SQL escape hatches, Threat modeling and trust boundaries (ORM and query builders), Abuse cases and adversarial testing (ORM and query builders), Logging, audit, and detection (ORM and query builders)

### Do

- Validate and canonicalize all inputs touching ORM and query builders; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ORM and query builders.
- Keep dependencies patched; pin versions for ORM and query builders components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat ORM and query builders in ORM and query builders as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for ORM and query builders (Data protection and databases).
- Require security review for material changes affecting ORM and query builders.

### Design

- Apply least privilege and defense in depth for ORM and query builders.
- Prefer established patterns and libraries over custom crypto or auth for ORM and query builders.
- Fail closed: deny by default when ORM and query builders cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching ORM and query builders; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ORM and query builders.
- Keep dependencies patched; pin versions for ORM and query builders components.

### Verification

- Add automated tests and SAST/DAST coverage for ORM and query builders paths.
- Run dependency and secret scanning on every change touching ORM and query builders.
- Perform targeted manual tests (abuse cases) for ORM and query builders.

### Operations

- Log security-relevant events for ORM and query builders without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in ORM and query builders.
- Review access and configuration for ORM and query builders on a regular cadence.

## Encryption at rest

Sub-topics: TDE, Column-level, KMS integration, Threat modeling and trust boundaries (Encryption at rest), Abuse cases and adversarial testing (Encryption at rest)

### Do

- Validate and canonicalize all inputs touching Encryption at rest; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Encryption at rest.
- Keep dependencies patched; pin versions for Encryption at rest components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Encryption at rest in Encryption at rest as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Encryption at rest (Data protection and databases).
- Require security review for material changes affecting Encryption at rest.

### Design

- Apply least privilege and defense in depth for Encryption at rest.
- Prefer established patterns and libraries over custom crypto or auth for Encryption at rest.
- Fail closed: deny by default when Encryption at rest cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Encryption at rest; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Encryption at rest.
- Keep dependencies patched; pin versions for Encryption at rest components.

### Verification

- Add automated tests and SAST/DAST coverage for Encryption at rest paths.
- Run dependency and secret scanning on every change touching Encryption at rest.
- Perform targeted manual tests (abuse cases) for Encryption at rest.

### Operations

- Log security-relevant events for Encryption at rest without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Encryption at rest.
- Review access and configuration for Encryption at rest on a regular cadence.

## Backup and restore

Sub-topics: Ransomware, Test restores, Offsite, Threat modeling and trust boundaries (Backup and restore), Abuse cases and adversarial testing (Backup and restore)

### Do

- Validate and canonicalize all inputs touching Backup and restore; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Backup and restore.
- Keep dependencies patched; pin versions for Backup and restore components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Backup and restore in Backup and restore as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Backup and restore (Data protection and databases).
- Require security review for material changes affecting Backup and restore.

### Design

- Apply least privilege and defense in depth for Backup and restore.
- Prefer established patterns and libraries over custom crypto or auth for Backup and restore.
- Fail closed: deny by default when Backup and restore cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Backup and restore; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Backup and restore.
- Keep dependencies patched; pin versions for Backup and restore components.

### Verification

- Add automated tests and SAST/DAST coverage for Backup and restore paths.
- Run dependency and secret scanning on every change touching Backup and restore.
- Perform targeted manual tests (abuse cases) for Backup and restore.

### Operations

- Log security-relevant events for Backup and restore without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Backup and restore.
- Review access and configuration for Backup and restore on a regular cadence.

## Replication and CDC

Sub-topics: Lag, Read replica exposure, Threat modeling and trust boundaries (Replication and CDC), Abuse cases and adversarial testing (Replication and CDC), Logging, audit, and detection (Replication and CDC)

### Do

- Validate and canonicalize all inputs touching Replication and CDC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Replication and CDC.
- Keep dependencies patched; pin versions for Replication and CDC components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Replication and CDC in Replication and CDC as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Replication and CDC (Data protection and databases).
- Require security review for material changes affecting Replication and CDC.

### Design

- Apply least privilege and defense in depth for Replication and CDC.
- Prefer established patterns and libraries over custom crypto or auth for Replication and CDC.
- Fail closed: deny by default when Replication and CDC cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Replication and CDC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Replication and CDC.
- Keep dependencies patched; pin versions for Replication and CDC components.

### Verification

- Add automated tests and SAST/DAST coverage for Replication and CDC paths.
- Run dependency and secret scanning on every change touching Replication and CDC.
- Perform targeted manual tests (abuse cases) for Replication and CDC.

### Operations

- Log security-relevant events for Replication and CDC without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Replication and CDC.
- Review access and configuration for Replication and CDC on a regular cadence.

## Data minimization

Sub-topics: Retention, Anonymization, Threat modeling and trust boundaries (Data minimization), Abuse cases and adversarial testing (Data minimization), Logging, audit, and detection (Data minimization)

### Do

- Validate and canonicalize all inputs touching Data minimization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data minimization.
- Keep dependencies patched; pin versions for Data minimization components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Data minimization in Data minimization as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Data minimization (Data protection and databases).
- Require security review for material changes affecting Data minimization.

### Design

- Apply least privilege and defense in depth for Data minimization.
- Prefer established patterns and libraries over custom crypto or auth for Data minimization.
- Fail closed: deny by default when Data minimization cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Data minimization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data minimization.
- Keep dependencies patched; pin versions for Data minimization components.

### Verification

- Add automated tests and SAST/DAST coverage for Data minimization paths.
- Run dependency and secret scanning on every change touching Data minimization.
- Perform targeted manual tests (abuse cases) for Data minimization.

### Operations

- Log security-relevant events for Data minimization without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Data minimization.
- Review access and configuration for Data minimization on a regular cadence.

## PII and sensitive fields

Sub-topics: Tokenization, Masking in logs, Threat modeling and trust boundaries (PII and sensitive fields), Abuse cases and adversarial testing (PII and sensitive fields), Logging, audit, and detection (PII and sensitive fields)

### Do

- Validate and canonicalize all inputs touching PII and sensitive fields; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII and sensitive fields.
- Keep dependencies patched; pin versions for PII and sensitive fields components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat PII and sensitive fields in PII and sensitive fields as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PII and sensitive fields (Data protection and databases).
- Require security review for material changes affecting PII and sensitive fields.

### Design

- Apply least privilege and defense in depth for PII and sensitive fields.
- Prefer established patterns and libraries over custom crypto or auth for PII and sensitive fields.
- Fail closed: deny by default when PII and sensitive fields cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PII and sensitive fields; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII and sensitive fields.
- Keep dependencies patched; pin versions for PII and sensitive fields components.

### Verification

- Add automated tests and SAST/DAST coverage for PII and sensitive fields paths.
- Run dependency and secret scanning on every change touching PII and sensitive fields.
- Perform targeted manual tests (abuse cases) for PII and sensitive fields.

### Operations

- Log security-relevant events for PII and sensitive fields without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PII and sensitive fields.
- Review access and configuration for PII and sensitive fields on a regular cadence.

## Schema migrations safety

Sub-topics: Destructive changes, Locking, Threat modeling and trust boundaries (Schema migrations safety), Abuse cases and adversarial testing (Schema migrations safety), Logging, audit, and detection (Schema migrations safety)

### Do

- Validate and canonicalize all inputs touching Schema migrations safety; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Schema migrations safety.
- Keep dependencies patched; pin versions for Schema migrations safety components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Schema migrations safety in Schema migrations safety as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Schema migrations safety (Data protection and databases).
- Require security review for material changes affecting Schema migrations safety.

### Design

- Apply least privilege and defense in depth for Schema migrations safety.
- Prefer established patterns and libraries over custom crypto or auth for Schema migrations safety.
- Fail closed: deny by default when Schema migrations safety cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Schema migrations safety; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Schema migrations safety.
- Keep dependencies patched; pin versions for Schema migrations safety components.

### Verification

- Add automated tests and SAST/DAST coverage for Schema migrations safety paths.
- Run dependency and secret scanning on every change touching Schema migrations safety.
- Perform targeted manual tests (abuse cases) for Schema migrations safety.

### Operations

- Log security-relevant events for Schema migrations safety without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Schema migrations safety.
- Review access and configuration for Schema migrations safety on a regular cadence.

## Connection strings and pooling

Sub-topics: Credential rotation, TLS to DB, Threat modeling and trust boundaries (Connection strings and pooling), Abuse cases and adversarial testing (Connection strings and pooling), Logging, audit, and detection (Connection strings and pooling)

### Do

- Validate and canonicalize all inputs touching Connection strings and pooling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Connection strings and pooling.
- Keep dependencies patched; pin versions for Connection strings and pooling components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Connection strings and pooling in Connection strings and pooling as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Connection strings and pooling (Data protection and databases).
- Require security review for material changes affecting Connection strings and pooling.

### Design

- Apply least privilege and defense in depth for Connection strings and pooling.
- Prefer established patterns and libraries over custom crypto or auth for Connection strings and pooling.
- Fail closed: deny by default when Connection strings and pooling cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Connection strings and pooling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Connection strings and pooling.
- Keep dependencies patched; pin versions for Connection strings and pooling components.

### Verification

- Add automated tests and SAST/DAST coverage for Connection strings and pooling paths.
- Run dependency and secret scanning on every change touching Connection strings and pooling.
- Perform targeted manual tests (abuse cases) for Connection strings and pooling.

### Operations

- Log security-relevant events for Connection strings and pooling without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Connection strings and pooling.
- Review access and configuration for Connection strings and pooling on a regular cadence.

## Row-level and column security

Sub-topics: RLS policies, Views, Threat modeling and trust boundaries (Row-level and column security), Abuse cases and adversarial testing (Row-level and column security), Logging, audit, and detection (Row-level and column security)

### Do

- Validate and canonicalize all inputs touching Row-level and column security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Row-level and column security.
- Keep dependencies patched; pin versions for Row-level and column security components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Row-level and column security in Row-level and column security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Row-level and column security (Data protection and databases).
- Require security review for material changes affecting Row-level and column security.

### Design

- Apply least privilege and defense in depth for Row-level and column security.
- Prefer established patterns and libraries over custom crypto or auth for Row-level and column security.
- Fail closed: deny by default when Row-level and column security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Row-level and column security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Row-level and column security.
- Keep dependencies patched; pin versions for Row-level and column security components.

### Verification

- Add automated tests and SAST/DAST coverage for Row-level and column security paths.
- Run dependency and secret scanning on every change touching Row-level and column security.
- Perform targeted manual tests (abuse cases) for Row-level and column security.

### Operations

- Log security-relevant events for Row-level and column security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Row-level and column security.
- Review access and configuration for Row-level and column security on a regular cadence.

## Search indexes

Sub-topics: Elasticsearch exposure, Leaked fields, Threat modeling and trust boundaries (Search indexes), Abuse cases and adversarial testing (Search indexes), Logging, audit, and detection (Search indexes)

### Do

- Validate and canonicalize all inputs touching Search indexes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Search indexes.
- Keep dependencies patched; pin versions for Search indexes components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Search indexes in Search indexes as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Search indexes (Data protection and databases).
- Require security review for material changes affecting Search indexes.

### Design

- Apply least privilege and defense in depth for Search indexes.
- Prefer established patterns and libraries over custom crypto or auth for Search indexes.
- Fail closed: deny by default when Search indexes cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Search indexes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Search indexes.
- Keep dependencies patched; pin versions for Search indexes components.

### Verification

- Add automated tests and SAST/DAST coverage for Search indexes paths.
- Run dependency and secret scanning on every change touching Search indexes.
- Perform targeted manual tests (abuse cases) for Search indexes.

### Operations

- Log security-relevant events for Search indexes without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Search indexes.
- Review access and configuration for Search indexes on a regular cadence.

