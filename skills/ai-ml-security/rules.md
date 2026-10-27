# Rules reference: AI and ML system security

LLMs, agents, training data, and model serving.

## Prompt injection

Sub-topics: Indirect injection, Tool abuse

### Policy

- Treat Prompt injection in Prompt injection as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Prompt injection (AI and ML system security).
- Require security review for material changes affecting Prompt injection.

### Design

- Apply least privilege and defense in depth for Prompt injection.
- Prefer established patterns and libraries over custom crypto or auth for Prompt injection.
- Fail closed: deny by default when Prompt injection cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Prompt injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Prompt injection.
- Keep dependencies patched; pin versions for Prompt injection components.

### Verification

- Add automated tests and SAST/DAST coverage for Prompt injection paths.
- Run dependency and secret scanning on every change touching Prompt injection.
- Perform targeted manual tests (abuse cases) for Prompt injection.

### Operations

- Log security-relevant events for Prompt injection without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Prompt injection.
- Review access and configuration for Prompt injection on a regular cadence.

## RAG and retrieval

Sub-topics: Poisoned documents, ACL on chunks

### Policy

- Treat RAG and retrieval in RAG and retrieval as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for RAG and retrieval (AI and ML system security).
- Require security review for material changes affecting RAG and retrieval.

### Design

- Apply least privilege and defense in depth for RAG and retrieval.
- Prefer established patterns and libraries over custom crypto or auth for RAG and retrieval.
- Fail closed: deny by default when RAG and retrieval cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching RAG and retrieval; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RAG and retrieval.
- Keep dependencies patched; pin versions for RAG and retrieval components.

### Verification

- Add automated tests and SAST/DAST coverage for RAG and retrieval paths.
- Run dependency and secret scanning on every change touching RAG and retrieval.
- Perform targeted manual tests (abuse cases) for RAG and retrieval.

### Operations

- Log security-relevant events for RAG and retrieval without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in RAG and retrieval.
- Review access and configuration for RAG and retrieval on a regular cadence.

## Model abuse and cost

Sub-topics: Token flooding, Unbounded context

### Policy

- Treat Model abuse and cost in Model abuse and cost as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Model abuse and cost (AI and ML system security).
- Require security review for material changes affecting Model abuse and cost.

### Design

- Apply least privilege and defense in depth for Model abuse and cost.
- Prefer established patterns and libraries over custom crypto or auth for Model abuse and cost.
- Fail closed: deny by default when Model abuse and cost cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Model abuse and cost; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Model abuse and cost.
- Keep dependencies patched; pin versions for Model abuse and cost components.

### Verification

- Add automated tests and SAST/DAST coverage for Model abuse and cost paths.
- Run dependency and secret scanning on every change touching Model abuse and cost.
- Perform targeted manual tests (abuse cases) for Model abuse and cost.

### Operations

- Log security-relevant events for Model abuse and cost without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Model abuse and cost.
- Review access and configuration for Model abuse and cost on a regular cadence.

## Training data poisoning

Sub-topics: PII in datasets

### Policy

- Treat Training data poisoning in Training data poisoning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Training data poisoning (AI and ML system security).
- Require security review for material changes affecting Training data poisoning.

### Design

- Apply least privilege and defense in depth for Training data poisoning.
- Prefer established patterns and libraries over custom crypto or auth for Training data poisoning.
- Fail closed: deny by default when Training data poisoning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Training data poisoning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Training data poisoning.
- Keep dependencies patched; pin versions for Training data poisoning components.

### Verification

- Add automated tests and SAST/DAST coverage for Training data poisoning paths.
- Run dependency and secret scanning on every change touching Training data poisoning.
- Perform targeted manual tests (abuse cases) for Training data poisoning.

### Operations

- Log security-relevant events for Training data poisoning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Training data poisoning.
- Review access and configuration for Training data poisoning on a regular cadence.

## Model and weight exfiltration

Sub-topics: API leakage

### Policy

- Treat Model and weight exfiltration in Model and weight exfiltration as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Model and weight exfiltration (AI and ML system security).
- Require security review for material changes affecting Model and weight exfiltration.

### Design

- Apply least privilege and defense in depth for Model and weight exfiltration.
- Prefer established patterns and libraries over custom crypto or auth for Model and weight exfiltration.
- Fail closed: deny by default when Model and weight exfiltration cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Model and weight exfiltration; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Model and weight exfiltration.
- Keep dependencies patched; pin versions for Model and weight exfiltration components.

### Verification

- Add automated tests and SAST/DAST coverage for Model and weight exfiltration paths.
- Run dependency and secret scanning on every change touching Model and weight exfiltration.
- Perform targeted manual tests (abuse cases) for Model and weight exfiltration.

### Operations

- Log security-relevant events for Model and weight exfiltration without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Model and weight exfiltration.
- Review access and configuration for Model and weight exfiltration on a regular cadence.

## Agent tool invocation

Sub-topics: SSRF via tools, Shell tools

### Policy

- Treat Agent tool invocation in Agent tool invocation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Agent tool invocation (AI and ML system security).
- Require security review for material changes affecting Agent tool invocation.

### Design

- Apply least privilege and defense in depth for Agent tool invocation.
- Prefer established patterns and libraries over custom crypto or auth for Agent tool invocation.
- Fail closed: deny by default when Agent tool invocation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Agent tool invocation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Agent tool invocation.
- Keep dependencies patched; pin versions for Agent tool invocation components.

### Verification

- Add automated tests and SAST/DAST coverage for Agent tool invocation paths.
- Run dependency and secret scanning on every change touching Agent tool invocation.
- Perform targeted manual tests (abuse cases) for Agent tool invocation.

### Operations

