# LangChain / LangGraph: Data protection and databases

Stack-specific implementation for **LangChain / LangGraph** (AI). Normative rules: domain skill `security-data-databases` / `reference.md`.

## Relational databases

**Sub-topics:** PostgreSQL, MySQL, Migrations, Threat modeling and trust boundaries (Relational databases), Abuse cases and adversarial testing (Relational databases)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Relational databases; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Relational databases.
- Keep dependencies patched; pin versions for Relational databases components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Relational databases before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Relational databases paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## NoSQL stores

**Sub-topics:** MongoDB, DynamoDB, Redis, Threat modeling and trust boundaries (NoSQL stores), Abuse cases and adversarial testing (NoSQL stores)

### Platform rules (summary)

- Validate and canonicalize all inputs touching NoSQL stores; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NoSQL stores.
- Keep dependencies patched; pin versions for NoSQL stores components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for NoSQL stores before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for NoSQL stores paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## ORM and query builders

**Sub-topics:** N+1, Raw SQL escape hatches, Threat modeling and trust boundaries (ORM and query builders), Abuse cases and adversarial testing (ORM and query builders), Logging, audit, and detection (ORM and query builders)

### Platform rules (summary)

- Validate and canonicalize all inputs touching ORM and query builders; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ORM and query builders.
- Keep dependencies patched; pin versions for ORM and query builders components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for ORM and query builders before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for ORM and query builders paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Encryption at rest

**Sub-topics:** TDE, Column-level, KMS integration, Threat modeling and trust boundaries (Encryption at rest), Abuse cases and adversarial testing (Encryption at rest)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Encryption at rest; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Encryption at rest.
- Keep dependencies patched; pin versions for Encryption at rest components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Encryption at rest before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Encryption at rest paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Backup and restore

**Sub-topics:** Ransomware, Test restores, Offsite, Threat modeling and trust boundaries (Backup and restore), Abuse cases and adversarial testing (Backup and restore)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Backup and restore; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Backup and restore.
- Keep dependencies patched; pin versions for Backup and restore components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Backup and restore before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Backup and restore paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Replication and CDC

**Sub-topics:** Lag, Read replica exposure, Threat modeling and trust boundaries (Replication and CDC), Abuse cases and adversarial testing (Replication and CDC), Logging, audit, and detection (Replication and CDC)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Replication and CDC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Replication and CDC.
- Keep dependencies patched; pin versions for Replication and CDC components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Replication and CDC before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Replication and CDC paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Data minimization

**Sub-topics:** Retention, Anonymization, Threat modeling and trust boundaries (Data minimization), Abuse cases and adversarial testing (Data minimization), Logging, audit, and detection (Data minimization)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Data minimization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data minimization.
- Keep dependencies patched; pin versions for Data minimization components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Data minimization before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Data minimization paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## PII and sensitive fields

**Sub-topics:** Tokenization, Masking in logs, Threat modeling and trust boundaries (PII and sensitive fields), Abuse cases and adversarial testing (PII and sensitive fields), Logging, audit, and detection (PII and sensitive fields)

### Platform rules (summary)

- Validate and canonicalize all inputs touching PII and sensitive fields; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII and sensitive fields.
- Keep dependencies patched; pin versions for PII and sensitive fields components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PII and sensitive fields before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PII and sensitive fields paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Schema migrations safety

**Sub-topics:** Destructive changes, Locking, Threat modeling and trust boundaries (Schema migrations safety), Abuse cases and adversarial testing (Schema migrations safety), Logging, audit, and detection (Schema migrations safety)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Schema migrations safety; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Schema migrations safety.
- Keep dependencies patched; pin versions for Schema migrations safety components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Schema migrations safety before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Schema migrations safety paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Connection strings and pooling

**Sub-topics:** Credential rotation, TLS to DB, Threat modeling and trust boundaries (Connection strings and pooling), Abuse cases and adversarial testing (Connection strings and pooling), Logging, audit, and detection (Connection strings and pooling)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Connection strings and pooling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Connection strings and pooling.
- Keep dependencies patched; pin versions for Connection strings and pooling components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Connection strings and pooling before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Connection strings and pooling paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Row-level and column security

**Sub-topics:** RLS policies, Views, Threat modeling and trust boundaries (Row-level and column security), Abuse cases and adversarial testing (Row-level and column security), Logging, audit, and detection (Row-level and column security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Row-level and column security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Row-level and column security.
- Keep dependencies patched; pin versions for Row-level and column security components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Row-level and column security before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Row-level and column security paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Search indexes

**Sub-topics:** Elasticsearch exposure, Leaked fields, Threat modeling and trust boundaries (Search indexes), Abuse cases and adversarial testing (Search indexes), Logging, audit, and detection (Search indexes)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Search indexes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Search indexes.
- Keep dependencies patched; pin versions for Search indexes components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-data-databases` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Search indexes before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Search indexes paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

