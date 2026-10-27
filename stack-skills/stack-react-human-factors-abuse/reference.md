# React: Human factors, social engineering, and support abuse

Stack-specific implementation for **React** (Web UI). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in React)

- Use lockfile-only installs (`npm ci` / `pnpm i --frozen-lockfile`) in React CI.
- Enable Dependabot/Renovate with required status checks before merge.
- Require code review for any dependency that adds `postinstall` scripts.

### Don't

- Do not install packages from typosquatted names (`react-domm`, `@types/nodee`).
- Do not approve GitHub OAuth apps requesting `repo` or `workflow` from unknown vendors.

### Verify

- Run `npm audit --audit-level=high` (or pnpm equivalent) as a merge gate.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in React)

- Mask email/phone in React support-facing UI; reveal full values only after re-auth.
- Never render password-reset or magic links in client-side logs or analytics.

### Don't

- Do not store support impersonation tokens in localStorage.
- Do not show 'click here to login as user' links in the browser bundle.

### Verify

- E2E: support view cannot read another user's PII without server-approved session.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in React)

- Publish official React on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy React.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in React)

- Scope React production credentials per engineer; no shared `.env` files in chat.
- Monitor anomalous git pushes and package publishes from service accounts.

### Don't

- Do not leave production API keys in personal dotfiles repos.

### Verify

- SIEM rule: first-time access to prod secrets from new workstation.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in React)

- Lock laptops running React IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in React)

- Include React-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

## Incident communications

**Sub-topics:** Status page accuracy, Rumor control, Legal hold comms, Customer notification, Media leaks

### Do (use this in React)

- Map `Incident communications` controls to React APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Incident communications` before merge.

### Don't

- Do not ship `Incident communications` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Incident communications`.

### Verify

- Peer review `Incident communications` against domain skill `security-human-factors-abuse`.

## Bug bounty operations

**Sub-topics:** Researcher relations, Safe harbor, Duplicate handling, SLA payouts, Disclosure timelines

### Do (use this in React)

- Map `Bug bounty operations` controls to React APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Bug bounty operations` before merge.

### Don't

- Do not ship `Bug bounty operations` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Bug bounty operations`.

### Verify

- Peer review `Bug bounty operations` against domain skill `security-human-factors-abuse`.

## Law enforcement requests

**Sub-topics:** Subpoena validation, Emergency disclosure, Transparency reports, User notice, National security

### Do (use this in React)

- Map `Law enforcement requests` controls to React APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Law enforcement requests` before merge.

### Don't

- Do not ship `Law enforcement requests` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Law enforcement requests`.

### Verify

- Peer review `Law enforcement requests` against domain skill `security-human-factors-abuse`.

## Social engineering of login flows

**Sub-topics:** Fake OAuth apps, Consent screen tricks, Passwordless confusion, Magic link forwarding, QR login

### Do (use this in React)

- Map `Social engineering of login flows` controls to React APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Social engineering of login flows` before merge.

### Don't

- Do not ship `Social engineering of login flows` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Social engineering of login flows`.

### Verify

- Peer review `Social engineering of login flows` against domain skill `security-human-factors-abuse`.

## Documentation and wiki leaks

**Sub-topics:** Public Confluence, Pastebin creds, Runbooks with secrets, Architecture diagrams, Zoom recordings

### Do (use this in React)

- Map `Documentation and wiki leaks` controls to React APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `Documentation and wiki leaks` before merge.

### Don't

- Do not ship `Documentation and wiki leaks` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `Documentation and wiki leaks`.

### Verify

- Peer review `Documentation and wiki leaks` against domain skill `security-human-factors-abuse`.

## BPO and outsourced access

**Sub-topics:** VPN accounts, Time-bound access, Screen monitoring, Data handling, Contract clauses

### Do (use this in React)

- Map `BPO and outsourced access` controls to React APIs documented for `security-human-factors-abuse`.
- Add an abuse-case test or check for `BPO and outsourced access` before merge.

### Don't

- Do not ship `BPO and outsourced access` work in React with only happy-path tests.
- Do not disable React security defaults to unblock `BPO and outsourced access`.

### Verify

- Peer review `BPO and outsourced access` against domain skill `security-human-factors-abuse`.

