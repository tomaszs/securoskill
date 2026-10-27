# SQLAlchemy: Human factors, social engineering, and support abuse

Stack-specific implementation for **SQLAlchemy** (ORM / data access). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in SQLAlchemy)

- Pin hashes in Poetry/pip-tools lockfiles; run `pip-audit` in CI.
- Verify PyPI package owner matches your internal allowlist.

### Don't

- Do not `pip install` from arbitrary git URLs pasted into tickets.

### Verify

- Bandit + dependency scan on every merge touching requirements.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in SQLAlchemy)

- Align SQLAlchemy with org support playbook: verify caller identity before account changes.

### Don't

- Do not train staff to bypass MFA for VIP customers.

### Verify

- Quarterly tabletop: fake support chat attempting account takeover.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in SQLAlchemy)

- Publish official SQLAlchemy on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy SQLAlchemy.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in SQLAlchemy)

- Scope SQLAlchemy production credentials per engineer; no shared `.env` files in chat.
- Monitor anomalous git pushes and package publishes from service accounts.

### Don't

- Do not leave production API keys in personal dotfiles repos.

### Verify

- SIEM rule: first-time access to prod secrets from new workstation.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in SQLAlchemy)

- Lock laptops running SQLAlchemy IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in SQLAlchemy)

- Include SQLAlchemy-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

