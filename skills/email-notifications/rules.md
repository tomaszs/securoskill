# Rules reference: Email and notifications security

Transactional email, templates, and messaging.

## Email authentication

Sub-topics: SPF, DKIM, DMARC

### Policy

- Treat Email authentication in Email authentication as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Email authentication (Email and notifications security).
- Require security review for material changes affecting Email authentication.

### Design

- Apply least privilege and defense in depth for Email authentication.
- Prefer established patterns and libraries over custom crypto or auth for Email authentication.
- Fail closed: deny by default when Email authentication cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Email authentication; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Email authentication.
- Keep dependencies patched; pin versions for Email authentication components.

### Verification

- Add automated tests and SAST/DAST coverage for Email authentication paths.
- Run dependency and secret scanning on every change touching Email authentication.
- Perform targeted manual tests (abuse cases) for Email authentication.

### Operations

- Log security-relevant events for Email authentication without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Email authentication.
- Review access and configuration for Email authentication on a regular cadence.

## Template injection in email

Sub-topics: SSTI in mailers

### Policy

- Treat Template injection in email in Template injection in email as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Template injection in email (Email and notifications security).
- Require security review for material changes affecting Template injection in email.

### Design

- Apply least privilege and defense in depth for Template injection in email.
- Prefer established patterns and libraries over custom crypto or auth for Template injection in email.
- Fail closed: deny by default when Template injection in email cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Template injection in email; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Template injection in email.
- Keep dependencies patched; pin versions for Template injection in email components.

### Verification

- Add automated tests and SAST/DAST coverage for Template injection in email paths.
- Run dependency and secret scanning on every change touching Template injection in email.
- Perform targeted manual tests (abuse cases) for Template injection in email.

### Operations

- Log security-relevant events for Template injection in email without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Template injection in email.
- Review access and configuration for Template injection in email on a regular cadence.

## Links in email

Sub-topics: Open redirect, Tracking

### Policy

- Treat Links in email in Links in email as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Links in email (Email and notifications security).
- Require security review for material changes affecting Links in email.

### Design

- Apply least privilege and defense in depth for Links in email.
- Prefer established patterns and libraries over custom crypto or auth for Links in email.
- Fail closed: deny by default when Links in email cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Links in email; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Links in email.
- Keep dependencies patched; pin versions for Links in email components.

### Verification

- Add automated tests and SAST/DAST coverage for Links in email paths.
- Run dependency and secret scanning on every change touching Links in email.
- Perform targeted manual tests (abuse cases) for Links in email.

### Operations

- Log security-relevant events for Links in email without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Links in email.
- Review access and configuration for Links in email on a regular cadence.

## Bounce and webhook handling

Sub-topics: Forged events

### Policy

- Treat Bounce and webhook handling in Bounce and webhook handling as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Bounce and webhook handling (Email and notifications security).
- Require security review for material changes affecting Bounce and webhook handling.

### Design

- Apply least privilege and defense in depth for Bounce and webhook handling.
- Prefer established patterns and libraries over custom crypto or auth for Bounce and webhook handling.
- Fail closed: deny by default when Bounce and webhook handling cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Bounce and webhook handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bounce and webhook handling.
- Keep dependencies patched; pin versions for Bounce and webhook handling components.

### Verification

- Add automated tests and SAST/DAST coverage for Bounce and webhook handling paths.
- Run dependency and secret scanning on every change touching Bounce and webhook handling.
- Perform targeted manual tests (abuse cases) for Bounce and webhook handling.

### Operations

- Log security-relevant events for Bounce and webhook handling without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Bounce and webhook handling.
- Review access and configuration for Bounce and webhook handling on a regular cadence.

## List management

Sub-topics: Header injection

### Policy

- Treat List management in List management as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for List management (Email and notifications security).
- Require security review for material changes affecting List management.

### Design

- Apply least privilege and defense in depth for List management.
- Prefer established patterns and libraries over custom crypto or auth for List management.
- Fail closed: deny by default when List management cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching List management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to List management.
- Keep dependencies patched; pin versions for List management components.

### Verification

- Add automated tests and SAST/DAST coverage for List management paths.
- Run dependency and secret scanning on every change touching List management.
- Perform targeted manual tests (abuse cases) for List management.

### Operations

- Log security-relevant events for List management without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in List management.
- Review access and configuration for List management on a regular cadence.

## Brand impersonation

Sub-topics: From addresses, BIMI

### Policy

- Treat Brand impersonation in Brand impersonation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Brand impersonation (Email and notifications security).
- Require security review for material changes affecting Brand impersonation.

### Design

- Apply least privilege and defense in depth for Brand impersonation.
- Prefer established patterns and libraries over custom crypto or auth for Brand impersonation.
- Fail closed: deny by default when Brand impersonation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Brand impersonation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Brand impersonation.
- Keep dependencies patched; pin versions for Brand impersonation components.

### Verification

- Add automated tests and SAST/DAST coverage for Brand impersonation paths.
- Run dependency and secret scanning on every change touching Brand impersonation.
- Perform targeted manual tests (abuse cases) for Brand impersonation.

### Operations

