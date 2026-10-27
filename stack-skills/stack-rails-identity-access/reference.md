# Ruby on Rails: Identity, authentication, and access control

Stack-specific implementation for **Ruby on Rails** (Ruby). Normative rules: domain skill `security-identity-access` / `reference.md`.

## Passwords and credentials

**Sub-topics:** Hashing, Pepper, Breached password checks, Threat modeling and trust boundaries (Passwords and credentials), Abuse cases and adversarial testing (Passwords and credentials)

### Do (use this in Ruby on Rails)

- Map `Passwords and credentials` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Passwords and credentials` before merge.

### Don't

- Do not ship `Passwords and credentials` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Passwords and credentials`.

### Verify

- Peer review `Passwords and credentials` against domain skill `security-identity-access`.

## MFA and step-up auth

**Sub-topics:** TOTP, WebAuthn, Recovery codes, Threat modeling and trust boundaries (MFA and step-up auth), Abuse cases and adversarial testing (MFA and step-up auth)

### Do (use this in Ruby on Rails)

- Map `MFA and step-up auth` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `MFA and step-up auth` before merge.

### Don't

- Do not ship `MFA and step-up auth` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `MFA and step-up auth`.

### Verify

- Peer review `MFA and step-up auth` against domain skill `security-identity-access`.

## SSO and federation

**Sub-topics:** SAML, OIDC, JIT provisioning, Threat modeling and trust boundaries (SSO and federation), Abuse cases and adversarial testing (SSO and federation)

### Do (use this in Ruby on Rails)

- Map `SSO and federation` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `SSO and federation` before merge.

### Don't

- Do not ship `SSO and federation` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `SSO and federation`.

### Verify

- Peer review `SSO and federation` against domain skill `security-identity-access`.

## RBAC

**Sub-topics:** Role explosion, Default roles, Threat modeling and trust boundaries (RBAC), Abuse cases and adversarial testing (RBAC), Logging, audit, and detection (RBAC)

### Do (use this in Ruby on Rails)

- Map `RBAC` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `RBAC` before merge.

### Don't

- Do not ship `RBAC` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `RBAC`.

### Verify

- Peer review `RBAC` against domain skill `security-identity-access`.

## ABAC and policy engines

**Sub-topics:** OPA,  Cedar, Policy tests, Threat modeling and trust boundaries (ABAC and policy engines), Abuse cases and adversarial testing (ABAC and policy engines)

### Do (use this in Ruby on Rails)

- Map `ABAC and policy engines` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `ABAC and policy engines` before merge.

### Don't

- Do not ship `ABAC and policy engines` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `ABAC and policy engines`.

### Verify

- Peer review `ABAC and policy engines` against domain skill `security-identity-access`.

## Service accounts and workloads

**Sub-topics:** SPIFFE, IAM roles, Threat modeling and trust boundaries (Service accounts and workloads), Abuse cases and adversarial testing (Service accounts and workloads), Logging, audit, and detection (Service accounts and workloads)

### Do (use this in Ruby on Rails)

- Map `Service accounts and workloads` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Service accounts and workloads` before merge.

### Don't

- Do not ship `Service accounts and workloads` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Service accounts and workloads`.

### Verify

- Peer review `Service accounts and workloads` against domain skill `security-identity-access`.

## Break-glass and emergency access

**Sub-topics:** Audit, Time bounds, Threat modeling and trust boundaries (Break-glass and emergency access), Abuse cases and adversarial testing (Break-glass and emergency access), Logging, audit, and detection (Break-glass and emergency access)

### Do (use this in Ruby on Rails)

- Map `Break-glass and emergency access` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Break-glass and emergency access` before merge.

### Don't

- Do not ship `Break-glass and emergency access` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Break-glass and emergency access`.

### Verify

- Peer review `Break-glass and emergency access` against domain skill `security-identity-access`.

## Account lifecycle

**Sub-topics:** Joiner-mover-leaver, Orphan accounts, Threat modeling and trust boundaries (Account lifecycle), Abuse cases and adversarial testing (Account lifecycle), Logging, audit, and detection (Account lifecycle)

### Do (use this in Ruby on Rails)

- Map `Account lifecycle` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Account lifecycle` before merge.

### Don't

- Do not ship `Account lifecycle` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Account lifecycle`.

### Verify

- Peer review `Account lifecycle` against domain skill `security-identity-access`.

## Privilege escalation

**Sub-topics:** Horizontal, Vertical, IDOR, Threat modeling and trust boundaries (Privilege escalation), Abuse cases and adversarial testing (Privilege escalation)

### Do (use this in Ruby on Rails)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run brakeman on changes affecting `Privilege escalation`.

## Zero trust access

**Sub-topics:** Device posture, Continuous auth, Threat modeling and trust boundaries (Zero trust access), Abuse cases and adversarial testing (Zero trust access), Logging, audit, and detection (Zero trust access)

### Do (use this in Ruby on Rails)

- Map `Zero trust access` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Zero trust access` before merge.

### Don't

- Do not ship `Zero trust access` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Zero trust access`.

### Verify

- Peer review `Zero trust access` against domain skill `security-identity-access`.

## Biometrics and device binding

**Sub-topics:** Liveness, Replay, Threat modeling and trust boundaries (Biometrics and device binding), Abuse cases and adversarial testing (Biometrics and device binding), Logging, audit, and detection (Biometrics and device binding)

### Do (use this in Ruby on Rails)

- Map `Biometrics and device binding` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Biometrics and device binding` before merge.

### Don't

- Do not ship `Biometrics and device binding` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Biometrics and device binding`.

### Verify

- Peer review `Biometrics and device binding` against domain skill `security-identity-access`.

## Guest and anonymous access

**Sub-topics:** Scoped tokens, Rate limits, Threat modeling and trust boundaries (Guest and anonymous access), Abuse cases and adversarial testing (Guest and anonymous access), Logging, audit, and detection (Guest and anonymous access)

### Do (use this in Ruby on Rails)

- Map `Guest and anonymous access` controls to Ruby on Rails APIs documented for `security-identity-access`.
- Add an abuse-case test or check for `Guest and anonymous access` before merge.

### Don't

- Do not ship `Guest and anonymous access` work in Ruby on Rails with only happy-path tests.
- Do not disable Ruby on Rails security defaults to unblock `Guest and anonymous access`.

### Verify

- Peer review `Guest and anonymous access` against domain skill `security-identity-access`.

