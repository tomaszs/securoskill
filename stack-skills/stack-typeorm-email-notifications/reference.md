# TypeORM: Email and notifications security

Stack-specific implementation for **TypeORM** (ORM / data access). Normative rules: domain skill `security-email-notifications` / `reference.md`.

## Email authentication

**Sub-topics:** SPF, DKIM, DMARC, Threat modeling and trust boundaries (Email authentication), Abuse cases and adversarial testing (Email authentication)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Email authentication; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Email authentication.
- Keep dependencies patched; pin versions for Email authentication components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Email authentication before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Email authentication paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Template injection in email

**Sub-topics:** SSTI in mailers, Threat modeling and trust boundaries (Template injection in email), Abuse cases and adversarial testing (Template injection in email), Logging, audit, and detection (Template injection in email), Access control and least privilege (Template injection in email)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Template injection in email; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Template injection in email.
- Keep dependencies patched; pin versions for Template injection in email components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Template injection in email before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Template injection in email paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Links in email

**Sub-topics:** Open redirect, Tracking, Threat modeling and trust boundaries (Links in email), Abuse cases and adversarial testing (Links in email), Logging, audit, and detection (Links in email)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Links in email; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Links in email.
- Keep dependencies patched; pin versions for Links in email components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Links in email before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Links in email paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Bounce and webhook handling

**Sub-topics:** Forged events, Threat modeling and trust boundaries (Bounce and webhook handling), Abuse cases and adversarial testing (Bounce and webhook handling), Logging, audit, and detection (Bounce and webhook handling), Access control and least privilege (Bounce and webhook handling)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Bounce and webhook handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bounce and webhook handling.
- Keep dependencies patched; pin versions for Bounce and webhook handling components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Bounce and webhook handling before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Bounce and webhook handling paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## List management

**Sub-topics:** Header injection, Threat modeling and trust boundaries (List management), Abuse cases and adversarial testing (List management), Logging, audit, and detection (List management), Access control and least privilege (List management)

### Platform rules (summary)

- Validate and canonicalize all inputs touching List management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to List management.
- Keep dependencies patched; pin versions for List management components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for List management before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for List management paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Brand impersonation

**Sub-topics:** From addresses, BIMI, Threat modeling and trust boundaries (Brand impersonation), Abuse cases and adversarial testing (Brand impersonation), Logging, audit, and detection (Brand impersonation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Brand impersonation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Brand impersonation.
- Keep dependencies patched; pin versions for Brand impersonation components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Brand impersonation before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Brand impersonation paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Attachments

**Sub-topics:** Malware scanning, Threat modeling and trust boundaries (Attachments), Abuse cases and adversarial testing (Attachments), Logging, audit, and detection (Attachments), Access control and least privilege (Attachments)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Attachments; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Attachments.
- Keep dependencies patched; pin versions for Attachments components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Attachments before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Attachments paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## SMS and push

**Sub-topics:** OTP leakage, SIM swap awareness, Threat modeling and trust boundaries (SMS and push), Abuse cases and adversarial testing (SMS and push), Logging, audit, and detection (SMS and push)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SMS and push; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SMS and push.
- Keep dependencies patched; pin versions for SMS and push components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SMS and push before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SMS and push paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## User inbox rules attacks

**Sub-topics:** Forwarding rules, Threat modeling and trust boundaries (User inbox rules attacks), Abuse cases and adversarial testing (User inbox rules attacks), Logging, audit, and detection (User inbox rules attacks), Access control and least privilege (User inbox rules attacks)

### Platform rules (summary)

- Validate and canonicalize all inputs touching User inbox rules attacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to User inbox rules attacks.
- Keep dependencies patched; pin versions for User inbox rules attacks components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for User inbox rules attacks before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for User inbox rules attacks paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Email provider APIs

**Sub-topics:** API keys, Send-as, Threat modeling and trust boundaries (Email provider APIs), Abuse cases and adversarial testing (Email provider APIs), Logging, audit, and detection (Email provider APIs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Email provider APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Email provider APIs.
- Keep dependencies patched; pin versions for Email provider APIs components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Email provider APIs before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Email provider APIs paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## PII in email bodies

**Sub-topics:** Encryption, Retention, Threat modeling and trust boundaries (PII in email bodies), Abuse cases and adversarial testing (PII in email bodies), Logging, audit, and detection (PII in email bodies)

### Platform rules (summary)

- Validate and canonicalize all inputs touching PII in email bodies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in email bodies.
- Keep dependencies patched; pin versions for PII in email bodies components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PII in email bodies before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PII in email bodies paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

## Email abuse

**Sub-topics:** Forgot password spam, Threat modeling and trust boundaries (Email abuse), Abuse cases and adversarial testing (Email abuse), Logging, audit, and detection (Email abuse), Access control and least privilege (Email abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Email abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Email abuse.
- Keep dependencies patched; pin versions for Email abuse components.

### How to do this in TypeORM

- Read normative rules in domain skill `security-email-notifications` / `reference.md`, then apply them using TypeORM APIs and deployment model.
- Prefer framework-maintained security features in TypeORM over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Email abuse before merge.
- Pin TypeORM dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Email abuse paths in TypeORM.
- Run SAST/dependency scan configured for ORM / data access.

