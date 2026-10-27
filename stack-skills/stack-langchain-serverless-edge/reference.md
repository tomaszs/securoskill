# LangChain / LangGraph: Serverless, edge, and FaaS security

Stack-specific implementation for **LangChain / LangGraph** (AI). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

