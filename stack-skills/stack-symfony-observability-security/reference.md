# Symfony: Observability and debugging security

Stack-specific implementation for **Symfony** (PHP). Normative rules: domain skill `security-observability-security` / `reference.md`.

## PII in traces

**Sub-topics:** Sampling, Scrubbing, Threat modeling and trust boundaries (PII in traces), Abuse cases and adversarial testing (PII in traces), Logging, audit, and detection (PII in traces)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for trace_pii controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Metrics cardinality abuse

**Sub-topics:** Label injection, Threat modeling and trust boundaries (Metrics cardinality abuse), Abuse cases and adversarial testing (Metrics cardinality abuse), Logging, audit, and detection (Metrics cardinality abuse), Access control and least privilege (Metrics cardinality abuse)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for metrics_cardinality controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## APM and session replay

**Sub-topics:** Recording secrets, Threat modeling and trust boundaries (APM and session replay), Abuse cases and adversarial testing (APM and session replay), Logging, audit, and detection (APM and session replay), Access control and least privilege (APM and session replay)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for apm controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Production debugging

**Sub-topics:** Feature flags, Access, Threat modeling and trust boundaries (Production debugging), Abuse cases and adversarial testing (Production debugging), Logging, audit, and detection (Production debugging)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for debug_prod controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Error trackers

**Sub-topics:** Breadcrumbs with tokens, Threat modeling and trust boundaries (Error trackers), Abuse cases and adversarial testing (Error trackers), Logging, audit, and detection (Error trackers), Access control and least privilege (Error trackers)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for error_tracking controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Log injection

**Sub-topics:** CRLF, Forged entries, Threat modeling and trust boundaries (Log injection), Abuse cases and adversarial testing (Log injection), Logging, audit, and detection (Log injection)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for log_injection controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Dashboard access

**Sub-topics:** SSO, Embedding, Threat modeling and trust boundaries (Dashboard access), Abuse cases and adversarial testing (Dashboard access), Logging, audit, and detection (Dashboard access)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for dashboards controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## OpenTelemetry exporters

**Sub-topics:** Endpoints, Auth, Threat modeling and trust boundaries (OpenTelemetry exporters), Abuse cases and adversarial testing (OpenTelemetry exporters), Logging, audit, and detection (OpenTelemetry exporters)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for otel controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Continuous profiling

**Sub-topics:** Heap dumps, Threat modeling and trust boundaries (Continuous profiling), Abuse cases and adversarial testing (Continuous profiling), Logging, audit, and detection (Continuous profiling), Access control and least privilege (Continuous profiling)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for profiling controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Synthetic monitoring creds

**Sub-topics:** Stored passwords, Threat modeling and trust boundaries (Synthetic monitoring creds), Abuse cases and adversarial testing (Synthetic monitoring creds), Logging, audit, and detection (Synthetic monitoring creds), Access control and least privilege (Synthetic monitoring creds)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for synthetic controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## RUM and client beacons

**Sub-topics:** Data minimization, Threat modeling and trust boundaries (RUM and client beacons), Abuse cases and adversarial testing (RUM and client beacons), Logging, audit, and detection (RUM and client beacons), Access control and least privilege (RUM and client beacons)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for rum controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

## Alert routing secrets

**Sub-topics:** Webhook URLs in alerts, Threat modeling and trust boundaries (Alert routing secrets), Abuse cases and adversarial testing (Alert routing secrets), Logging, audit, and detection (Alert routing secrets), Access control and least privilege (Alert routing secrets)

### Do (use this in Symfony)

- Apply domain skill `security-observability-security` requirements using symfony supported APIs only.
- Use the official symfony security documentation for alerting controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of symfony for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on symfony projects in CI.

