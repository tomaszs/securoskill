# Laravel: Observability and debugging security

Stack-specific implementation for **Laravel** (PHP). Normative rules: domain skill `security-observability-security` / `reference.md`.

## PII in traces

**Sub-topics:** Sampling, Scrubbing, Threat modeling and trust boundaries (PII in traces), Abuse cases and adversarial testing (PII in traces), Logging, audit, and detection (PII in traces)

### Platform rules (summary)

- Validate and canonicalize all inputs touching PII in traces; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in traces.
- Keep dependencies patched; pin versions for PII in traces components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PII in traces before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PII in traces paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Metrics cardinality abuse

**Sub-topics:** Label injection, Threat modeling and trust boundaries (Metrics cardinality abuse), Abuse cases and adversarial testing (Metrics cardinality abuse), Logging, audit, and detection (Metrics cardinality abuse), Access control and least privilege (Metrics cardinality abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Metrics cardinality abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Metrics cardinality abuse.
- Keep dependencies patched; pin versions for Metrics cardinality abuse components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Metrics cardinality abuse before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Metrics cardinality abuse paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## APM and session replay

**Sub-topics:** Recording secrets, Threat modeling and trust boundaries (APM and session replay), Abuse cases and adversarial testing (APM and session replay), Logging, audit, and detection (APM and session replay), Access control and least privilege (APM and session replay)

### Platform rules (summary)

- Validate and canonicalize all inputs touching APM and session replay; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to APM and session replay.
- Keep dependencies patched; pin versions for APM and session replay components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for APM and session replay before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for APM and session replay paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Production debugging

**Sub-topics:** Feature flags, Access, Threat modeling and trust boundaries (Production debugging), Abuse cases and adversarial testing (Production debugging), Logging, audit, and detection (Production debugging)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Production debugging; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Production debugging.
- Keep dependencies patched; pin versions for Production debugging components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Production debugging before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Production debugging paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Error trackers

**Sub-topics:** Breadcrumbs with tokens, Threat modeling and trust boundaries (Error trackers), Abuse cases and adversarial testing (Error trackers), Logging, audit, and detection (Error trackers), Access control and least privilege (Error trackers)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Error trackers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Error trackers.
- Keep dependencies patched; pin versions for Error trackers components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Error trackers before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Error trackers paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Log injection

**Sub-topics:** CRLF, Forged entries, Threat modeling and trust boundaries (Log injection), Abuse cases and adversarial testing (Log injection), Logging, audit, and detection (Log injection)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Log injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Log injection.
- Keep dependencies patched; pin versions for Log injection components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Log injection before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Log injection paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Dashboard access

**Sub-topics:** SSO, Embedding, Threat modeling and trust boundaries (Dashboard access), Abuse cases and adversarial testing (Dashboard access), Logging, audit, and detection (Dashboard access)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Dashboard access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dashboard access.
- Keep dependencies patched; pin versions for Dashboard access components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Dashboard access before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Dashboard access paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## OpenTelemetry exporters

**Sub-topics:** Endpoints, Auth, Threat modeling and trust boundaries (OpenTelemetry exporters), Abuse cases and adversarial testing (OpenTelemetry exporters), Logging, audit, and detection (OpenTelemetry exporters)

### Platform rules (summary)

- Validate and canonicalize all inputs touching OpenTelemetry exporters; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OpenTelemetry exporters.
- Keep dependencies patched; pin versions for OpenTelemetry exporters components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for OpenTelemetry exporters before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for OpenTelemetry exporters paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Continuous profiling

**Sub-topics:** Heap dumps, Threat modeling and trust boundaries (Continuous profiling), Abuse cases and adversarial testing (Continuous profiling), Logging, audit, and detection (Continuous profiling), Access control and least privilege (Continuous profiling)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Continuous profiling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Continuous profiling.
- Keep dependencies patched; pin versions for Continuous profiling components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Continuous profiling before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Continuous profiling paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Synthetic monitoring creds

**Sub-topics:** Stored passwords, Threat modeling and trust boundaries (Synthetic monitoring creds), Abuse cases and adversarial testing (Synthetic monitoring creds), Logging, audit, and detection (Synthetic monitoring creds), Access control and least privilege (Synthetic monitoring creds)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Synthetic monitoring creds; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Synthetic monitoring creds.
- Keep dependencies patched; pin versions for Synthetic monitoring creds components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Synthetic monitoring creds before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Synthetic monitoring creds paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## RUM and client beacons

**Sub-topics:** Data minimization, Threat modeling and trust boundaries (RUM and client beacons), Abuse cases and adversarial testing (RUM and client beacons), Logging, audit, and detection (RUM and client beacons), Access control and least privilege (RUM and client beacons)

### Platform rules (summary)

- Validate and canonicalize all inputs touching RUM and client beacons; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RUM and client beacons.
- Keep dependencies patched; pin versions for RUM and client beacons components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for RUM and client beacons before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for RUM and client beacons paths in Laravel.
- Run SAST/dependency scan configured for PHP.

## Alert routing secrets

**Sub-topics:** Webhook URLs in alerts, Threat modeling and trust boundaries (Alert routing secrets), Abuse cases and adversarial testing (Alert routing secrets), Logging, audit, and detection (Alert routing secrets), Access control and least privilege (Alert routing secrets)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Alert routing secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Alert routing secrets.
- Keep dependencies patched; pin versions for Alert routing secrets components.

### How to do this in Laravel

- Read normative rules in domain skill `security-observability-security` / `reference.md`, then apply them using Laravel APIs and deployment model.
- Prefer framework-maintained security features in Laravel over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Alert routing secrets before merge.
- Pin Laravel dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Alert routing secrets paths in Laravel.
- Run SAST/dependency scan configured for PHP.

