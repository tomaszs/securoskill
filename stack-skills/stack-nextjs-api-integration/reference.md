# Next.js: API and integration security

Stack-specific implementation for **Next.js** (Web UI). Normative rules: domain skill `security-api-integration` / `reference.md`.

## REST API design security

**Sub-topics:** Versioning, Idempotency, Mass assignment, Threat modeling and trust boundaries (REST API design security), Abuse cases and adversarial testing (REST API design security)

### Do (use this in Next.js)

- Map `REST API design security` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `REST API design security` before merge.

### Don't

- Do not ship `REST API design security` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `REST API design security`.

### Verify

- Peer review `REST API design security` against domain skill `security-api-integration`.

## GraphQL security

**Sub-topics:** Depth limits, Introspection, Batching abuse, Threat modeling and trust boundaries (GraphQL security), Abuse cases and adversarial testing (GraphQL security)

### Do (use this in Next.js)

- Enforce max query depth and complexity limits.
- Disable introspection in production unless required for trusted tools.
- Authorize each resolver field (not only top-level entry).

### Don't

- Do not expose admin-only fields on the same schema without field-level auth.
- Do not allow batch aliases to bypass rate limits.

### Verify

- Load-test GraphQL with deeply nested queries; expect rejection.

## gRPC and protobuf

**Sub-topics:** mTLS, Message size, Auth metadata, Threat modeling and trust boundaries (gRPC and protobuf), Abuse cases and adversarial testing (gRPC and protobuf)

### Do (use this in Next.js)

- Map `gRPC and protobuf` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `gRPC and protobuf` before merge.

### Don't

- Do not ship `gRPC and protobuf` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `gRPC and protobuf`.

### Verify

- Peer review `gRPC and protobuf` against domain skill `security-api-integration`.

## Webhooks outbound and inbound

**Sub-topics:** Signature verification, Replay, SSRF from callbacks, Threat modeling and trust boundaries (Webhooks outbound and inbound), Abuse cases and adversarial testing (Webhooks outbound and inbound)

### Do (use this in Next.js)

- Map `Webhooks outbound and inbound` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `Webhooks outbound and inbound` before merge.

### Don't

- Do not ship `Webhooks outbound and inbound` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `Webhooks outbound and inbound`.

### Verify

- Peer review `Webhooks outbound and inbound` against domain skill `security-api-integration`.

## OAuth2/OIDC for APIs

**Sub-topics:** Scopes, Client credentials, Token exchange, Threat modeling and trust boundaries (OAuth2/OIDC for APIs), Abuse cases and adversarial testing (OAuth2/OIDC for APIs)

### Do (use this in Next.js)

- Map `OAuth2/OIDC for APIs` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `OAuth2/OIDC for APIs` before merge.

### Don't

- Do not ship `OAuth2/OIDC for APIs` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `OAuth2/OIDC for APIs`.

### Verify

- Peer review `OAuth2/OIDC for APIs` against domain skill `security-api-integration`.

## API keys and HMAC

**Sub-topics:** Rotation, Per-tenant keys, Constant-time compare, Threat modeling and trust boundaries (API keys and HMAC), Abuse cases and adversarial testing (API keys and HMAC)

### Do (use this in Next.js)

- Map `API keys and HMAC` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `API keys and HMAC` before merge.

### Don't

- Do not ship `API keys and HMAC` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `API keys and HMAC`.

### Verify

- Peer review `API keys and HMAC` against domain skill `security-api-integration`.

## Pagination and filtering abuse

**Sub-topics:** Large offsets, Filter injection, Threat modeling and trust boundaries (Pagination and filtering abuse), Abuse cases and adversarial testing (Pagination and filtering abuse), Logging, audit, and detection (Pagination and filtering abuse)

### Do (use this in Next.js)

- Map `Pagination and filtering abuse` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `Pagination and filtering abuse` before merge.

### Don't

- Do not ship `Pagination and filtering abuse` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `Pagination and filtering abuse`.

### Verify

- Peer review `Pagination and filtering abuse` against domain skill `security-api-integration`.

## CORS for APIs

**Sub-topics:** Credentials, Wildcard origins, Threat modeling and trust boundaries (CORS for APIs), Abuse cases and adversarial testing (CORS for APIs), Logging, audit, and detection (CORS for APIs)

### Do (use this in Next.js)

- Map `CORS for APIs` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `CORS for APIs` before merge.

### Don't

- Do not ship `CORS for APIs` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `CORS for APIs`.

### Verify

- Peer review `CORS for APIs` against domain skill `security-api-integration`.

## OpenAPI and documentation leakage

**Sub-topics:** Hidden admin paths, Example secrets, Threat modeling and trust boundaries (OpenAPI and documentation leakage), Abuse cases and adversarial testing (OpenAPI and documentation leakage), Logging, audit, and detection (OpenAPI and documentation leakage)

### Do (use this in Next.js)

- Map `OpenAPI and documentation leakage` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `OpenAPI and documentation leakage` before merge.

### Don't

- Do not ship `OpenAPI and documentation leakage` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `OpenAPI and documentation leakage`.

### Verify

- Peer review `OpenAPI and documentation leakage` against domain skill `security-api-integration`.

## Backend-for-frontend patterns

**Sub-topics:** Token handling, Aggregation leaks, Threat modeling and trust boundaries (Backend-for-frontend patterns), Abuse cases and adversarial testing (Backend-for-frontend patterns), Logging, audit, and detection (Backend-for-frontend patterns)

### Do (use this in Next.js)

- Map `Backend-for-frontend patterns` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `Backend-for-frontend patterns` before merge.

### Don't

- Do not ship `Backend-for-frontend patterns` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `Backend-for-frontend patterns`.

### Verify

- Peer review `Backend-for-frontend patterns` against domain skill `security-api-integration`.

## Legacy SOAP/XML APIs

**Sub-topics:** XXE, WS-Security misconfig, Threat modeling and trust boundaries (Legacy SOAP/XML APIs), Abuse cases and adversarial testing (Legacy SOAP/XML APIs), Logging, audit, and detection (Legacy SOAP/XML APIs)

### Do (use this in Next.js)

- Map `Legacy SOAP/XML APIs` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `Legacy SOAP/XML APIs` before merge.

### Don't

- Do not ship `Legacy SOAP/XML APIs` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `Legacy SOAP/XML APIs`.

### Verify

- Peer review `Legacy SOAP/XML APIs` against domain skill `security-api-integration`.

## Event buses and streaming

**Sub-topics:** Schema evolution, Poison messages, Threat modeling and trust boundaries (Event buses and streaming), Abuse cases and adversarial testing (Event buses and streaming), Logging, audit, and detection (Event buses and streaming)

### Do (use this in Next.js)

- Map `Event buses and streaming` controls to Next.js APIs documented for `security-api-integration`.
- Add an abuse-case test or check for `Event buses and streaming` before merge.

### Don't

- Do not ship `Event buses and streaming` work in Next.js with only happy-path tests.
- Do not disable Next.js security defaults to unblock `Event buses and streaming`.

### Verify

- Peer review `Event buses and streaming` against domain skill `security-api-integration`.

