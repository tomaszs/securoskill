# Laravel: Human factors, social engineering, and support abuse

Stack-specific implementation for **Laravel** (PHP). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in Laravel)

- Document how Laravel engineers report suspicious dependency or CI messages.

### Don't

- Do not merge urgent 'hotfix' PRs that only change lockfiles without review.

### Verify

- Annual phishing simulation includes fake package/CI scenarios.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in Laravel)

- In Laravel, require step-up auth (MFA or fresh session) before email/phone/password changes.
- Bind support actions to ticket IDs; log actor, customer id, and fields changed.
- Use out-of-band confirmation (SMS to old number) for SIM-sensitive flows.

### Don't

- Do not reset MFA or passwords from a single inbound email without callback verification.
- Do not expose full account recovery tokens in API JSON error messages.
- Do not let support use shared admin passwords without per-user audit trails.

### Verify

- Integration tests: support endpoint without elevated role returns 403.
- Alert on burst of password resets from one support account.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in Laravel)

- Publish official Laravel on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy Laravel.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in Laravel)

- Scope Laravel production credentials per engineer; no shared `.env` files in chat.
- Monitor anomalous git pushes and package publishes from service accounts.

### Don't

- Do not leave production API keys in personal dotfiles repos.

### Verify

- SIEM rule: first-time access to prod secrets from new workstation.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in Laravel)

- Lock laptops running Laravel IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in Laravel)

- Include Laravel-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

## Incident communications

**Sub-topics:** Status page accuracy, Rumor control, Legal hold comms, Customer notification, Media leaks

### Do (use this in Laravel)

- Map `Incident communications` controls to Laravel APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Incident communications` before merge.

### Don't

- Do not ship `Incident communications` work in Laravel with only happy-path tests.
- Do not disable Laravel security defaults to unblock `Incident communications`.

### Verify

- Peer review `Incident communications` against domain skill `security-human-factors-abuse`.

## Bug bounty operations

**Sub-topics:** Researcher relations, Safe harbor, Duplicate handling, SLA payouts, Disclosure timelines

### Do (use this in Laravel)

- Map `Bug bounty operations` controls to Laravel APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Bug bounty operations` before merge.

### Don't

- Do not ship `Bug bounty operations` work in Laravel with only happy-path tests.
- Do not disable Laravel security defaults to unblock `Bug bounty operations`.

### Verify

- Peer review `Bug bounty operations` against domain skill `security-human-factors-abuse`.

## Law enforcement requests

**Sub-topics:** Subpoena validation, Emergency disclosure, Transparency reports, User notice, National security

### Do (use this in Laravel)

- Map `Law enforcement requests` controls to Laravel APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Law enforcement requests` before merge.

### Don't

- Do not ship `Law enforcement requests` work in Laravel with only happy-path tests.
- Do not disable Laravel security defaults to unblock `Law enforcement requests`.

### Verify

- Peer review `Law enforcement requests` against domain skill `security-human-factors-abuse`.

## Social engineering of login flows

**Sub-topics:** Fake OAuth apps, Consent screen tricks, Passwordless confusion, Magic link forwarding, QR login

### Do (use this in Laravel)

- Map `Social engineering of login flows` controls to Laravel APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Social engineering of login flows` before merge.

### Don't

- Do not ship `Social engineering of login flows` work in Laravel with only happy-path tests.
- Do not disable Laravel security defaults to unblock `Social engineering of login flows`.

### Verify

- Peer review `Social engineering of login flows` against domain skill `security-human-factors-abuse`.

## Documentation and wiki leaks

**Sub-topics:** Public Confluence, Pastebin creds, Runbooks with secrets, Architecture diagrams, Zoom recordings

### Do (use this in Laravel)

- Map `Documentation and wiki leaks` controls to Laravel APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Documentation and wiki leaks` before merge.

### Don't

- Do not ship `Documentation and wiki leaks` work in Laravel with only happy-path tests.
- Do not disable Laravel security defaults to unblock `Documentation and wiki leaks`.

### Verify

- Peer review `Documentation and wiki leaks` against domain skill `security-human-factors-abuse`.

## BPO and outsourced access

**Sub-topics:** VPN accounts, Time-bound access, Screen monitoring, Data handling, Contract clauses

### Do (use this in Laravel)

- Map `BPO and outsourced access` controls to Laravel APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `BPO and outsourced access` before merge.

### Don't

- Do not ship `BPO and outsourced access` work in Laravel with only happy-path tests.
- Do not disable Laravel security defaults to unblock `BPO and outsourced access`.

### Verify

- Peer review `BPO and outsourced access` against domain skill `security-human-factors-abuse`.

