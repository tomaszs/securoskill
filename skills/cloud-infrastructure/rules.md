# Rules reference: Cloud and infrastructure security

IaaS/PaaS, IAM, storage, and networking in cloud.

## Cloud IAM

Sub-topics: Overprivileged roles, IAM conditions

### Policy

- Treat Cloud IAM in Cloud IAM as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Cloud IAM (Cloud and infrastructure security).
- Require security review for material changes affecting Cloud IAM.

### Design

- Apply least privilege and defense in depth for Cloud IAM.
- Prefer established patterns and libraries over custom crypto or auth for Cloud IAM.
- Fail closed: deny by default when Cloud IAM cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Cloud IAM; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Cloud IAM.
- Keep dependencies patched; pin versions for Cloud IAM components.

### Verification

- Add automated tests and SAST/DAST coverage for Cloud IAM paths.
- Run dependency and secret scanning on every change touching Cloud IAM.
- Perform targeted manual tests (abuse cases) for Cloud IAM.

### Operations

- Log security-relevant events for Cloud IAM without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Cloud IAM.
- Review access and configuration for Cloud IAM on a regular cadence.

## Object storage buckets

Sub-topics: Public ACLs, Policy mistakes

### Policy

- Treat Object storage buckets in Object storage buckets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Object storage buckets (Cloud and infrastructure security).
- Require security review for material changes affecting Object storage buckets.

### Design

- Apply least privilege and defense in depth for Object storage buckets.
- Prefer established patterns and libraries over custom crypto or auth for Object storage buckets.
- Fail closed: deny by default when Object storage buckets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Object storage buckets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Object storage buckets.
- Keep dependencies patched; pin versions for Object storage buckets components.

### Verification

- Add automated tests and SAST/DAST coverage for Object storage buckets paths.
- Run dependency and secret scanning on every change touching Object storage buckets.
- Perform targeted manual tests (abuse cases) for Object storage buckets.

### Operations

- Log security-relevant events for Object storage buckets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Object storage buckets.
- Review access and configuration for Object storage buckets on a regular cadence.

## Compute instances

Sub-topics: IMDSv2, SSH keys, Metadata

### Policy

- Treat Compute instances in Compute instances as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Compute instances (Cloud and infrastructure security).
- Require security review for material changes affecting Compute instances.

### Design

- Apply least privilege and defense in depth for Compute instances.
- Prefer established patterns and libraries over custom crypto or auth for Compute instances.
- Fail closed: deny by default when Compute instances cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Compute instances; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Compute instances.
- Keep dependencies patched; pin versions for Compute instances components.

### Verification

- Add automated tests and SAST/DAST coverage for Compute instances paths.
- Run dependency and secret scanning on every change touching Compute instances.
- Perform targeted manual tests (abuse cases) for Compute instances.

### Operations

- Log security-relevant events for Compute instances without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Compute instances.
- Review access and configuration for Compute instances on a regular cadence.

## Managed serverless

Sub-topics: Function URLs, Concurrency

### Policy

- Treat Managed serverless in Managed serverless as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Managed serverless (Cloud and infrastructure security).
- Require security review for material changes affecting Managed serverless.

### Design

- Apply least privilege and defense in depth for Managed serverless.
- Prefer established patterns and libraries over custom crypto or auth for Managed serverless.
- Fail closed: deny by default when Managed serverless cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Managed serverless; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Managed serverless.
- Keep dependencies patched; pin versions for Managed serverless components.

### Verification

- Add automated tests and SAST/DAST coverage for Managed serverless paths.
- Run dependency and secret scanning on every change touching Managed serverless.
- Perform targeted manual tests (abuse cases) for Managed serverless.

### Operations

- Log security-relevant events for Managed serverless without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Managed serverless.
- Review access and configuration for Managed serverless on a regular cadence.

## Secrets managers

Sub-topics: Rotation, Access policies

### Policy

- Treat Secrets managers in Secrets managers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secrets managers (Cloud and infrastructure security).
- Require security review for material changes affecting Secrets managers.

### Design

- Apply least privilege and defense in depth for Secrets managers.
- Prefer established patterns and libraries over custom crypto or auth for Secrets managers.
- Fail closed: deny by default when Secrets managers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secrets managers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secrets managers.
- Keep dependencies patched; pin versions for Secrets managers components.

### Verification

- Add automated tests and SAST/DAST coverage for Secrets managers paths.
- Run dependency and secret scanning on every change touching Secrets managers.
- Perform targeted manual tests (abuse cases) for Secrets managers.

### Operations

- Log security-relevant events for Secrets managers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secrets managers.
- Review access and configuration for Secrets managers on a regular cadence.

## VPC and security groups

Sub-topics: 0.0.0.0/0, Peering leaks

### Policy

- Treat VPC and security groups in VPC and security groups as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for VPC and security groups (Cloud and infrastructure security).
- Require security review for material changes affecting VPC and security groups.

### Design

- Apply least privilege and defense in depth for VPC and security groups.
- Prefer established patterns and libraries over custom crypto or auth for VPC and security groups.
- Fail closed: deny by default when VPC and security groups cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching VPC and security groups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPC and security groups.
- Keep dependencies patched; pin versions for VPC and security groups components.

### Verification

- Add automated tests and SAST/DAST coverage for VPC and security groups paths.
- Run dependency and secret scanning on every change touching VPC and security groups.
- Perform targeted manual tests (abuse cases) for VPC and security groups.

### Operations

- Log security-relevant events for VPC and security groups without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in VPC and security groups.
- Review access and configuration for VPC and security groups on a regular cadence.

## Cloud audit logs

