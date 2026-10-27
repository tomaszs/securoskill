# Rules reference: Observability and debugging security

Traces, metrics, APM, and debug tooling.

## PII in traces

Sub-topics: Sampling, Scrubbing

### Policy

- Treat PII in traces in PII in traces as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PII in traces (Observability and debugging security).
- Require security review for material changes affecting PII in traces.

### Design

- Apply least privilege and defense in depth for PII in traces.
- Prefer established patterns and libraries over custom crypto or auth for PII in traces.
- Fail closed: deny by default when PII in traces cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PII in traces; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PII in traces.
- Keep dependencies patched; pin versions for PII in traces components.

### Verification

- Add automated tests and SAST/DAST coverage for PII in traces paths.
- Run dependency and secret scanning on every change touching PII in traces.
- Perform targeted manual tests (abuse cases) for PII in traces.

### Operations

- Log security-relevant events for PII in traces without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PII in traces.
- Review access and configuration for PII in traces on a regular cadence.

## Metrics cardinality abuse

Sub-topics: Label injection

### Policy

- Treat Metrics cardinality abuse in Metrics cardinality abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Metrics cardinality abuse (Observability and debugging security).
- Require security review for material changes affecting Metrics cardinality abuse.

### Design

- Apply least privilege and defense in depth for Metrics cardinality abuse.
- Prefer established patterns and libraries over custom crypto or auth for Metrics cardinality abuse.
- Fail closed: deny by default when Metrics cardinality abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Metrics cardinality abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Metrics cardinality abuse.
- Keep dependencies patched; pin versions for Metrics cardinality abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Metrics cardinality abuse paths.
- Run dependency and secret scanning on every change touching Metrics cardinality abuse.
- Perform targeted manual tests (abuse cases) for Metrics cardinality abuse.

### Operations

- Log security-relevant events for Metrics cardinality abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Metrics cardinality abuse.
- Review access and configuration for Metrics cardinality abuse on a regular cadence.

## APM and session replay

Sub-topics: Recording secrets

### Policy

- Treat APM and session replay in APM and session replay as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for APM and session replay (Observability and debugging security).
- Require security review for material changes affecting APM and session replay.

### Design

- Apply least privilege and defense in depth for APM and session replay.
- Prefer established patterns and libraries over custom crypto or auth for APM and session replay.
- Fail closed: deny by default when APM and session replay cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching APM and session replay; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to APM and session replay.
- Keep dependencies patched; pin versions for APM and session replay components.

### Verification

- Add automated tests and SAST/DAST coverage for APM and session replay paths.
- Run dependency and secret scanning on every change touching APM and session replay.
- Perform targeted manual tests (abuse cases) for APM and session replay.

### Operations

- Log security-relevant events for APM and session replay without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in APM and session replay.
- Review access and configuration for APM and session replay on a regular cadence.

## Production debugging

Sub-topics: Feature flags, Access

### Policy

- Treat Production debugging in Production debugging as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Production debugging (Observability and debugging security).
- Require security review for material changes affecting Production debugging.

### Design

- Apply least privilege and defense in depth for Production debugging.
- Prefer established patterns and libraries over custom crypto or auth for Production debugging.
- Fail closed: deny by default when Production debugging cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Production debugging; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Production debugging.
- Keep dependencies patched; pin versions for Production debugging components.

### Verification

- Add automated tests and SAST/DAST coverage for Production debugging paths.
- Run dependency and secret scanning on every change touching Production debugging.
- Perform targeted manual tests (abuse cases) for Production debugging.

### Operations

- Log security-relevant events for Production debugging without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Production debugging.
- Review access and configuration for Production debugging on a regular cadence.

## Error trackers

Sub-topics: Breadcrumbs with tokens

### Policy

- Treat Error trackers in Error trackers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Error trackers (Observability and debugging security).
- Require security review for material changes affecting Error trackers.

### Design

- Apply least privilege and defense in depth for Error trackers.
- Prefer established patterns and libraries over custom crypto or auth for Error trackers.
- Fail closed: deny by default when Error trackers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Error trackers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Error trackers.
- Keep dependencies patched; pin versions for Error trackers components.

### Verification

- Add automated tests and SAST/DAST coverage for Error trackers paths.
- Run dependency and secret scanning on every change touching Error trackers.
- Perform targeted manual tests (abuse cases) for Error trackers.

### Operations

- Log security-relevant events for Error trackers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Error trackers.
- Review access and configuration for Error trackers on a regular cadence.

## Log injection

Sub-topics: CRLF, Forged entries

### Policy

- Treat Log injection in Log injection as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Log injection (Observability and debugging security).
- Require security review for material changes affecting Log injection.

### Design

- Apply least privilege and defense in depth for Log injection.
- Prefer established patterns and libraries over custom crypto or auth for Log injection.
- Fail closed: deny by default when Log injection cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Log injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Log injection.
- Keep dependencies patched; pin versions for Log injection components.

### Verification

- Add automated tests and SAST/DAST coverage for Log injection paths.
- Run dependency and secret scanning on every change touching Log injection.
- Perform targeted manual tests (abuse cases) for Log injection.

### Operations

- Log security-relevant events for Log injection without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Log injection.
- Review access and configuration for Log injection on a regular cadence.

## Dashboard access

Sub-topics: SSO, Embedding

### Policy

- Treat Dashboard access in Dashboard access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Dashboard access (Observability and debugging security).
- Require security review for material changes affecting Dashboard access.

### Design

