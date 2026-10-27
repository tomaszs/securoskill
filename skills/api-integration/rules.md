# Rules reference: API and integration security

REST, GraphQL, gRPC, webhooks, and partner APIs.

## REST API design security

Sub-topics: Versioning, Idempotency, Mass assignment

### Policy

- Treat REST API design security in REST API design security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for REST API design security (API and integration security).
- Require security review for material changes affecting REST API design security.

### Design

- Apply least privilege and defense in depth for REST API design security.
- Prefer established patterns and libraries over custom crypto or auth for REST API design security.
- Fail closed: deny by default when REST API design security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching REST API design security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to REST API design security.
- Keep dependencies patched; pin versions for REST API design security components.

### Verification

- Add automated tests and SAST/DAST coverage for REST API design security paths.
- Run dependency and secret scanning on every change touching REST API design security.
- Perform targeted manual tests (abuse cases) for REST API design security.

### Operations

- Log security-relevant events for REST API design security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in REST API design security.
- Review access and configuration for REST API design security on a regular cadence.

## GraphQL security

Sub-topics: Depth limits, Introspection, Batching abuse

### Policy

- Treat GraphQL security in GraphQL security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for GraphQL security (API and integration security).
- Require security review for material changes affecting GraphQL security.

### Design

- Apply least privilege and defense in depth for GraphQL security.
- Prefer established patterns and libraries over custom crypto or auth for GraphQL security.
- Fail closed: deny by default when GraphQL security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching GraphQL security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to GraphQL security.
- Keep dependencies patched; pin versions for GraphQL security components.

### Verification

- Add automated tests and SAST/DAST coverage for GraphQL security paths.
- Run dependency and secret scanning on every change touching GraphQL security.
- Perform targeted manual tests (abuse cases) for GraphQL security.

### Operations

- Log security-relevant events for GraphQL security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in GraphQL security.
- Review access and configuration for GraphQL security on a regular cadence.

## gRPC and protobuf

Sub-topics: mTLS, Message size, Auth metadata

### Policy

- Treat gRPC and protobuf in gRPC and protobuf as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for gRPC and protobuf (API and integration security).
- Require security review for material changes affecting gRPC and protobuf.

### Design

- Apply least privilege and defense in depth for gRPC and protobuf.
- Prefer established patterns and libraries over custom crypto or auth for gRPC and protobuf.
- Fail closed: deny by default when gRPC and protobuf cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching gRPC and protobuf; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to gRPC and protobuf.
- Keep dependencies patched; pin versions for gRPC and protobuf components.

### Verification

- Add automated tests and SAST/DAST coverage for gRPC and protobuf paths.
- Run dependency and secret scanning on every change touching gRPC and protobuf.
- Perform targeted manual tests (abuse cases) for gRPC and protobuf.

### Operations

- Log security-relevant events for gRPC and protobuf without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in gRPC and protobuf.
- Review access and configuration for gRPC and protobuf on a regular cadence.

## Webhooks outbound and inbound

Sub-topics: Signature verification, Replay, SSRF from callbacks

### Policy

- Treat Webhooks outbound and inbound in Webhooks outbound and inbound as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Webhooks outbound and inbound (API and integration security).
- Require security review for material changes affecting Webhooks outbound and inbound.

### Design

- Apply least privilege and defense in depth for Webhooks outbound and inbound.
- Prefer established patterns and libraries over custom crypto or auth for Webhooks outbound and inbound.
- Fail closed: deny by default when Webhooks outbound and inbound cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Webhooks outbound and inbound; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Webhooks outbound and inbound.
- Keep dependencies patched; pin versions for Webhooks outbound and inbound components.

### Verification

- Add automated tests and SAST/DAST coverage for Webhooks outbound and inbound paths.
- Run dependency and secret scanning on every change touching Webhooks outbound and inbound.
- Perform targeted manual tests (abuse cases) for Webhooks outbound and inbound.

### Operations

- Log security-relevant events for Webhooks outbound and inbound without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Webhooks outbound and inbound.
- Review access and configuration for Webhooks outbound and inbound on a regular cadence.

## OAuth2/OIDC for APIs

Sub-topics: Scopes, Client credentials, Token exchange

### Policy

