# Amazon Web Services: Zero trust and secure access

Stack-specific implementation for **Amazon Web Services** (Cloud). Normative rules: domain skill `security-zero-trust-access` / `reference.md`.

## Zero trust principles

**Sub-topics:** Never trust network, Explicit verify, Least privilege session, Assume breach, Continuous validation

### Do (use this in Amazon Web Services)

- Map `Zero trust principles` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Zero trust principles` before merge.

### Don't

- Do not ship `Zero trust principles` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Zero trust principles`.

### Verify

- Peer review `Zero trust principles` against domain skill `security-zero-trust-access`.

## Device posture

**Sub-topics:** MDM, Disk encryption, Jailbreak detection, Certificate device ID, BYOD

### Do (use this in Amazon Web Services)

- Map `Device posture` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Device posture` before merge.

### Don't

- Do not ship `Device posture` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Device posture`.

### Verify

- Peer review `Device posture` against domain skill `security-zero-trust-access`.

## ZTNA and private access

**Sub-topics:** App connectors, Split tunnel, Exposed admin, Lateral movement, Policy per app

### Do (use this in Amazon Web Services)

- Map `ZTNA and private access` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `ZTNA and private access` before merge.

### Don't

- Do not ship `ZTNA and private access` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `ZTNA and private access`.

### Verify

- Peer review `ZTNA and private access` against domain skill `security-zero-trust-access`.

## Micro-segmentation

**Sub-topics:** East-west firewalls, Identity labels, Default deny, Policy drift, IPv6 gaps

### Do (use this in Amazon Web Services)

- Map `Micro-segmentation` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Micro-segmentation` before merge.

### Don't

- Do not ship `Micro-segmentation` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Micro-segmentation`.

### Verify

- Peer review `Micro-segmentation` against domain skill `security-zero-trust-access`.

## Service mesh identity

**Sub-topics:** SPIFFE IDs, mTLS STRICT, Authorization policies, Egress gateways, Waypoint proxies

### Do (use this in Amazon Web Services)

- Map `Service mesh identity` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Service mesh identity` before merge.

### Don't

- Do not ship `Service mesh identity` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Service mesh identity`.

### Verify

- Peer review `Service mesh identity` against domain skill `security-zero-trust-access`.

## Privileged access management

**Sub-topics:** Just-in-time, Session recording, Break glass, Vaulted creds, Approval workflows

### Do (use this in Amazon Web Services)

- Map `Privileged access management` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Privileged access management` before merge.

### Don't

- Do not ship `Privileged access management` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Privileged access management`.

### Verify

- Peer review `Privileged access management` against domain skill `security-zero-trust-access`.

## Conditional access policies

**Sub-topics:** Geo block, Risk score, Compliant device, Legacy auth block, Token protection

### Do (use this in Amazon Web Services)

- Map `Conditional access policies` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Conditional access policies` before merge.

### Don't

- Do not ship `Conditional access policies` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Conditional access policies`.

### Verify

- Peer review `Conditional access policies` against domain skill `security-zero-trust-access`.

## Bastion-less admin

**Sub-topics:** SSO to cloud, IAM Identity Center, Short-lived creds, Audit trails, IP pinning pitfalls

### Do (use this in Amazon Web Services)

- Map `Bastion-less admin` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Bastion-less admin` before merge.

### Don't

- Do not ship `Bastion-less admin` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Bastion-less admin`.

### Verify

- Peer review `Bastion-less admin` against domain skill `security-zero-trust-access`.

## Workload identity federation

**Sub-topics:** OIDC to cloud, GitHub Actions, K8s service accounts, Token exchange, Audience binding

### Do (use this in Amazon Web Services)

- Map `Workload identity federation` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Workload identity federation` before merge.

### Don't

- Do not ship `Workload identity federation` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Workload identity federation`.

### Verify

- Peer review `Workload identity federation` against domain skill `security-zero-trust-access`.

## Network device trust

**Sub-topics:** 802.1X, NAC, Guest Wi-Fi isolation, Printer VLANs, IoT segmentation

### Do (use this in Amazon Web Services)

- Map `Network device trust` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Network device trust` before merge.

### Don't

- Do not ship `Network device trust` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Network device trust`.

### Verify

- Peer review `Network device trust` against domain skill `security-zero-trust-access`.

## Remote work access

**Sub-topics:** VPN alternatives, VDI, Clipboard exfil, Screen share, Home network risk

### Do (use this in Amazon Web Services)

- Map `Remote work access` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Remote work access` before merge.

### Don't

- Do not ship `Remote work access` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Remote work access`.

### Verify

- Peer review `Remote work access` against domain skill `security-zero-trust-access`.

## Zero trust measurement

**Sub-topics:** Coverage metrics, Policy exceptions, Shadow IT, Unmanaged assets, Phishing resilience

### Do (use this in Amazon Web Services)

- Map `Zero trust measurement` controls to Amazon Web Services APIs documented for `security-zero-trust-access`.
- Add an abuse-case test or check for `Zero trust measurement` before merge.

### Don't

- Do not ship `Zero trust measurement` work in Amazon Web Services with only happy-path tests.
- Do not disable Amazon Web Services security defaults to unblock `Zero trust measurement`.

### Verify

- Peer review `Zero trust measurement` against domain skill `security-zero-trust-access`.