- Apply least privilege and defense in depth for Dashboard access.
- Prefer established patterns and libraries over custom crypto or auth for Dashboard access.
- Fail closed: deny by default when Dashboard access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Dashboard access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dashboard access.
- Keep dependencies patched; pin versions for Dashboard access components.

### Verification

- Add automated tests and SAST/DAST coverage for Dashboard access paths.
- Run dependency and secret scanning on every change touching Dashboard access.
- Perform targeted manual tests (abuse cases) for Dashboard access.

### Operations

- Log security-relevant events for Dashboard access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Dashboard access.
- Review access and configuration for Dashboard access on a regular cadence.

## OpenTelemetry exporters

Sub-topics: Endpoints, Auth

### Policy

- Treat OpenTelemetry exporters in OpenTelemetry exporters as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for OpenTelemetry exporters (Observability and debugging security).
- Require security review for material changes affecting OpenTelemetry exporters.

### Design

- Apply least privilege and defense in depth for OpenTelemetry exporters.
- Prefer established patterns and libraries over custom crypto or auth for OpenTelemetry exporters.
- Fail closed: deny by default when OpenTelemetry exporters cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching OpenTelemetry exporters; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OpenTelemetry exporters.
- Keep dependencies patched; pin versions for OpenTelemetry exporters components.

### Verification

- Add automated tests and SAST/DAST coverage for OpenTelemetry exporters paths.
- Run dependency and secret scanning on every change touching OpenTelemetry exporters.
- Perform targeted manual tests (abuse cases) for OpenTelemetry exporters.

### Operations

- Log security-relevant events for OpenTelemetry exporters without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in OpenTelemetry exporters.
- Review access and configuration for OpenTelemetry exporters on a regular cadence.

## Continuous profiling

Sub-topics: Heap dumps

### Policy

- Treat Continuous profiling in Continuous profiling as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Continuous profiling (Observability and debugging security).
- Require security review for material changes affecting Continuous profiling.

### Design

- Apply least privilege and defense in depth for Continuous profiling.
- Prefer established patterns and libraries over custom crypto or auth for Continuous profiling.
- Fail closed: deny by default when Continuous profiling cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Continuous profiling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Continuous profiling.
- Keep dependencies patched; pin versions for Continuous profiling components.

### Verification

- Add automated tests and SAST/DAST coverage for Continuous profiling paths.
- Run dependency and secret scanning on every change touching Continuous profiling.
- Perform targeted manual tests (abuse cases) for Continuous profiling.

### Operations

- Log security-relevant events for Continuous profiling without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Continuous profiling.
- Review access and configuration for Continuous profiling on a regular cadence.

## Synthetic monitoring creds

Sub-topics: Stored passwords

### Policy

- Treat Synthetic monitoring creds in Synthetic monitoring creds as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Synthetic monitoring creds (Observability and debugging security).
- Require security review for material changes affecting Synthetic monitoring creds.

### Design

- Apply least privilege and defense in depth for Synthetic monitoring creds.
- Prefer established patterns and libraries over custom crypto or auth for Synthetic monitoring creds.
- Fail closed: deny by default when Synthetic monitoring creds cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Synthetic monitoring creds; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Synthetic monitoring creds.
- Keep dependencies patched; pin versions for Synthetic monitoring creds components.

### Verification

- Add automated tests and SAST/DAST coverage for Synthetic monitoring creds paths.
- Run dependency and secret scanning on every change touching Synthetic monitoring creds.
- Perform targeted manual tests (abuse cases) for Synthetic monitoring creds.

### Operations

- Log security-relevant events for Synthetic monitoring creds without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Synthetic monitoring creds.
- Review access and configuration for Synthetic monitoring creds on a regular cadence.

## RUM and client beacons

Sub-topics: Data minimization

### Policy

- Treat RUM and client beacons in RUM and client beacons as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for RUM and client beacons (Observability and debugging security).
- Require security review for material changes affecting RUM and client beacons.

### Design

- Apply least privilege and defense in depth for RUM and client beacons.
- Prefer established patterns and libraries over custom crypto or auth for RUM and client beacons.
- Fail closed: deny by default when RUM and client beacons cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching RUM and client beacons; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RUM and client beacons.
- Keep dependencies patched; pin versions for RUM and client beacons components.

### Verification

- Add automated tests and SAST/DAST coverage for RUM and client beacons paths.
- Run dependency and secret scanning on every change touching RUM and client beacons.
- Perform targeted manual tests (abuse cases) for RUM and client beacons.

### Operations

- Log security-relevant events for RUM and client beacons without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in RUM and client beacons.
- Review access and configuration for RUM and client beacons on a regular cadence.

## Alert routing secrets

Sub-topics: Webhook URLs in alerts

### Policy

- Treat Alert routing secrets in Alert routing secrets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Alert routing secrets (Observability and debugging security).
- Require security review for material changes affecting Alert routing secrets.

### Design

- Apply least privilege and defense in depth for Alert routing secrets.
- Prefer established patterns and libraries over custom crypto or auth for Alert routing secrets.
- Fail closed: deny by default when Alert routing secrets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Alert routing secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Alert routing secrets.
- Keep dependencies patched; pin versions for Alert routing secrets components.

### Verification

- Add automated tests and SAST/DAST coverage for Alert routing secrets paths.
- Run dependency and secret scanning on every change touching Alert routing secrets.
- Perform targeted manual tests (abuse cases) for Alert routing secrets.

### Operations

- Log security-relevant events for Alert routing secrets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Alert routing secrets.
- Review access and configuration for Alert routing secrets on a regular cadence.

