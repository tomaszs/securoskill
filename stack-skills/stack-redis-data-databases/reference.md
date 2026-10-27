# Redis: Data protection and databases

Stack-specific implementation for **Redis** (Database). Normative rules: domain skill `security-data-databases` / `reference.md`.

## Relational databases

**Sub-topics:** PostgreSQL, MySQL, Migrations, Threat modeling and trust boundaries (Relational databases), Abuse cases and adversarial testing (Relational databases)

### Do (use this in Redis)

- Map `Relational databases` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Relational databases` before merge.

### Don't

- Do not ship `Relational databases` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Relational databases`.

### Verify

- Peer review `Relational databases` against domain skill `security-data-databases`.

## NoSQL stores

**Sub-topics:** MongoDB, DynamoDB, Redis, Threat modeling and trust boundaries (NoSQL stores), Abuse cases and adversarial testing (NoSQL stores)

### Do (use this in Redis)

- Map `NoSQL stores` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `NoSQL stores` before merge.

### Don't

- Do not ship `NoSQL stores` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `NoSQL stores`.

### Verify

- Peer review `NoSQL stores` against domain skill `security-data-databases`.

## ORM and query builders

**Sub-topics:** N+1, Raw SQL escape hatches, Threat modeling and trust boundaries (ORM and query builders), Abuse cases and adversarial testing (ORM and query builders), Logging, audit, and detection (ORM and query builders)

### Do (use this in Redis)

- Map `ORM and query builders` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `ORM and query builders` before merge.

### Don't

- Do not ship `ORM and query builders` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `ORM and query builders`.

### Verify

- Peer review `ORM and query builders` against domain skill `security-data-databases`.

## Encryption at rest

**Sub-topics:** TDE, Column-level, KMS integration, Threat modeling and trust boundaries (Encryption at rest), Abuse cases and adversarial testing (Encryption at rest)

### Do (use this in Redis)

- Map `Encryption at rest` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Encryption at rest` before merge.

### Don't

- Do not ship `Encryption at rest` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Encryption at rest`.

### Verify

- Peer review `Encryption at rest` against domain skill `security-data-databases`.

## Backup and restore

**Sub-topics:** Ransomware, Test restores, Offsite, Threat modeling and trust boundaries (Backup and restore), Abuse cases and adversarial testing (Backup and restore)

### Do (use this in Redis)

- Map `Backup and restore` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Backup and restore` before merge.

### Don't

- Do not ship `Backup and restore` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Backup and restore`.

### Verify

- Peer review `Backup and restore` against domain skill `security-data-databases`.

## Replication and CDC

**Sub-topics:** Lag, Read replica exposure, Threat modeling and trust boundaries (Replication and CDC), Abuse cases and adversarial testing (Replication and CDC), Logging, audit, and detection (Replication and CDC)

### Do (use this in Redis)

- Map `Replication and CDC` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Replication and CDC` before merge.

### Don't

- Do not ship `Replication and CDC` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Replication and CDC`.

### Verify

- Peer review `Replication and CDC` against domain skill `security-data-databases`.

## Data minimization

**Sub-topics:** Retention, Anonymization, Threat modeling and trust boundaries (Data minimization), Abuse cases and adversarial testing (Data minimization), Logging, audit, and detection (Data minimization)

### Do (use this in Redis)

- Map `Data minimization` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Data minimization` before merge.

### Don't

- Do not ship `Data minimization` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Data minimization`.

### Verify

- Peer review `Data minimization` against domain skill `security-data-databases`.

## PII and sensitive fields

**Sub-topics:** Tokenization, Masking in logs, Threat modeling and trust boundaries (PII and sensitive fields), Abuse cases and adversarial testing (PII and sensitive fields), Logging, audit, and detection (PII and sensitive fields)

### Do (use this in Redis)

- Map `PII and sensitive fields` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `PII and sensitive fields` before merge.

### Don't

- Do not ship `PII and sensitive fields` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `PII and sensitive fields`.

### Verify

- Peer review `PII and sensitive fields` against domain skill `security-data-databases`.

## Schema migrations safety

**Sub-topics:** Destructive changes, Locking, Threat modeling and trust boundaries (Schema migrations safety), Abuse cases and adversarial testing (Schema migrations safety), Logging, audit, and detection (Schema migrations safety)

### Do (use this in Redis)

- Map `Schema migrations safety` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Schema migrations safety` before merge.

### Don't

- Do not ship `Schema migrations safety` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Schema migrations safety`.

### Verify

- Peer review `Schema migrations safety` against domain skill `security-data-databases`.

## Connection strings and pooling

**Sub-topics:** Credential rotation, TLS to DB, Threat modeling and trust boundaries (Connection strings and pooling), Abuse cases and adversarial testing (Connection strings and pooling), Logging, audit, and detection (Connection strings and pooling)

### Do (use this in Redis)

- Map `Connection strings and pooling` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Connection strings and pooling` before merge.

### Don't

- Do not ship `Connection strings and pooling` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Connection strings and pooling`.

### Verify

- Peer review `Connection strings and pooling` against domain skill `security-data-databases`.

## Row-level and column security

**Sub-topics:** RLS policies, Views, Threat modeling and trust boundaries (Row-level and column security), Abuse cases and adversarial testing (Row-level and column security), Logging, audit, and detection (Row-level and column security)

### Do (use this in Redis)

- Map `Row-level and column security` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Row-level and column security` before merge.

### Don't

- Do not ship `Row-level and column security` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Row-level and column security`.

### Verify

- Peer review `Row-level and column security` against domain skill `security-data-databases`.

## Search indexes

**Sub-topics:** Elasticsearch exposure, Leaked fields, Threat modeling and trust boundaries (Search indexes), Abuse cases and adversarial testing (Search indexes), Logging, audit, and detection (Search indexes)

### Do (use this in Redis)

- Map `Search indexes` controls to Redis APIs documented for `security-data-databases`.
- Add an abuse-case test or check for `Search indexes` before merge.

### Don't

- Do not ship `Search indexes` work in Redis with only happy-path tests.
- Do not disable Redis security defaults to unblock `Search indexes`.

### Verify

- Peer review `Search indexes` against domain skill `security-data-databases`.

