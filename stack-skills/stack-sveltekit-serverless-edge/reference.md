# SvelteKit: Serverless, edge, and FaaS security

Stack-specific implementation for **SvelteKit** (Web UI). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in SvelteKit)

- Map `Function authentication` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Function authentication` before merge.

### Don't

- Do not ship `Function authentication` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Function authentication`.

### Verify

- Peer review `Function authentication` against domain skill `security-serverless-edge`.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in SvelteKit)

- Map `Event source trust` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Event source trust` before merge.

### Don't

- Do not ship `Event source trust` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Event source trust`.

### Verify

- Peer review `Event source trust` against domain skill `security-serverless-edge`.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in SvelteKit)

- Map `Secrets in serverless` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Secrets in serverless` before merge.

### Don't

- Do not ship `Secrets in serverless` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Secrets in serverless`.

### Verify

- Peer review `Secrets in serverless` against domain skill `security-serverless-edge`.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in SvelteKit)

- Map `VPC and network placement` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `VPC and network placement` before merge.

### Don't

- Do not ship `VPC and network placement` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `VPC and network placement`.

### Verify

- Peer review `VPC and network placement` against domain skill `security-serverless-edge`.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in SvelteKit)

- Map `Edge workers (CDN)` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Edge workers (CDN)` before merge.

### Don't

- Do not ship `Edge workers (CDN)` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Edge workers (CDN)`.

### Verify

- Peer review `Edge workers (CDN)` against domain skill `security-serverless-edge`.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in SvelteKit)

- Map `Denial of wallet` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Denial of wallet` before merge.

### Don't

- Do not ship `Denial of wallet` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Denial of wallet`.

### Verify

- Peer review `Denial of wallet` against domain skill `security-serverless-edge`.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in SvelteKit)

- Map `Idempotency and retries` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Idempotency and retries` before merge.

### Don't

- Do not ship `Idempotency and retries` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Idempotency and retries`.

### Verify

- Peer review `Idempotency and retries` against domain skill `security-serverless-edge`.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in SvelteKit)

- Map `Local dev parity` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Local dev parity` before merge.

### Don't

- Do not ship `Local dev parity` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Local dev parity`.

### Verify

- Peer review `Local dev parity` against domain skill `security-serverless-edge`.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in SvelteKit)

- Map `Multi-region functions` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Multi-region functions` before merge.

### Don't

- Do not ship `Multi-region functions` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Multi-region functions`.

### Verify

- Peer review `Multi-region functions` against domain skill `security-serverless-edge`.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in SvelteKit)

- Map `Wasm at edge` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Wasm at edge` before merge.

### Don't

- Do not ship `Wasm at edge` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Wasm at edge`.

### Verify

- Peer review `Wasm at edge` against domain skill `security-serverless-edge`.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in SvelteKit)

- Map `Orchestration workflows` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Orchestration workflows` before merge.

### Don't

- Do not ship `Orchestration workflows` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Orchestration workflows`.

### Verify

- Peer review `Orchestration workflows` against domain skill `security-serverless-edge`.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in SvelteKit)

- Map `Platform limit abuse` controls to SvelteKit APIs documented for `security-serverless-edge`.
- Add an abuse-case test or check for `Platform limit abuse` before merge.

### Don't

- Do not ship `Platform limit abuse` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Platform limit abuse`.

### Verify

- Peer review `Platform limit abuse` against domain skill `security-serverless-edge`.