- Treat OAuth2/OIDC for APIs in OAuth2/OIDC for APIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for OAuth2/OIDC for APIs (API and integration security).
- Require security review for material changes affecting OAuth2/OIDC for APIs.

### Design

- Apply least privilege and defense in depth for OAuth2/OIDC for APIs.
- Prefer established patterns and libraries over custom crypto or auth for OAuth2/OIDC for APIs.
- Fail closed: deny by default when OAuth2/OIDC for APIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching OAuth2/OIDC for APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OAuth2/OIDC for APIs.
- Keep dependencies patched; pin versions for OAuth2/OIDC for APIs components.

### Verification

- Add automated tests and SAST/DAST coverage for OAuth2/OIDC for APIs paths.
- Run dependency and secret scanning on every change touching OAuth2/OIDC for APIs.
- Perform targeted manual tests (abuse cases) for OAuth2/OIDC for APIs.

### Operations

- Log security-relevant events for OAuth2/OIDC for APIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in OAuth2/OIDC for APIs.
- Review access and configuration for OAuth2/OIDC for APIs on a regular cadence.

## API keys and HMAC

Sub-topics: Rotation, Per-tenant keys, Constant-time compare

### Policy

- Treat API keys and HMAC in API keys and HMAC as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for API keys and HMAC (API and integration security).
- Require security review for material changes affecting API keys and HMAC.

### Design

- Apply least privilege and defense in depth for API keys and HMAC.
- Prefer established patterns and libraries over custom crypto or auth for API keys and HMAC.
- Fail closed: deny by default when API keys and HMAC cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching API keys and HMAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to API keys and HMAC.
- Keep dependencies patched; pin versions for API keys and HMAC components.

### Verification

- Add automated tests and SAST/DAST coverage for API keys and HMAC paths.
- Run dependency and secret scanning on every change touching API keys and HMAC.
- Perform targeted manual tests (abuse cases) for API keys and HMAC.

### Operations

- Log security-relevant events for API keys and HMAC without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in API keys and HMAC.
- Review access and configuration for API keys and HMAC on a regular cadence.

## Pagination and filtering abuse

Sub-topics: Large offsets, Filter injection

### Policy

- Treat Pagination and filtering abuse in Pagination and filtering abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Pagination and filtering abuse (API and integration security).
- Require security review for material changes affecting Pagination and filtering abuse.

### Design

- Apply least privilege and defense in depth for Pagination and filtering abuse.
- Prefer established patterns and libraries over custom crypto or auth for Pagination and filtering abuse.
- Fail closed: deny by default when Pagination and filtering abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Pagination and filtering abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Pagination and filtering abuse.
- Keep dependencies patched; pin versions for Pagination and filtering abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Pagination and filtering abuse paths.
- Run dependency and secret scanning on every change touching Pagination and filtering abuse.
- Perform targeted manual tests (abuse cases) for Pagination and filtering abuse.

### Operations

- Log security-relevant events for Pagination and filtering abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Pagination and filtering abuse.
- Review access and configuration for Pagination and filtering abuse on a regular cadence.

## CORS for APIs

Sub-topics: Credentials, Wildcard origins

### Policy

- Treat CORS for APIs in CORS for APIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CORS for APIs (API and integration security).
- Require security review for material changes affecting CORS for APIs.

### Design

- Apply least privilege and defense in depth for CORS for APIs.
- Prefer established patterns and libraries over custom crypto or auth for CORS for APIs.
- Fail closed: deny by default when CORS for APIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CORS for APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CORS for APIs.
- Keep dependencies patched; pin versions for CORS for APIs components.

### Verification

- Add automated tests and SAST/DAST coverage for CORS for APIs paths.
- Run dependency and secret scanning on every change touching CORS for APIs.
- Perform targeted manual tests (abuse cases) for CORS for APIs.

### Operations

- Log security-relevant events for CORS for APIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CORS for APIs.
- Review access and configuration for CORS for APIs on a regular cadence.

## OpenAPI and documentation leakage

Sub-topics: Hidden admin paths, Example secrets

### Policy

- Treat OpenAPI and documentation leakage in OpenAPI and documentation leakage as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for OpenAPI and documentation leakage (API and integration security).
- Require security review for material changes affecting OpenAPI and documentation leakage.

