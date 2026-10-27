# MySQL / MariaDB: Multi-tenancy and SaaS isolation

Stack-specific implementation for **MySQL / MariaDB** (Database). Normative rules: domain skill `security-multi-tenancy-saas` / `reference.md`.

## Tenant-scoped authorization

**Sub-topics:** Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Do (use this in MySQL / MariaDB)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

