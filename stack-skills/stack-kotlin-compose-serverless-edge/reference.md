# Kotlin / Jetpack Compose: Serverless, edge, and FaaS security

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in Kotlin / Jetpack Compose)

- Kotlin / Jetpack Compose is not the primary enforcement point for `serverless-edge`; load stack skill `security-serverless-edge` when you touch that layer.
- Keep Kotlin / Jetpack Compose configuration aligned with requirements from `security-serverless-edge` (domain reference.md).

### Don't

- Do not duplicate `serverless-edge` controls only in Kotlin / Jetpack Compose config while leaving security-serverless-edge misconfigured.
- Do not assume Kotlin / Jetpack Compose defaults satisfy `security-serverless-edge` without verification.

### Verify

- Integration test the full path: Kotlin / Jetpack Compose plus the system covered by `security-serverless-edge`.

