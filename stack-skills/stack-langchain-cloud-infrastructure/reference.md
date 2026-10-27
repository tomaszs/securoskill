# LangChain / LangGraph: Cloud and infrastructure security

Stack-specific implementation for **LangChain / LangGraph** (AI). Normative rules: domain skill `security-cloud-infrastructure` / `reference.md`.

## Cloud IAM

**Sub-topics:** Overprivileged roles, IAM conditions, Threat modeling and trust boundaries (Cloud IAM), Abuse cases and adversarial testing (Cloud IAM), Logging, audit, and detection (Cloud IAM)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Object storage buckets

**Sub-topics:** Public ACLs, Policy mistakes, Threat modeling and trust boundaries (Object storage buckets), Abuse cases and adversarial testing (Object storage buckets), Logging, audit, and detection (Object storage buckets)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Compute instances

**Sub-topics:** IMDSv2, SSH keys, Metadata, Threat modeling and trust boundaries (Compute instances), Abuse cases and adversarial testing (Compute instances)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Managed serverless

**Sub-topics:** Function URLs, Concurrency, Threat modeling and trust boundaries (Managed serverless), Abuse cases and adversarial testing (Managed serverless), Logging, audit, and detection (Managed serverless)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Secrets managers

**Sub-topics:** Rotation, Access policies, Threat modeling and trust boundaries (Secrets managers), Abuse cases and adversarial testing (Secrets managers), Logging, audit, and detection (Secrets managers)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## VPC and security groups

**Sub-topics:** 0.0.0.0/0, Peering leaks, Threat modeling and trust boundaries (VPC and security groups), Abuse cases and adversarial testing (VPC and security groups), Logging, audit, and detection (VPC and security groups)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Cloud audit logs

**Sub-topics:** Tampering, Retention, Threat modeling and trust boundaries (Cloud audit logs), Abuse cases and adversarial testing (Cloud audit logs), Logging, audit, and detection (Cloud audit logs)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Infrastructure as code

**Sub-topics:** State files, Drift, Threat modeling and trust boundaries (Infrastructure as code), Abuse cases and adversarial testing (Infrastructure as code), Logging, audit, and detection (Infrastructure as code)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Multi-cloud identity

**Sub-topics:** Federation, Key sprawl, Threat modeling and trust boundaries (Multi-cloud identity), Abuse cases and adversarial testing (Multi-cloud identity), Logging, audit, and detection (Multi-cloud identity)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## SaaS admin consoles

**Sub-topics:** MFA, SCIM, Threat modeling and trust boundaries (SaaS admin consoles), Abuse cases and adversarial testing (SaaS admin consoles), Logging, audit, and detection (SaaS admin consoles)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## CDN and edge

**Sub-topics:** Cache deception, Origin shield, Threat modeling and trust boundaries (CDN and edge), Abuse cases and adversarial testing (CDN and edge), Logging, audit, and detection (CDN and edge)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## DR and regions

**Sub-topics:** Failover security, Data residency, Threat modeling and trust boundaries (DR and regions), Abuse cases and adversarial testing (DR and regions), Logging, audit, and detection (DR and regions)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

