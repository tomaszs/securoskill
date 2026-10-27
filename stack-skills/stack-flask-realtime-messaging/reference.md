# Flask: Real-time, WebSocket, and messaging

Stack-specific implementation for **Flask** (Python). Normative rules: domain skill `security-realtime-messaging` / `reference.md`.

## WebSocket authentication

**Sub-topics:** Cookie vs token, Reconnect, Threat modeling and trust boundaries (WebSocket authentication), Abuse cases and adversarial testing (WebSocket authentication), Logging, audit, and detection (WebSocket authentication)

### Do (use this in Flask)

- Map `WebSocket authentication` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `WebSocket authentication` before merge.

### Don't

- Do not ship `WebSocket authentication` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `WebSocket authentication`.

### Verify

- Peer review `WebSocket authentication` against domain skill `security-realtime-messaging`.

## Room and channel authorization

**Sub-topics:** Join tokens, Threat modeling and trust boundaries (Room and channel authorization), Abuse cases and adversarial testing (Room and channel authorization), Logging, audit, and detection (Room and channel authorization), Access control and least privilege (Room and channel authorization)

### Do (use this in Flask)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run bandit on changes affecting `Room and channel authorization`.

## Message integrity

**Sub-topics:** Signing, Ordering, Threat modeling and trust boundaries (Message integrity), Abuse cases and adversarial testing (Message integrity), Logging, audit, and detection (Message integrity)

### Do (use this in Flask)

- Map `Message integrity` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Message integrity` before merge.

### Don't

- Do not ship `Message integrity` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Message integrity`.

### Verify

- Peer review `Message integrity` against domain skill `security-realtime-messaging`.

## Presence leaks

**Sub-topics:** Online status, Typing, Threat modeling and trust boundaries (Presence leaks), Abuse cases and adversarial testing (Presence leaks), Logging, audit, and detection (Presence leaks)

### Do (use this in Flask)

- Map `Presence leaks` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Presence leaks` before merge.

### Don't

- Do not ship `Presence leaks` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Presence leaks`.

### Verify

- Peer review `Presence leaks` against domain skill `security-realtime-messaging`.

## MQTT and IoT protocols

**Sub-topics:** ACLs, TLS, Threat modeling and trust boundaries (MQTT and IoT protocols), Abuse cases and adversarial testing (MQTT and IoT protocols), Logging, audit, and detection (MQTT and IoT protocols)

### Do (use this in Flask)

- Map `MQTT and IoT protocols` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `MQTT and IoT protocols` before merge.

### Don't

- Do not ship `MQTT and IoT protocols` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `MQTT and IoT protocols`.

### Verify

- Peer review `MQTT and IoT protocols` against domain skill `security-realtime-messaging`.

## Kafka security

**Sub-topics:** ACLs, SASL, Threat modeling and trust boundaries (Kafka security), Abuse cases and adversarial testing (Kafka security), Logging, audit, and detection (Kafka security)

### Do (use this in Flask)

- Map `Kafka security` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Kafka security` before merge.

### Don't

- Do not ship `Kafka security` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Kafka security`.

### Verify

- Peer review `Kafka security` against domain skill `security-realtime-messaging`.

## Redis pub/sub

**Sub-topics:** Unauthenticated instances, Threat modeling and trust boundaries (Redis pub/sub), Abuse cases and adversarial testing (Redis pub/sub), Logging, audit, and detection (Redis pub/sub), Access control and least privilege (Redis pub/sub)

### Do (use this in Flask)

- Map `Redis pub/sub` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Redis pub/sub` before merge.

### Don't

- Do not ship `Redis pub/sub` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Redis pub/sub`.

### Verify

- Peer review `Redis pub/sub` against domain skill `security-realtime-messaging`.

## Server-sent events

**Sub-topics:** CSRF, Caching, Threat modeling and trust boundaries (Server-sent events), Abuse cases and adversarial testing (Server-sent events), Logging, audit, and detection (Server-sent events)

### Do (use this in Flask)

- Map `Server-sent events` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Server-sent events` before merge.

### Don't

- Do not ship `Server-sent events` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Server-sent events`.

### Verify

- Peer review `Server-sent events` against domain skill `security-realtime-messaging`.

## Collaborative editing

**Sub-topics:** OT/CRDT authz, Threat modeling and trust boundaries (Collaborative editing), Abuse cases and adversarial testing (Collaborative editing), Logging, audit, and detection (Collaborative editing), Access control and least privilege (Collaborative editing)

### Do (use this in Flask)

- Map `Collaborative editing` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Collaborative editing` before merge.

### Don't

- Do not ship `Collaborative editing` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Collaborative editing`.

### Verify

- Peer review `Collaborative editing` against domain skill `security-realtime-messaging`.

## WebRTC

**Sub-topics:** ICE, TURN credentials, Threat modeling and trust boundaries (WebRTC), Abuse cases and adversarial testing (WebRTC), Logging, audit, and detection (WebRTC)

### Do (use this in Flask)

- Map `WebRTC` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `WebRTC` before merge.

### Don't

- Do not ship `WebRTC` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `WebRTC`.

### Verify

- Peer review `WebRTC` against domain skill `security-realtime-messaging`.

## Fan-out abuse

**Sub-topics:** Large rooms, Bots, Threat modeling and trust boundaries (Fan-out abuse), Abuse cases and adversarial testing (Fan-out abuse), Logging, audit, and detection (Fan-out abuse)

### Do (use this in Flask)

- Map `Fan-out abuse` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Fan-out abuse` before merge.

### Don't

- Do not ship `Fan-out abuse` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Fan-out abuse`.

### Verify

- Peer review `Fan-out abuse` against domain skill `security-realtime-messaging`.

## Message retention

**Sub-topics:** Legal hold, E2EE, Threat modeling and trust boundaries (Message retention), Abuse cases and adversarial testing (Message retention), Logging, audit, and detection (Message retention)

### Do (use this in Flask)

- Map `Message retention` controls to Flask APIs documented for `security-realtime-messaging`.
- Add an abuse-case test or check for `Message retention` before merge.

### Don't

- Do not ship `Message retention` work in Flask with only happy-path tests.
- Do not disable Flask security defaults to unblock `Message retention`.

### Verify

- Peer review `Message retention` against domain skill `security-realtime-messaging`.

