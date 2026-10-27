# React Native: API and integration security

Stack-specific implementation for **React Native** (Mobile). Normative rules: domain skill `security-api-integration` / `reference.md`.

## REST API design security

**Sub-topics:** Versioning, Idempotency, Mass assignment, Threat modeling and trust boundaries (REST API design security), Abuse cases and adversarial testing (REST API design security)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## GraphQL security

**Sub-topics:** Depth limits, Introspection, Batching abuse, Threat modeling and trust boundaries (GraphQL security), Abuse cases and adversarial testing (GraphQL security)

### Do (use this in React Native)

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

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## Webhooks outbound and inbound

**Sub-topics:** Signature verification, Replay, SSRF from callbacks, Threat modeling and trust boundaries (Webhooks outbound and inbound), Abuse cases and adversarial testing (Webhooks outbound and inbound)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## OAuth2/OIDC for APIs

**Sub-topics:** Scopes, Client credentials, Token exchange, Threat modeling and trust boundaries (OAuth2/OIDC for APIs), Abuse cases and adversarial testing (OAuth2/OIDC for APIs)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## API keys and HMAC

**Sub-topics:** Rotation, Per-tenant keys, Constant-time compare, Threat modeling and trust boundaries (API keys and HMAC), Abuse cases and adversarial testing (API keys and HMAC)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## Pagination and filtering abuse

**Sub-topics:** Large offsets, Filter injection, Threat modeling and trust boundaries (Pagination and filtering abuse), Abuse cases and adversarial testing (Pagination and filtering abuse), Logging, audit, and detection (Pagination and filtering abuse)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## CORS for APIs

**Sub-topics:** Credentials, Wildcard origins, Threat modeling and trust boundaries (CORS for APIs), Abuse cases and adversarial testing (CORS for APIs), Logging, audit, and detection (CORS for APIs)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## OpenAPI and documentation leakage

**Sub-topics:** Hidden admin paths, Example secrets, Threat modeling and trust boundaries (OpenAPI and documentation leakage), Abuse cases and adversarial testing (OpenAPI and documentation leakage), Logging, audit, and detection (OpenAPI and documentation leakage)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## Backend-for-frontend patterns

**Sub-topics:** Token handling, Aggregation leaks, Threat modeling and trust boundaries (Backend-for-frontend patterns), Abuse cases and adversarial testing (Backend-for-frontend patterns), Logging, audit, and detection (Backend-for-frontend patterns)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## Legacy SOAP/XML APIs

**Sub-topics:** XXE, WS-Security misconfig, Threat modeling and trust boundaries (Legacy SOAP/XML APIs), Abuse cases and adversarial testing (Legacy SOAP/XML APIs), Logging, audit, and detection (Legacy SOAP/XML APIs)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

## Event buses and streaming

**Sub-topics:** Schema evolution, Poison messages, Threat modeling and trust boundaries (Event buses and streaming), Abuse cases and adversarial testing (Event buses and streaming), Logging, audit, and detection (Event buses and streaming)

### Do (use this in React Native)

- React Native is not the primary enforcement point for `api-integration`; load stack skill `security-api-integration` when you touch that layer.
- Keep React Native configuration aligned with requirements from `security-api-integration` (domain reference.md).

### Don't

- Do not duplicate `api-integration` controls only in React Native config while leaving security-api-integration misconfigured.
- Do not assume React Native defaults satisfy `security-api-integration` without verification.

### Verify

- Integration test the full path: React Native plus the system covered by `security-api-integration`.

