# Docker: Human factors, social engineering, and support abuse

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-human-factors-abuse` / `reference.md`.

## Developer phishing

**Sub-topics:** Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Customer support takeover

**Sub-topics:** Security questions, SIM swap, Email change, Manual password reset, VIP support

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Vishing and impersonation

**Sub-topics:** CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Insider threat

**Sub-topics:** Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Physical access to dev assets

**Sub-topics:** Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Security awareness

**Sub-topics:** Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Incident communications

**Sub-topics:** Status page accuracy, Rumor control, Legal hold comms, Customer notification, Media leaks

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Bug bounty operations

**Sub-topics:** Researcher relations, Safe harbor, Duplicate handling, SLA payouts, Disclosure timelines

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Law enforcement requests

**Sub-topics:** Subpoena validation, Emergency disclosure, Transparency reports, User notice, National security

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Social engineering of login flows

**Sub-topics:** Fake OAuth apps, Consent screen tricks, Passwordless confusion, Magic link forwarding, QR login

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Documentation and wiki leaks

**Sub-topics:** Public Confluence, Pastebin creds, Runbooks with secrets, Architecture diagrams, Zoom recordings

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## BPO and outsourced access

**Sub-topics:** VPN accounts, Time-bound access, Screen monitoring, Data handling, Contract clauses

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

