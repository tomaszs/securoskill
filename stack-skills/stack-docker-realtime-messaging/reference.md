# Docker: Real-time, WebSocket, and messaging

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-realtime-messaging` / `reference.md`.

## WebSocket authentication

**Sub-topics:** Cookie vs token, Reconnect, Threat modeling and trust boundaries (WebSocket authentication), Abuse cases and adversarial testing (WebSocket authentication), Logging, audit, and detection (WebSocket authentication)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Room and channel authorization

**Sub-topics:** Join tokens, Threat modeling and trust boundaries (Room and channel authorization), Abuse cases and adversarial testing (Room and channel authorization), Logging, audit, and detection (Room and channel authorization), Access control and least privilege (Room and channel authorization)

### Do (use this in Docker)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Message integrity

**Sub-topics:** Signing, Ordering, Threat modeling and trust boundaries (Message integrity), Abuse cases and adversarial testing (Message integrity), Logging, audit, and detection (Message integrity)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Presence leaks

**Sub-topics:** Online status, Typing, Threat modeling and trust boundaries (Presence leaks), Abuse cases and adversarial testing (Presence leaks), Logging, audit, and detection (Presence leaks)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## MQTT and IoT protocols

**Sub-topics:** ACLs, TLS, Threat modeling and trust boundaries (MQTT and IoT protocols), Abuse cases and adversarial testing (MQTT and IoT protocols), Logging, audit, and detection (MQTT and IoT protocols)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Kafka security

**Sub-topics:** ACLs, SASL, Threat modeling and trust boundaries (Kafka security), Abuse cases and adversarial testing (Kafka security), Logging, audit, and detection (Kafka security)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Redis pub/sub

**Sub-topics:** Unauthenticated instances, Threat modeling and trust boundaries (Redis pub/sub), Abuse cases and adversarial testing (Redis pub/sub), Logging, audit, and detection (Redis pub/sub), Access control and least privilege (Redis pub/sub)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Server-sent events

**Sub-topics:** CSRF, Caching, Threat modeling and trust boundaries (Server-sent events), Abuse cases and adversarial testing (Server-sent events), Logging, audit, and detection (Server-sent events)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Collaborative editing

**Sub-topics:** OT/CRDT authz, Threat modeling and trust boundaries (Collaborative editing), Abuse cases and adversarial testing (Collaborative editing), Logging, audit, and detection (Collaborative editing), Access control and least privilege (Collaborative editing)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## WebRTC

**Sub-topics:** ICE, TURN credentials, Threat modeling and trust boundaries (WebRTC), Abuse cases and adversarial testing (WebRTC), Logging, audit, and detection (WebRTC)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Fan-out abuse

**Sub-topics:** Large rooms, Bots, Threat modeling and trust boundaries (Fan-out abuse), Abuse cases and adversarial testing (Fan-out abuse), Logging, audit, and detection (Fan-out abuse)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Message retention

**Sub-topics:** Legal hold, E2EE, Threat modeling and trust boundaries (Message retention), Abuse cases and adversarial testing (Message retention), Logging, audit, and detection (Message retention)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