- Log security-relevant events for Brand impersonation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Brand impersonation.
- Review access and configuration for Brand impersonation on a regular cadence.

## Attachments

Sub-topics: Malware scanning

### Policy

- Treat Attachments in Attachments as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Attachments (Email and notifications security).
- Require security review for material changes affecting Attachments.

### Design

- Apply least privilege and defense in depth for Attachments.
- Prefer established patterns and libraries over custom crypto or auth for Attachments.
- Fail closed: deny by default when Attachments cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Attachments; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Attachments.
- Keep dependencies patched; pin versions for Attachments components.

### Verification

- Add automated tests and SAST/DAST coverage for Attachments paths.
- Run dependency and secret scanning on every change touching Attachments.
- Perform targeted manual tests (abuse cases) for Attachments.

### Operations

- Log security-relevant events for Attachments without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Attachments.
- Review access and configuration for Attachments on a regular cadence.

## SMS and push

Sub-topics: OTP leakage, SIM swap awareness

### Policy

- Treat SMS and push in SMS and push as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SMS and push (Email and notifications security).
- Require security review for material changes affecting SMS and push.

### Design

- Apply least privilege and defense in depth for SMS and push.
- Prefer established patterns and libraries over custom crypto or auth for SMS and push.
- Fail closed: deny by default when SMS and push cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SMS and push; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SMS and push.
- Keep dependencies patched; pin versions for SMS and push components.

### Verification

- Add automated tests and SAST/DAST coverage for SMS and push paths.
- Run dependency and secret scanning on every change touching SMS and push.
- Perform targeted manual tests (abuse cases) for SMS and push.

### Operations

- Log security-relevant events for SMS and push without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SMS and push.
- Review access and configuration for SMS and push on a regular cadence.

## User inbox rules attacks

Sub-topics: Forwarding rules

### Policy

- Treat User inbox rules attacks in User inbox rules attacks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for User inbox rules attacks (Email and notifications security).
- Require security review for material changes affecting User inbox rules attacks.

### Design

- Apply least privilege and defense in depth for User inbox rules attacks.
- Prefer established patterns and libraries over custom crypto or auth for User inbox rules attacks.
- Fail closed: deny by default when User inbox rules attacks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching User inbox rules attacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to User inbox rules attacks.
- Keep dependencies patched; pin versions for User inbox rules attacks components.

### Verification

- Add automated tests and SAST/DAST coverage for User inbox rules attacks paths.
- Run dependency and secret scanning on every change touching User inbox rules attacks.
- Perform targeted manual tests (abuse cases) for User inbox rules attacks.

### Operations

- Log security-relevant events for User inbox rules attacks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in User inbox rules attacks.
- Review access and configuration for User inbox rules attacks on a regular cadence.

## Email provider APIs

Sub-topics: API keys, Send-as

### Policy

- Treat Email provider APIs in Email provider APIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Email provider APIs (Email and notifications security).
- Require security review for material changes affecting Email provider APIs.

### Design

- Apply least privilege and defense in depth for Email provider APIs.
- Prefer established patterns and libraries over custom crypto or auth for Email provider APIs.
- Fail closed: deny by default when Email provider APIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Email provider APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Email provider APIs.
- Keep dependencies patched; pin versions for Email provider APIs components.

### Verification

- Add automated tests and SAST/DAST coverage for Email provider APIs paths.
- Run dependency and secret scanning on every change touching Email provider APIs.
- Perform targeted manual tests (abuse cases) for Email provider APIs.

### Operations

- Log security-relevant events for Email provider APIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Email provider APIs.
- Review access and configuration for Email provider APIs on a regular cadence.

## PII in email bodies

Sub-topics: Encryption, Retention

### Policy

- Treat PII in email bodies in PII in email bodies as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PII in email bodies (Email and notifications security).
- Require security review for material changes affecting PII in email bodies.

### Design

- Apply least privilege and defense in depth for PII in email bodies.
- Prefer established patterns and libraries over custom crypto or auth for PII in email bodies.
- Fail closed: deny by default when PII in email bodies cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PII in email bodies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in email bodies.
- Keep dependencies patched; pin versions for PII in email bodies components.

### Verification

- Add automated tests and SAST/DAST coverage for PII in email bodies paths.
- Run dependency and secret scanning on every change touching PII in email bodies.
- Perform targeted manual tests (abuse cases) for PII in email bodies.

### Operations

- Log security-relevant events for PII in email bodies without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PII in email bodies.
- Review access and configuration for PII in email bodies on a regular cadence.

## Email abuse

Sub-topics: Forgot password spam

### Policy

- Treat Email abuse in Email abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Email abuse (Email and notifications security).
- Require security review for material changes affecting Email abuse.

### Design

- Apply least privilege and defense in depth for Email abuse.
- Prefer established patterns and libraries over custom crypto or auth for Email abuse.
- Fail closed: deny by default when Email abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Email abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Email abuse.
- Keep dependencies patched; pin versions for Email abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Email abuse paths.
- Run dependency and secret scanning on every change touching Email abuse.
- Perform targeted manual tests (abuse cases) for Email abuse.

### Operations

- Log security-relevant events for Email abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Email abuse.
- Review access and configuration for Email abuse on a regular cadence.

