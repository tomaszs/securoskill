# LangChain / LangGraph: API and integration security

Stack-specific implementation for **LangChain / LangGraph** (AI). Normative rules: domain skill `security-api-integration` / `reference.md`.

## REST API design security

**Sub-topics:** Versioning, Idempotency, Mass assignment, Threat modeling and trust boundaries (REST API design security), Abuse cases and adversarial testing (REST API design security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching REST API design security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to REST API design security.
- Keep dependencies patched; pin versions for REST API design security components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for REST API design security before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for REST API design security paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## GraphQL security

**Sub-topics:** Depth limits, Introspection, Batching abuse, Threat modeling and trust boundaries (GraphQL security), Abuse cases and adversarial testing (GraphQL security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching GraphQL security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to GraphQL security.
- Keep dependencies patched; pin versions for GraphQL security components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for GraphQL security before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for GraphQL security paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## gRPC and protobuf

**Sub-topics:** mTLS, Message size, Auth metadata, Threat modeling and trust boundaries (gRPC and protobuf), Abuse cases and adversarial testing (gRPC and protobuf)

### Platform rules (summary)

- Validate and canonicalize all inputs touching gRPC and protobuf; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to gRPC and protobuf.
- Keep dependencies patched; pin versions for gRPC and protobuf components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for gRPC and protobuf before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for gRPC and protobuf paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Webhooks outbound and inbound

**Sub-topics:** Signature verification, Replay, SSRF from callbacks, Threat modeling and trust boundaries (Webhooks outbound and inbound), Abuse cases and adversarial testing (Webhooks outbound and inbound)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Webhooks outbound and inbound; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Webhooks outbound and inbound.
- Keep dependencies patched; pin versions for Webhooks outbound and inbound components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Webhooks outbound and inbound before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Webhooks outbound and inbound paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## OAuth2/OIDC for APIs

**Sub-topics:** Scopes, Client credentials, Token exchange, Threat modeling and trust boundaries (OAuth2/OIDC for APIs), Abuse cases and adversarial testing (OAuth2/OIDC for APIs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching OAuth2/OIDC for APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OAuth2/OIDC for APIs.
- Keep dependencies patched; pin versions for OAuth2/OIDC for APIs components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for OAuth2/OIDC for APIs before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for OAuth2/OIDC for APIs paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## API keys and HMAC

**Sub-topics:** Rotation, Per-tenant keys, Constant-time compare, Threat modeling and trust boundaries (API keys and HMAC), Abuse cases and adversarial testing (API keys and HMAC)

### Platform rules (summary)

- Validate and canonicalize all inputs touching API keys and HMAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to API keys and HMAC.
- Keep dependencies patched; pin versions for API keys and HMAC components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for API keys and HMAC before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for API keys and HMAC paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Pagination and filtering abuse

**Sub-topics:** Large offsets, Filter injection, Threat modeling and trust boundaries (Pagination and filtering abuse), Abuse cases and adversarial testing (Pagination and filtering abuse), Logging, audit, and detection (Pagination and filtering abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Pagination and filtering abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Pagination and filtering abuse.
- Keep dependencies patched; pin versions for Pagination and filtering abuse components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Pagination and filtering abuse before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Pagination and filtering abuse paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## CORS for APIs

**Sub-topics:** Credentials, Wildcard origins, Threat modeling and trust boundaries (CORS for APIs), Abuse cases and adversarial testing (CORS for APIs), Logging, audit, and detection (CORS for APIs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching CORS for APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CORS for APIs.
- Keep dependencies patched; pin versions for CORS for APIs components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CORS for APIs before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CORS for APIs paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## OpenAPI and documentation leakage

**Sub-topics:** Hidden admin paths, Example secrets, Threat modeling and trust boundaries (OpenAPI and documentation leakage), Abuse cases and adversarial testing (OpenAPI and documentation leakage), Logging, audit, and detection (OpenAPI and documentation leakage)

### Platform rules (summary)

- Validate and canonicalize all inputs touching OpenAPI and documentation leakage; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OpenAPI and documentation leakage.
- Keep dependencies patched; pin versions for OpenAPI and documentation leakage components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for OpenAPI and documentation leakage before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for OpenAPI and documentation leakage paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Backend-for-frontend patterns

**Sub-topics:** Token handling, Aggregation leaks, Threat modeling and trust boundaries (Backend-for-frontend patterns), Abuse cases and adversarial testing (Backend-for-frontend patterns), Logging, audit, and detection (Backend-for-frontend patterns)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Backend-for-frontend patterns; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Backend-for-frontend patterns.
- Keep dependencies patched; pin versions for Backend-for-frontend patterns components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Backend-for-frontend patterns before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Backend-for-frontend patterns paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Legacy SOAP/XML APIs

**Sub-topics:** XXE, WS-Security misconfig, Threat modeling and trust boundaries (Legacy SOAP/XML APIs), Abuse cases and adversarial testing (Legacy SOAP/XML APIs), Logging, audit, and detection (Legacy SOAP/XML APIs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Legacy SOAP/XML APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Legacy SOAP/XML APIs.
- Keep dependencies patched; pin versions for Legacy SOAP/XML APIs components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Legacy SOAP/XML APIs before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Legacy SOAP/XML APIs paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

## Event buses and streaming

**Sub-topics:** Schema evolution, Poison messages, Threat modeling and trust boundaries (Event buses and streaming), Abuse cases and adversarial testing (Event buses and streaming), Logging, audit, and detection (Event buses and streaming)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Event buses and streaming; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Event buses and streaming.
- Keep dependencies patched; pin versions for Event buses and streaming components.

### How to do this in LangChain / LangGraph

- Treat model tool calls like RPC: allowlist tools, validate args, run with least privilege from LangChain / LangGraph.
- Strip untrusted content from RAG chunks; enforce ACL on retrieval per tenant.
- Read normative rules in domain skill `security-api-integration` / `reference.md`, then apply them using LangChain / LangGraph APIs and deployment model.
- Prefer framework-maintained security features in LangChain / LangGraph over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Event buses and streaming before merge.
- Pin LangChain / LangGraph dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Event buses and streaming paths in LangChain / LangGraph.
- Run SAST/dependency scan configured for AI.

