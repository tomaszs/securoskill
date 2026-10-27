# Rules reference: Identity, authentication, and access control

Users, machines, roles, and federation.

## Passwords and credentials

Sub-topics: Hashing, Pepper, Breached password checks, Threat modeling and trust boundaries (Passwords and credentials), Abuse cases and adversarial testing (Passwords and credentials)

### Do

- Validate and canonicalize all inputs touching Passwords and credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Passwords and credentials.
- Keep dependencies patched; pin versions for Passwords and credentials components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Passwords and credentials in Passwords and credentials as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Passwords and credentials (Identity, authentication, and access control).
- Require security review for material changes affecting Passwords and credentials.

### Design

- Apply least privilege and defense in depth for Passwords and credentials.
- Prefer established patterns and libraries over custom crypto or auth for Passwords and credentials.
- Fail closed: deny by default when Passwords and credentials cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Passwords and credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Passwords and credentials.
- Keep dependencies patched; pin versions for Passwords and credentials components.

### Verification

- Add automated tests and SAST/DAST coverage for Passwords and credentials paths.
- Run dependency and secret scanning on every change touching Passwords and credentials.
- Perform targeted manual tests (abuse cases) for Passwords and credentials.

### Operations

- Log security-relevant events for Passwords and credentials without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Passwords and credentials.
- Review access and configuration for Passwords and credentials on a regular cadence.

## MFA and step-up auth

Sub-topics: TOTP, WebAuthn, Recovery codes, Threat modeling and trust boundaries (MFA and step-up auth), Abuse cases and adversarial testing (MFA and step-up auth)

### Do

- Validate and canonicalize all inputs touching MFA and step-up auth; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MFA and step-up auth.
- Keep dependencies patched; pin versions for MFA and step-up auth components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat MFA and step-up auth in MFA and step-up auth as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for MFA and step-up auth (Identity, authentication, and access control).
- Require security review for material changes affecting MFA and step-up auth.

### Design

- Apply least privilege and defense in depth for MFA and step-up auth.
- Prefer established patterns and libraries over custom crypto or auth for MFA and step-up auth.
- Fail closed: deny by default when MFA and step-up auth cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching MFA and step-up auth; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MFA and step-up auth.
- Keep dependencies patched; pin versions for MFA and step-up auth components.

### Verification

- Add automated tests and SAST/DAST coverage for MFA and step-up auth paths.
- Run dependency and secret scanning on every change touching MFA and step-up auth.
- Perform targeted manual tests (abuse cases) for MFA and step-up auth.

### Operations

- Log security-relevant events for MFA and step-up auth without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in MFA and step-up auth.
- Review access and configuration for MFA and step-up auth on a regular cadence.

## SSO and federation

Sub-topics: SAML, OIDC, JIT provisioning, Threat modeling and trust boundaries (SSO and federation), Abuse cases and adversarial testing (SSO and federation)

### Do

- Validate and canonicalize all inputs touching SSO and federation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSO and federation.
- Keep dependencies patched; pin versions for SSO and federation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SSO and federation in SSO and federation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SSO and federation (Identity, authentication, and access control).
- Require security review for material changes affecting SSO and federation.

### Design

- Apply least privilege and defense in depth for SSO and federation.
- Prefer established patterns and libraries over custom crypto or auth for SSO and federation.
- Fail closed: deny by default when SSO and federation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SSO and federation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSO and federation.
- Keep dependencies patched; pin versions for SSO and federation components.

### Verification

- Add automated tests and SAST/DAST coverage for SSO and federation paths.
- Run dependency and secret scanning on every change touching SSO and federation.
- Perform targeted manual tests (abuse cases) for SSO and federation.

### Operations

- Log security-relevant events for SSO and federation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SSO and federation.
- Review access and configuration for SSO and federation on a regular cadence.

## RBAC

Sub-topics: Role explosion, Default roles, Threat modeling and trust boundaries (RBAC), Abuse cases and adversarial testing (RBAC), Logging, audit, and detection (RBAC)

### Do

- Validate and canonicalize all inputs touching RBAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RBAC.
- Keep dependencies patched; pin versions for RBAC components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat RBAC in RBAC as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for RBAC (Identity, authentication, and access control).
- Require security review for material changes affecting RBAC.

### Design

- Apply least privilege and defense in depth for RBAC.
- Prefer established patterns and libraries over custom crypto or auth for RBAC.
- Fail closed: deny by default when RBAC cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching RBAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RBAC.
- Keep dependencies patched; pin versions for RBAC components.

### Verification

- Add automated tests and SAST/DAST coverage for RBAC paths.
- Run dependency and secret scanning on every change touching RBAC.
- Perform targeted manual tests (abuse cases) for RBAC.

### Operations

- Log security-relevant events for RBAC without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in RBAC.
- Review access and configuration for RBAC on a regular cadence.

## ABAC and policy engines

Sub-topics: OPA,  Cedar, Policy tests, Threat modeling and trust boundaries (ABAC and policy engines), Abuse cases and adversarial testing (ABAC and policy engines)

