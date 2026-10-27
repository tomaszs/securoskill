# Cloudflare Workers: Zero trust and secure access

Stack-specific implementation for **Cloudflare Workers** (Platform). Normative rules: domain skill `security-zero-trust-access` / `reference.md`.

## Zero trust principles

**Sub-topics:** Never trust network, Explicit verify, Least privilege session, Assume breach, Continuous validation

### Platform rules (summary)

- Validate and canonicalize all inputs touching Zero trust principles; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust principles.
- Keep dependencies patched; pin versions for Zero trust principles components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Zero trust principles before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Zero trust principles paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Device posture

**Sub-topics:** MDM, Disk encryption, Jailbreak detection, Certificate device ID, BYOD

### Platform rules (summary)

- Validate and canonicalize all inputs touching Device posture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Device posture.
- Keep dependencies patched; pin versions for Device posture components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Device posture before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Device posture paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## ZTNA and private access

**Sub-topics:** App connectors, Split tunnel, Exposed admin, Lateral movement, Policy per app

### Platform rules (summary)

- Validate and canonicalize all inputs touching ZTNA and private access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ZTNA and private access.
- Keep dependencies patched; pin versions for ZTNA and private access components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for ZTNA and private access before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for ZTNA and private access paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Micro-segmentation

**Sub-topics:** East-west firewalls, Identity labels, Default deny, Policy drift, IPv6 gaps

### Platform rules (summary)

- Validate and canonicalize all inputs touching Micro-segmentation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Micro-segmentation.
- Keep dependencies patched; pin versions for Micro-segmentation components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Micro-segmentation before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Micro-segmentation paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Service mesh identity

**Sub-topics:** SPIFFE IDs, mTLS STRICT, Authorization policies, Egress gateways, Waypoint proxies

### Platform rules (summary)

- Validate and canonicalize all inputs touching Service mesh identity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service mesh identity.
- Keep dependencies patched; pin versions for Service mesh identity components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Service mesh identity before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Service mesh identity paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Privileged access management

**Sub-topics:** Just-in-time, Session recording, Break glass, Vaulted creds, Approval workflows

### Platform rules (summary)

- Validate and canonicalize all inputs touching Privileged access management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Privileged access management.
- Keep dependencies patched; pin versions for Privileged access management components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Privileged access management before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Privileged access management paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Conditional access policies

**Sub-topics:** Geo block, Risk score, Compliant device, Legacy auth block, Token protection

### Platform rules (summary)

- Validate and canonicalize all inputs touching Conditional access policies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Conditional access policies.
- Keep dependencies patched; pin versions for Conditional access policies components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Conditional access policies before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Conditional access policies paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Bastion-less admin

**Sub-topics:** SSO to cloud, IAM Identity Center, Short-lived creds, Audit trails, IP pinning pitfalls

### Platform rules (summary)

- Validate and canonicalize all inputs touching Bastion-less admin; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bastion-less admin.
- Keep dependencies patched; pin versions for Bastion-less admin components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Bastion-less admin before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Bastion-less admin paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Workload identity federation

**Sub-topics:** OIDC to cloud, GitHub Actions, K8s service accounts, Token exchange, Audience binding

### Platform rules (summary)

- Validate and canonicalize all inputs touching Workload identity federation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Workload identity federation.
- Keep dependencies patched; pin versions for Workload identity federation components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Workload identity federation before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Workload identity federation paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Network device trust

**Sub-topics:** 802.1X, NAC, Guest Wi-Fi isolation, Printer VLANs, IoT segmentation

### Platform rules (summary)

- Validate and canonicalize all inputs touching Network device trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Network device trust.
- Keep dependencies patched; pin versions for Network device trust components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Network device trust before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Network device trust paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Remote work access

**Sub-topics:** VPN alternatives, VDI, Clipboard exfil, Screen share, Home network risk

### Platform rules (summary)

- Validate and canonicalize all inputs touching Remote work access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Remote work access.
- Keep dependencies patched; pin versions for Remote work access components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Remote work access before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Remote work access paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

## Zero trust measurement

**Sub-topics:** Coverage metrics, Policy exceptions, Shadow IT, Unmanaged assets, Phishing resilience

### Platform rules (summary)

- Validate and canonicalize all inputs touching Zero trust measurement; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Zero trust measurement.
- Keep dependencies patched; pin versions for Zero trust measurement components.

### How to do this in Cloudflare Workers

- Read normative rules in domain skill `security-zero-trust-access` / `reference.md`, then apply them using Cloudflare Workers APIs and deployment model.
- Prefer framework-maintained security features in Cloudflare Workers over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Zero trust measurement before merge.
- Pin Cloudflare Workers dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Zero trust measurement paths in Cloudflare Workers.
- Run SAST/dependency scan configured for Platform.

