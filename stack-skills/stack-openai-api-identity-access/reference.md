# OpenAI API / Agents SDK: Identity, authentication, and access control

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-identity-access` / `reference.md`.

## Passwords and credentials

**Sub-topics:** Hashing, Pepper, Breached password checks, Threat modeling and trust boundaries (Passwords and credentials), Abuse cases and adversarial testing (Passwords and credentials)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## MFA and step-up auth

**Sub-topics:** TOTP, WebAuthn, Recovery codes, Threat modeling and trust boundaries (MFA and step-up auth), Abuse cases and adversarial testing (MFA and step-up auth)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## SSO and federation

**Sub-topics:** SAML, OIDC, JIT provisioning, Threat modeling and trust boundaries (SSO and federation), Abuse cases and adversarial testing (SSO and federation)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## RBAC

**Sub-topics:** Role explosion, Default roles, Threat modeling and trust boundaries (RBAC), Abuse cases and adversarial testing (RBAC), Logging, audit, and detection (RBAC)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## ABAC and policy engines

**Sub-topics:** OPA,  Cedar, Policy tests, Threat modeling and trust boundaries (ABAC and policy engines), Abuse cases and adversarial testing (ABAC and policy engines)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Service accounts and workloads

**Sub-topics:** SPIFFE, IAM roles, Threat modeling and trust boundaries (Service accounts and workloads), Abuse cases and adversarial testing (Service accounts and workloads), Logging, audit, and detection (Service accounts and workloads)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Break-glass and emergency access

**Sub-topics:** Audit, Time bounds, Threat modeling and trust boundaries (Break-glass and emergency access), Abuse cases and adversarial testing (Break-glass and emergency access), Logging, audit, and detection (Break-glass and emergency access)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Account lifecycle

**Sub-topics:** Joiner-mover-leaver, Orphan accounts, Threat modeling and trust boundaries (Account lifecycle), Abuse cases and adversarial testing (Account lifecycle), Logging, audit, and detection (Account lifecycle)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Privilege escalation

**Sub-topics:** Horizontal, Vertical, IDOR, Threat modeling and trust boundaries (Privilege escalation), Abuse cases and adversarial testing (Privilege escalation)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Zero trust access

**Sub-topics:** Device posture, Continuous auth, Threat modeling and trust boundaries (Zero trust access), Abuse cases and adversarial testing (Zero trust access), Logging, audit, and detection (Zero trust access)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Biometrics and device binding

**Sub-topics:** Liveness, Replay, Threat modeling and trust boundaries (Biometrics and device binding), Abuse cases and adversarial testing (Biometrics and device binding), Logging, audit, and detection (Biometrics and device binding)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Guest and anonymous access

**Sub-topics:** Scoped tokens, Rate limits, Threat modeling and trust boundaries (Guest and anonymous access), Abuse cases and adversarial testing (Guest and anonymous access), Logging, audit, and detection (Guest and anonymous access)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

