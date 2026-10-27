# Kubernetes: Human factors, social engineering, and support abuse

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in Kubernetes)

- Document how Kubernetes engineers report suspicious dependency or CI messages.

### Don't

- Do not merge urgent 'hotfix' PRs that only change lockfiles without review.

### Verify

- Annual phishing simulation includes fake package/CI scenarios.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in Kubernetes)

- Align Kubernetes with org support playbook: verify caller identity before account changes.

### Don't

- Do not train staff to bypass MFA for VIP customers.

### Verify

- Quarterly tabletop: fake support chat attempting account takeover.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in Kubernetes)

- Publish official Kubernetes on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy Kubernetes.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in Kubernetes)

- Remove kubeconfig / cloud CLI keys on offboarding; rotate CI deploy keys quarterly.
- Use just-in-time elevation for production changes to Kubernetes clusters.

### Don't

- Do not leave former employees in `cluster-admin` or cloud Owner groups.

### Verify

- Access review export from IAM/K8s RBAC matched to HR terminations.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in Kubernetes)

- Lock laptops running Kubernetes IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in Kubernetes)

- Include Kubernetes-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

## Incident communications

**Sub-topics:** Status page accuracy, Rumor control, Legal hold comms, Customer notification, Media leaks

### Do (use this in Kubernetes)

- Map `Incident communications` controls to Kubernetes APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Incident communications` before merge.

### Don't

- Do not ship `Incident communications` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Incident communications`.

### Verify

- Peer review `Incident communications` against domain skill `security-human-factors-abuse`.

## Bug bounty operations

**Sub-topics:** Researcher relations, Safe harbor, Duplicate handling, SLA payouts, Disclosure timelines

### Do (use this in Kubernetes)

- Map `Bug bounty operations` controls to Kubernetes APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Bug bounty operations` before merge.

### Don't

- Do not ship `Bug bounty operations` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Bug bounty operations`.

### Verify

- Peer review `Bug bounty operations` against domain skill `security-human-factors-abuse`.

## Law enforcement requests

**Sub-topics:** Subpoena validation, Emergency disclosure, Transparency reports, User notice, National security

### Do (use this in Kubernetes)

- Map `Law enforcement requests` controls to Kubernetes APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Law enforcement requests` before merge.

### Don't

- Do not ship `Law enforcement requests` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Law enforcement requests`.

### Verify

- Peer review `Law enforcement requests` against domain skill `security-human-factors-abuse`.

## Social engineering of login flows

**Sub-topics:** Fake OAuth apps, Consent screen tricks, Passwordless confusion, Magic link forwarding, QR login

### Do (use this in Kubernetes)

- Map `Social engineering of login flows` controls to Kubernetes APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Social engineering of login flows` before merge.

### Don't

- Do not ship `Social engineering of login flows` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Social engineering of login flows`.

### Verify

- Peer review `Social engineering of login flows` against domain skill `security-human-factors-abuse`.

## Documentation and wiki leaks

**Sub-topics:** Public Confluence, Pastebin creds, Runbooks with secrets, Architecture diagrams, Zoom recordings

### Do (use this in Kubernetes)

- Map `Documentation and wiki leaks` controls to Kubernetes APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Documentation and wiki leaks` before merge.

### Don't

- Do not ship `Documentation and wiki leaks` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Documentation and wiki leaks`.

### Verify

- Peer review `Documentation and wiki leaks` against domain skill `security-human-factors-abuse`.

## BPO and outsourced access

**Sub-topics:** VPN accounts, Time-bound access, Screen monitoring, Data handling, Contract clauses

### Do (use this in Kubernetes)

- Map `BPO and outsourced access` controls to Kubernetes APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `BPO and outsourced access` before merge.

### Don't

- Do not ship `BPO and outsourced access` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `BPO and outsourced access`.

### Verify

- Peer review `BPO and outsourced access` against domain skill `security-human-factors-abuse`.

