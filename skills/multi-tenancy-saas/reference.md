# Rules reference: Multi-tenancy and SaaS isolation

Tenant boundaries, noisy neighbors, and B2B SaaS data separation.

## Tenant identification

Sub-topics: Subdomain routing, Header spoofing, JWT tenant claim, Shared login portals, Cross-tenant IDs

### Policy

- Treat Tenant identification in Tenant identification as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tenant identification (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Tenant identification.

### Design

- Apply least privilege and defense in depth for Tenant identification.
- Prefer established patterns and libraries over custom crypto or auth for Tenant identification.
- Fail closed: deny by default when Tenant identification cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tenant identification; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant identification.
- Keep dependencies patched; pin versions for Tenant identification components.

### Verification

- Add automated tests and SAST/DAST coverage for Tenant identification paths.
- Run dependency and secret scanning on every change touching Tenant identification.
- Perform targeted manual tests (abuse cases) for Tenant identification.

### Operations

- Log security-relevant events for Tenant identification without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tenant identification.
- Review access and configuration for Tenant identification on a regular cadence.

## Data isolation models

Sub-topics: Separate DB, Shared schema RLS, Shard keys, Cache namespacing, Search index isolation

### Policy

- Treat Data isolation models in Data isolation models as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Data isolation models (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Data isolation models.

### Design

- Apply least privilege and defense in depth for Data isolation models.
- Prefer established patterns and libraries over custom crypto or auth for Data isolation models.
- Fail closed: deny by default when Data isolation models cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Data isolation models; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Data isolation models.
- Keep dependencies patched; pin versions for Data isolation models components.

### Verification

- Add automated tests and SAST/DAST coverage for Data isolation models paths.
- Run dependency and secret scanning on every change touching Data isolation models.
- Perform targeted manual tests (abuse cases) for Data isolation models.

### Operations

- Log security-relevant events for Data isolation models without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Data isolation models.
- Review access and configuration for Data isolation models on a regular cadence.

## Tenant-scoped authorization

Sub-topics: Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Policy

- Treat Tenant-scoped authorization in Tenant-scoped authorization as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tenant-scoped authorization (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Tenant-scoped authorization.

### Design

- Apply least privilege and defense in depth for Tenant-scoped authorization.
- Prefer established patterns and libraries over custom crypto or auth for Tenant-scoped authorization.
- Fail closed: deny by default when Tenant-scoped authorization cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tenant-scoped authorization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant-scoped authorization.
- Keep dependencies patched; pin versions for Tenant-scoped authorization components.

### Verification

- Add automated tests and SAST/DAST coverage for Tenant-scoped authorization paths.
- Run dependency and secret scanning on every change touching Tenant-scoped authorization.
- Perform targeted manual tests (abuse cases) for Tenant-scoped authorization.

### Operations

- Log security-relevant events for Tenant-scoped authorization without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tenant-scoped authorization.
- Review access and configuration for Tenant-scoped authorization on a regular cadence.

## Billing and plan enforcement

Sub-topics: Feature flags per plan, Usage metering, Trial abuse, Seat limits, Upgrade bypass

### Policy

- Treat Billing and plan enforcement in Billing and plan enforcement as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Billing and plan enforcement (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Billing and plan enforcement.

### Design

- Apply least privilege and defense in depth for Billing and plan enforcement.
- Prefer established patterns and libraries over custom crypto or auth for Billing and plan enforcement.
- Fail closed: deny by default when Billing and plan enforcement cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Billing and plan enforcement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Billing and plan enforcement.
- Keep dependencies patched; pin versions for Billing and plan enforcement components.

### Verification

- Add automated tests and SAST/DAST coverage for Billing and plan enforcement paths.
- Run dependency and secret scanning on every change touching Billing and plan enforcement.
- Perform targeted manual tests (abuse cases) for Billing and plan enforcement.

### Operations

- Log security-relevant events for Billing and plan enforcement without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Billing and plan enforcement.
- Review access and configuration for Billing and plan enforcement on a regular cadence.

## Custom domains and TLS

Sub-topics: Domain verification, Cert provisioning, Host header attacks, Tenant vanity URLs, DNS takeover

### Policy

- Treat Custom domains and TLS in Custom domains and TLS as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Custom domains and TLS (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Custom domains and TLS.

### Design

- Apply least privilege and defense in depth for Custom domains and TLS.
- Prefer established patterns and libraries over custom crypto or auth for Custom domains and TLS.
- Fail closed: deny by default when Custom domains and TLS cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Custom domains and TLS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Custom domains and TLS.
- Keep dependencies patched; pin versions for Custom domains and TLS components.

### Verification

- Add automated tests and SAST/DAST coverage for Custom domains and TLS paths.
- Run dependency and secret scanning on every change touching Custom domains and TLS.
- Perform targeted manual tests (abuse cases) for Custom domains and TLS.

### Operations

- Log security-relevant events for Custom domains and TLS without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Custom domains and TLS.
- Review access and configuration for Custom domains and TLS on a regular cadence.

## Tenant export and backup

Sub-topics: Bulk export IDOR, Scheduled exports, Restore to wrong tenant, GDPR per tenant, Retention per tenant

### Policy

- Treat Tenant export and backup in Tenant export and backup as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tenant export and backup (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Tenant export and backup.

### Design

- Apply least privilege and defense in depth for Tenant export and backup.
- Prefer established patterns and libraries over custom crypto or auth for Tenant export and backup.
- Fail closed: deny by default when Tenant export and backup cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tenant export and backup; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant export and backup.
- Keep dependencies patched; pin versions for Tenant export and backup components.

### Verification

- Add automated tests and SAST/DAST coverage for Tenant export and backup paths.
- Run dependency and secret scanning on every change touching Tenant export and backup.
- Perform targeted manual tests (abuse cases) for Tenant export and backup.

### Operations

- Log security-relevant events for Tenant export and backup without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tenant export and backup.
- Review access and configuration for Tenant export and backup on a regular cadence.

## Per-tenant integrations

Sub-topics: OAuth app installs, Webhook endpoints, SCIM provisioning, API rate per tenant, Third-party tokens

### Policy

- Treat Per-tenant integrations in Per-tenant integrations as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Per-tenant integrations (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Per-tenant integrations.

### Design

- Apply least privilege and defense in depth for Per-tenant integrations.
- Prefer established patterns and libraries over custom crypto or auth for Per-tenant integrations.
- Fail closed: deny by default when Per-tenant integrations cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Per-tenant integrations; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Per-tenant integrations.
- Keep dependencies patched; pin versions for Per-tenant integrations components.

### Verification

- Add automated tests and SAST/DAST coverage for Per-tenant integrations paths.
- Run dependency and secret scanning on every change touching Per-tenant integrations.
- Perform targeted manual tests (abuse cases) for Per-tenant integrations.

### Operations

- Log security-relevant events for Per-tenant integrations without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Per-tenant integrations.
- Review access and configuration for Per-tenant integrations on a regular cadence.

## Noisy neighbor and quotas

Sub-topics: CPU limits, Queue fairness, DB connection pools, Rate limits, Burst abuse

### Policy

- Treat Noisy neighbor and quotas in Noisy neighbor and quotas as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Noisy neighbor and quotas (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Noisy neighbor and quotas.

### Design

- Apply least privilege and defense in depth for Noisy neighbor and quotas.
- Prefer established patterns and libraries over custom crypto or auth for Noisy neighbor and quotas.
- Fail closed: deny by default when Noisy neighbor and quotas cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Noisy neighbor and quotas; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Noisy neighbor and quotas.
- Keep dependencies patched; pin versions for Noisy neighbor and quotas components.

### Verification

- Add automated tests and SAST/DAST coverage for Noisy neighbor and quotas paths.
- Run dependency and secret scanning on every change touching Noisy neighbor and quotas.
- Perform targeted manual tests (abuse cases) for Noisy neighbor and quotas.

### Operations

- Log security-relevant events for Noisy neighbor and quotas without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Noisy neighbor and quotas.
- Review access and configuration for Noisy neighbor and quotas on a regular cadence.

## Tenant onboarding

Sub-topics: Self-signup abuse, Email domain verification, Invite flows, Default permissions, Sandbox tenants

### Policy

- Treat Tenant onboarding in Tenant onboarding as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tenant onboarding (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Tenant onboarding.

### Design

- Apply least privilege and defense in depth for Tenant onboarding.
- Prefer established patterns and libraries over custom crypto or auth for Tenant onboarding.
- Fail closed: deny by default when Tenant onboarding cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tenant onboarding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant onboarding.
- Keep dependencies patched; pin versions for Tenant onboarding components.

### Verification

- Add automated tests and SAST/DAST coverage for Tenant onboarding paths.
- Run dependency and secret scanning on every change touching Tenant onboarding.
- Perform targeted manual tests (abuse cases) for Tenant onboarding.

### Operations

- Log security-relevant events for Tenant onboarding without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tenant onboarding.
- Review access and configuration for Tenant onboarding on a regular cadence.

## Tenant offboarding

Sub-topics: Data deletion, Legal hold, Reactivation, Orphan resources, Subprocessor notice

### Policy

- Treat Tenant offboarding in Tenant offboarding as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tenant offboarding (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Tenant offboarding.

### Design

- Apply least privilege and defense in depth for Tenant offboarding.
- Prefer established patterns and libraries over custom crypto or auth for Tenant offboarding.
- Fail closed: deny by default when Tenant offboarding cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tenant offboarding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant offboarding.
- Keep dependencies patched; pin versions for Tenant offboarding components.

### Verification

- Add automated tests and SAST/DAST coverage for Tenant offboarding paths.
- Run dependency and secret scanning on every change touching Tenant offboarding.
- Perform targeted manual tests (abuse cases) for Tenant offboarding.

### Operations

- Log security-relevant events for Tenant offboarding without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tenant offboarding.
- Review access and configuration for Tenant offboarding on a regular cadence.

## Compliance per tenant

Sub-topics: Data residency, Audit logs per tenant, DPA variants, HIPAA BAA, SOC reports

### Policy

- Treat Compliance per tenant in Compliance per tenant as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Compliance per tenant (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting Compliance per tenant.

### Design

- Apply least privilege and defense in depth for Compliance per tenant.
- Prefer established patterns and libraries over custom crypto or auth for Compliance per tenant.
- Fail closed: deny by default when Compliance per tenant cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Compliance per tenant; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Compliance per tenant.
- Keep dependencies patched; pin versions for Compliance per tenant components.

### Verification

- Add automated tests and SAST/DAST coverage for Compliance per tenant paths.
- Run dependency and secret scanning on every change touching Compliance per tenant.
- Perform targeted manual tests (abuse cases) for Compliance per tenant.

### Operations

- Log security-relevant events for Compliance per tenant without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Compliance per tenant.
- Review access and configuration for Compliance per tenant on a regular cadence.

## SaaS penetration patterns

Sub-topics: Horizontal privilege, Vertical to platform admin, Cross-tenant file access, Report IDOR, Shared infrastructure

### Policy

- Treat SaaS penetration patterns in SaaS penetration patterns as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SaaS penetration patterns (Multi-tenancy and SaaS isolation).
- Require security review for material changes affecting SaaS penetration patterns.

### Design

- Apply least privilege and defense in depth for SaaS penetration patterns.
- Prefer established patterns and libraries over custom crypto or auth for SaaS penetration patterns.
- Fail closed: deny by default when SaaS penetration patterns cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SaaS penetration patterns; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SaaS penetration patterns.
- Keep dependencies patched; pin versions for SaaS penetration patterns components.

### Verification

- Add automated tests and SAST/DAST coverage for SaaS penetration patterns paths.
- Run dependency and secret scanning on every change touching SaaS penetration patterns.
- Perform targeted manual tests (abuse cases) for SaaS penetration patterns.

### Operations

- Log security-relevant events for SaaS penetration patterns without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SaaS penetration patterns.
- Review access and configuration for SaaS penetration patterns on a regular cadence.