### Do

- Validate and canonicalize all inputs touching ABAC and policy engines; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ABAC and policy engines.
- Keep dependencies patched; pin versions for ABAC and policy engines components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat ABAC and policy engines in ABAC and policy engines as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for ABAC and policy engines (Identity, authentication, and access control).
- Require security review for material changes affecting ABAC and policy engines.

### Design

- Apply least privilege and defense in depth for ABAC and policy engines.
- Prefer established patterns and libraries over custom crypto or auth for ABAC and policy engines.
- Fail closed: deny by default when ABAC and policy engines cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching ABAC and policy engines; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ABAC and policy engines.
- Keep dependencies patched; pin versions for ABAC and policy engines components.

### Verification

- Add automated tests and SAST/DAST coverage for ABAC and policy engines paths.
- Run dependency and secret scanning on every change touching ABAC and policy engines.
- Perform targeted manual tests (abuse cases) for ABAC and policy engines.

### Operations

- Log security-relevant events for ABAC and policy engines without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in ABAC and policy engines.
- Review access and configuration for ABAC and policy engines on a regular cadence.

## Service accounts and workloads

Sub-topics: SPIFFE, IAM roles, Threat modeling and trust boundaries (Service accounts and workloads), Abuse cases and adversarial testing (Service accounts and workloads), Logging, audit, and detection (Service accounts and workloads)

### Do

- Validate and canonicalize all inputs touching Service accounts and workloads; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service accounts and workloads.
- Keep dependencies patched; pin versions for Service accounts and workloads components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Service accounts and workloads in Service accounts and workloads as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Service accounts and workloads (Identity, authentication, and access control).
- Require security review for material changes affecting Service accounts and workloads.

### Design

- Apply least privilege and defense in depth for Service accounts and workloads.
- Prefer established patterns and libraries over custom crypto or auth for Service accounts and workloads.
- Fail closed: deny by default when Service accounts and workloads cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Service accounts and workloads; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service accounts and workloads.
- Keep dependencies patched; pin versions for Service accounts and workloads components.

### Verification

- Add automated tests and SAST/DAST coverage for Service accounts and workloads paths.
- Run dependency and secret scanning on every change touching Service accounts and workloads.
- Perform targeted manual tests (abuse cases) for Service accounts and workloads.

### Operations

- Log security-relevant events for Service accounts and workloads without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Service accounts and workloads.
- Review access and configuration for Service accounts and workloads on a regular cadence.

## Break-glass and emergency access

Sub-topics: Audit, Time bounds, Threat modeling and trust boundaries (Break-glass and emergency access), Abuse cases and adversarial testing (Break-glass and emergency access), Logging, audit, and detection (Break-glass and emergency access)

### Do

- Validate and canonicalize all inputs touching Break-glass and emergency access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Break-glass and emergency access.
- Keep dependencies patched; pin versions for Break-glass and emergency access components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Break-glass and emergency access in Break-glass and emergency access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Break-glass and emergency access (Identity, authentication, and access control).
- Require security review for material changes affecting Break-glass and emergency access.

### Design

- Apply least privilege and defense in depth for Break-glass and emergency access.
- Prefer established patterns and libraries over custom crypto or auth for Break-glass and emergency access.
- Fail closed: deny by default when Break-glass and emergency access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Break-glass and emergency access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Break-glass and emergency access.
- Keep dependencies patched; pin versions for Break-glass and emergency access components.

### Verification

- Add automated tests and SAST/DAST coverage for Break-glass and emergency access paths.
- Run dependency and secret scanning on every change touching Break-glass and emergency access.
- Perform targeted manual tests (abuse cases) for Break-glass and emergency access.

### Operations

- Log security-relevant events for Break-glass and emergency access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Break-glass and emergency access.
- Review access and configuration for Break-glass and emergency access on a regular cadence.

## Account lifecycle

Sub-topics: Joiner-mover-leaver, Orphan accounts, Threat modeling and trust boundaries (Account lifecycle), Abuse cases and adversarial testing (Account lifecycle), Logging, audit, and detection (Account lifecycle)

### Do

- Validate and canonicalize all inputs touching Account lifecycle; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Account lifecycle.
- Keep dependencies patched; pin versions for Account lifecycle components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Account lifecycle in Account lifecycle as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Account lifecycle (Identity, authentication, and access control).
- Require security review for material changes affecting Account lifecycle.

### Design

- Apply least privilege and defense in depth for Account lifecycle.
- Prefer established patterns and libraries over custom crypto or auth for Account lifecycle.
- Fail closed: deny by default when Account lifecycle cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Account lifecycle; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Account lifecycle.
- Keep dependencies patched; pin versions for Account lifecycle components.

### Verification

- Add automated tests and SAST/DAST coverage for Account lifecycle paths.
- Run dependency and secret scanning on every change touching Account lifecycle.
- Perform targeted manual tests (abuse cases) for Account lifecycle.

### Operations

- Log security-relevant events for Account lifecycle without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Account lifecycle.
- Review access and configuration for Account lifecycle on a regular cadence.

