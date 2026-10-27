# Spring Boot: Network and transport security

Stack-specific implementation for **Spring Boot** (Java). Normative rules: domain skill `security-network-transport` / `reference.md`.

## SSRF

**Sub-topics:** Metadata endpoints, URL parsers, Allowlists, Threat modeling and trust boundaries (SSRF), Abuse cases and adversarial testing (SSRF)

### Do (use this in Spring Boot)

- Resolve URLs server-side with allowlisted hosts; block link-local and metadata IPs (169.254.169.254).
- Use a dedicated HTTP client with redirects disabled or limited.

### Don't

- Do not fetch arbitrary user-supplied URLs without SSRF guards.
- Do not trust DNS rebinding to reach internal services.

### Verify

- Unit-test SSRF payloads against your URL fetch helper.
- Run SpotBugs + OWASP dependency-check on changes affecting `SSRF`.

