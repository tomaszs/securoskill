# Google Cloud: Real-time, WebSocket, and messaging

Stack-specific implementation for **Google Cloud** (Cloud). Normative rules: domain skill `security-realtime-messaging` / `reference.md`.

## WebSocket authentication

**Sub-topics:** Cookie vs token, Reconnect, Threat modeling and trust boundaries (WebSocket authentication), Abuse cases and adversarial testing (WebSocket authentication), Logging, audit, and detection (WebSocket authentication)

### Platform rules (summary)

- Validate and canonicalize all inputs touching WebSocket authentication; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebSocket authentication.
- Keep dependencies patched; pin versions for WebSocket authentication components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for WebSocket authentication before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for WebSocket authentication paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Room and channel authorization

**Sub-topics:** Join tokens, Threat modeling and trust boundaries (Room and channel authorization), Abuse cases and adversarial testing (Room and channel authorization), Logging, audit, and detection (Room and channel authorization), Access control and least privilege (Room and channel authorization)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Room and channel authorization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Room and channel authorization.
- Keep dependencies patched; pin versions for Room and channel authorization components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Room and channel authorization before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Room and channel authorization paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Message integrity

**Sub-topics:** Signing, Ordering, Threat modeling and trust boundaries (Message integrity), Abuse cases and adversarial testing (Message integrity), Logging, audit, and detection (Message integrity)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Message integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Message integrity.
- Keep dependencies patched; pin versions for Message integrity components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Message integrity before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Message integrity paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Presence leaks

**Sub-topics:** Online status, Typing, Threat modeling and trust boundaries (Presence leaks), Abuse cases and adversarial testing (Presence leaks), Logging, audit, and detection (Presence leaks)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Presence leaks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Presence leaks.
- Keep dependencies patched; pin versions for Presence leaks components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Presence leaks before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Presence leaks paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## MQTT and IoT protocols

**Sub-topics:** ACLs, TLS, Threat modeling and trust boundaries (MQTT and IoT protocols), Abuse cases and adversarial testing (MQTT and IoT protocols), Logging, audit, and detection (MQTT and IoT protocols)

### Platform rules (summary)

- Validate and canonicalize all inputs touching MQTT and IoT protocols; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MQTT and IoT protocols.
- Keep dependencies patched; pin versions for MQTT and IoT protocols components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for MQTT and IoT protocols before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for MQTT and IoT protocols paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Kafka security

**Sub-topics:** ACLs, SASL, Threat modeling and trust boundaries (Kafka security), Abuse cases and adversarial testing (Kafka security), Logging, audit, and detection (Kafka security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Kafka security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Kafka security.
- Keep dependencies patched; pin versions for Kafka security components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Kafka security before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Kafka security paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Redis pub/sub

**Sub-topics:** Unauthenticated instances, Threat modeling and trust boundaries (Redis pub/sub), Abuse cases and adversarial testing (Redis pub/sub), Logging, audit, and detection (Redis pub/sub), Access control and least privilege (Redis pub/sub)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Redis pub/sub; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Redis pub/sub.
- Keep dependencies patched; pin versions for Redis pub/sub components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Redis pub/sub before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Redis pub/sub paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Server-sent events

**Sub-topics:** CSRF, Caching, Threat modeling and trust boundaries (Server-sent events), Abuse cases and adversarial testing (Server-sent events), Logging, audit, and detection (Server-sent events)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Server-sent events; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server-sent events.
- Keep dependencies patched; pin versions for Server-sent events components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Server-sent events before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Server-sent events paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Collaborative editing

**Sub-topics:** OT/CRDT authz, Threat modeling and trust boundaries (Collaborative editing), Abuse cases and adversarial testing (Collaborative editing), Logging, audit, and detection (Collaborative editing), Access control and least privilege (Collaborative editing)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Collaborative editing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Collaborative editing.
- Keep dependencies patched; pin versions for Collaborative editing components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Collaborative editing before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Collaborative editing paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## WebRTC

**Sub-topics:** ICE, TURN credentials, Threat modeling and trust boundaries (WebRTC), Abuse cases and adversarial testing (WebRTC), Logging, audit, and detection (WebRTC)

### Platform rules (summary)

- Validate and canonicalize all inputs touching WebRTC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebRTC.
- Keep dependencies patched; pin versions for WebRTC components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for WebRTC before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for WebRTC paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Fan-out abuse

**Sub-topics:** Large rooms, Bots, Threat modeling and trust boundaries (Fan-out abuse), Abuse cases and adversarial testing (Fan-out abuse), Logging, audit, and detection (Fan-out abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Fan-out abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Fan-out abuse.
- Keep dependencies patched; pin versions for Fan-out abuse components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Fan-out abuse before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Fan-out abuse paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Message retention

**Sub-topics:** Legal hold, E2EE, Threat modeling and trust boundaries (Message retention), Abuse cases and adversarial testing (Message retention), Logging, audit, and detection (Message retention)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Message retention; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Message retention.
- Keep dependencies patched; pin versions for Message retention components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-realtime-messaging` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Message retention before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Message retention paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

