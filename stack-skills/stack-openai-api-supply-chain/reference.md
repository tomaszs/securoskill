# OpenAI API / Agents SDK: Software supply chain

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-supply-chain` / `reference.md`.

## Package registries

**Sub-topics:** Typosquatting, Maintainer takeover, Threat modeling and trust boundaries (Package registries), Abuse cases and adversarial testing (Package registries), Logging, audit, and detection (Package registries)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Lockfiles and reproducibility

**Sub-topics:** Integrity hashes, Threat modeling and trust boundaries (Lockfiles and reproducibility), Abuse cases and adversarial testing (Lockfiles and reproducibility), Logging, audit, and detection (Lockfiles and reproducibility), Access control and least privilege (Lockfiles and reproducibility)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Vendoring

**Sub-topics:** Fork drift, Patch review, Threat modeling and trust boundaries (Vendoring), Abuse cases and adversarial testing (Vendoring), Logging, audit, and detection (Vendoring)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Build integrity

**Sub-topics:** SLSA levels, Hermetic builds, Threat modeling and trust boundaries (Build integrity), Abuse cases and adversarial testing (Build integrity), Logging, audit, and detection (Build integrity)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Third-party SaaS

**Sub-topics:** DPAs, Subprocessors, Threat modeling and trust boundaries (Third-party SaaS), Abuse cases and adversarial testing (Third-party SaaS), Logging, audit, and detection (Third-party SaaS)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## License compliance

**Sub-topics:** Copyleft in SaaS, Threat modeling and trust boundaries (License compliance), Abuse cases and adversarial testing (License compliance), Logging, audit, and detection (License compliance), Access control and least privilege (License compliance)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Binary dependencies

**Sub-topics:** Provenance, Checksums, Threat modeling and trust boundaries (Binary dependencies), Abuse cases and adversarial testing (Binary dependencies), Logging, audit, and detection (Binary dependencies)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Git submodules

**Sub-topics:** Pinned refs, URL hijack, Threat modeling and trust boundaries (Git submodules), Abuse cases and adversarial testing (Git submodules), Logging, audit, and detection (Git submodules)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Internal packages

**Sub-topics:** Namespace, Publishing tokens, Threat modeling and trust boundaries (Internal packages), Abuse cases and adversarial testing (Internal packages), Logging, audit, and detection (Internal packages)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## CVE response

**Sub-topics:** Triage, Emergency patches, Threat modeling and trust boundaries (CVE response), Abuse cases and adversarial testing (CVE response), Logging, audit, and detection (CVE response)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Malware in repos

**Sub-topics:** Obfuscated scripts, Postinstall, Threat modeling and trust boundaries (Malware in repos), Abuse cases and adversarial testing (Malware in repos), Logging, audit, and detection (Malware in repos)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## SBOM distribution

**Sub-topics:** VEX, Consumer updates, Threat modeling and trust boundaries (SBOM distribution), Abuse cases and adversarial testing (SBOM distribution), Logging, audit, and detection (SBOM distribution)

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

