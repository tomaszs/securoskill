# SwiftUI (iOS): AI and ML system security

Stack-specific implementation for **SwiftUI (iOS)** (Mobile). Normative rules: domain skill `security-ai-ml-security` / `reference.md`.

## Prompt injection

**Sub-topics:** Indirect injection, Tool abuse, Threat modeling and trust boundaries (Prompt injection), Abuse cases and adversarial testing (Prompt injection), Logging, audit, and detection (Prompt injection)

### Do (use this in SwiftUI (iOS))

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## RAG and retrieval

**Sub-topics:** Poisoned documents, ACL on chunks, Threat modeling and trust boundaries (RAG and retrieval), Abuse cases and adversarial testing (RAG and retrieval), Logging, audit, and detection (RAG and retrieval)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Model abuse and cost

**Sub-topics:** Token flooding, Unbounded context, Threat modeling and trust boundaries (Model abuse and cost), Abuse cases and adversarial testing (Model abuse and cost), Logging, audit, and detection (Model abuse and cost)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Training data poisoning

**Sub-topics:** PII in datasets, Threat modeling and trust boundaries (Training data poisoning), Abuse cases and adversarial testing (Training data poisoning), Logging, audit, and detection (Training data poisoning), Access control and least privilege (Training data poisoning)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Model and weight exfiltration

**Sub-topics:** API leakage, Threat modeling and trust boundaries (Model and weight exfiltration), Abuse cases and adversarial testing (Model and weight exfiltration), Logging, audit, and detection (Model and weight exfiltration), Access control and least privilege (Model and weight exfiltration)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Agent tool invocation

**Sub-topics:** SSRF via tools, Shell tools, Threat modeling and trust boundaries (Agent tool invocation), Abuse cases and adversarial testing (Agent tool invocation), Logging, audit, and detection (Agent tool invocation)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Unsafe outputs

**Sub-topics:** Code execution suggestions, XSS in chat UI, Threat modeling and trust boundaries (Unsafe outputs), Abuse cases and adversarial testing (Unsafe outputs), Logging, audit, and detection (Unsafe outputs)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Red teaming LLMs

**Sub-topics:** Jailbreaks, Benchmarks, Threat modeling and trust boundaries (Red teaming LLMs), Abuse cases and adversarial testing (Red teaming LLMs), Logging, audit, and detection (Red teaming LLMs)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Fine-tuning access

**Sub-topics:** Tenant isolation, Threat modeling and trust boundaries (Fine-tuning access), Abuse cases and adversarial testing (Fine-tuning access), Logging, audit, and detection (Fine-tuning access), Access control and least privilege (Fine-tuning access)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Embeddings privacy

**Sub-topics:** Membership inference, Threat modeling and trust boundaries (Embeddings privacy), Abuse cases and adversarial testing (Embeddings privacy), Logging, audit, and detection (Embeddings privacy), Access control and least privilege (Embeddings privacy)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## MCP and external tools

**Sub-topics:** OAuth to tools, Scope, Threat modeling and trust boundaries (MCP and external tools), Abuse cases and adversarial testing (MCP and external tools), Logging, audit, and detection (MCP and external tools)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## AI governance

**Sub-topics:** Human review, Logging prompts, Threat modeling and trust boundaries (AI governance), Abuse cases and adversarial testing (AI governance), Logging, audit, and detection (AI governance)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

