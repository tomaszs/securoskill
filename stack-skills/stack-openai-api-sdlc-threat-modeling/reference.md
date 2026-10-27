# OpenAI API / Agents SDK: SDLC, threat modeling, and secure design

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-sdlc-threat-modeling` / `reference.md`.

## STRIDE and threat models

**Sub-topics:** Diagrams, Trust boundaries, Threat modeling and trust boundaries (STRIDE and threat models), Abuse cases and adversarial testing (STRIDE and threat models), Logging, audit, and detection (STRIDE and threat models)

### Platform rules (summary)

- Validate and canonicalize all inputs touching STRIDE and threat models; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to STRIDE and threat models.
- Keep dependencies patched; pin versions for STRIDE and threat models components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for STRIDE and threat models before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for STRIDE and threat models paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Security requirements

**Sub-topics:** Non-functionals, Acceptance, Threat modeling and trust boundaries (Security requirements), Abuse cases and adversarial testing (Security requirements), Logging, audit, and detection (Security requirements)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Security requirements; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security requirements.
- Keep dependencies patched; pin versions for Security requirements components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Security requirements before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Security requirements paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Design review

**Sub-topics:** Checklists, Sign-off, Threat modeling and trust boundaries (Design review), Abuse cases and adversarial testing (Design review), Logging, audit, and detection (Design review)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Design review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Design review.
- Keep dependencies patched; pin versions for Design review components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Design review before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Design review paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Security-focused code review

**Sub-topics:** Hotspots, Threat modeling and trust boundaries (Security-focused code review), Abuse cases and adversarial testing (Security-focused code review), Logging, audit, and detection (Security-focused code review), Access control and least privilege (Security-focused code review)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Security-focused code review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security-focused code review.
- Keep dependencies patched; pin versions for Security-focused code review components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Security-focused code review before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Security-focused code review paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Security test planning

**Sub-topics:** Coverage maps, Threat modeling and trust boundaries (Security test planning), Abuse cases and adversarial testing (Security test planning), Logging, audit, and detection (Security test planning), Access control and least privilege (Security test planning)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Security test planning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security test planning.
- Keep dependencies patched; pin versions for Security test planning components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Security test planning before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Security test planning paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Secure defaults culture

**Sub-topics:** Templates, Golden paths, Threat modeling and trust boundaries (Secure defaults culture), Abuse cases and adversarial testing (Secure defaults culture), Logging, audit, and detection (Secure defaults culture)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secure defaults culture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secure defaults culture.
- Keep dependencies patched; pin versions for Secure defaults culture components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secure defaults culture before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secure defaults culture paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Developer education

**Sub-topics:** Labs, Phishing sims, Threat modeling and trust boundaries (Developer education), Abuse cases and adversarial testing (Developer education), Logging, audit, and detection (Developer education)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Developer education; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Developer education.
- Keep dependencies patched; pin versions for Developer education components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Developer education before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Developer education paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Vendor security assessment

**Sub-topics:** Questionnaires, Threat modeling and trust boundaries (Vendor security assessment), Abuse cases and adversarial testing (Vendor security assessment), Logging, audit, and detection (Vendor security assessment), Access control and least privilege (Vendor security assessment)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Vendor security assessment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vendor security assessment.
- Keep dependencies patched; pin versions for Vendor security assessment components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Vendor security assessment before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Vendor security assessment paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Architecture decision records

**Sub-topics:** Security ADRs, Threat modeling and trust boundaries (Architecture decision records), Abuse cases and adversarial testing (Architecture decision records), Logging, audit, and detection (Architecture decision records), Access control and least privilege (Architecture decision records)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Architecture decision records; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Architecture decision records.
- Keep dependencies patched; pin versions for Architecture decision records components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Architecture decision records before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Architecture decision records paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Attack surface management

**Sub-topics:** Inventory, Exposure, Threat modeling and trust boundaries (Attack surface management), Abuse cases and adversarial testing (Attack surface management), Logging, audit, and detection (Attack surface management)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Attack surface management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Attack surface management.
- Keep dependencies patched; pin versions for Attack surface management components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Attack surface management before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Attack surface management paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## Purple team exercises

**Sub-topics:** Scenarios, Threat modeling and trust boundaries (Purple team exercises), Abuse cases and adversarial testing (Purple team exercises), Logging, audit, and detection (Purple team exercises), Access control and least privilege (Purple team exercises)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Purple team exercises; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Purple team exercises.
- Keep dependencies patched; pin versions for Purple team exercises components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Purple team exercises before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Purple team exercises paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

## SDL metrics

**Sub-topics:** Defect density, Lead time, Threat modeling and trust boundaries (SDL metrics), Abuse cases and adversarial testing (SDL metrics), Logging, audit, and detection (SDL metrics)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SDL metrics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SDL metrics.
- Keep dependencies patched; pin versions for SDL metrics components.

### How to do this in OpenAI API / Agents SDK

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from OpenAI API / Agents SDK.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-sdlc-threat-modeling` / `reference.md`, then apply them using OpenAI API / Agents SDK APIs and deployment model.
- Prefer framework-maintained security features in OpenAI API / Agents SDK over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SDL metrics before merge.
- Pin OpenAI API / Agents SDK dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SDL metrics paths in OpenAI API / Agents SDK.
- Run SAST/dependency scan configured for AI.

