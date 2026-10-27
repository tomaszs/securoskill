# Rules reference: Logging, monitoring, and incident response

Detect, respond, and learn from security events.

## Structured logging

Sub-topics: Correlation IDs, PII redaction, Threat modeling and trust boundaries (Structured logging), Abuse cases and adversarial testing (Structured logging), Logging, audit, and detection (Structured logging)

### Do

- Validate and canonicalize all inputs touching Structured logging; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Structured logging.
- Keep dependencies patched; pin versions for Structured logging components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Structured logging in Structured logging as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Structured logging (Logging, monitoring, and incident response).
- Require security review for material changes affecting Structured logging.

### Design

- Apply least privilege and defense in depth for Structured logging.
- Prefer established patterns and libraries over custom crypto or auth for Structured logging.
- Fail closed: deny by default when Structured logging cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Structured logging; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Structured logging.
- Keep dependencies patched; pin versions for Structured logging components.

### Verification

- Add automated tests and SAST/DAST coverage for Structured logging paths.
- Run dependency and secret scanning on every change touching Structured logging.
- Perform targeted manual tests (abuse cases) for Structured logging.

### Operations

- Log security-relevant events for Structured logging without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Structured logging.
- Review access and configuration for Structured logging on a regular cadence.

## SIEM and alerting

Sub-topics: Noise, Tuning, Threat modeling and trust boundaries (SIEM and alerting), Abuse cases and adversarial testing (SIEM and alerting), Logging, audit, and detection (SIEM and alerting)

### Do

- Validate and canonicalize all inputs touching SIEM and alerting; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SIEM and alerting.
- Keep dependencies patched; pin versions for SIEM and alerting components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SIEM and alerting in SIEM and alerting as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SIEM and alerting (Logging, monitoring, and incident response).
- Require security review for material changes affecting SIEM and alerting.

### Design

- Apply least privilege and defense in depth for SIEM and alerting.
- Prefer established patterns and libraries over custom crypto or auth for SIEM and alerting.
- Fail closed: deny by default when SIEM and alerting cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SIEM and alerting; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SIEM and alerting.
- Keep dependencies patched; pin versions for SIEM and alerting components.

### Verification

- Add automated tests and SAST/DAST coverage for SIEM and alerting paths.
- Run dependency and secret scanning on every change touching SIEM and alerting.
- Perform targeted manual tests (abuse cases) for SIEM and alerting.

### Operations

- Log security-relevant events for SIEM and alerting without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SIEM and alerting.
- Review access and configuration for SIEM and alerting on a regular cadence.

## Audit trails

Sub-topics: Tamper evidence, Clock sync, Threat modeling and trust boundaries (Audit trails), Abuse cases and adversarial testing (Audit trails), Logging, audit, and detection (Audit trails)

### Do

- Validate and canonicalize all inputs touching Audit trails; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Audit trails.
- Keep dependencies patched; pin versions for Audit trails components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Audit trails in Audit trails as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Audit trails (Logging, monitoring, and incident response).
- Require security review for material changes affecting Audit trails.

### Design

- Apply least privilege and defense in depth for Audit trails.
- Prefer established patterns and libraries over custom crypto or auth for Audit trails.
- Fail closed: deny by default when Audit trails cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Audit trails; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Audit trails.
- Keep dependencies patched; pin versions for Audit trails components.

### Verification

- Add automated tests and SAST/DAST coverage for Audit trails paths.
- Run dependency and secret scanning on every change touching Audit trails.
- Perform targeted manual tests (abuse cases) for Audit trails.

### Operations

- Log security-relevant events for Audit trails without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Audit trails.
- Review access and configuration for Audit trails on a regular cadence.

## Incident response playbooks

Sub-topics: Roles, Comms, Threat modeling and trust boundaries (Incident response playbooks), Abuse cases and adversarial testing (Incident response playbooks), Logging, audit, and detection (Incident response playbooks)

### Do

- Validate and canonicalize all inputs touching Incident response playbooks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Incident response playbooks.
- Keep dependencies patched; pin versions for Incident response playbooks components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Incident response playbooks in Incident response playbooks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Incident response playbooks (Logging, monitoring, and incident response).
- Require security review for material changes affecting Incident response playbooks.

### Design

- Apply least privilege and defense in depth for Incident response playbooks.
- Prefer established patterns and libraries over custom crypto or auth for Incident response playbooks.
- Fail closed: deny by default when Incident response playbooks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Incident response playbooks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Incident response playbooks.
- Keep dependencies patched; pin versions for Incident response playbooks components.

### Verification

- Add automated tests and SAST/DAST coverage for Incident response playbooks paths.
- Run dependency and secret scanning on every change touching Incident response playbooks.
- Perform targeted manual tests (abuse cases) for Incident response playbooks.

### Operations

