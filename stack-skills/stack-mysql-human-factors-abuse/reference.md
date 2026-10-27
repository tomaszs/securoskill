# MySQL / MariaDB: Human factors, social engineering, and support abuse

Stack-specific implementation for **MySQL / MariaDB** (Database). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in MySQL / MariaDB)

- Rotate MySQL / MariaDB admin credentials via vault; never share superuser passwords in chat.

### Don't

- Do not click vendor emails asking to 'verify' database console login.

### Verify

- MFA enforced on cloud DB console; alert on new admin users.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in MySQL / MariaDB)

- Align MySQL / MariaDB with org support playbook: verify caller identity before account changes.

### Don't

- Do not train staff to bypass MFA for VIP customers.

### Verify

- Quarterly tabletop: fake support chat attempting account takeover.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in MySQL / MariaDB)

- Publish official MySQL / MariaDB on-call and security contact channels on an internal wiki (not DMs).
- Require callback to known numbers for wire transfers, production access, or secret rotation.

### Don't

- Do not share production credentials or break-glass codes on unverified phone or video calls.
- Do not trust caller ID alone for vendor or 'CEO' urgent requests.

### Verify

- Run vishing simulation targeting engineers who deploy MySQL / MariaDB.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in MySQL / MariaDB)

- Disable MySQL / MariaDB logins on offboarding same day; revoke replication and backup roles.
- Alert when DBA exports exceed normal row counts or run outside business hours.

### Don't

- Do not share one break-glass DB user across the team.

### Verify

- Monthly query: active DB users vs HR roster.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in MySQL / MariaDB)

- Lock laptops running MySQL / MariaDB IDEs when away; use hardware security keys for git and cloud.
- Shred or secure-wipe drives before hardware disposal.

### Don't

- Do not plug unknown USB devices into machines with production kubeconfig.

### Verify

- Office walk-through: unattended unlocked dev machines logged as findings.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in MySQL / MariaDB)

- Include MySQL / MariaDB-specific abuse cases (not generic OWASP slides) in onboarding.

### Don't

- Do not treat security training as checkbox-only without stack examples.

### Verify

- Quiz includes a scenario tied to this stack's deployment model.

