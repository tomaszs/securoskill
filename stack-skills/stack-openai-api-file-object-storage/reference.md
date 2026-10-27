# OpenAI API / Agents SDK: File, blob, and object storage security

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-file-object-storage` / `reference.md`.

## Upload validation

**Sub-topics:** MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Malware scanning

**Sub-topics:** Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Presigned URLs

**Sub-topics:** TTL, Method restriction, Object key guessing, Header signing, Revocation

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Bucket policies and ACLs

**Sub-topics:** Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## CDN and origin access

**Sub-topics:** OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Image and media processing

**Sub-topics:** ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Document preview

**Sub-topics:** PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## User-generated content hosting

**Sub-topics:** Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Versioning and lifecycle

**Sub-topics:** Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Object encryption

**Sub-topics:** SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Metadata and headers

**Sub-topics:** x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

## Archives and backups

**Sub-topics:** Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Do (use this in OpenAI API / Agents SDK)

- Treat retrieved documents and tool outputs as untrusted; delimit and label untrusted blocks in prompts.
- Allowlist tools; validate JSON arguments with a strict schema before execution.
- Run privileged tools with service accounts scoped to the requesting user/tenant.

### Don't

- Do not pass raw user chat text directly into system prompts without separation.
- Do not give models shell, SQL, or HTTP tools without path/host allowlists.

### Verify

- Red-team with indirect injection samples in RAG fixtures.

