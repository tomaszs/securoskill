# Redis: Identity, authentication, and access control

Stack-specific implementation for **Redis** (Database). Normative rules: domain skill `security-identity-access` / `reference.md`.

## Passwords and credentials

**Sub-topics:** Hashing, Pepper, Breached password checks, Threat modeling and trust boundaries (Passwords and credentials), Abuse cases and adversarial testing (Passwords and credentials)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for passwords controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## MFA and step-up auth

**Sub-topics:** TOTP, WebAuthn, Recovery codes, Threat modeling and trust boundaries (MFA and step-up auth), Abuse cases and adversarial testing (MFA and step-up auth)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for mfa controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## SSO and federation

**Sub-topics:** SAML, OIDC, JIT provisioning, Threat modeling and trust boundaries (SSO and federation), Abuse cases and adversarial testing (SSO and federation)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for sso controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## RBAC

**Sub-topics:** Role explosion, Default roles, Threat modeling and trust boundaries (RBAC), Abuse cases and adversarial testing (RBAC), Logging, audit, and detection (RBAC)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for rbac controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## ABAC and policy engines

**Sub-topics:** OPA,  Cedar, Policy tests, Threat modeling and trust boundaries (ABAC and policy engines), Abuse cases and adversarial testing (ABAC and policy engines)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for abac controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## Service accounts and workloads

**Sub-topics:** SPIFFE, IAM roles, Threat modeling and trust boundaries (Service accounts and workloads), Abuse cases and adversarial testing (Service accounts and workloads), Logging, audit, and detection (Service accounts and workloads)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for service_accounts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## Break-glass and emergency access

**Sub-topics:** Audit, Time bounds, Threat modeling and trust boundaries (Break-glass and emergency access), Abuse cases and adversarial testing (Break-glass and emergency access), Logging, audit, and detection (Break-glass and emergency access)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for break_glass controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## Account lifecycle

**Sub-topics:** Joiner-mover-leaver, Orphan accounts, Threat modeling and trust boundaries (Account lifecycle), Abuse cases and adversarial testing (Account lifecycle), Logging, audit, and detection (Account lifecycle)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for account_lifecycle controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## Privilege escalation

**Sub-topics:** Horizontal, Vertical, IDOR, Threat modeling and trust boundaries (Privilege escalation), Abuse cases and adversarial testing (Privilege escalation)

### Do (use this in Redis)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Zero trust access

**Sub-topics:** Device posture, Continuous auth, Threat modeling and trust boundaries (Zero trust access), Abuse cases and adversarial testing (Zero trust access), Logging, audit, and detection (Zero trust access)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for zero_trust controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## Biometrics and device binding

**Sub-topics:** Liveness, Replay, Threat modeling and trust boundaries (Biometrics and device binding), Abuse cases and adversarial testing (Biometrics and device binding), Logging, audit, and detection (Biometrics and device binding)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for biometrics controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

## Guest and anonymous access

**Sub-topics:** Scoped tokens, Rate limits, Threat modeling and trust boundaries (Guest and anonymous access), Abuse cases and adversarial testing (Guest and anonymous access), Logging, audit, and detection (Guest and anonymous access)

### Do (use this in Redis)

- Apply domain skill `security-identity-access` requirements using redis supported APIs only.
- Use the official redis security documentation for anonymous controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of redis for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on redis projects in CI.

