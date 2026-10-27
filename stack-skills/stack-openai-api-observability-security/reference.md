# OpenAI API / Agents SDK: Observability and debugging security

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-observability-security` / `reference.md`.

## PII in traces

**Sub-topics:** Sampling, Scrubbing, Threat modeling and trust boundaries (PII in traces), Abuse cases and adversarial testing (PII in traces), Logging, audit, and detection (PII in traces)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Metrics cardinality abuse

**Sub-topics:** Label injection, Threat modeling and trust boundaries (Metrics cardinality abuse), Abuse cases and adversarial testing (Metrics cardinality abuse), Logging, audit, and detection (Metrics cardinality abuse), Access control and least privilege (Metrics cardinality abuse)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## APM and session replay

**Sub-topics:** Recording secrets, Threat modeling and trust boundaries (APM and session replay), Abuse cases and adversarial testing (APM and session replay), Logging, audit, and detection (APM and session replay), Access control and least privilege (APM and session replay)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Production debugging

**Sub-topics:** Feature flags, Access, Threat modeling and trust boundaries (Production debugging), Abuse cases and adversarial testing (Production debugging), Logging, audit, and detection (Production debugging)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Error trackers

**Sub-topics:** Breadcrumbs with tokens, Threat modeling and trust boundaries (Error trackers), Abuse cases and adversarial testing (Error trackers), Logging, audit, and detection (Error trackers), Access control and least privilege (Error trackers)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Log injection

**Sub-topics:** CRLF, Forged entries, Threat modeling and trust boundaries (Log injection), Abuse cases and adversarial testing (Log injection), Logging, audit, and detection (Log injection)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Dashboard access

**Sub-topics:** SSO, Embedding, Threat modeling and trust boundaries (Dashboard access), Abuse cases and adversarial testing (Dashboard access), Logging, audit, and detection (Dashboard access)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## OpenTelemetry exporters

**Sub-topics:** Endpoints, Auth, Threat modeling and trust boundaries (OpenTelemetry exporters), Abuse cases and adversarial testing (OpenTelemetry exporters), Logging, audit, and detection (OpenTelemetry exporters)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Continuous profiling

**Sub-topics:** Heap dumps, Threat modeling and trust boundaries (Continuous profiling), Abuse cases and adversarial testing (Continuous profiling), Logging, audit, and detection (Continuous profiling), Access control and least privilege (Continuous profiling)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Synthetic monitoring creds

**Sub-topics:** Stored passwords, Threat modeling and trust boundaries (Synthetic monitoring creds), Abuse cases and adversarial testing (Synthetic monitoring creds), Logging, audit, and detection (Synthetic monitoring creds), Access control and least privilege (Synthetic monitoring creds)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## RUM and client beacons

**Sub-topics:** Data minimization, Threat modeling and trust boundaries (RUM and client beacons), Abuse cases and adversarial testing (RUM and client beacons), Logging, audit, and detection (RUM and client beacons), Access control and least privilege (RUM and client beacons)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Alert routing secrets

**Sub-topics:** Webhook URLs in alerts, Threat modeling and trust boundaries (Alert routing secrets), Abuse cases and adversarial testing (Alert routing secrets), Logging, audit, and detection (Alert routing secrets), Access control and least privilege (Alert routing secrets)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

