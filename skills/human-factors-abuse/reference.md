# Rules reference: Human factors, social engineering, and support abuse

People, process, and support-channel risks in software delivery.

## Developer phishing

Sub-topics: Fake npm, Malicious PR, Stolen OAuth, Slack DMs, Fake CI notifications

### Policy

- Treat Developer phishing in Developer phishing as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Developer phishing (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Developer phishing.

### Design

- Apply least privilege and defense in depth for Developer phishing.
- Prefer established patterns and libraries over custom crypto or auth for Developer phishing.
- Fail closed: deny by default when Developer phishing cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Developer phishing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Developer phishing.
- Keep dependencies patched; pin versions for Developer phishing components.

### Verification

- Add automated tests and SAST/DAST coverage for Developer phishing paths.
- Run dependency and secret scanning on every change touching Developer phishing.
- Perform targeted manual tests (abuse cases) for Developer phishing.

### Operations

- Log security-relevant events for Developer phishing without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Developer phishing.
- Review access and configuration for Developer phishing on a regular cadence.

## Customer support takeover

Sub-topics: Security questions, SIM swap, Email change, Manual password reset, VIP support

### Policy

- Treat Customer support takeover in Customer support takeover as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Customer support takeover (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Customer support takeover.

### Design

- Apply least privilege and defense in depth for Customer support takeover.
- Prefer established patterns and libraries over custom crypto or auth for Customer support takeover.
- Fail closed: deny by default when Customer support takeover cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Customer support takeover; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Customer support takeover.
- Keep dependencies patched; pin versions for Customer support takeover components.

### Verification

- Add automated tests and SAST/DAST coverage for Customer support takeover paths.
- Run dependency and secret scanning on every change touching Customer support takeover.
- Perform targeted manual tests (abuse cases) for Customer support takeover.

### Operations

- Log security-relevant events for Customer support takeover without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Customer support takeover.
- Review access and configuration for Customer support takeover on a regular cadence.

## Vishing and impersonation

Sub-topics: CEO fraud, Vendor impersonation, Callback phishing, Deepfake calls, Help desk pressure

### Policy

- Treat Vishing and impersonation in Vishing and impersonation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Vishing and impersonation (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Vishing and impersonation.

### Design

- Apply least privilege and defense in depth for Vishing and impersonation.
- Prefer established patterns and libraries over custom crypto or auth for Vishing and impersonation.
- Fail closed: deny by default when Vishing and impersonation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Vishing and impersonation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vishing and impersonation.
- Keep dependencies patched; pin versions for Vishing and impersonation components.

### Verification

- Add automated tests and SAST/DAST coverage for Vishing and impersonation paths.
- Run dependency and secret scanning on every change touching Vishing and impersonation.
- Perform targeted manual tests (abuse cases) for Vishing and impersonation.

### Operations

- Log security-relevant events for Vishing and impersonation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Vishing and impersonation.
- Review access and configuration for Vishing and impersonation on a regular cadence.

## Insider threat

Sub-topics: Offboarding gaps, Privileged monitoring, Data exfil jobs, Sabotage, Whistleblower channels

### Policy

- Treat Insider threat in Insider threat as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Insider threat (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Insider threat.

### Design

- Apply least privilege and defense in depth for Insider threat.
- Prefer established patterns and libraries over custom crypto or auth for Insider threat.
- Fail closed: deny by default when Insider threat cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Insider threat; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insider threat.
- Keep dependencies patched; pin versions for Insider threat components.

### Verification

- Add automated tests and SAST/DAST coverage for Insider threat paths.
- Run dependency and secret scanning on every change touching Insider threat.
- Perform targeted manual tests (abuse cases) for Insider threat.

### Operations

- Log security-relevant events for Insider threat without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Insider threat.
- Review access and configuration for Insider threat on a regular cadence.

## Physical access to dev assets

Sub-topics: Unattended laptops, USB drops, Office tailgating, Printer rooms, Hardware tokens

### Policy

- Treat Physical access to dev assets in Physical access to dev assets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Physical access to dev assets (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Physical access to dev assets.

### Design

- Apply least privilege and defense in depth for Physical access to dev assets.
- Prefer established patterns and libraries over custom crypto or auth for Physical access to dev assets.
- Fail closed: deny by default when Physical access to dev assets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Physical access to dev assets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Physical access to dev assets.
- Keep dependencies patched; pin versions for Physical access to dev assets components.

### Verification

- Add automated tests and SAST/DAST coverage for Physical access to dev assets paths.
- Run dependency and secret scanning on every change touching Physical access to dev assets.
- Perform targeted manual tests (abuse cases) for Physical access to dev assets.

### Operations

- Log security-relevant events for Physical access to dev assets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Physical access to dev assets.
- Review access and configuration for Physical access to dev assets on a regular cadence.

## Security awareness

Sub-topics: Phishing sims, Report buttons, Metrics, Role-based training, Contractors

### Policy

- Treat Security awareness in Security awareness as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Security awareness (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Security awareness.

### Design

- Apply least privilege and defense in depth for Security awareness.
- Prefer established patterns and libraries over custom crypto or auth for Security awareness.
- Fail closed: deny by default when Security awareness cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Security awareness; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security awareness.
- Keep dependencies patched; pin versions for Security awareness components.

### Verification

- Add automated tests and SAST/DAST coverage for Security awareness paths.
- Run dependency and secret scanning on every change touching Security awareness.
- Perform targeted manual tests (abuse cases) for Security awareness.

### Operations

- Log security-relevant events for Security awareness without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Security awareness.
- Review access and configuration for Security awareness on a regular cadence.

## Incident communications

Sub-topics: Status page accuracy, Rumor control, Legal hold comms, Customer notification, Media leaks

### Policy

- Treat Incident communications in Incident communications as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Incident communications (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Incident communications.

### Design

- Apply least privilege and defense in depth for Incident communications.
- Prefer established patterns and libraries over custom crypto or auth for Incident communications.
- Fail closed: deny by default when Incident communications cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Incident communications; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Incident communications.
- Keep dependencies patched; pin versions for Incident communications components.

### Verification

- Add automated tests and SAST/DAST coverage for Incident communications paths.
- Run dependency and secret scanning on every change touching Incident communications.
- Perform targeted manual tests (abuse cases) for Incident communications.

### Operations

- Log security-relevant events for Incident communications without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Incident communications.
- Review access and configuration for Incident communications on a regular cadence.

## Bug bounty operations

Sub-topics: Researcher relations, Safe harbor, Duplicate handling, SLA payouts, Disclosure timelines

### Policy

- Treat Bug bounty operations in Bug bounty operations as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Bug bounty operations (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Bug bounty operations.

### Design

- Apply least privilege and defense in depth for Bug bounty operations.
- Prefer established patterns and libraries over custom crypto or auth for Bug bounty operations.
- Fail closed: deny by default when Bug bounty operations cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Bug bounty operations; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bug bounty operations.
- Keep dependencies patched; pin versions for Bug bounty operations components.

### Verification

- Add automated tests and SAST/DAST coverage for Bug bounty operations paths.
- Run dependency and secret scanning on every change touching Bug bounty operations.
- Perform targeted manual tests (abuse cases) for Bug bounty operations.

### Operations

- Log security-relevant events for Bug bounty operations without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Bug bounty operations.
- Review access and configuration for Bug bounty operations on a regular cadence.

## Law enforcement requests

Sub-topics: Subpoena validation, Emergency disclosure, Transparency reports, User notice, National security

### Policy

- Treat Law enforcement requests in Law enforcement requests as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Law enforcement requests (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Law enforcement requests.

### Design

- Apply least privilege and defense in depth for Law enforcement requests.
- Prefer established patterns and libraries over custom crypto or auth for Law enforcement requests.
- Fail closed: deny by default when Law enforcement requests cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Law enforcement requests; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Law enforcement requests.
- Keep dependencies patched; pin versions for Law enforcement requests components.

### Verification

- Add automated tests and SAST/DAST coverage for Law enforcement requests paths.
- Run dependency and secret scanning on every change touching Law enforcement requests.
- Perform targeted manual tests (abuse cases) for Law enforcement requests.

### Operations

- Log security-relevant events for Law enforcement requests without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Law enforcement requests.
- Review access and configuration for Law enforcement requests on a regular cadence.

## Social engineering of login flows

Sub-topics: Fake OAuth apps, Consent screen tricks, Passwordless confusion, Magic link forwarding, QR login

### Policy

- Treat Social engineering of login flows in Social engineering of login flows as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Social engineering of login flows (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Social engineering of login flows.

### Design

- Apply least privilege and defense in depth for Social engineering of login flows.
- Prefer established patterns and libraries over custom crypto or auth for Social engineering of login flows.
- Fail closed: deny by default when Social engineering of login flows cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Social engineering of login flows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Social engineering of login flows.
- Keep dependencies patched; pin versions for Social engineering of login flows components.

### Verification

- Add automated tests and SAST/DAST coverage for Social engineering of login flows paths.
- Run dependency and secret scanning on every change touching Social engineering of login flows.
- Perform targeted manual tests (abuse cases) for Social engineering of login flows.

### Operations

- Log security-relevant events for Social engineering of login flows without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Social engineering of login flows.
- Review access and configuration for Social engineering of login flows on a regular cadence.

## Documentation and wiki leaks

Sub-topics: Public Confluence, Pastebin creds, Runbooks with secrets, Architecture diagrams, Zoom recordings

### Policy

- Treat Documentation and wiki leaks in Documentation and wiki leaks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Documentation and wiki leaks (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting Documentation and wiki leaks.

### Design

- Apply least privilege and defense in depth for Documentation and wiki leaks.
- Prefer established patterns and libraries over custom crypto or auth for Documentation and wiki leaks.
- Fail closed: deny by default when Documentation and wiki leaks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Documentation and wiki leaks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Documentation and wiki leaks.
- Keep dependencies patched; pin versions for Documentation and wiki leaks components.

### Verification

- Add automated tests and SAST/DAST coverage for Documentation and wiki leaks paths.
- Run dependency and secret scanning on every change touching Documentation and wiki leaks.
- Perform targeted manual tests (abuse cases) for Documentation and wiki leaks.

### Operations

- Log security-relevant events for Documentation and wiki leaks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Documentation and wiki leaks.
- Review access and configuration for Documentation and wiki leaks on a regular cadence.

## BPO and outsourced access

Sub-topics: VPN accounts, Time-bound access, Screen monitoring, Data handling, Contract clauses

### Policy

- Treat BPO and outsourced access in BPO and outsourced access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for BPO and outsourced access (Human factors, social engineering, and support abuse).
- Require security review for material changes affecting BPO and outsourced access.

### Design

- Apply least privilege and defense in depth for BPO and outsourced access.
- Prefer established patterns and libraries over custom crypto or auth for BPO and outsourced access.
- Fail closed: deny by default when BPO and outsourced access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching BPO and outsourced access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to BPO and outsourced access.
- Keep dependencies patched; pin versions for BPO and outsourced access components.

### Verification

- Add automated tests and SAST/DAST coverage for BPO and outsourced access paths.
- Run dependency and secret scanning on every change touching BPO and outsourced access.
- Perform targeted manual tests (abuse cases) for BPO and outsourced access.

### Operations

- Log security-relevant events for BPO and outsourced access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in BPO and outsourced access.
- Review access and configuration for BPO and outsourced access on a regular cadence.