- Log security-relevant events for Incident response playbooks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Incident response playbooks.
- Review access and configuration for Incident response playbooks on a regular cadence.

## Forensics readiness

Sub-topics: Memory dumps, Chain of custody, Threat modeling and trust boundaries (Forensics readiness), Abuse cases and adversarial testing (Forensics readiness), Logging, audit, and detection (Forensics readiness)

### Do

- Validate and canonicalize all inputs touching Forensics readiness; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Forensics readiness.
- Keep dependencies patched; pin versions for Forensics readiness components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Forensics readiness in Forensics readiness as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Forensics readiness (Logging, monitoring, and incident response).
- Require security review for material changes affecting Forensics readiness.

### Design

- Apply least privilege and defense in depth for Forensics readiness.
- Prefer established patterns and libraries over custom crypto or auth for Forensics readiness.
- Fail closed: deny by default when Forensics readiness cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Forensics readiness; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Forensics readiness.
- Keep dependencies patched; pin versions for Forensics readiness components.

### Verification

- Add automated tests and SAST/DAST coverage for Forensics readiness paths.
- Run dependency and secret scanning on every change touching Forensics readiness.
- Perform targeted manual tests (abuse cases) for Forensics readiness.

### Operations

- Log security-relevant events for Forensics readiness without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Forensics readiness.
- Review access and configuration for Forensics readiness on a regular cadence.

## Vulnerability disclosure

Sub-topics: Safe harbor, SLAs, Threat modeling and trust boundaries (Vulnerability disclosure), Abuse cases and adversarial testing (Vulnerability disclosure), Logging, audit, and detection (Vulnerability disclosure)

### Do

- Validate and canonicalize all inputs touching Vulnerability disclosure; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vulnerability disclosure.
- Keep dependencies patched; pin versions for Vulnerability disclosure components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Vulnerability disclosure in Vulnerability disclosure as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Vulnerability disclosure (Logging, monitoring, and incident response).
- Require security review for material changes affecting Vulnerability disclosure.

### Design

- Apply least privilege and defense in depth for Vulnerability disclosure.
- Prefer established patterns and libraries over custom crypto or auth for Vulnerability disclosure.
- Fail closed: deny by default when Vulnerability disclosure cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Vulnerability disclosure; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vulnerability disclosure.
- Keep dependencies patched; pin versions for Vulnerability disclosure components.

### Verification

- Add automated tests and SAST/DAST coverage for Vulnerability disclosure paths.
- Run dependency and secret scanning on every change touching Vulnerability disclosure.
- Perform targeted manual tests (abuse cases) for Vulnerability disclosure.

### Operations

- Log security-relevant events for Vulnerability disclosure without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Vulnerability disclosure.
- Review access and configuration for Vulnerability disclosure on a regular cadence.

## Security on-call

Sub-topics: Escalation, Paging hygiene, Threat modeling and trust boundaries (Security on-call), Abuse cases and adversarial testing (Security on-call), Logging, audit, and detection (Security on-call)

### Do

- Validate and canonicalize all inputs touching Security on-call; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security on-call.
- Keep dependencies patched; pin versions for Security on-call components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Security on-call in Security on-call as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Security on-call (Logging, monitoring, and incident response).
- Require security review for material changes affecting Security on-call.

### Design

- Apply least privilege and defense in depth for Security on-call.
- Prefer established patterns and libraries over custom crypto or auth for Security on-call.
- Fail closed: deny by default when Security on-call cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Security on-call; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security on-call.
- Keep dependencies patched; pin versions for Security on-call components.

### Verification

- Add automated tests and SAST/DAST coverage for Security on-call paths.
- Run dependency and secret scanning on every change touching Security on-call.
- Perform targeted manual tests (abuse cases) for Security on-call.

### Operations

- Log security-relevant events for Security on-call without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Security on-call.
- Review access and configuration for Security on-call on a regular cadence.

## Security metrics

Sub-topics: MTTD, Patch latency, Threat modeling and trust boundaries (Security metrics), Abuse cases and adversarial testing (Security metrics), Logging, audit, and detection (Security metrics)

### Do

- Validate and canonicalize all inputs touching Security metrics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security metrics.
- Keep dependencies patched; pin versions for Security metrics components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Security metrics in Security metrics as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Security metrics (Logging, monitoring, and incident response).
- Require security review for material changes affecting Security metrics.

### Design

- Apply least privilege and defense in depth for Security metrics.
- Prefer established patterns and libraries over custom crypto or auth for Security metrics.
- Fail closed: deny by default when Security metrics cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Security metrics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security metrics.
- Keep dependencies patched; pin versions for Security metrics components.

### Verification

- Add automated tests and SAST/DAST coverage for Security metrics paths.
- Run dependency and secret scanning on every change touching Security metrics.
- Perform targeted manual tests (abuse cases) for Security metrics.

### Operations

