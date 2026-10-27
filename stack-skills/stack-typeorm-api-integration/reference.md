# TypeORM: API and integration security

Stack-specific implementation for **TypeORM** (ORM / data access). Normative rules: domain skill `security-api-integration` / `reference.md`.

## GraphQL security

**Sub-topics:** Depth limits, Introspection, Batching abuse, Threat modeling and trust boundaries (GraphQL security), Abuse cases and adversarial testing (GraphQL security)

### Do (use this in TypeORM)

- Enforce max query depth and complexity limits.
- Disable introspection in production unless required for trusted tools.
- Authorize each resolver field (not only top-level entry).

### Don't

- Do not expose admin-only fields on the same schema without field-level auth.
- Do not allow batch aliases to bypass rate limits.

### Verify

- Load-test GraphQL with deeply nested queries; expect rejection.