### Design

- Apply least privilege and defense in depth for OpenAPI and documentation leakage.
- Prefer established patterns and libraries over custom crypto or auth for OpenAPI and documentation leakage.
- Fail closed: deny by default when OpenAPI and documentation leakage cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching OpenAPI and documentation leakage; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OpenAPI and documentation leakage.
- Keep dependencies patched; pin versions for OpenAPI and documentation leakage components.

### Verification

- Add automated tests and SAST/DAST coverage for OpenAPI and documentation leakage paths.
- Run dependency and secret scanning on every change touching OpenAPI and documentation leakage.
- Perform targeted manual tests (abuse cases) for OpenAPI and documentation leakage.

### Operations

- Log security-relevant events for OpenAPI and documentation leakage without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in OpenAPI and documentation leakage.
- Review access and configuration for OpenAPI and documentation leakage on a regular cadence.

## Backend-for-frontend patterns

Sub-topics: Token handling, Aggregation leaks

### Policy

- Treat Backend-for-frontend patterns in Backend-for-frontend patterns as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Backend-for-frontend patterns (API and integration security).
- Require security review for material changes affecting Backend-for-frontend patterns.

### Design

- Apply least privilege and defense in depth for Backend-for-frontend patterns.
- Prefer established patterns and libraries over custom crypto or auth for Backend-for-frontend patterns.
- Fail closed: deny by default when Backend-for-frontend patterns cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Backend-for-frontend patterns; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Backend-for-frontend patterns.
- Keep dependencies patched; pin versions for Backend-for-frontend patterns components.

### Verification

- Add automated tests and SAST/DAST coverage for Backend-for-frontend patterns paths.
- Run dependency and secret scanning on every change touching Backend-for-frontend patterns.
- Perform targeted manual tests (abuse cases) for Backend-for-frontend patterns.

### Operations

- Log security-relevant events for Backend-for-frontend patterns without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Backend-for-frontend patterns.
- Review access and configuration for Backend-for-frontend patterns on a regular cadence.

## Legacy SOAP/XML APIs

Sub-topics: XXE, WS-Security misconfig

### Policy

- Treat Legacy SOAP/XML APIs in Legacy SOAP/XML APIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Legacy SOAP/XML APIs (API and integration security).
- Require security review for material changes affecting Legacy SOAP/XML APIs.

### Design

- Apply least privilege and defense in depth for Legacy SOAP/XML APIs.
- Prefer established patterns and libraries over custom crypto or auth for Legacy SOAP/XML APIs.
- Fail closed: deny by default when Legacy SOAP/XML APIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Legacy SOAP/XML APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Legacy SOAP/XML APIs.
- Keep dependencies patched; pin versions for Legacy SOAP/XML APIs components.

### Verification

- Add automated tests and SAST/DAST coverage for Legacy SOAP/XML APIs paths.
- Run dependency and secret scanning on every change touching Legacy SOAP/XML APIs.
- Perform targeted manual tests (abuse cases) for Legacy SOAP/XML APIs.

### Operations

- Log security-relevant events for Legacy SOAP/XML APIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Legacy SOAP/XML APIs.
- Review access and configuration for Legacy SOAP/XML APIs on a regular cadence.

## Event buses and streaming

Sub-topics: Schema evolution, Poison messages

### Policy

- Treat Event buses and streaming in Event buses and streaming as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Event buses and streaming (API and integration security).
- Require security review for material changes affecting Event buses and streaming.

### Design

- Apply least privilege and defense in depth for Event buses and streaming.
- Prefer established patterns and libraries over custom crypto or auth for Event buses and streaming.
- Fail closed: deny by default when Event buses and streaming cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Event buses and streaming; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Event buses and streaming.
- Keep dependencies patched; pin versions for Event buses and streaming components.

### Verification

- Add automated tests and SAST/DAST coverage for Event buses and streaming paths.
- Run dependency and secret scanning on every change touching Event buses and streaming.
- Perform targeted manual tests (abuse cases) for Event buses and streaming.

### Operations

- Log security-relevant events for Event buses and streaming without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Event buses and streaming.
- Review access and configuration for Event buses and streaming on a regular cadence.