Sub-topics: Tampering, Retention

### Policy

- Treat Cloud audit logs in Cloud audit logs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Cloud audit logs (Cloud and infrastructure security).
- Require security review for material changes affecting Cloud audit logs.

### Design

- Apply least privilege and defense in depth for Cloud audit logs.
- Prefer established patterns and libraries over custom crypto or auth for Cloud audit logs.
- Fail closed: deny by default when Cloud audit logs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Cloud audit logs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Cloud audit logs.
- Keep dependencies patched; pin versions for Cloud audit logs components.

### Verification

- Add automated tests and SAST/DAST coverage for Cloud audit logs paths.
- Run dependency and secret scanning on every change touching Cloud audit logs.
- Perform targeted manual tests (abuse cases) for Cloud audit logs.

### Operations

- Log security-relevant events for Cloud audit logs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Cloud audit logs.
- Review access and configuration for Cloud audit logs on a regular cadence.

## Infrastructure as code

Sub-topics: State files, Drift

### Policy

- Treat Infrastructure as code in Infrastructure as code as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Infrastructure as code (Cloud and infrastructure security).
- Require security review for material changes affecting Infrastructure as code.

### Design

- Apply least privilege and defense in depth for Infrastructure as code.
- Prefer established patterns and libraries over custom crypto or auth for Infrastructure as code.
- Fail closed: deny by default when Infrastructure as code cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Infrastructure as code; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Infrastructure as code.
- Keep dependencies patched; pin versions for Infrastructure as code components.

### Verification

- Add automated tests and SAST/DAST coverage for Infrastructure as code paths.
- Run dependency and secret scanning on every change touching Infrastructure as code.
- Perform targeted manual tests (abuse cases) for Infrastructure as code.

### Operations

- Log security-relevant events for Infrastructure as code without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Infrastructure as code.
- Review access and configuration for Infrastructure as code on a regular cadence.

## Multi-cloud identity

Sub-topics: Federation, Key sprawl

### Policy

- Treat Multi-cloud identity in Multi-cloud identity as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Multi-cloud identity (Cloud and infrastructure security).
- Require security review for material changes affecting Multi-cloud identity.

### Design

- Apply least privilege and defense in depth for Multi-cloud identity.
- Prefer established patterns and libraries over custom crypto or auth for Multi-cloud identity.
- Fail closed: deny by default when Multi-cloud identity cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Multi-cloud identity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-cloud identity.
- Keep dependencies patched; pin versions for Multi-cloud identity components.

### Verification

- Add automated tests and SAST/DAST coverage for Multi-cloud identity paths.
- Run dependency and secret scanning on every change touching Multi-cloud identity.
- Perform targeted manual tests (abuse cases) for Multi-cloud identity.

### Operations

- Log security-relevant events for Multi-cloud identity without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Multi-cloud identity.
- Review access and configuration for Multi-cloud identity on a regular cadence.

## SaaS admin consoles

Sub-topics: MFA, SCIM

### Policy

- Treat SaaS admin consoles in SaaS admin consoles as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SaaS admin consoles (Cloud and infrastructure security).
- Require security review for material changes affecting SaaS admin consoles.

### Design

- Apply least privilege and defense in depth for SaaS admin consoles.
- Prefer established patterns and libraries over custom crypto or auth for SaaS admin consoles.
- Fail closed: deny by default when SaaS admin consoles cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SaaS admin consoles; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SaaS admin consoles.
- Keep dependencies patched; pin versions for SaaS admin consoles components.

### Verification

- Add automated tests and SAST/DAST coverage for SaaS admin consoles paths.
- Run dependency and secret scanning on every change touching SaaS admin consoles.
- Perform targeted manual tests (abuse cases) for SaaS admin consoles.

### Operations

- Log security-relevant events for SaaS admin consoles without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SaaS admin consoles.
- Review access and configuration for SaaS admin consoles on a regular cadence.

## CDN and edge

Sub-topics: Cache deception, Origin shield

### Policy

- Treat CDN and edge in CDN and edge as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CDN and edge (Cloud and infrastructure security).
- Require security review for material changes affecting CDN and edge.

### Design

- Apply least privilege and defense in depth for CDN and edge.
- Prefer established patterns and libraries over custom crypto or auth for CDN and edge.
- Fail closed: deny by default when CDN and edge cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CDN and edge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CDN and edge.
- Keep dependencies patched; pin versions for CDN and edge components.

### Verification

- Add automated tests and SAST/DAST coverage for CDN and edge paths.
- Run dependency and secret scanning on every change touching CDN and edge.
- Perform targeted manual tests (abuse cases) for CDN and edge.

### Operations

- Log security-relevant events for CDN and edge without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CDN and edge.
- Review access and configuration for CDN and edge on a regular cadence.

## DR and regions

Sub-topics: Failover security, Data residency

### Policy

- Treat DR and regions in DR and regions as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for DR and regions (Cloud and infrastructure security).
- Require security review for material changes affecting DR and regions.

### Design

- Apply least privilege and defense in depth for DR and regions.
- Prefer established patterns and libraries over custom crypto or auth for DR and regions.
- Fail closed: deny by default when DR and regions cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching DR and regions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DR and regions.
- Keep dependencies patched; pin versions for DR and regions components.

### Verification

- Add automated tests and SAST/DAST coverage for DR and regions paths.
- Run dependency and secret scanning on every change touching DR and regions.
- Perform targeted manual tests (abuse cases) for DR and regions.

### Operations

- Log security-relevant events for DR and regions without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in DR and regions.
- Review access and configuration for DR and regions on a regular cadence.

