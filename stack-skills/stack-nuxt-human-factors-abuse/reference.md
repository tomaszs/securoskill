# Nuxt: Human factors, social engineering, and support abuse

Stack-specific implementation for **Nuxt** (Web UI). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in Nuxt)

- Use lockfile-only installs (`npm ci` / `pnpm i --frozen-lockfile`) in Nuxt CI.
- Enable Dependabot/Renovate with required status checks before merge.
- Require code review for any dependency that adds `postinstall` scripts.

### Don't

- Do not install packages from typosquatted names (`react-domm`, `@types/nodee`).
- Do not approve GitHub OAuth apps requesting `repo` or `workflow` from unknown vendors.

### Verify

- Run `npm audit --audit-level=high` (or pnpm equivalent) as a merge gate.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in Nuxt)

- In Nuxt, require step-up auth (MFA or fresh session) before email/phone/password changes.
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

### Do (use this in Nuxt)

- Publish official Nuxt on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy Nuxt.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in Nuxt)

- Scope Nuxt production credentials per engineer; no shared `.env` files in chat.
- Monitor anomalous git pushes and package publishes from service accounts.

### Don't

- Do not leave production API keys in personal dotfiles repos.

### Verify

- SIEM rule: first-time access to prod secrets from new workstation.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in Nuxt)

- Lock laptops running Nuxt IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in Nuxt)

- Include Nuxt-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