- Log security-relevant events for Agent tool invocation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Agent tool invocation.
- Review access and configuration for Agent tool invocation on a regular cadence.

## Unsafe outputs

Sub-topics: Code execution suggestions, XSS in chat UI

### Policy

- Treat Unsafe outputs in Unsafe outputs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Unsafe outputs (AI and ML system security).
- Require security review for material changes affecting Unsafe outputs.

### Design

- Apply least privilege and defense in depth for Unsafe outputs.
- Prefer established patterns and libraries over custom crypto or auth for Unsafe outputs.
- Fail closed: deny by default when Unsafe outputs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Unsafe outputs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Unsafe outputs.
- Keep dependencies patched; pin versions for Unsafe outputs components.

### Verification

- Add automated tests and SAST/DAST coverage for Unsafe outputs paths.
- Run dependency and secret scanning on every change touching Unsafe outputs.
- Perform targeted manual tests (abuse cases) for Unsafe outputs.

### Operations

- Log security-relevant events for Unsafe outputs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Unsafe outputs.
- Review access and configuration for Unsafe outputs on a regular cadence.

## Red teaming LLMs

Sub-topics: Jailbreaks, Benchmarks

### Policy

- Treat Red teaming LLMs in Red teaming LLMs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Red teaming LLMs (AI and ML system security).
- Require security review for material changes affecting Red teaming LLMs.

### Design

- Apply least privilege and defense in depth for Red teaming LLMs.
- Prefer established patterns and libraries over custom crypto or auth for Red teaming LLMs.
- Fail closed: deny by default when Red teaming LLMs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Red teaming LLMs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Red teaming LLMs.
- Keep dependencies patched; pin versions for Red teaming LLMs components.

### Verification

- Add automated tests and SAST/DAST coverage for Red teaming LLMs paths.
- Run dependency and secret scanning on every change touching Red teaming LLMs.
- Perform targeted manual tests (abuse cases) for Red teaming LLMs.

### Operations

- Log security-relevant events for Red teaming LLMs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Red teaming LLMs.
- Review access and configuration for Red teaming LLMs on a regular cadence.

## Fine-tuning access

Sub-topics: Tenant isolation

### Policy

- Treat Fine-tuning access in Fine-tuning access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Fine-tuning access (AI and ML system security).
- Require security review for material changes affecting Fine-tuning access.

### Design

- Apply least privilege and defense in depth for Fine-tuning access.
- Prefer established patterns and libraries over custom crypto or auth for Fine-tuning access.
- Fail closed: deny by default when Fine-tuning access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Fine-tuning access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Fine-tuning access.
- Keep dependencies patched; pin versions for Fine-tuning access components.

### Verification

- Add automated tests and SAST/DAST coverage for Fine-tuning access paths.
- Run dependency and secret scanning on every change touching Fine-tuning access.
- Perform targeted manual tests (abuse cases) for Fine-tuning access.

### Operations

- Log security-relevant events for Fine-tuning access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Fine-tuning access.
- Review access and configuration for Fine-tuning access on a regular cadence.

## Embeddings privacy

Sub-topics: Membership inference

### Policy

- Treat Embeddings privacy in Embeddings privacy as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Embeddings privacy (AI and ML system security).
- Require security review for material changes affecting Embeddings privacy.

### Design

- Apply least privilege and defense in depth for Embeddings privacy.
- Prefer established patterns and libraries over custom crypto or auth for Embeddings privacy.
- Fail closed: deny by default when Embeddings privacy cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Embeddings privacy; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Embeddings privacy.
- Keep dependencies patched; pin versions for Embeddings privacy components.

### Verification

- Add automated tests and SAST/DAST coverage for Embeddings privacy paths.
- Run dependency and secret scanning on every change touching Embeddings privacy.
- Perform targeted manual tests (abuse cases) for Embeddings privacy.

### Operations

- Log security-relevant events for Embeddings privacy without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Embeddings privacy.
- Review access and configuration for Embeddings privacy on a regular cadence.

## MCP and external tools

Sub-topics: OAuth to tools, Scope

### Policy

- Treat MCP and external tools in MCP and external tools as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for MCP and external tools (AI and ML system security).
- Require security review for material changes affecting MCP and external tools.

### Design

- Apply least privilege and defense in depth for MCP and external tools.
- Prefer established patterns and libraries over custom crypto or auth for MCP and external tools.
- Fail closed: deny by default when MCP and external tools cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching MCP and external tools; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MCP and external tools.
- Keep dependencies patched; pin versions for MCP and external tools components.

### Verification

- Add automated tests and SAST/DAST coverage for MCP and external tools paths.
- Run dependency and secret scanning on every change touching MCP and external tools.
- Perform targeted manual tests (abuse cases) for MCP and external tools.

### Operations

- Log security-relevant events for MCP and external tools without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in MCP and external tools.
- Review access and configuration for MCP and external tools on a regular cadence.

## AI governance

Sub-topics: Human review, Logging prompts

### Policy

- Treat AI governance in AI governance as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for AI governance (AI and ML system security).
- Require security review for material changes affecting AI governance.

### Design

- Apply least privilege and defense in depth for AI governance.
- Prefer established patterns and libraries over custom crypto or auth for AI governance.
- Fail closed: deny by default when AI governance cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching AI governance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to AI governance.
- Keep dependencies patched; pin versions for AI governance components.

### Verification

- Add automated tests and SAST/DAST coverage for AI governance paths.
- Run dependency and secret scanning on every change touching AI governance.
- Perform targeted manual tests (abuse cases) for AI governance.

### Operations

- Log security-relevant events for AI governance without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in AI governance.
- Review access and configuration for AI governance on a regular cadence.

