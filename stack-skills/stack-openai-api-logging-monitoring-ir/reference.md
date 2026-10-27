# OpenAI API / Agents SDK: Logging, monitoring, and incident response

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-logging-monitoring-ir` / `reference.md`.

## Structured logging

**Sub-topics:** Correlation IDs, PII redaction, Threat modeling and trust boundaries (Structured logging), Abuse cases and adversarial testing (Structured logging), Logging, audit, and detection (Structured logging)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## SIEM and alerting

**Sub-topics:** Noise, Tuning, Threat modeling and trust boundaries (SIEM and alerting), Abuse cases and adversarial testing (SIEM and alerting), Logging, audit, and detection (SIEM and alerting)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Audit trails

**Sub-topics:** Tamper evidence, Clock sync, Threat modeling and trust boundaries (Audit trails), Abuse cases and adversarial testing (Audit trails), Logging, audit, and detection (Audit trails)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Incident response playbooks

**Sub-topics:** Roles, Comms, Threat modeling and trust boundaries (Incident response playbooks), Abuse cases and adversarial testing (Incident response playbooks), Logging, audit, and detection (Incident response playbooks)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Forensics readiness

**Sub-topics:** Memory dumps, Chain of custody, Threat modeling and trust boundaries (Forensics readiness), Abuse cases and adversarial testing (Forensics readiness), Logging, audit, and detection (Forensics readiness)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Vulnerability disclosure

**Sub-topics:** Safe harbor, SLAs, Threat modeling and trust boundaries (Vulnerability disclosure), Abuse cases and adversarial testing (Vulnerability disclosure), Logging, audit, and detection (Vulnerability disclosure)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Security on-call

**Sub-topics:** Escalation, Paging hygiene, Threat modeling and trust boundaries (Security on-call), Abuse cases and adversarial testing (Security on-call), Logging, audit, and detection (Security on-call)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Security metrics

**Sub-topics:** MTTD, Patch latency, Threat modeling and trust boundaries (Security metrics), Abuse cases and adversarial testing (Security metrics), Logging, audit, and detection (Security metrics)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Deception and honeypots

**Sub-topics:** Legal, Scope, Threat modeling and trust boundaries (Deception and honeypots), Abuse cases and adversarial testing (Deception and honeypots), Logging, audit, and detection (Deception and honeypots)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## UEBA

**Sub-topics:** Insider threat, False positives, Threat modeling and trust boundaries (UEBA), Abuse cases and adversarial testing (UEBA), Logging, audit, and detection (UEBA)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Post-incident review

**Sub-topics:** Blameless, Tracking, Threat modeling and trust boundaries (Post-incident review), Abuse cases and adversarial testing (Post-incident review), Logging, audit, and detection (Post-incident review)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Lawful access logs

**Sub-topics:** Subpoena, Customer notice, Threat modeling and trust boundaries (Lawful access logs), Abuse cases and adversarial testing (Lawful access logs), Logging, audit, and detection (Lawful access logs)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

