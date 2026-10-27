# Rules reference: Serverless, edge, and FaaS security

Lambda, workers, edge functions, and event-driven compute.

## Function authentication

Sub-topics: IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Policy

- Treat Function authentication in Function authentication as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Function authentication (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Function authentication.

### Design

- Apply least privilege and defense in depth for Function authentication.
- Prefer established patterns and libraries over custom crypto or auth for Function authentication.
- Fail closed: deny by default when Function authentication cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Function authentication; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Function authentication.
- Keep dependencies patched; pin versions for Function authentication components.

### Verification

- Add automated tests and SAST/DAST coverage for Function authentication paths.
- Run dependency and secret scanning on every change touching Function authentication.
- Perform targeted manual tests (abuse cases) for Function authentication.

### Operations

- Log security-relevant events for Function authentication without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Function authentication.
- Review access and configuration for Function authentication on a regular cadence.

## Event source trust

Sub-topics: S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Policy

- Treat Event source trust in Event source trust as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Event source trust (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Event source trust.

### Design

- Apply least privilege and defense in depth for Event source trust.
- Prefer established patterns and libraries over custom crypto or auth for Event source trust.
- Fail closed: deny by default when Event source trust cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Event source trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Event source trust.
- Keep dependencies patched; pin versions for Event source trust components.

### Verification

- Add automated tests and SAST/DAST coverage for Event source trust paths.
- Run dependency and secret scanning on every change touching Event source trust.
- Perform targeted manual tests (abuse cases) for Event source trust.

### Operations

- Log security-relevant events for Event source trust without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Event source trust.
- Review access and configuration for Event source trust on a regular cadence.

## Secrets in serverless

Sub-topics: Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Policy

- Treat Secrets in serverless in Secrets in serverless as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secrets in serverless (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Secrets in serverless.

### Design

- Apply least privilege and defense in depth for Secrets in serverless.
- Prefer established patterns and libraries over custom crypto or auth for Secrets in serverless.
- Fail closed: deny by default when Secrets in serverless cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secrets in serverless; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secrets in serverless.
- Keep dependencies patched; pin versions for Secrets in serverless components.

### Verification

- Add automated tests and SAST/DAST coverage for Secrets in serverless paths.
- Run dependency and secret scanning on every change touching Secrets in serverless.
- Perform targeted manual tests (abuse cases) for Secrets in serverless.

### Operations

- Log security-relevant events for Secrets in serverless without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secrets in serverless.
- Review access and configuration for Secrets in serverless on a regular cadence.

## VPC and network placement

Sub-topics: NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Policy

- Treat VPC and network placement in VPC and network placement as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for VPC and network placement (Serverless, edge, and FaaS security).
- Require security review for material changes affecting VPC and network placement.

### Design

- Apply least privilege and defense in depth for VPC and network placement.
- Prefer established patterns and libraries over custom crypto or auth for VPC and network placement.
- Fail closed: deny by default when VPC and network placement cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching VPC and network placement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPC and network placement.
- Keep dependencies patched; pin versions for VPC and network placement components.

### Verification

- Add automated tests and SAST/DAST coverage for VPC and network placement paths.
- Run dependency and secret scanning on every change touching VPC and network placement.
- Perform targeted manual tests (abuse cases) for VPC and network placement.

### Operations

- Log security-relevant events for VPC and network placement without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in VPC and network placement.
- Review access and configuration for VPC and network placement on a regular cadence.

## Edge workers (CDN)

Sub-topics: KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Policy

- Treat Edge workers (CDN) in Edge workers (CDN) as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Edge workers (CDN) (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Edge workers (CDN).

### Design

- Apply least privilege and defense in depth for Edge workers (CDN).
- Prefer established patterns and libraries over custom crypto or auth for Edge workers (CDN).
- Fail closed: deny by default when Edge workers (CDN) cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Edge workers (CDN); never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Edge workers (CDN).
- Keep dependencies patched; pin versions for Edge workers (CDN) components.

### Verification

- Add automated tests and SAST/DAST coverage for Edge workers (CDN) paths.
- Run dependency and secret scanning on every change touching Edge workers (CDN).
- Perform targeted manual tests (abuse cases) for Edge workers (CDN).

### Operations

- Log security-relevant events for Edge workers (CDN) without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Edge workers (CDN).
- Review access and configuration for Edge workers (CDN) on a regular cadence.

## Denial of wallet

Sub-topics: Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Policy

- Treat Denial of wallet in Denial of wallet as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Denial of wallet (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Denial of wallet.

### Design

- Apply least privilege and defense in depth for Denial of wallet.
- Prefer established patterns and libraries over custom crypto or auth for Denial of wallet.
- Fail closed: deny by default when Denial of wallet cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Denial of wallet; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Denial of wallet.
- Keep dependencies patched; pin versions for Denial of wallet components.

### Verification

- Add automated tests and SAST/DAST coverage for Denial of wallet paths.
- Run dependency and secret scanning on every change touching Denial of wallet.
- Perform targeted manual tests (abuse cases) for Denial of wallet.

### Operations

- Log security-relevant events for Denial of wallet without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Denial of wallet.
- Review access and configuration for Denial of wallet on a regular cadence.

## Idempotency and retries

Sub-topics: Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Policy

- Treat Idempotency and retries in Idempotency and retries as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Idempotency and retries (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Idempotency and retries.

### Design

- Apply least privilege and defense in depth for Idempotency and retries.
- Prefer established patterns and libraries over custom crypto or auth for Idempotency and retries.
- Fail closed: deny by default when Idempotency and retries cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Idempotency and retries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Idempotency and retries.
- Keep dependencies patched; pin versions for Idempotency and retries components.

### Verification

- Add automated tests and SAST/DAST coverage for Idempotency and retries paths.
- Run dependency and secret scanning on every change touching Idempotency and retries.
- Perform targeted manual tests (abuse cases) for Idempotency and retries.

### Operations

- Log security-relevant events for Idempotency and retries without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Idempotency and retries.
- Review access and configuration for Idempotency and retries on a regular cadence.

## Local dev parity

Sub-topics: sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Policy

- Treat Local dev parity in Local dev parity as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Local dev parity (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Local dev parity.

### Design

- Apply least privilege and defense in depth for Local dev parity.
- Prefer established patterns and libraries over custom crypto or auth for Local dev parity.
- Fail closed: deny by default when Local dev parity cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Local dev parity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Local dev parity.
- Keep dependencies patched; pin versions for Local dev parity components.

### Verification

- Add automated tests and SAST/DAST coverage for Local dev parity paths.
- Run dependency and secret scanning on every change touching Local dev parity.
- Perform targeted manual tests (abuse cases) for Local dev parity.

### Operations

- Log security-relevant events for Local dev parity without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Local dev parity.
- Review access and configuration for Local dev parity on a regular cadence.

## Multi-region functions

Sub-topics: Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Policy

- Treat Multi-region functions in Multi-region functions as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Multi-region functions (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Multi-region functions.

### Design

- Apply least privilege and defense in depth for Multi-region functions.
- Prefer established patterns and libraries over custom crypto or auth for Multi-region functions.
- Fail closed: deny by default when Multi-region functions cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Multi-region functions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-region functions.
- Keep dependencies patched; pin versions for Multi-region functions components.

### Verification

- Add automated tests and SAST/DAST coverage for Multi-region functions paths.
- Run dependency and secret scanning on every change touching Multi-region functions.
- Perform targeted manual tests (abuse cases) for Multi-region functions.

### Operations

- Log security-relevant events for Multi-region functions without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Multi-region functions.
- Review access and configuration for Multi-region functions on a regular cadence.

## Wasm at edge

Sub-topics: Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Policy

- Treat Wasm at edge in Wasm at edge as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Wasm at edge (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Wasm at edge.

### Design

- Apply least privilege and defense in depth for Wasm at edge.
- Prefer established patterns and libraries over custom crypto or auth for Wasm at edge.
- Fail closed: deny by default when Wasm at edge cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Wasm at edge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Wasm at edge.
- Keep dependencies patched; pin versions for Wasm at edge components.

### Verification

- Add automated tests and SAST/DAST coverage for Wasm at edge paths.
- Run dependency and secret scanning on every change touching Wasm at edge.
- Perform targeted manual tests (abuse cases) for Wasm at edge.

### Operations

- Log security-relevant events for Wasm at edge without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Wasm at edge.
- Review access and configuration for Wasm at edge on a regular cadence.

## Orchestration workflows

Sub-topics: State injection, IAM chaining, Long-running abuse, Input size, Observability

### Policy

- Treat Orchestration workflows in Orchestration workflows as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Orchestration workflows (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Orchestration workflows.

### Design

- Apply least privilege and defense in depth for Orchestration workflows.
- Prefer established patterns and libraries over custom crypto or auth for Orchestration workflows.
- Fail closed: deny by default when Orchestration workflows cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Orchestration workflows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Orchestration workflows.
- Keep dependencies patched; pin versions for Orchestration workflows components.

### Verification

- Add automated tests and SAST/DAST coverage for Orchestration workflows paths.
- Run dependency and secret scanning on every change touching Orchestration workflows.
- Perform targeted manual tests (abuse cases) for Orchestration workflows.

### Operations

- Log security-relevant events for Orchestration workflows without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Orchestration workflows.
- Review access and configuration for Orchestration workflows on a regular cadence.

## Platform limit abuse

Sub-topics: Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Policy

- Treat Platform limit abuse in Platform limit abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Platform limit abuse (Serverless, edge, and FaaS security).
- Require security review for material changes affecting Platform limit abuse.

### Design

- Apply least privilege and defense in depth for Platform limit abuse.
- Prefer established patterns and libraries over custom crypto or auth for Platform limit abuse.
- Fail closed: deny by default when Platform limit abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Platform limit abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Platform limit abuse.
- Keep dependencies patched; pin versions for Platform limit abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Platform limit abuse paths.
- Run dependency and secret scanning on every change touching Platform limit abuse.
- Perform targeted manual tests (abuse cases) for Platform limit abuse.

### Operations

- Log security-relevant events for Platform limit abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Platform limit abuse.
- Review access and configuration for Platform limit abuse on a regular cadence.

