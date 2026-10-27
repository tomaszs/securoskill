# Kubernetes: Data protection and databases

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-data-databases` / `reference.md`.

## Relational databases

**Sub-topics:** PostgreSQL, MySQL, Migrations, Threat modeling and trust boundaries (Relational databases), Abuse cases and adversarial testing (Relational databases)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## NoSQL stores

**Sub-topics:** MongoDB, DynamoDB, Redis, Threat modeling and trust boundaries (NoSQL stores), Abuse cases and adversarial testing (NoSQL stores)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## ORM and query builders

**Sub-topics:** N+1, Raw SQL escape hatches, Threat modeling and trust boundaries (ORM and query builders), Abuse cases and adversarial testing (ORM and query builders), Logging, audit, and detection (ORM and query builders)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Encryption at rest

**Sub-topics:** TDE, Column-level, KMS integration, Threat modeling and trust boundaries (Encryption at rest), Abuse cases and adversarial testing (Encryption at rest)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Backup and restore

**Sub-topics:** Ransomware, Test restores, Offsite, Threat modeling and trust boundaries (Backup and restore), Abuse cases and adversarial testing (Backup and restore)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Replication and CDC

**Sub-topics:** Lag, Read replica exposure, Threat modeling and trust boundaries (Replication and CDC), Abuse cases and adversarial testing (Replication and CDC), Logging, audit, and detection (Replication and CDC)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Data minimization

**Sub-topics:** Retention, Anonymization, Threat modeling and trust boundaries (Data minimization), Abuse cases and adversarial testing (Data minimization), Logging, audit, and detection (Data minimization)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## PII and sensitive fields

**Sub-topics:** Tokenization, Masking in logs, Threat modeling and trust boundaries (PII and sensitive fields), Abuse cases and adversarial testing (PII and sensitive fields), Logging, audit, and detection (PII and sensitive fields)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Schema migrations safety

**Sub-topics:** Destructive changes, Locking, Threat modeling and trust boundaries (Schema migrations safety), Abuse cases and adversarial testing (Schema migrations safety), Logging, audit, and detection (Schema migrations safety)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Connection strings and pooling

**Sub-topics:** Credential rotation, TLS to DB, Threat modeling and trust boundaries (Connection strings and pooling), Abuse cases and adversarial testing (Connection strings and pooling), Logging, audit, and detection (Connection strings and pooling)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Row-level and column security

**Sub-topics:** RLS policies, Views, Threat modeling and trust boundaries (Row-level and column security), Abuse cases and adversarial testing (Row-level and column security), Logging, audit, and detection (Row-level and column security)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

## Search indexes

**Sub-topics:** Elasticsearch exposure, Leaked fields, Threat modeling and trust boundaries (Search indexes), Abuse cases and adversarial testing (Search indexes), Logging, audit, and detection (Search indexes)

### Do (use this in Kubernetes)

- Kubernetes is not the primary enforcement point for `data-databases`; load stack skill `stack-postgresql-data-databases (or your DB/ORM stack)` when you touch that layer.
- Keep Kubernetes configuration aligned with requirements from `security-data-databases` (domain reference.md).

### Don't

- Do not duplicate `data-databases` controls only in Kubernetes config while leaving stack-postgresql-data-databases (or your DB/ORM stack) misconfigured.
- Do not assume Kubernetes defaults satisfy `security-data-databases` without verification.

### Verify

- Integration test the full path: Kubernetes plus the system covered by `stack-postgresql-data-databases (or your DB/ORM stack)`.

