# Symfony: Observability and debugging security

Stack-specific implementation for **Symfony** (PHP). Normative rules: domain skill `security-observability-security` / `reference.md`.

## PII in traces

**Sub-topics:** Sampling, Scrubbing, Threat modeling and trust boundaries (PII in traces), Abuse cases and adversarial testing (PII in traces), Logging, audit, and detection (PII in traces)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Metrics cardinality abuse

**Sub-topics:** Label injection, Threat modeling and trust boundaries (Metrics cardinality abuse), Abuse cases and adversarial testing (Metrics cardinality abuse), Logging, audit, and detection (Metrics cardinality abuse), Access control and least privilege (Metrics cardinality abuse)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## APM and session replay

**Sub-topics:** Recording secrets, Threat modeling and trust boundaries (APM and session replay), Abuse cases and adversarial testing (APM and session replay), Logging, audit, and detection (APM and session replay), Access control and least privilege (APM and session replay)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Production debugging

**Sub-topics:** Feature flags, Access, Threat modeling and trust boundaries (Production debugging), Abuse cases and adversarial testing (Production debugging), Logging, audit, and detection (Production debugging)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Error trackers

**Sub-topics:** Breadcrumbs with tokens, Threat modeling and trust boundaries (Error trackers), Abuse cases and adversarial testing (Error trackers), Logging, audit, and detection (Error trackers), Access control and least privilege (Error trackers)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Log injection

**Sub-topics:** CRLF, Forged entries, Threat modeling and trust boundaries (Log injection), Abuse cases and adversarial testing (Log injection), Logging, audit, and detection (Log injection)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Dashboard access

**Sub-topics:** SSO, Embedding, Threat modeling and trust boundaries (Dashboard access), Abuse cases and adversarial testing (Dashboard access), Logging, audit, and detection (Dashboard access)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## OpenTelemetry exporters

**Sub-topics:** Endpoints, Auth, Threat modeling and trust boundaries (OpenTelemetry exporters), Abuse cases and adversarial testing (OpenTelemetry exporters), Logging, audit, and detection (OpenTelemetry exporters)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Continuous profiling

**Sub-topics:** Heap dumps, Threat modeling and trust boundaries (Continuous profiling), Abuse cases and adversarial testing (Continuous profiling), Logging, audit, and detection (Continuous profiling), Access control and least privilege (Continuous profiling)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Synthetic monitoring creds

**Sub-topics:** Stored passwords, Threat modeling and trust boundaries (Synthetic monitoring creds), Abuse cases and adversarial testing (Synthetic monitoring creds), Logging, audit, and detection (Synthetic monitoring creds), Access control and least privilege (Synthetic monitoring creds)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## RUM and client beacons

**Sub-topics:** Data minimization, Threat modeling and trust boundaries (RUM and client beacons), Abuse cases and adversarial testing (RUM and client beacons), Logging, audit, and detection (RUM and client beacons), Access control and least privilege (RUM and client beacons)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

## Alert routing secrets

**Sub-topics:** Webhook URLs in alerts, Threat modeling and trust boundaries (Alert routing secrets), Abuse cases and adversarial testing (Alert routing secrets), Logging, audit, and detection (Alert routing secrets), Access control and least privilege (Alert routing secrets)

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `observability-security`; load stack skill `security-observability-security` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-observability-security` (domain reference.md).

### Don't

- Do not duplicate `observability-security` controls only in Symfony config while leaving security-observability-security misconfigured.
- Do not assume Symfony defaults satisfy `security-observability-security` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-observability-security`.

