# Vue.js: Zero trust and secure access

Stack-specific implementation for **Vue.js** (Web UI). Normative rules: domain skill `security-zero-trust-access` / `reference.md`.

## Zero trust principles

**Sub-topics:** Never trust network, Explicit verify, Least privilege session, Assume breach, Continuous validation

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Device posture

**Sub-topics:** MDM, Disk encryption, Jailbreak detection, Certificate device ID, BYOD

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## ZTNA and private access

**Sub-topics:** App connectors, Split tunnel, Exposed admin, Lateral movement, Policy per app

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Micro-segmentation

**Sub-topics:** East-west firewalls, Identity labels, Default deny, Policy drift, IPv6 gaps

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Service mesh identity

**Sub-topics:** SPIFFE IDs, mTLS STRICT, Authorization policies, Egress gateways, Waypoint proxies

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Privileged access management

**Sub-topics:** Just-in-time, Session recording, Break glass, Vaulted creds, Approval workflows

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Conditional access policies

**Sub-topics:** Geo block, Risk score, Compliant device, Legacy auth block, Token protection

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Bastion-less admin

**Sub-topics:** SSO to cloud, IAM Identity Center, Short-lived creds, Audit trails, IP pinning pitfalls

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Workload identity federation

**Sub-topics:** OIDC to cloud, GitHub Actions, K8s service accounts, Token exchange, Audience binding

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Network device trust

**Sub-topics:** 802.1X, NAC, Guest Wi-Fi isolation, Printer VLANs, IoT segmentation

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Remote work access

**Sub-topics:** VPN alternatives, VDI, Clipboard exfil, Screen share, Home network risk

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

## Zero trust measurement

**Sub-topics:** Coverage metrics, Policy exceptions, Shadow IT, Unmanaged assets, Phishing resilience

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `zero-trust-access`; load stack skill `security-zero-trust-access` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-zero-trust-access` (domain reference.md).

### Don't

- Do not duplicate `zero-trust-access` controls only in Vue.js config while leaving security-zero-trust-access misconfigured.
- Do not assume Vue.js defaults satisfy `security-zero-trust-access` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `security-zero-trust-access`.

