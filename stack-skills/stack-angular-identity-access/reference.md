# Angular: Identity, authentication, and access control

Stack-specific implementation for **Angular** (Web UI). Normative rules: domain skill `security-identity-access` / `reference.md`.

## Passwords and credentials

**Sub-topics:** Hashing, Pepper, Breached password checks, Threat modeling and trust boundaries (Passwords and credentials), Abuse cases and adversarial testing (Passwords and credentials)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Passwords and credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Passwords and credentials.
- Keep dependencies patched; pin versions for Passwords and credentials components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Passwords and credentials before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Passwords and credentials paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## MFA and step-up auth

**Sub-topics:** TOTP, WebAuthn, Recovery codes, Threat modeling and trust boundaries (MFA and step-up auth), Abuse cases and adversarial testing (MFA and step-up auth)

### Platform rules (summary)

- Validate and canonicalize all inputs touching MFA and step-up auth; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MFA and step-up auth.
- Keep dependencies patched; pin versions for MFA and step-up auth components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for MFA and step-up auth before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for MFA and step-up auth paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## SSO and federation

**Sub-topics:** SAML, OIDC, JIT provisioning, Threat modeling and trust boundaries (SSO and federation), Abuse cases and adversarial testing (SSO and federation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SSO and federation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSO and federation.
- Keep dependencies patched; pin versions for SSO and federation components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SSO and federation before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SSO and federation paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## RBAC

**Sub-topics:** Role explosion, Default roles, Threat modeling and trust boundaries (RBAC), Abuse cases and adversarial testing (RBAC), Logging, audit, and detection (RBAC)

### Platform rules (summary)

- Validate and canonicalize all inputs touching RBAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RBAC.
- Keep dependencies patched; pin versions for RBAC components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for RBAC before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for RBAC paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## ABAC and policy engines

**Sub-topics:** OPA,  Cedar, Policy tests, Threat modeling and trust boundaries (ABAC and policy engines), Abuse cases and adversarial testing (ABAC and policy engines)

### Platform rules (summary)

- Validate and canonicalize all inputs touching ABAC and policy engines; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ABAC and policy engines.
- Keep dependencies patched; pin versions for ABAC and policy engines components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for ABAC and policy engines before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for ABAC and policy engines paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Service accounts and workloads

**Sub-topics:** SPIFFE, IAM roles, Threat modeling and trust boundaries (Service accounts and workloads), Abuse cases and adversarial testing (Service accounts and workloads), Logging, audit, and detection (Service accounts and workloads)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Service accounts and workloads; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service accounts and workloads.
- Keep dependencies patched; pin versions for Service accounts and workloads components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Service accounts and workloads before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Service accounts and workloads paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Break-glass and emergency access

**Sub-topics:** Audit, Time bounds, Threat modeling and trust boundaries (Break-glass and emergency access), Abuse cases and adversarial testing (Break-glass and emergency access), Logging, audit, and detection (Break-glass and emergency access)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Break-glass and emergency access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Break-glass and emergency access.
- Keep dependencies patched; pin versions for Break-glass and emergency access components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Break-glass and emergency access before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Break-glass and emergency access paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Account lifecycle

**Sub-topics:** Joiner-mover-leaver, Orphan accounts, Threat modeling and trust boundaries (Account lifecycle), Abuse cases and adversarial testing (Account lifecycle), Logging, audit, and detection (Account lifecycle)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Account lifecycle; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Account lifecycle.
- Keep dependencies patched; pin versions for Account lifecycle components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Account lifecycle before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Account lifecycle paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Privilege escalation

**Sub-topics:** Horizontal, Vertical, IDOR, Threat modeling and trust boundaries (Privilege escalation), Abuse cases and adversarial testing (Privilege escalation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Privilege escalation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Privilege escalation.
- Keep dependencies patched; pin versions for Privilege escalation components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Privilege escalation before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Privilege escalation paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Zero trust access

**Sub-topics:** Device posture, Continuous auth, Threat modeling and trust boundaries (Zero trust access), Abuse cases and adversarial testing (Zero trust access), Logging, audit, and detection (Zero trust access)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Zero trust access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust access.
- Keep dependencies patched; pin versions for Zero trust access components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Zero trust access before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Zero trust access paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Biometrics and device binding

**Sub-topics:** Liveness, Replay, Threat modeling and trust boundaries (Biometrics and device binding), Abuse cases and adversarial testing (Biometrics and device binding), Logging, audit, and detection (Biometrics and device binding)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Biometrics and device binding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Biometrics and device binding.
- Keep dependencies patched; pin versions for Biometrics and device binding components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Biometrics and device binding before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Biometrics and device binding paths in Angular.
- Run SAST/dependency scan configured for Web UI.

## Guest and anonymous access

**Sub-topics:** Scoped tokens, Rate limits, Threat modeling and trust boundaries (Guest and anonymous access), Abuse cases and adversarial testing (Guest and anonymous access), Logging, audit, and detection (Guest and anonymous access)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Guest and anonymous access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Guest and anonymous access.
- Keep dependencies patched; pin versions for Guest and anonymous access components.

### How to do this in Angular

- Use vetted auth libraries for Angular; never roll custom password hashing or session tokens.
- Enforce MFA and short-lived access tokens at the IdP; map roles to server-side checks, not client flags.
- Read normative rules in domain skill `security-identity-access` / `reference.md`, then apply them using Angular APIs and deployment model.
- Prefer framework-maintained security features in Angular over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Guest and anonymous access before merge.
- Pin Angular dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Guest and anonymous access paths in Angular.
- Run SAST/dependency scan configured for Web UI.

