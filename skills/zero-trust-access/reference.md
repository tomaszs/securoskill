# Rules reference: Zero trust and secure access

Identity-aware access, device trust, and micro-segmentation.

## Zero trust principles

Sub-topics: Never trust network, Explicit verify, Least privilege session, Assume breach, Continuous validation

### Do

- Validate and canonicalize all inputs touching Zero trust principles; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust principles.
- Keep dependencies patched; pin versions for Zero trust principles components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Zero trust principles in Zero trust principles as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Zero trust principles (Zero trust and secure access).
- Require security review for material changes affecting Zero trust principles.

### Design

- Apply least privilege and defense in depth for Zero trust principles.
- Prefer established patterns and libraries over custom crypto or auth for Zero trust principles.
- Fail closed: deny by default when Zero trust principles cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Zero trust principles; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust principles.
- Keep dependencies patched; pin versions for Zero trust principles components.

### Verification

- Add automated tests and SAST/DAST coverage for Zero trust principles paths.
- Run dependency and secret scanning on every change touching Zero trust principles.
- Perform targeted manual tests (abuse cases) for Zero trust principles.

### Operations

- Log security-relevant events for Zero trust principles without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Zero trust principles.
- Review access and configuration for Zero trust principles on a regular cadence.

## Device posture

Sub-topics: MDM, Disk encryption, Jailbreak detection, Certificate device ID, BYOD

### Do

- Validate and canonicalize all inputs touching Device posture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Device posture.
- Keep dependencies patched; pin versions for Device posture components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Device posture in Device posture as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Device posture (Zero trust and secure access).
- Require security review for material changes affecting Device posture.

### Design

- Apply least privilege and defense in depth for Device posture.
- Prefer established patterns and libraries over custom crypto or auth for Device posture.
- Fail closed: deny by default when Device posture cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Device posture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Device posture.
- Keep dependencies patched; pin versions for Device posture components.

### Verification

- Add automated tests and SAST/DAST coverage for Device posture paths.
- Run dependency and secret scanning on every change touching Device posture.
- Perform targeted manual tests (abuse cases) for Device posture.

### Operations

- Log security-relevant events for Device posture without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Device posture.
- Review access and configuration for Device posture on a regular cadence.

## ZTNA and private access

Sub-topics: App connectors, Split tunnel, Exposed admin, Lateral movement, Policy per app

### Do

- Validate and canonicalize all inputs touching ZTNA and private access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ZTNA and private access.
- Keep dependencies patched; pin versions for ZTNA and private access components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat ZTNA and private access in ZTNA and private access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for ZTNA and private access (Zero trust and secure access).
- Require security review for material changes affecting ZTNA and private access.

### Design

- Apply least privilege and defense in depth for ZTNA and private access.
- Prefer established patterns and libraries over custom crypto or auth for ZTNA and private access.
- Fail closed: deny by default when ZTNA and private access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching ZTNA and private access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ZTNA and private access.
- Keep dependencies patched; pin versions for ZTNA and private access components.

### Verification

- Add automated tests and SAST/DAST coverage for ZTNA and private access paths.
- Run dependency and secret scanning on every change touching ZTNA and private access.
- Perform targeted manual tests (abuse cases) for ZTNA and private access.

### Operations

- Log security-relevant events for ZTNA and private access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in ZTNA and private access.
- Review access and configuration for ZTNA and private access on a regular cadence.

## Micro-segmentation

Sub-topics: East-west firewalls, Identity labels, Default deny, Policy drift, IPv6 gaps

### Do

- Validate and canonicalize all inputs touching Micro-segmentation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Micro-segmentation.
- Keep dependencies patched; pin versions for Micro-segmentation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Micro-segmentation in Micro-segmentation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Micro-segmentation (Zero trust and secure access).
- Require security review for material changes affecting Micro-segmentation.

### Design

- Apply least privilege and defense in depth for Micro-segmentation.
- Prefer established patterns and libraries over custom crypto or auth for Micro-segmentation.
- Fail closed: deny by default when Micro-segmentation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Micro-segmentation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Micro-segmentation.
- Keep dependencies patched; pin versions for Micro-segmentation components.

### Verification

- Add automated tests and SAST/DAST coverage for Micro-segmentation paths.
- Run dependency and secret scanning on every change touching Micro-segmentation.
- Perform targeted manual tests (abuse cases) for Micro-segmentation.

### Operations

