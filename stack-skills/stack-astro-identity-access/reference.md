# Astro: Identity, authentication, and access control

Stack-specific implementation for **Astro** (Web UI). Normative rules: domain skill `security-identity-access` / `reference.md`.

## Privilege escalation

**Sub-topics:** Horizontal, Vertical, IDOR, Threat modeling and trust boundaries (Privilege escalation), Abuse cases and adversarial testing (Privilege escalation)

### Do (use this in Astro)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run eslint on changes affecting `Privilege escalation`.

