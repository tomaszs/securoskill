# Redis: Cloud and infrastructure security

Stack-specific implementation for **Redis** (Database). Normative rules: domain skill `security-cloud-infrastructure` / `reference.md`.

## Cloud IAM

**Sub-topics:** Overprivileged roles, IAM conditions, Threat modeling and trust boundaries (Cloud IAM), Abuse cases and adversarial testing (Cloud IAM), Logging, audit, and detection (Cloud IAM)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Cloud IAM; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Cloud IAM.
- Keep dependencies patched; pin versions for Cloud IAM components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Cloud IAM before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Cloud IAM paths in Redis.
- Run SAST/dependency scan configured for Database.

## Object storage buckets

**Sub-topics:** Public ACLs, Policy mistakes, Threat modeling and trust boundaries (Object storage buckets), Abuse cases and adversarial testing (Object storage buckets), Logging, audit, and detection (Object storage buckets)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Object storage buckets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Object storage buckets.
- Keep dependencies patched; pin versions for Object storage buckets components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Object storage buckets before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Object storage buckets paths in Redis.
- Run SAST/dependency scan configured for Database.

## Compute instances

**Sub-topics:** IMDSv2, SSH keys, Metadata, Threat modeling and trust boundaries (Compute instances), Abuse cases and adversarial testing (Compute instances)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Compute instances; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Compute instances.
- Keep dependencies patched; pin versions for Compute instances components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Compute instances before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Compute instances paths in Redis.
- Run SAST/dependency scan configured for Database.

## Managed serverless

**Sub-topics:** Function URLs, Concurrency, Threat modeling and trust boundaries (Managed serverless), Abuse cases and adversarial testing (Managed serverless), Logging, audit, and detection (Managed serverless)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Managed serverless; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Managed serverless.
- Keep dependencies patched; pin versions for Managed serverless components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Managed serverless before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Managed serverless paths in Redis.
- Run SAST/dependency scan configured for Database.

## Secrets managers

**Sub-topics:** Rotation, Access policies, Threat modeling and trust boundaries (Secrets managers), Abuse cases and adversarial testing (Secrets managers), Logging, audit, and detection (Secrets managers)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secrets managers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secrets managers.
- Keep dependencies patched; pin versions for Secrets managers components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secrets managers before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secrets managers paths in Redis.
- Run SAST/dependency scan configured for Database.

## VPC and security groups

**Sub-topics:** 0.0.0.0/0, Peering leaks, Threat modeling and trust boundaries (VPC and security groups), Abuse cases and adversarial testing (VPC and security groups), Logging, audit, and detection (VPC and security groups)

### Platform rules (summary)

- Validate and canonicalize all inputs touching VPC and security groups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPC and security groups.
- Keep dependencies patched; pin versions for VPC and security groups components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for VPC and security groups before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for VPC and security groups paths in Redis.
- Run SAST/dependency scan configured for Database.

## Cloud audit logs

**Sub-topics:** Tampering, Retention, Threat modeling and trust boundaries (Cloud audit logs), Abuse cases and adversarial testing (Cloud audit logs), Logging, audit, and detection (Cloud audit logs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Cloud audit logs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Cloud audit logs.
- Keep dependencies patched; pin versions for Cloud audit logs components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Cloud audit logs before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Cloud audit logs paths in Redis.
- Run SAST/dependency scan configured for Database.

## Infrastructure as code

**Sub-topics:** State files, Drift, Threat modeling and trust boundaries (Infrastructure as code), Abuse cases and adversarial testing (Infrastructure as code), Logging, audit, and detection (Infrastructure as code)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Infrastructure as code; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Infrastructure as code.
- Keep dependencies patched; pin versions for Infrastructure as code components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Infrastructure as code before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Infrastructure as code paths in Redis.
- Run SAST/dependency scan configured for Database.

## Multi-cloud identity

**Sub-topics:** Federation, Key sprawl, Threat modeling and trust boundaries (Multi-cloud identity), Abuse cases and adversarial testing (Multi-cloud identity), Logging, audit, and detection (Multi-cloud identity)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Multi-cloud identity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-cloud identity.
- Keep dependencies patched; pin versions for Multi-cloud identity components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Multi-cloud identity before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Multi-cloud identity paths in Redis.
- Run SAST/dependency scan configured for Database.

## SaaS admin consoles

**Sub-topics:** MFA, SCIM, Threat modeling and trust boundaries (SaaS admin consoles), Abuse cases and adversarial testing (SaaS admin consoles), Logging, audit, and detection (SaaS admin consoles)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SaaS admin consoles; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SaaS admin consoles.
- Keep dependencies patched; pin versions for SaaS admin consoles components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SaaS admin consoles before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SaaS admin consoles paths in Redis.
- Run SAST/dependency scan configured for Database.

## CDN and edge

**Sub-topics:** Cache deception, Origin shield, Threat modeling and trust boundaries (CDN and edge), Abuse cases and adversarial testing (CDN and edge), Logging, audit, and detection (CDN and edge)

### Platform rules (summary)

- Validate and canonicalize all inputs touching CDN and edge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CDN and edge.
- Keep dependencies patched; pin versions for CDN and edge components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CDN and edge before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CDN and edge paths in Redis.
- Run SAST/dependency scan configured for Database.

## DR and regions

**Sub-topics:** Failover security, Data residency, Threat modeling and trust boundaries (DR and regions), Abuse cases and adversarial testing (DR and regions), Logging, audit, and detection (DR and regions)

### Platform rules (summary)

- Validate and canonicalize all inputs touching DR and regions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DR and regions.
- Keep dependencies patched; pin versions for DR and regions components.

### How to do this in Redis

- Read normative rules in domain skill `security-cloud-infrastructure` / `reference.md`, then apply them using Redis APIs and deployment model.
- Prefer framework-maintained security features in Redis over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for DR and regions before merge.
- Pin Redis dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for DR and regions paths in Redis.
- Run SAST/dependency scan configured for Database.

