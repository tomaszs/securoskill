# Actix Web (Rust): Real-time, WebSocket, and messaging

Stack-specific implementation for **Actix Web (Rust)** (Rust). Normative rules: domain skill `security-realtime-messaging` / `reference.md`.

## WebSocket authentication

**Sub-topics:** Cookie vs token, Reconnect, Threat modeling and trust boundaries (WebSocket authentication), Abuse cases and adversarial testing (WebSocket authentication), Logging, audit, and detection (WebSocket authentication)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for ws_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Room and channel authorization

**Sub-topics:** Join tokens, Threat modeling and trust boundaries (Room and channel authorization), Abuse cases and adversarial testing (Room and channel authorization), Logging, audit, and detection (Room and channel authorization), Access control and least privilege (Room and channel authorization)

### Do (use this in Actix Web (Rust))

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Message integrity

**Sub-topics:** Signing, Ordering, Threat modeling and trust boundaries (Message integrity), Abuse cases and adversarial testing (Message integrity), Logging, audit, and detection (Message integrity)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for message_integrity controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Presence leaks

**Sub-topics:** Online status, Typing, Threat modeling and trust boundaries (Presence leaks), Abuse cases and adversarial testing (Presence leaks), Logging, audit, and detection (Presence leaks)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for presence_leak controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## MQTT and IoT protocols

**Sub-topics:** ACLs, TLS, Threat modeling and trust boundaries (MQTT and IoT protocols), Abuse cases and adversarial testing (MQTT and IoT protocols), Logging, audit, and detection (MQTT and IoT protocols)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for mqtt controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Kafka security

**Sub-topics:** ACLs, SASL, Threat modeling and trust boundaries (Kafka security), Abuse cases and adversarial testing (Kafka security), Logging, audit, and detection (Kafka security)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for kafka controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Redis pub/sub

**Sub-topics:** Unauthenticated instances, Threat modeling and trust boundaries (Redis pub/sub), Abuse cases and adversarial testing (Redis pub/sub), Logging, audit, and detection (Redis pub/sub), Access control and least privilege (Redis pub/sub)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for redis_pubsub controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Server-sent events

**Sub-topics:** CSRF, Caching, Threat modeling and trust boundaries (Server-sent events), Abuse cases and adversarial testing (Server-sent events), Logging, audit, and detection (Server-sent events)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for sse controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Collaborative editing

**Sub-topics:** OT/CRDT authz, Threat modeling and trust boundaries (Collaborative editing), Abuse cases and adversarial testing (Collaborative editing), Logging, audit, and detection (Collaborative editing), Access control and least privilege (Collaborative editing)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for collab controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## WebRTC

**Sub-topics:** ICE, TURN credentials, Threat modeling and trust boundaries (WebRTC), Abuse cases and adversarial testing (WebRTC), Logging, audit, and detection (WebRTC)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for webrtc controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Fan-out abuse

**Sub-topics:** Large rooms, Bots, Threat modeling and trust boundaries (Fan-out abuse), Abuse cases and adversarial testing (Fan-out abuse), Logging, audit, and detection (Fan-out abuse)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for fanout controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Message retention

**Sub-topics:** Legal hold, E2EE, Threat modeling and trust boundaries (Message retention), Abuse cases and adversarial testing (Message retention), Logging, audit, and detection (Message retention)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-realtime-messaging` requirements using actix supported APIs only.
- Use the official actix security documentation for retention controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