- Log security-relevant events for Micro-segmentation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Micro-segmentation.
- Review access and configuration for Micro-segmentation on a regular cadence.

## Service mesh identity

Sub-topics: SPIFFE IDs, mTLS STRICT, Authorization policies, Egress gateways, Waypoint proxies

### Do

- Validate and canonicalize all inputs touching Service mesh identity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service mesh identity.
- Keep dependencies patched; pin versions for Service mesh identity components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Service mesh identity in Service mesh identity as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Service mesh identity (Zero trust and secure access).
- Require security review for material changes affecting Service mesh identity.

### Design

- Apply least privilege and defense in depth for Service mesh identity.
- Prefer established patterns and libraries over custom crypto or auth for Service mesh identity.
- Fail closed: deny by default when Service mesh identity cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Service mesh identity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service mesh identity.
- Keep dependencies patched; pin versions for Service mesh identity components.

### Verification

- Add automated tests and SAST/DAST coverage for Service mesh identity paths.
- Run dependency and secret scanning on every change touching Service mesh identity.
- Perform targeted manual tests (abuse cases) for Service mesh identity.

### Operations

- Log security-relevant events for Service mesh identity without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Service mesh identity.
- Review access and configuration for Service mesh identity on a regular cadence.

## Privileged access management

Sub-topics: Just-in-time, Session recording, Break glass, Vaulted creds, Approval workflows

### Do

- Validate and canonicalize all inputs touching Privileged access management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Privileged access management.
- Keep dependencies patched; pin versions for Privileged access management components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Privileged access management in Privileged access management as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Privileged access management (Zero trust and secure access).
- Require security review for material changes affecting Privileged access management.

### Design

- Apply least privilege and defense in depth for Privileged access management.
- Prefer established patterns and libraries over custom crypto or auth for Privileged access management.
- Fail closed: deny by default when Privileged access management cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Privileged access management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Privileged access management.
- Keep dependencies patched; pin versions for Privileged access management components.

### Verification

- Add automated tests and SAST/DAST coverage for Privileged access management paths.
- Run dependency and secret scanning on every change touching Privileged access management.
- Perform targeted manual tests (abuse cases) for Privileged access management.

### Operations

- Log security-relevant events for Privileged access management without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Privileged access management.
- Review access and configuration for Privileged access management on a regular cadence.

## Conditional access policies

Sub-topics: Geo block, Risk score, Compliant device, Legacy auth block, Token protection

### Do

- Validate and canonicalize all inputs touching Conditional access policies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Conditional access policies.
- Keep dependencies patched; pin versions for Conditional access policies components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Conditional access policies in Conditional access policies as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Conditional access policies (Zero trust and secure access).
- Require security review for material changes affecting Conditional access policies.

### Design

- Apply least privilege and defense in depth for Conditional access policies.
- Prefer established patterns and libraries over custom crypto or auth for Conditional access policies.
- Fail closed: deny by default when Conditional access policies cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Conditional access policies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Conditional access policies.
- Keep dependencies patched; pin versions for Conditional access policies components.

### Verification

- Add automated tests and SAST/DAST coverage for Conditional access policies paths.
- Run dependency and secret scanning on every change touching Conditional access policies.
- Perform targeted manual tests (abuse cases) for Conditional access policies.

### Operations

- Log security-relevant events for Conditional access policies without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Conditional access policies.
- Review access and configuration for Conditional access policies on a regular cadence.

## Bastion-less admin

Sub-topics: SSO to cloud, IAM Identity Center, Short-lived creds, Audit trails, IP pinning pitfalls

### Do

- Validate and canonicalize all inputs touching Bastion-less admin; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bastion-less admin.
- Keep dependencies patched; pin versions for Bastion-less admin components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Bastion-less admin in Bastion-less admin as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Bastion-less admin (Zero trust and secure access).
- Require security review for material changes affecting Bastion-less admin.

### Design

- Apply least privilege and defense in depth for Bastion-less admin.
- Prefer established patterns and libraries over custom crypto or auth for Bastion-less admin.
- Fail closed: deny by default when Bastion-less admin cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Bastion-less admin; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bastion-less admin.
- Keep dependencies patched; pin versions for Bastion-less admin components.

### Verification

- Add automated tests and SAST/DAST coverage for Bastion-less admin paths.
- Run dependency and secret scanning on every change touching Bastion-less admin.
- Perform targeted manual tests (abuse cases) for Bastion-less admin.

### Operations

