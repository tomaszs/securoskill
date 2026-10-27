# Google Cloud: Business logic and abuse prevention

Stack-specific implementation for **Google Cloud** (Cloud). Normative rules: domain skill `security-business-logic-abuse` / `reference.md`.

## Insecure direct object references

**Sub-topics:** UUID guessing, IDOR in APIs, Threat modeling and trust boundaries (Insecure direct object references), Abuse cases and adversarial testing (Insecure direct object references), Logging, audit, and detection (Insecure direct object references)

### Do (use this in Google Cloud)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Mass assignment

**Sub-topics:** Hidden fields, DTO allowlists, Threat modeling and trust boundaries (Mass assignment), Abuse cases and adversarial testing (Mass assignment), Logging, audit, and detection (Mass assignment)

### Do (use this in Google Cloud)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