- Log security-relevant events for Security metrics without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Security metrics.
- Review access and configuration for Security metrics on a regular cadence.

## Deception and honeypots

Sub-topics: Legal, Scope, Threat modeling and trust boundaries (Deception and honeypots), Abuse cases and adversarial testing (Deception and honeypots), Logging, audit, and detection (Deception and honeypots)

### Do

- Validate and canonicalize all inputs touching Deception and honeypots; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deception and honeypots.
- Keep dependencies patched; pin versions for Deception and honeypots components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Deception and honeypots in Deception and honeypots as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Deception and honeypots (Logging, monitoring, and incident response).
- Require security review for material changes affecting Deception and honeypots.

### Design

- Apply least privilege and defense in depth for Deception and honeypots.
- Prefer established patterns and libraries over custom crypto or auth for Deception and honeypots.
- Fail closed: deny by default when Deception and honeypots cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Deception and honeypots; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deception and honeypots.
- Keep dependencies patched; pin versions for Deception and honeypots components.

### Verification

- Add automated tests and SAST/DAST coverage for Deception and honeypots paths.
- Run dependency and secret scanning on every change touching Deception and honeypots.
- Perform targeted manual tests (abuse cases) for Deception and honeypots.

### Operations

- Log security-relevant events for Deception and honeypots without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Deception and honeypots.
- Review access and configuration for Deception and honeypots on a regular cadence.

## UEBA

Sub-topics: Insider threat, False positives, Threat modeling and trust boundaries (UEBA), Abuse cases and adversarial testing (UEBA), Logging, audit, and detection (UEBA)

### Do

- Validate and canonicalize all inputs touching UEBA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to UEBA.
- Keep dependencies patched; pin versions for UEBA components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat UEBA in UEBA as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for UEBA (Logging, monitoring, and incident response).
- Require security review for material changes affecting UEBA.

### Design

- Apply least privilege and defense in depth for UEBA.
- Prefer established patterns and libraries over custom crypto or auth for UEBA.
- Fail closed: deny by default when UEBA cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching UEBA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to UEBA.
- Keep dependencies patched; pin versions for UEBA components.

### Verification

- Add automated tests and SAST/DAST coverage for UEBA paths.
- Run dependency and secret scanning on every change touching UEBA.
- Perform targeted manual tests (abuse cases) for UEBA.

### Operations

- Log security-relevant events for UEBA without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in UEBA.
- Review access and configuration for UEBA on a regular cadence.

## Post-incident review

Sub-topics: Blameless, Tracking, Threat modeling and trust boundaries (Post-incident review), Abuse cases and adversarial testing (Post-incident review), Logging, audit, and detection (Post-incident review)

### Do

- Validate and canonicalize all inputs touching Post-incident review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Post-incident review.
- Keep dependencies patched; pin versions for Post-incident review components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Post-incident review in Post-incident review as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Post-incident review (Logging, monitoring, and incident response).
- Require security review for material changes affecting Post-incident review.

### Design

- Apply least privilege and defense in depth for Post-incident review.
- Prefer established patterns and libraries over custom crypto or auth for Post-incident review.
- Fail closed: deny by default when Post-incident review cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Post-incident review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Post-incident review.
- Keep dependencies patched; pin versions for Post-incident review components.

### Verification

- Add automated tests and SAST/DAST coverage for Post-incident review paths.
- Run dependency and secret scanning on every change touching Post-incident review.
- Perform targeted manual tests (abuse cases) for Post-incident review.

### Operations

- Log security-relevant events for Post-incident review without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Post-incident review.
- Review access and configuration for Post-incident review on a regular cadence.

## Lawful access logs

Sub-topics: Subpoena, Customer notice, Threat modeling and trust boundaries (Lawful access logs), Abuse cases and adversarial testing (Lawful access logs), Logging, audit, and detection (Lawful access logs)

### Do

- Validate and canonicalize all inputs touching Lawful access logs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Lawful access logs.
- Keep dependencies patched; pin versions for Lawful access logs components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Lawful access logs in Lawful access logs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Lawful access logs (Logging, monitoring, and incident response).
- Require security review for material changes affecting Lawful access logs.

### Design

- Apply least privilege and defense in depth for Lawful access logs.
- Prefer established patterns and libraries over custom crypto or auth for Lawful access logs.
- Fail closed: deny by default when Lawful access logs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Lawful access logs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Lawful access logs.
- Keep dependencies patched; pin versions for Lawful access logs components.

### Verification

- Add automated tests and SAST/DAST coverage for Lawful access logs paths.
- Run dependency and secret scanning on every change touching Lawful access logs.
- Perform targeted manual tests (abuse cases) for Lawful access logs.

### Operations

- Log security-relevant events for Lawful access logs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Lawful access logs.
- Review access and configuration for Lawful access logs on a regular cadence.

