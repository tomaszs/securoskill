# Vercel: Data protection and databases

Stack-specific implementation for **Vercel** (Platform). Normative rules: domain skill `security-data-databases` / `reference.md`.

## Relational databases

**Sub-topics:** PostgreSQL, MySQL, Migrations, Threat modeling and trust boundaries (Relational databases), Abuse cases and adversarial testing (Relational databases)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for sql_dba controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## NoSQL stores

**Sub-topics:** MongoDB, DynamoDB, Redis, Threat modeling and trust boundaries (NoSQL stores), Abuse cases and adversarial testing (NoSQL stores)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for nosql controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## ORM and query builders

**Sub-topics:** N+1, Raw SQL escape hatches, Threat modeling and trust boundaries (ORM and query builders), Abuse cases and adversarial testing (ORM and query builders), Logging, audit, and detection (ORM and query builders)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for orm controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Encryption at rest

**Sub-topics:** TDE, Column-level, KMS integration, Threat modeling and trust boundaries (Encryption at rest), Abuse cases and adversarial testing (Encryption at rest)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for encryption_at_rest controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Backup and restore

**Sub-topics:** Ransomware, Test restores, Offsite, Threat modeling and trust boundaries (Backup and restore), Abuse cases and adversarial testing (Backup and restore)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for backups controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Replication and CDC

**Sub-topics:** Lag, Read replica exposure, Threat modeling and trust boundaries (Replication and CDC), Abuse cases and adversarial testing (Replication and CDC), Logging, audit, and detection (Replication and CDC)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for replication controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Data minimization

**Sub-topics:** Retention, Anonymization, Threat modeling and trust boundaries (Data minimization), Abuse cases and adversarial testing (Data minimization), Logging, audit, and detection (Data minimization)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for data_minimization controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## PII and sensitive fields

**Sub-topics:** Tokenization, Masking in logs, Threat modeling and trust boundaries (PII and sensitive fields), Abuse cases and adversarial testing (PII and sensitive fields), Logging, audit, and detection (PII and sensitive fields)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for pii controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Schema migrations safety

**Sub-topics:** Destructive changes, Locking, Threat modeling and trust boundaries (Schema migrations safety), Abuse cases and adversarial testing (Schema migrations safety), Logging, audit, and detection (Schema migrations safety)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for migrations controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Connection strings and pooling

**Sub-topics:** Credential rotation, TLS to DB, Threat modeling and trust boundaries (Connection strings and pooling), Abuse cases and adversarial testing (Connection strings and pooling), Logging, audit, and detection (Connection strings and pooling)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for db_connections controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Row-level and column security

**Sub-topics:** RLS policies, Views, Threat modeling and trust boundaries (Row-level and column security), Abuse cases and adversarial testing (Row-level and column security), Logging, audit, and detection (Row-level and column security)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for rls controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Search indexes

**Sub-topics:** Elasticsearch exposure, Leaked fields, Threat modeling and trust boundaries (Search indexes), Abuse cases and adversarial testing (Search indexes), Logging, audit, and detection (Search indexes)

### Do (use this in Vercel)

- Apply domain skill `security-data-databases` requirements using vercel supported APIs only.
- Use the official vercel security documentation for search_index controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

