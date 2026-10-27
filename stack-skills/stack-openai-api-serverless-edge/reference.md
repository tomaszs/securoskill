# OpenAI API / Agents SDK: Serverless, edge, and FaaS security

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in OpenAI API / Agents SDK)

- Apply domain skill `security-serverless-edge` requirements using openai-api supported APIs only.
- Use the official openai-api security documentation for faas_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of openai-api for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on openai-api projects in CI.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in OpenAI API / Agents SDK)

- Apply domain skill `security-serverless-edge` requirements using openai-api supported APIs only.
- Use the official openai-api security documentation for faas_events controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of openai-api for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on openai-api projects in CI.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in OpenAI API / Agents SDK)

- Apply domain skill `security-serverless-edge` requirements using openai-api supported APIs only.
- Use the official openai-api security documentation for faas_secrets controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of openai-api for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on openai-api projects in CI.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in OpenAI API / Agents SDK)

- Apply domain skill `security-serverless-edge` requirements using openai-api supported APIs only.
- Use the official openai-api security documentation for edge_workers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of openai-api for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on openai-api projects in CI.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

