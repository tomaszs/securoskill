# Kubernetes: Serverless, edge, and FaaS security

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Platform rules (summary)

- Validate and canonicalize all inputs touching Function authentication; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Function authentication.
- Keep dependencies patched; pin versions for Function authentication components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Function authentication before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Function authentication paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Platform rules (summary)

- Validate and canonicalize all inputs touching Event source trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Event source trust.
- Keep dependencies patched; pin versions for Event source trust components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Event source trust before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Event source trust paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secrets in serverless; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secrets in serverless.
- Keep dependencies patched; pin versions for Secrets in serverless components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secrets in serverless before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secrets in serverless paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Platform rules (summary)

- Validate and canonicalize all inputs touching VPC and network placement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPC and network placement.
- Keep dependencies patched; pin versions for VPC and network placement components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for VPC and network placement before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for VPC and network placement paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Platform rules (summary)

- Validate and canonicalize all inputs touching Edge workers (CDN); never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Edge workers (CDN).
- Keep dependencies patched; pin versions for Edge workers (CDN) components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Edge workers (CDN) before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Edge workers (CDN) paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Platform rules (summary)

- Validate and canonicalize all inputs touching Denial of wallet; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Denial of wallet.
- Keep dependencies patched; pin versions for Denial of wallet components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Denial of wallet before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Denial of wallet paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Platform rules (summary)

- Validate and canonicalize all inputs touching Idempotency and retries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Idempotency and retries.
- Keep dependencies patched; pin versions for Idempotency and retries components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Idempotency and retries before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Idempotency and retries paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Platform rules (summary)

- Validate and canonicalize all inputs touching Local dev parity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Local dev parity.
- Keep dependencies patched; pin versions for Local dev parity components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Local dev parity before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Local dev parity paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Platform rules (summary)

- Validate and canonicalize all inputs touching Multi-region functions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-region functions.
- Keep dependencies patched; pin versions for Multi-region functions components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Multi-region functions before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Multi-region functions paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Platform rules (summary)

- Validate and canonicalize all inputs touching Wasm at edge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Wasm at edge.
- Keep dependencies patched; pin versions for Wasm at edge components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Wasm at edge before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Wasm at edge paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Platform rules (summary)

- Validate and canonicalize all inputs touching Orchestration workflows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Orchestration workflows.
- Keep dependencies patched; pin versions for Orchestration workflows components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Orchestration workflows before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Orchestration workflows paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Platform rules (summary)

- Validate and canonicalize all inputs touching Platform limit abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Platform limit abuse.
- Keep dependencies patched; pin versions for Platform limit abuse components.

### How to do this in Kubernetes

- Read normative rules in domain skill `security-serverless-edge` / `reference.md`, then apply them using Kubernetes APIs and deployment model.
- Prefer framework-maintained security features in Kubernetes over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Platform limit abuse before merge.
- Pin Kubernetes dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Platform limit abuse paths in Kubernetes.
- Run SAST/dependency scan configured for Infrastructure.

