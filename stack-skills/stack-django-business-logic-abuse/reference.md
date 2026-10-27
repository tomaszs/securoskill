# Django: Business logic and abuse prevention

Stack-specific implementation for **Django** (Python). Normative rules: domain skill `security-business-logic-abuse` / `reference.md`.

## Payment and checkout abuse

**Sub-topics:** Coupon stacking, Currency, Threat modeling and trust boundaries (Payment and checkout abuse), Abuse cases and adversarial testing (Payment and checkout abuse), Logging, audit, and detection (Payment and checkout abuse)

### Do (use this in Django)

- Map `Payment and checkout abuse` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Payment and checkout abuse` before merge.

### Don't

- Do not ship `Payment and checkout abuse` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Payment and checkout abuse`.

### Verify

- Peer review `Payment and checkout abuse` against domain skill `security-business-logic-abuse`.

## Workflow bypass

**Sub-topics:** State machine skips, Threat modeling and trust boundaries (Workflow bypass), Abuse cases and adversarial testing (Workflow bypass), Logging, audit, and detection (Workflow bypass), Access control and least privilege (Workflow bypass)

### Do (use this in Django)

- Map `Workflow bypass` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Workflow bypass` before merge.

### Don't

- Do not ship `Workflow bypass` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Workflow bypass`.

### Verify

- Peer review `Workflow bypass` against domain skill `security-business-logic-abuse`.

## Insecure direct object references

**Sub-topics:** UUID guessing, IDOR in APIs, Threat modeling and trust boundaries (Insecure direct object references), Abuse cases and adversarial testing (Insecure direct object references), Logging, audit, and detection (Insecure direct object references)

### Do (use this in Django)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run bandit + ruff on changes affecting `Insecure direct object references`.

## Mass assignment

**Sub-topics:** Hidden fields, DTO allowlists, Threat modeling and trust boundaries (Mass assignment), Abuse cases and adversarial testing (Mass assignment), Logging, audit, and detection (Mass assignment)

### Do (use this in Django)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run bandit + ruff on changes affecting `Mass assignment`.

## Bots and automation

**Sub-topics:** CAPTCHA alternatives, Behavior, Threat modeling and trust boundaries (Bots and automation), Abuse cases and adversarial testing (Bots and automation), Logging, audit, and detection (Bots and automation)

### Do (use this in Django)

- Map `Bots and automation` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Bots and automation` before merge.

### Don't

- Do not ship `Bots and automation` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Bots and automation`.

### Verify

- Peer review `Bots and automation` against domain skill `security-business-logic-abuse`.

## Referral and loyalty abuse

**Sub-topics:** Self-referral, Threat modeling and trust boundaries (Referral and loyalty abuse), Abuse cases and adversarial testing (Referral and loyalty abuse), Logging, audit, and detection (Referral and loyalty abuse), Access control and least privilege (Referral and loyalty abuse)

### Do (use this in Django)

- Map `Referral and loyalty abuse` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Referral and loyalty abuse` before merge.

### Don't

- Do not ship `Referral and loyalty abuse` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Referral and loyalty abuse`.

### Verify

- Peer review `Referral and loyalty abuse` against domain skill `security-business-logic-abuse`.

## Marketplace trust

**Sub-topics:** Chargeback, Escrow, Threat modeling and trust boundaries (Marketplace trust), Abuse cases and adversarial testing (Marketplace trust), Logging, audit, and detection (Marketplace trust)

### Do (use this in Django)

- Map `Marketplace trust` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Marketplace trust` before merge.

### Don't

- Do not ship `Marketplace trust` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Marketplace trust`.

### Verify

- Peer review `Marketplace trust` against domain skill `security-business-logic-abuse`.

## Content abuse

**Sub-topics:** Spam, Illegal content, Threat modeling and trust boundaries (Content abuse), Abuse cases and adversarial testing (Content abuse), Logging, audit, and detection (Content abuse)

### Do (use this in Django)

- Map `Content abuse` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Content abuse` before merge.

### Don't

- Do not ship `Content abuse` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Content abuse`.

### Verify

- Peer review `Content abuse` against domain skill `security-business-logic-abuse`.

## Quota and limit bypass

**Sub-topics:** Parallel requests, Threat modeling and trust boundaries (Quota and limit bypass), Abuse cases and adversarial testing (Quota and limit bypass), Logging, audit, and detection (Quota and limit bypass), Access control and least privilege (Quota and limit bypass)

### Do (use this in Django)

- Map `Quota and limit bypass` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Quota and limit bypass` before merge.

### Don't

- Do not ship `Quota and limit bypass` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Quota and limit bypass`.

### Verify

- Peer review `Quota and limit bypass` against domain skill `security-business-logic-abuse`.

## Admin misuse

**Sub-topics:** Separation of duties, Threat modeling and trust boundaries (Admin misuse), Abuse cases and adversarial testing (Admin misuse), Logging, audit, and detection (Admin misuse), Access control and least privilege (Admin misuse)

### Do (use this in Django)

- Map `Admin misuse` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Admin misuse` before merge.

### Don't

- Do not ship `Admin misuse` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Admin misuse`.

### Verify

- Peer review `Admin misuse` against domain skill `security-business-logic-abuse`.

## Time-based logic

**Sub-topics:** Timezone, Leap seconds, Threat modeling and trust boundaries (Time-based logic), Abuse cases and adversarial testing (Time-based logic), Logging, audit, and detection (Time-based logic)

### Do (use this in Django)

- Map `Time-based logic` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Time-based logic` before merge.

### Don't

- Do not ship `Time-based logic` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Time-based logic`.

### Verify

- Peer review `Time-based logic` against domain skill `security-business-logic-abuse`.

## Feature gating bypass

**Sub-topics:** Client flags, Threat modeling and trust boundaries (Feature gating bypass), Abuse cases and adversarial testing (Feature gating bypass), Logging, audit, and detection (Feature gating bypass), Access control and least privilege (Feature gating bypass)

### Do (use this in Django)

- Map `Feature gating bypass` controls to Django APIs documented for `security-business-logic-abuse`.
- Add an abuse-case test or check for `Feature gating bypass` before merge.

### Don't

- Do not ship `Feature gating bypass` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Feature gating bypass`.

### Verify

- Peer review `Feature gating bypass` against domain skill `security-business-logic-abuse`.

