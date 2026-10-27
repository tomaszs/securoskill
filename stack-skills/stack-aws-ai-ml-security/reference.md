# Amazon Web Services: AI and ML system security

Stack-specific implementation for **Amazon Web Services** (Cloud). Normative rules: domain skill `security-ai-ml-security` / `reference.md`.

## Prompt injection

**Sub-topics:** Indirect injection, Tool abuse, Threat modeling and trust boundaries (Prompt injection), Abuse cases and adversarial testing (Prompt injection), Logging, audit, and detection (Prompt injection)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Prompt injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Prompt injection.
- Keep dependencies patched; pin versions for Prompt injection components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Prompt injection before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Prompt injection paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## RAG and retrieval

**Sub-topics:** Poisoned documents, ACL on chunks, Threat modeling and trust boundaries (RAG and retrieval), Abuse cases and adversarial testing (RAG and retrieval), Logging, audit, and detection (RAG and retrieval)

### Platform rules (summary)

- Validate and canonicalize all inputs touching RAG and retrieval; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RAG and retrieval.
- Keep dependencies patched; pin versions for RAG and retrieval components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for RAG and retrieval before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for RAG and retrieval paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Model abuse and cost

**Sub-topics:** Token flooding, Unbounded context, Threat modeling and trust boundaries (Model abuse and cost), Abuse cases and adversarial testing (Model abuse and cost), Logging, audit, and detection (Model abuse and cost)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Model abuse and cost; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Model abuse and cost.
- Keep dependencies patched; pin versions for Model abuse and cost components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Model abuse and cost before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Model abuse and cost paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Training data poisoning

**Sub-topics:** PII in datasets, Threat modeling and trust boundaries (Training data poisoning), Abuse cases and adversarial testing (Training data poisoning), Logging, audit, and detection (Training data poisoning), Access control and least privilege (Training data poisoning)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Training data poisoning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Training data poisoning.
- Keep dependencies patched; pin versions for Training data poisoning components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Training data poisoning before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Training data poisoning paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Model and weight exfiltration

**Sub-topics:** API leakage, Threat modeling and trust boundaries (Model and weight exfiltration), Abuse cases and adversarial testing (Model and weight exfiltration), Logging, audit, and detection (Model and weight exfiltration), Access control and least privilege (Model and weight exfiltration)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Model and weight exfiltration; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Model and weight exfiltration.
- Keep dependencies patched; pin versions for Model and weight exfiltration components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Model and weight exfiltration before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Model and weight exfiltration paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Agent tool invocation

**Sub-topics:** SSRF via tools, Shell tools, Threat modeling and trust boundaries (Agent tool invocation), Abuse cases and adversarial testing (Agent tool invocation), Logging, audit, and detection (Agent tool invocation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Agent tool invocation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Agent tool invocation.
- Keep dependencies patched; pin versions for Agent tool invocation components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Agent tool invocation before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Agent tool invocation paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Unsafe outputs

**Sub-topics:** Code execution suggestions, XSS in chat UI, Threat modeling and trust boundaries (Unsafe outputs), Abuse cases and adversarial testing (Unsafe outputs), Logging, audit, and detection (Unsafe outputs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Unsafe outputs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Unsafe outputs.
- Keep dependencies patched; pin versions for Unsafe outputs components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Unsafe outputs before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Unsafe outputs paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Red teaming LLMs

**Sub-topics:** Jailbreaks, Benchmarks, Threat modeling and trust boundaries (Red teaming LLMs), Abuse cases and adversarial testing (Red teaming LLMs), Logging, audit, and detection (Red teaming LLMs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Red teaming LLMs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Red teaming LLMs.
- Keep dependencies patched; pin versions for Red teaming LLMs components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Red teaming LLMs before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Red teaming LLMs paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Fine-tuning access

**Sub-topics:** Tenant isolation, Threat modeling and trust boundaries (Fine-tuning access), Abuse cases and adversarial testing (Fine-tuning access), Logging, audit, and detection (Fine-tuning access), Access control and least privilege (Fine-tuning access)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Fine-tuning access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Fine-tuning access.
- Keep dependencies patched; pin versions for Fine-tuning access components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Fine-tuning access before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Fine-tuning access paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Embeddings privacy

**Sub-topics:** Membership inference, Threat modeling and trust boundaries (Embeddings privacy), Abuse cases and adversarial testing (Embeddings privacy), Logging, audit, and detection (Embeddings privacy), Access control and least privilege (Embeddings privacy)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Embeddings privacy; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Embeddings privacy.
- Keep dependencies patched; pin versions for Embeddings privacy components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Embeddings privacy before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Embeddings privacy paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## MCP and external tools

**Sub-topics:** OAuth to tools, Scope, Threat modeling and trust boundaries (MCP and external tools), Abuse cases and adversarial testing (MCP and external tools), Logging, audit, and detection (MCP and external tools)

### Platform rules (summary)

- Validate and canonicalize all inputs touching MCP and external tools; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MCP and external tools.
- Keep dependencies patched; pin versions for MCP and external tools components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for MCP and external tools before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for MCP and external tools paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## AI governance

**Sub-topics:** Human review, Logging prompts, Threat modeling and trust boundaries (AI governance), Abuse cases and adversarial testing (AI governance), Logging, audit, and detection (AI governance)

### Platform rules (summary)

- Validate and canonicalize all inputs touching AI governance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to AI governance.
- Keep dependencies patched; pin versions for AI governance components.

### How to do this in Amazon Web Services

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from Amazon Web Services.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-ai-ml-security` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for AI governance before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for AI governance paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

