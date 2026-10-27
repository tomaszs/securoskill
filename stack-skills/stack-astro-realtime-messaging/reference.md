# Astro: Real-time, WebSocket, and messaging

Stack-specific implementation for **Astro** (Web UI). Normative rules: domain skill `security-realtime-messaging` / `reference.md`.

## Room and channel authorization

**Sub-topics:** Join tokens, Threat modeling and trust boundaries (Room and channel authorization), Abuse cases and adversarial testing (Room and channel authorization), Logging, audit, and detection (Room and channel authorization), Access control and least privilege (Room and channel authorization)

### Do (use this in Astro)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run eslint on changes affecting `Room and channel authorization`.

