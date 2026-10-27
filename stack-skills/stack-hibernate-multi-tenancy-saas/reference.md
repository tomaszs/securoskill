# Hibernate / JPA: Multi-tenancy and SaaS isolation

Stack-specific implementation for **Hibernate / JPA** (ORM / data access). Normative rules: domain skill `security-multi-tenancy-saas` / `reference.md`.

## Tenant identification

**Sub-topics:** Subdomain routing, Header spoofing, JWT tenant claim, Shared login portals, Cross-tenant IDs

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tenant identification; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant identification.
- Keep dependencies patched; pin versions for Tenant identification components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tenant identification before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tenant identification paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Data isolation models

**Sub-topics:** Separate DB, Shared schema RLS, Shard keys, Cache namespacing, Search index isolation

### Platform rules (summary)

- Validate and canonicalize all inputs touching Data isolation models; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data isolation models.
- Keep dependencies patched; pin versions for Data isolation models components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Data isolation models before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Data isolation models paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Tenant-scoped authorization

**Sub-topics:** Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tenant-scoped authorization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant-scoped authorization.
- Keep dependencies patched; pin versions for Tenant-scoped authorization components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tenant-scoped authorization before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tenant-scoped authorization paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Billing and plan enforcement

**Sub-topics:** Feature flags per plan, Usage metering, Trial abuse, Seat limits, Upgrade bypass

### Platform rules (summary)

- Validate and canonicalize all inputs touching Billing and plan enforcement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Billing and plan enforcement.
- Keep dependencies patched; pin versions for Billing and plan enforcement components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Billing and plan enforcement before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Billing and plan enforcement paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Custom domains and TLS

**Sub-topics:** Domain verification, Cert provisioning, Host header attacks, Tenant vanity URLs, DNS takeover

### Platform rules (summary)

- Validate and canonicalize all inputs touching Custom domains and TLS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Custom domains and TLS.
- Keep dependencies patched; pin versions for Custom domains and TLS components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Custom domains and TLS before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Custom domains and TLS paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Tenant export and backup

**Sub-topics:** Bulk export IDOR, Scheduled exports, Restore to wrong tenant, GDPR per tenant, Retention per tenant

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tenant export and backup; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant export and backup.
- Keep dependencies patched; pin versions for Tenant export and backup components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tenant export and backup before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tenant export and backup paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Per-tenant integrations

**Sub-topics:** OAuth app installs, Webhook endpoints, SCIM provisioning, API rate per tenant, Third-party tokens

### Platform rules (summary)

- Validate and canonicalize all inputs touching Per-tenant integrations; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Per-tenant integrations.
- Keep dependencies patched; pin versions for Per-tenant integrations components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Per-tenant integrations before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Per-tenant integrations paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Noisy neighbor and quotas

**Sub-topics:** CPU limits, Queue fairness, DB connection pools, Rate limits, Burst abuse

### Platform rules (summary)

- Validate and canonicalize all inputs touching Noisy neighbor and quotas; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Noisy neighbor and quotas.
- Keep dependencies patched; pin versions for Noisy neighbor and quotas components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Noisy neighbor and quotas before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Noisy neighbor and quotas paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Tenant onboarding

**Sub-topics:** Self-signup abuse, Email domain verification, Invite flows, Default permissions, Sandbox tenants

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tenant onboarding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant onboarding.
- Keep dependencies patched; pin versions for Tenant onboarding components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tenant onboarding before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tenant onboarding paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Tenant offboarding

**Sub-topics:** Data deletion, Legal hold, Reactivation, Orphan resources, Subprocessor notice

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tenant offboarding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant offboarding.
- Keep dependencies patched; pin versions for Tenant offboarding components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tenant offboarding before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tenant offboarding paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## Compliance per tenant

**Sub-topics:** Data residency, Audit logs per tenant, DPA variants, HIPAA BAA, SOC reports

### Platform rules (summary)

- Validate and canonicalize all inputs touching Compliance per tenant; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Compliance per tenant.
- Keep dependencies patched; pin versions for Compliance per tenant components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Compliance per tenant before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Compliance per tenant paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

## SaaS penetration patterns

**Sub-topics:** Horizontal privilege, Vertical to platform admin, Cross-tenant file access, Report IDOR, Shared infrastructure

### Platform rules (summary)

- Validate and canonicalize all inputs touching SaaS penetration patterns; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SaaS penetration patterns.
- Keep dependencies patched; pin versions for SaaS penetration patterns components.

### How to do this in Hibernate / JPA

- Read normative rules in domain skill `security-multi-tenancy-saas` / `reference.md`, then apply them using Hibernate / JPA APIs and deployment model.
- Prefer framework-maintained security features in Hibernate / JPA over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SaaS penetration patterns before merge.
- Pin Hibernate / JPA dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SaaS penetration patterns paths in Hibernate / JPA.
- Run SAST/dependency scan configured for ORM / data access.

