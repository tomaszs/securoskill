# FastAPI: Zero trust and secure access

Stack-specific implementation for **FastAPI** (Python). Normative rules: domain skill `security-zero-trust-access` / `reference.md`.

## Zero trust principles

**Sub-topics:** Never trust network, Explicit verify, Least privilege session, Assume breach, Continuous validation

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for zt controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Device posture

**Sub-topics:** MDM, Disk encryption, Jailbreak detection, Certificate device ID, BYOD

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for device_posture controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## ZTNA and private access

**Sub-topics:** App connectors, Split tunnel, Exposed admin, Lateral movement, Policy per app

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for ztna controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Micro-segmentation

**Sub-topics:** East-west firewalls, Identity labels, Default deny, Policy drift, IPv6 gaps

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for microseg controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Service mesh identity

**Sub-topics:** SPIFFE IDs, mTLS STRICT, Authorization policies, Egress gateways, Waypoint proxies

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for mesh_zt controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Privileged access management

**Sub-topics:** Just-in-time, Session recording, Break glass, Vaulted creds, Approval workflows

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for pam controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Conditional access policies

**Sub-topics:** Geo block, Risk score, Compliant device, Legacy auth block, Token protection

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for conditional_access controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Bastion-less admin

**Sub-topics:** SSO to cloud, IAM Identity Center, Short-lived creds, Audit trails, IP pinning pitfalls

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for bastionless controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Workload identity federation

**Sub-topics:** OIDC to cloud, GitHub Actions, K8s service accounts, Token exchange, Audience binding

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for workload_identity controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Network device trust

**Sub-topics:** 802.1X, NAC, Guest Wi-Fi isolation, Printer VLANs, IoT segmentation

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for nac controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Remote work access

**Sub-topics:** VPN alternatives, VDI, Clipboard exfil, Screen share, Home network risk

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for remote_work controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

## Zero trust measurement

**Sub-topics:** Coverage metrics, Policy exceptions, Shadow IT, Unmanaged assets, Phishing resilience

### Do (use this in FastAPI)

- Apply domain skill `security-zero-trust-access` requirements using fastapi supported APIs only.
- Use the official fastapi security documentation for zt_metrics controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastapi for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastapi projects in CI.