- Log security-relevant events for Bastion-less admin without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Bastion-less admin.
- Review access and configuration for Bastion-less admin on a regular cadence.

## Workload identity federation

Sub-topics: OIDC to cloud, GitHub Actions, K8s service accounts, Token exchange, Audience binding

### Do

- Validate and canonicalize all inputs touching Workload identity federation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Workload identity federation.
- Keep dependencies patched; pin versions for Workload identity federation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Workload identity federation in Workload identity federation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Workload identity federation (Zero trust and secure access).
- Require security review for material changes affecting Workload identity federation.

### Design

- Apply least privilege and defense in depth for Workload identity federation.
- Prefer established patterns and libraries over custom crypto or auth for Workload identity federation.
- Fail closed: deny by default when Workload identity federation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Workload identity federation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Workload identity federation.
- Keep dependencies patched; pin versions for Workload identity federation components.

### Verification

- Add automated tests and SAST/DAST coverage for Workload identity federation paths.
- Run dependency and secret scanning on every change touching Workload identity federation.
- Perform targeted manual tests (abuse cases) for Workload identity federation.

### Operations

- Log security-relevant events for Workload identity federation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Workload identity federation.
- Review access and configuration for Workload identity federation on a regular cadence.

## Network device trust

Sub-topics: 802.1X, NAC, Guest Wi-Fi isolation, Printer VLANs, IoT segmentation

### Do

- Validate and canonicalize all inputs touching Network device trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Network device trust.
- Keep dependencies patched; pin versions for Network device trust components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Network device trust in Network device trust as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Network device trust (Zero trust and secure access).
- Require security review for material changes affecting Network device trust.

### Design

- Apply least privilege and defense in depth for Network device trust.
- Prefer established patterns and libraries over custom crypto or auth for Network device trust.
- Fail closed: deny by default when Network device trust cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Network device trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Network device trust.
- Keep dependencies patched; pin versions for Network device trust components.

### Verification

- Add automated tests and SAST/DAST coverage for Network device trust paths.
- Run dependency and secret scanning on every change touching Network device trust.
- Perform targeted manual tests (abuse cases) for Network device trust.

### Operations

- Log security-relevant events for Network device trust without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Network device trust.
- Review access and configuration for Network device trust on a regular cadence.

## Remote work access

Sub-topics: VPN alternatives, VDI, Clipboard exfil, Screen share, Home network risk

### Do

- Validate and canonicalize all inputs touching Remote work access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Remote work access.
- Keep dependencies patched; pin versions for Remote work access components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Remote work access in Remote work access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Remote work access (Zero trust and secure access).
- Require security review for material changes affecting Remote work access.

### Design

- Apply least privilege and defense in depth for Remote work access.
- Prefer established patterns and libraries over custom crypto or auth for Remote work access.
- Fail closed: deny by default when Remote work access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Remote work access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Remote work access.
- Keep dependencies patched; pin versions for Remote work access components.

### Verification

- Add automated tests and SAST/DAST coverage for Remote work access paths.
- Run dependency and secret scanning on every change touching Remote work access.
- Perform targeted manual tests (abuse cases) for Remote work access.

### Operations

- Log security-relevant events for Remote work access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Remote work access.
- Review access and configuration for Remote work access on a regular cadence.

## Zero trust measurement

Sub-topics: Coverage metrics, Policy exceptions, Shadow IT, Unmanaged assets, Phishing resilience

### Do

- Validate and canonicalize all inputs touching Zero trust measurement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust measurement.
- Keep dependencies patched; pin versions for Zero trust measurement components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Zero trust measurement in Zero trust measurement as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Zero trust measurement (Zero trust and secure access).
- Require security review for material changes affecting Zero trust measurement.

### Design

- Apply least privilege and defense in depth for Zero trust measurement.
- Prefer established patterns and libraries over custom crypto or auth for Zero trust measurement.
- Fail closed: deny by default when Zero trust measurement cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Zero trust measurement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust measurement.
- Keep dependencies patched; pin versions for Zero trust measurement components.

### Verification

- Add automated tests and SAST/DAST coverage for Zero trust measurement paths.
- Run dependency and secret scanning on every change touching Zero trust measurement.
- Perform targeted manual tests (abuse cases) for Zero trust measurement.

### Operations

- Log security-relevant events for Zero trust measurement without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Zero trust measurement.
- Review access and configuration for Zero trust measurement on a regular cadence.

