# Flutter: Human factors, social engineering, and support abuse

Stack-specific implementation for **Flutter** (Mobile). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in Flutter)

- Document how Flutter engineers report suspicious dependency or CI messages.

### Don't

- Do not merge urgent 'hotfix' PRs that only change lockfiles without review.

### Verify

- Annual phishing simulation includes fake package/CI scenarios.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in Flutter)

- Align Flutter with org support playbook: verify caller identity before account changes.

### Don't

- Do not train staff to bypass MFA for VIP customers.

### Verify

- Quarterly tabletop: fake support chat attempting account takeover.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in Flutter)

- Publish official Flutter on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy Flutter.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in Flutter)

- Scope Flutter production credentials per engineer; no shared `.env` files in chat.
- Monitor anomalous git pushes and package publishes from service accounts.

### Don't

- Do not leave production API keys in personal dotfiles repos.

### Verify

- SIEM rule: first-time access to prod secrets from new workstation.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in Flutter)

- Require device passcode/biometric; use MDM to remote-wipe lost dev phones with Flutter builds.

### Don't

- Do not leave TestFlight/APK builds on unlocked desks.

### Verify

- MDM compliance report monthly.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in Flutter)

- Include Flutter-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

