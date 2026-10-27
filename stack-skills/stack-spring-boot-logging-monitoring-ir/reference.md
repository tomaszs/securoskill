# Spring Boot: Logging, monitoring, and incident response

Stack-specific implementation for **Spring Boot** (Java). Normative rules: domain skill `security-logging-monitoring-ir` / `reference.md`.

## Structured logging

**Sub-topics:** Correlation IDs, PII redaction, Threat modeling and trust boundaries (Structured logging), Abuse cases and adversarial testing (Structured logging), Logging, audit, and detection (Structured logging)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Structured logging; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Structured logging.
- Keep dependencies patched; pin versions for Structured logging components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Structured logging before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Structured logging paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## SIEM and alerting

**Sub-topics:** Noise, Tuning, Threat modeling and trust boundaries (SIEM and alerting), Abuse cases and adversarial testing (SIEM and alerting), Logging, audit, and detection (SIEM and alerting)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SIEM and alerting; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SIEM and alerting.
- Keep dependencies patched; pin versions for SIEM and alerting components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SIEM and alerting before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SIEM and alerting paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Audit trails

**Sub-topics:** Tamper evidence, Clock sync, Threat modeling and trust boundaries (Audit trails), Abuse cases and adversarial testing (Audit trails), Logging, audit, and detection (Audit trails)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Audit trails; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Audit trails.
- Keep dependencies patched; pin versions for Audit trails components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Audit trails before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Audit trails paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Incident response playbooks

**Sub-topics:** Roles, Comms, Threat modeling and trust boundaries (Incident response playbooks), Abuse cases and adversarial testing (Incident response playbooks), Logging, audit, and detection (Incident response playbooks)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Incident response playbooks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Incident response playbooks.
- Keep dependencies patched; pin versions for Incident response playbooks components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Incident response playbooks before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Incident response playbooks paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Forensics readiness

**Sub-topics:** Memory dumps, Chain of custody, Threat modeling and trust boundaries (Forensics readiness), Abuse cases and adversarial testing (Forensics readiness), Logging, audit, and detection (Forensics readiness)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Forensics readiness; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Forensics readiness.
- Keep dependencies patched; pin versions for Forensics readiness components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Forensics readiness before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Forensics readiness paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Vulnerability disclosure

**Sub-topics:** Safe harbor, SLAs, Threat modeling and trust boundaries (Vulnerability disclosure), Abuse cases and adversarial testing (Vulnerability disclosure), Logging, audit, and detection (Vulnerability disclosure)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Vulnerability disclosure; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vulnerability disclosure.
- Keep dependencies patched; pin versions for Vulnerability disclosure components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Vulnerability disclosure before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Vulnerability disclosure paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Security on-call

**Sub-topics:** Escalation, Paging hygiene, Threat modeling and trust boundaries (Security on-call), Abuse cases and adversarial testing (Security on-call), Logging, audit, and detection (Security on-call)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Security on-call; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security on-call.
- Keep dependencies patched; pin versions for Security on-call components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Security on-call before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Security on-call paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Security metrics

**Sub-topics:** MTTD, Patch latency, Threat modeling and trust boundaries (Security metrics), Abuse cases and adversarial testing (Security metrics), Logging, audit, and detection (Security metrics)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Security metrics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security metrics.
- Keep dependencies patched; pin versions for Security metrics components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Security metrics before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Security metrics paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Deception and honeypots

**Sub-topics:** Legal, Scope, Threat modeling and trust boundaries (Deception and honeypots), Abuse cases and adversarial testing (Deception and honeypots), Logging, audit, and detection (Deception and honeypots)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Deception and honeypots; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deception and honeypots.
- Keep dependencies patched; pin versions for Deception and honeypots components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Deception and honeypots before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Deception and honeypots paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## UEBA

**Sub-topics:** Insider threat, False positives, Threat modeling and trust boundaries (UEBA), Abuse cases and adversarial testing (UEBA), Logging, audit, and detection (UEBA)

### Platform rules (summary)

- Validate and canonicalize all inputs touching UEBA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to UEBA.
- Keep dependencies patched; pin versions for UEBA components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for UEBA before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for UEBA paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Post-incident review

**Sub-topics:** Blameless, Tracking, Threat modeling and trust boundaries (Post-incident review), Abuse cases and adversarial testing (Post-incident review), Logging, audit, and detection (Post-incident review)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Post-incident review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Post-incident review.
- Keep dependencies patched; pin versions for Post-incident review components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Post-incident review before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Post-incident review paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Lawful access logs

**Sub-topics:** Subpoena, Customer notice, Threat modeling and trust boundaries (Lawful access logs), Abuse cases and adversarial testing (Lawful access logs), Logging, audit, and detection (Lawful access logs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Lawful access logs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Lawful access logs.
- Keep dependencies patched; pin versions for Lawful access logs components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-logging-monitoring-ir` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Lawful access logs before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Lawful access logs paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