## Privilege escalation

Sub-topics: Horizontal, Vertical, IDOR, Threat modeling and trust boundaries (Privilege escalation), Abuse cases and adversarial testing (Privilege escalation)

### Do

- Validate and canonicalize all inputs touching Privilege escalation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Privilege escalation.
- Keep dependencies patched; pin versions for Privilege escalation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Privilege escalation in Privilege escalation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Privilege escalation (Identity, authentication, and access control).
- Require security review for material changes affecting Privilege escalation.

### Design

- Apply least privilege and defense in depth for Privilege escalation.
- Prefer established patterns and libraries over custom crypto or auth for Privilege escalation.
- Fail closed: deny by default when Privilege escalation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Privilege escalation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Privilege escalation.
- Keep dependencies patched; pin versions for Privilege escalation components.

### Verification

- Add automated tests and SAST/DAST coverage for Privilege escalation paths.
- Run dependency and secret scanning on every change touching Privilege escalation.
- Perform targeted manual tests (abuse cases) for Privilege escalation.

### Operations

- Log security-relevant events for Privilege escalation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Privilege escalation.
- Review access and configuration for Privilege escalation on a regular cadence.

## Zero trust access

Sub-topics: Device posture, Continuous auth, Threat modeling and trust boundaries (Zero trust access), Abuse cases and adversarial testing (Zero trust access), Logging, audit, and detection (Zero trust access)

### Do

- Validate and canonicalize all inputs touching Zero trust access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust access.
- Keep dependencies patched; pin versions for Zero trust access components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Zero trust access in Zero trust access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Zero trust access (Identity, authentication, and access control).
- Require security review for material changes affecting Zero trust access.

### Design

- Apply least privilege and defense in depth for Zero trust access.
- Prefer established patterns and libraries over custom crypto or auth for Zero trust access.
- Fail closed: deny by default when Zero trust access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Zero trust access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust access.
- Keep dependencies patched; pin versions for Zero trust access components.

### Verification

- Add automated tests and SAST/DAST coverage for Zero trust access paths.
- Run dependency and secret scanning on every change touching Zero trust access.
- Perform targeted manual tests (abuse cases) for Zero trust access.

### Operations

- Log security-relevant events for Zero trust access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Zero trust access.
- Review access and configuration for Zero trust access on a regular cadence.

## Biometrics and device binding

Sub-topics: Liveness, Replay, Threat modeling and trust boundaries (Biometrics and device binding), Abuse cases and adversarial testing (Biometrics and device binding), Logging, audit, and detection (Biometrics and device binding)

### Do

- Validate and canonicalize all inputs touching Biometrics and device binding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Biometrics and device binding.
- Keep dependencies patched; pin versions for Biometrics and device binding components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Biometrics and device binding in Biometrics and device binding as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Biometrics and device binding (Identity, authentication, and access control).
- Require security review for material changes affecting Biometrics and device binding.

### Design

- Apply least privilege and defense in depth for Biometrics and device binding.
- Prefer established patterns and libraries over custom crypto or auth for Biometrics and device binding.
- Fail closed: deny by default when Biometrics and device binding cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Biometrics and device binding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Biometrics and device binding.
- Keep dependencies patched; pin versions for Biometrics and device binding components.

### Verification

- Add automated tests and SAST/DAST coverage for Biometrics and device binding paths.
- Run dependency and secret scanning on every change touching Biometrics and device binding.
- Perform targeted manual tests (abuse cases) for Biometrics and device binding.

### Operations

- Log security-relevant events for Biometrics and device binding without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Biometrics and device binding.
- Review access and configuration for Biometrics and device binding on a regular cadence.

## Guest and anonymous access

Sub-topics: Scoped tokens, Rate limits, Threat modeling and trust boundaries (Guest and anonymous access), Abuse cases and adversarial testing (Guest and anonymous access), Logging, audit, and detection (Guest and anonymous access)

### Do

- Validate and canonicalize all inputs touching Guest and anonymous access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Guest and anonymous access.
- Keep dependencies patched; pin versions for Guest and anonymous access components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Guest and anonymous access in Guest and anonymous access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Guest and anonymous access (Identity, authentication, and access control).
- Require security review for material changes affecting Guest and anonymous access.

### Design

- Apply least privilege and defense in depth for Guest and anonymous access.
- Prefer established patterns and libraries over custom crypto or auth for Guest and anonymous access.
- Fail closed: deny by default when Guest and anonymous access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Guest and anonymous access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Guest and anonymous access.
- Keep dependencies patched; pin versions for Guest and anonymous access components.

### Verification

- Add automated tests and SAST/DAST coverage for Guest and anonymous access paths.
- Run dependency and secret scanning on every change touching Guest and anonymous access.
- Perform targeted manual tests (abuse cases) for Guest and anonymous access.

### Operations

- Log security-relevant events for Guest and anonymous access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Guest and anonymous access.
- Review access and configuration for Guest and anonymous access on a regular cadence.

