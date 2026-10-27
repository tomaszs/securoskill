# Rules reference: Real-time, WebSocket, and messaging

Chat, pub/sub, and live updates.

## WebSocket authentication

Sub-topics: Cookie vs token, Reconnect

### Policy

- Treat WebSocket authentication in WebSocket authentication as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for WebSocket authentication (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting WebSocket authentication.

### Design

- Apply least privilege and defense in depth for WebSocket authentication.
- Prefer established patterns and libraries over custom crypto or auth for WebSocket authentication.
- Fail closed: deny by default when WebSocket authentication cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching WebSocket authentication; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebSocket authentication.
- Keep dependencies patched; pin versions for WebSocket authentication components.

### Verification

- Add automated tests and SAST/DAST coverage for WebSocket authentication paths.
- Run dependency and secret scanning on every change touching WebSocket authentication.
- Perform targeted manual tests (abuse cases) for WebSocket authentication.

### Operations

- Log security-relevant events for WebSocket authentication without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in WebSocket authentication.
- Review access and configuration for WebSocket authentication on a regular cadence.

## Room and channel authorization

Sub-topics: Join tokens

### Policy

- Treat Room and channel authorization in Room and channel authorization as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Room and channel authorization (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Room and channel authorization.

### Design

- Apply least privilege and defense in depth for Room and channel authorization.
- Prefer established patterns and libraries over custom crypto or auth for Room and channel authorization.
- Fail closed: deny by default when Room and channel authorization cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Room and channel authorization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Room and channel authorization.
- Keep dependencies patched; pin versions for Room and channel authorization components.

### Verification

- Add automated tests and SAST/DAST coverage for Room and channel authorization paths.
- Run dependency and secret scanning on every change touching Room and channel authorization.
- Perform targeted manual tests (abuse cases) for Room and channel authorization.

### Operations

- Log security-relevant events for Room and channel authorization without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Room and channel authorization.
- Review access and configuration for Room and channel authorization on a regular cadence.

## Message integrity

Sub-topics: Signing, Ordering

### Policy

- Treat Message integrity in Message integrity as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Message integrity (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Message integrity.

### Design

- Apply least privilege and defense in depth for Message integrity.
- Prefer established patterns and libraries over custom crypto or auth for Message integrity.
- Fail closed: deny by default when Message integrity cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Message integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Message integrity.
- Keep dependencies patched; pin versions for Message integrity components.

### Verification

- Add automated tests and SAST/DAST coverage for Message integrity paths.
- Run dependency and secret scanning on every change touching Message integrity.
- Perform targeted manual tests (abuse cases) for Message integrity.

### Operations

- Log security-relevant events for Message integrity without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Message integrity.
- Review access and configuration for Message integrity on a regular cadence.

## Presence leaks

Sub-topics: Online status, Typing

### Policy

- Treat Presence leaks in Presence leaks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Presence leaks (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Presence leaks.

### Design

- Apply least privilege and defense in depth for Presence leaks.
- Prefer established patterns and libraries over custom crypto or auth for Presence leaks.
- Fail closed: deny by default when Presence leaks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Presence leaks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Presence leaks.
- Keep dependencies patched; pin versions for Presence leaks components.

### Verification

- Add automated tests and SAST/DAST coverage for Presence leaks paths.
- Run dependency and secret scanning on every change touching Presence leaks.
- Perform targeted manual tests (abuse cases) for Presence leaks.

### Operations

- Log security-relevant events for Presence leaks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Presence leaks.
- Review access and configuration for Presence leaks on a regular cadence.

## MQTT and IoT protocols

Sub-topics: ACLs, TLS

### Policy

- Treat MQTT and IoT protocols in MQTT and IoT protocols as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for MQTT and IoT protocols (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting MQTT and IoT protocols.

### Design

- Apply least privilege and defense in depth for MQTT and IoT protocols.
- Prefer established patterns and libraries over custom crypto or auth for MQTT and IoT protocols.
- Fail closed: deny by default when MQTT and IoT protocols cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching MQTT and IoT protocols; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to MQTT and IoT protocols.
- Keep dependencies patched; pin versions for MQTT and IoT protocols components.

### Verification

- Add automated tests and SAST/DAST coverage for MQTT and IoT protocols paths.
- Run dependency and secret scanning on every change touching MQTT and IoT protocols.
- Perform targeted manual tests (abuse cases) for MQTT and IoT protocols.

### Operations

- Log security-relevant events for MQTT and IoT protocols without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in MQTT and IoT protocols.
- Review access and configuration for MQTT and IoT protocols on a regular cadence.

## Kafka security

Sub-topics: ACLs, SASL

### Policy

- Treat Kafka security in Kafka security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Kafka security (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Kafka security.

### Design

- Apply least privilege and defense in depth for Kafka security.
- Prefer established patterns and libraries over custom crypto or auth for Kafka security.
- Fail closed: deny by default when Kafka security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Kafka security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Kafka security.
- Keep dependencies patched; pin versions for Kafka security components.

### Verification

- Add automated tests and SAST/DAST coverage for Kafka security paths.
- Run dependency and secret scanning on every change touching Kafka security.
- Perform targeted manual tests (abuse cases) for Kafka security.

### Operations

- Log security-relevant events for Kafka security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Kafka security.
- Review access and configuration for Kafka security on a regular cadence.

## Redis pub/sub

Sub-topics: Unauthenticated instances

### Policy

- Treat Redis pub/sub in Redis pub/sub as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Redis pub/sub (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Redis pub/sub.

### Design

- Apply least privilege and defense in depth for Redis pub/sub.
- Prefer established patterns and libraries over custom crypto or auth for Redis pub/sub.
- Fail closed: deny by default when Redis pub/sub cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Redis pub/sub; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Redis pub/sub.
- Keep dependencies patched; pin versions for Redis pub/sub components.

### Verification

- Add automated tests and SAST/DAST coverage for Redis pub/sub paths.
- Run dependency and secret scanning on every change touching Redis pub/sub.
- Perform targeted manual tests (abuse cases) for Redis pub/sub.

### Operations

- Log security-relevant events for Redis pub/sub without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Redis pub/sub.
- Review access and configuration for Redis pub/sub on a regular cadence.

## Server-sent events

Sub-topics: CSRF, Caching

### Policy

- Treat Server-sent events in Server-sent events as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Server-sent events (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Server-sent events.

### Design

- Apply least privilege and defense in depth for Server-sent events.
- Prefer established patterns and libraries over custom crypto or auth for Server-sent events.
- Fail closed: deny by default when Server-sent events cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Server-sent events; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server-sent events.
- Keep dependencies patched; pin versions for Server-sent events components.

### Verification

- Add automated tests and SAST/DAST coverage for Server-sent events paths.
- Run dependency and secret scanning on every change touching Server-sent events.
- Perform targeted manual tests (abuse cases) for Server-sent events.

### Operations

- Log security-relevant events for Server-sent events without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Server-sent events.
- Review access and configuration for Server-sent events on a regular cadence.

## Collaborative editing

Sub-topics: OT/CRDT authz

### Policy

- Treat Collaborative editing in Collaborative editing as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Collaborative editing (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Collaborative editing.

### Design

- Apply least privilege and defense in depth for Collaborative editing.
- Prefer established patterns and libraries over custom crypto or auth for Collaborative editing.
- Fail closed: deny by default when Collaborative editing cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Collaborative editing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Collaborative editing.
- Keep dependencies patched; pin versions for Collaborative editing components.

### Verification

- Add automated tests and SAST/DAST coverage for Collaborative editing paths.
- Run dependency and secret scanning on every change touching Collaborative editing.
- Perform targeted manual tests (abuse cases) for Collaborative editing.

### Operations

- Log security-relevant events for Collaborative editing without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Collaborative editing.
- Review access and configuration for Collaborative editing on a regular cadence.

## WebRTC

Sub-topics: ICE, TURN credentials

### Policy

- Treat WebRTC in WebRTC as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for WebRTC (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting WebRTC.

### Design

- Apply least privilege and defense in depth for WebRTC.
- Prefer established patterns and libraries over custom crypto or auth for WebRTC.
- Fail closed: deny by default when WebRTC cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching WebRTC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebRTC.
- Keep dependencies patched; pin versions for WebRTC components.

### Verification

- Add automated tests and SAST/DAST coverage for WebRTC paths.
- Run dependency and secret scanning on every change touching WebRTC.
- Perform targeted manual tests (abuse cases) for WebRTC.

### Operations

- Log security-relevant events for WebRTC without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in WebRTC.
- Review access and configuration for WebRTC on a regular cadence.

## Fan-out abuse

Sub-topics: Large rooms, Bots

### Policy

- Treat Fan-out abuse in Fan-out abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Fan-out abuse (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Fan-out abuse.

### Design

- Apply least privilege and defense in depth for Fan-out abuse.
- Prefer established patterns and libraries over custom crypto or auth for Fan-out abuse.
- Fail closed: deny by default when Fan-out abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Fan-out abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Fan-out abuse.
- Keep dependencies patched; pin versions for Fan-out abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Fan-out abuse paths.
- Run dependency and secret scanning on every change touching Fan-out abuse.
- Perform targeted manual tests (abuse cases) for Fan-out abuse.

### Operations

- Log security-relevant events for Fan-out abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Fan-out abuse.
- Review access and configuration for Fan-out abuse on a regular cadence.

## Message retention

Sub-topics: Legal hold, E2EE

### Policy

- Treat Message retention in Message retention as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Message retention (Real-time, WebSocket, and messaging).
- Require security review for material changes affecting Message retention.

### Design

- Apply least privilege and defense in depth for Message retention.
- Prefer established patterns and libraries over custom crypto or auth for Message retention.
- Fail closed: deny by default when Message retention cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Message retention; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Message retention.
- Keep dependencies patched; pin versions for Message retention components.

### Verification

- Add automated tests and SAST/DAST coverage for Message retention paths.
- Run dependency and secret scanning on every change touching Message retention.
- Perform targeted manual tests (abuse cases) for Message retention.

### Operations

- Log security-relevant events for Message retention without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Message retention.
- Review access and configuration for Message retention on a regular cadence.

