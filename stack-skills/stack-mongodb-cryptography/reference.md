# MongoDB: Cryptography and key management

Stack-specific implementation for **MongoDB** (Database). Normative rules: domain skill `security-cryptography` / `reference.md`.

## JWT and JOSE

**Sub-topics:** alg none, Key confusion, JWK sets, Threat modeling and trust boundaries (JWT and JOSE), Abuse cases and adversarial testing (JWT and JOSE)

### Do (use this in MongoDB)

- Use RS256 or ES256; validate `aud`, `iss`, `exp`; store keys in KMS.
- Rotate signing keys with overlap.

### Don't

- Do not accept `alg: none` or HS256 with public client secrets.
- Do not put PII in JWT payloads.

### Verify

- Use jwt lint tools in CI for sample tokens.

