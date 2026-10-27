# React: Email and notifications security

Stack-specific implementation for **React** (Web UI). Normative rules: domain skill `security-email-notifications` / `reference.md`.

## Email authentication

**Sub-topics:** SPF, DKIM, DMARC, Threat modeling and trust boundaries (Email authentication), Abuse cases and adversarial testing (Email authentication)

### Do (use this in React)

- Map `Email authentication` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Email authentication` before merge.

### Don't

- Do not ship `Email authentication` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Email authentication`.

### Verify

- Peer review `Email authentication` against domain skill `security-email-notifications`.

## Template injection in email

**Sub-topics:** SSTI in mailers, Threat modeling and trust boundaries (Template injection in email), Abuse cases and adversarial testing (Template injection in email), Logging, audit, and detection (Template injection in email), Access control and least privilege (Template injection in email)

### Do (use this in React)

- Map `Template injection in email` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Template injection in email` before merge.

### Don't

- Do not ship `Template injection in email` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Template injection in email`.

### Verify

- Peer review `Template injection in email` against domain skill `security-email-notifications`.

## Links in email

**Sub-topics:** Open redirect, Tracking, Threat modeling and trust boundaries (Links in email), Abuse cases and adversarial testing (Links in email), Logging, audit, and detection (Links in email)

### Do (use this in React)

- Map `Links in email` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Links in email` before merge.

### Don't

- Do not ship `Links in email` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Links in email`.

### Verify

- Peer review `Links in email` against domain skill `security-email-notifications`.

## Bounce and webhook handling

**Sub-topics:** Forged events, Threat modeling and trust boundaries (Bounce and webhook handling), Abuse cases and adversarial testing (Bounce and webhook handling), Logging, audit, and detection (Bounce and webhook handling), Access control and least privilege (Bounce and webhook handling)

### Do (use this in React)

- Map `Bounce and webhook handling` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Bounce and webhook handling` before merge.

### Don't

- Do not ship `Bounce and webhook handling` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Bounce and webhook handling`.

### Verify

- Peer review `Bounce and webhook handling` against domain skill `security-email-notifications`.

## List management

**Sub-topics:** Header injection, Threat modeling and trust boundaries (List management), Abuse cases and adversarial testing (List management), Logging, audit, and detection (List management), Access control and least privilege (List management)

### Do (use this in React)

- Map `List management` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `List management` before merge.

### Don't

- Do not ship `List management` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `List management`.

### Verify

- Peer review `List management` against domain skill `security-email-notifications`.

## Brand impersonation

**Sub-topics:** From addresses, BIMI, Threat modeling and trust boundaries (Brand impersonation), Abuse cases and adversarial testing (Brand impersonation), Logging, audit, and detection (Brand impersonation)

### Do (use this in React)

- Map `Brand impersonation` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Brand impersonation` before merge.

### Don't

- Do not ship `Brand impersonation` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Brand impersonation`.

### Verify

- Peer review `Brand impersonation` against domain skill `security-email-notifications`.

## Attachments

**Sub-topics:** Malware scanning, Threat modeling and trust boundaries (Attachments), Abuse cases and adversarial testing (Attachments), Logging, audit, and detection (Attachments), Access control and least privilege (Attachments)

### Do (use this in React)

- Map `Attachments` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Attachments` before merge.

### Don't

- Do not ship `Attachments` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Attachments`.

### Verify

- Peer review `Attachments` against domain skill `security-email-notifications`.

## SMS and push

**Sub-topics:** OTP leakage, SIM swap awareness, Threat modeling and trust boundaries (SMS and push), Abuse cases and adversarial testing (SMS and push), Logging, audit, and detection (SMS and push)

### Do (use this in React)

- Map `SMS and push` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `SMS and push` before merge.

### Don't

- Do not ship `SMS and push` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `SMS and push`.

### Verify

- Peer review `SMS and push` against domain skill `security-email-notifications`.

## User inbox rules attacks

**Sub-topics:** Forwarding rules, Threat modeling and trust boundaries (User inbox rules attacks), Abuse cases and adversarial testing (User inbox rules attacks), Logging, audit, and detection (User inbox rules attacks), Access control and least privilege (User inbox rules attacks)

### Do (use this in React)

- Map `User inbox rules attacks` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `User inbox rules attacks` before merge.

### Don't

- Do not ship `User inbox rules attacks` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `User inbox rules attacks`.

### Verify

- Peer review `User inbox rules attacks` against domain skill `security-email-notifications`.

## Email provider APIs

**Sub-topics:** API keys, Send-as, Threat modeling and trust boundaries (Email provider APIs), Abuse cases and adversarial testing (Email provider APIs), Logging, audit, and detection (Email provider APIs)

### Do (use this in React)

- Map `Email provider APIs` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Email provider APIs` before merge.

### Don't

- Do not ship `Email provider APIs` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Email provider APIs`.

### Verify

- Peer review `Email provider APIs` against domain skill `security-email-notifications`.

## PII in email bodies

**Sub-topics:** Encryption, Retention, Threat modeling and trust boundaries (PII in email bodies), Abuse cases and adversarial testing (PII in email bodies), Logging, audit, and detection (PII in email bodies)

### Do (use this in React)

- Map `PII in email bodies` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `PII in email bodies` before merge.

### Don't

- Do not ship `PII in email bodies` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `PII in email bodies`.

### Verify

- Peer review `PII in email bodies` against domain skill `security-email-notifications`.

## Email abuse

**Sub-topics:** Forgot password spam, Threat modeling and trust boundaries (Email abuse), Abuse cases and adversarial testing (Email abuse), Logging, audit, and detection (Email abuse), Access control and least privilege (Email abuse)

### Do (use this in React)

- Map `Email abuse` controls to React APIs documented for `security-email-notifications`.
- Add an abuse-case test or check for `Email abuse` before merge.

### Don't

- Do not ship `Email abuse` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Email abuse`.

### Verify

- Peer review `Email abuse` against domain skill `security-email-notifications`.

