# Amazon Web Services: Human factors, social engineering, and support abuse

Stack-specific implementation for **Amazon Web Services** (Cloud). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in Amazon Web Services)

- Document how Amazon Web Services engineers report suspicious dependency or CI messages.

### Don't

- Do not merge urgent 'hotfix' PRs that only change lockfiles without review.

### Verify

- Annual phishing simulation includes fake package/CI scenarios.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in Amazon Web Services)

- Align Amazon Web Services with org support playbook: verify caller identity before account changes.

### Don't

- Do not train staff to bypass MFA for VIP customers.

### Verify

- Quarterly tabletop: fake support chat attempting account takeover.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in Amazon Web Services)

- Publish official Amazon Web Services on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy Amazon Web Services.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in Amazon Web Services)

- Remove kubeconfig / cloud CLI keys on offboarding; rotate CI deploy keys quarterly.
- Use just-in-time elevation for production changes to Amazon Web Services clusters.

### Don't

- Do not leave former employees in `cluster-admin` or cloud Owner groups.

### Verify

- Access review export from IAM/K8s RBAC matched to HR terminations.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in Amazon Web Services)

- Lock laptops running Amazon Web Services IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in Amazon Web Services)

- Include Amazon Web Services-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

