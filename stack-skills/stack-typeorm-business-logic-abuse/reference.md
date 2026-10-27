# TypeORM: Business logic and abuse prevention

Stack-specific implementation for **TypeORM** (ORM / data access). Normative rules: domain skill `security-business-logic-abuse` / `reference.md`.

## Payment and checkout abuse

**Sub-topics:** Coupon stacking, Currency, Threat modeling and trust boundaries (Payment and checkout abuse), Abuse cases and adversarial testing (Payment and checkout abuse), Logging, audit, and detection (Payment and checkout abuse)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Workflow bypass

**Sub-topics:** State machine skips, Threat modeling and trust boundaries (Workflow bypass), Abuse cases and adversarial testing (Workflow bypass), Logging, audit, and detection (Workflow bypass), Access control and least privilege (Workflow bypass)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Insecure direct object references

**Sub-topics:** UUID guessing, IDOR in APIs, Threat modeling and trust boundaries (Insecure direct object references), Abuse cases and adversarial testing (Insecure direct object references), Logging, audit, and detection (Insecure direct object references)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Mass assignment

**Sub-topics:** Hidden fields, DTO allowlists, Threat modeling and trust boundaries (Mass assignment), Abuse cases and adversarial testing (Mass assignment), Logging, audit, and detection (Mass assignment)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Bots and automation

**Sub-topics:** CAPTCHA alternatives, Behavior, Threat modeling and trust boundaries (Bots and automation), Abuse cases and adversarial testing (Bots and automation), Logging, audit, and detection (Bots and automation)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Referral and loyalty abuse

**Sub-topics:** Self-referral, Threat modeling and trust boundaries (Referral and loyalty abuse), Abuse cases and adversarial testing (Referral and loyalty abuse), Logging, audit, and detection (Referral and loyalty abuse), Access control and least privilege (Referral and loyalty abuse)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Marketplace trust

**Sub-topics:** Chargeback, Escrow, Threat modeling and trust boundaries (Marketplace trust), Abuse cases and adversarial testing (Marketplace trust), Logging, audit, and detection (Marketplace trust)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Content abuse

**Sub-topics:** Spam, Illegal content, Threat modeling and trust boundaries (Content abuse), Abuse cases and adversarial testing (Content abuse), Logging, audit, and detection (Content abuse)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Quota and limit bypass

**Sub-topics:** Parallel requests, Threat modeling and trust boundaries (Quota and limit bypass), Abuse cases and adversarial testing (Quota and limit bypass), Logging, audit, and detection (Quota and limit bypass), Access control and least privilege (Quota and limit bypass)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Admin misuse

**Sub-topics:** Separation of duties, Threat modeling and trust boundaries (Admin misuse), Abuse cases and adversarial testing (Admin misuse), Logging, audit, and detection (Admin misuse), Access control and least privilege (Admin misuse)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Time-based logic

**Sub-topics:** Timezone, Leap seconds, Threat modeling and trust boundaries (Time-based logic), Abuse cases and adversarial testing (Time-based logic), Logging, audit, and detection (Time-based logic)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

## Feature gating bypass

**Sub-topics:** Client flags, Threat modeling and trust boundaries (Feature gating bypass), Abuse cases and adversarial testing (Feature gating bypass), Logging, audit, and detection (Feature gating bypass), Access control and least privilege (Feature gating bypass)

### Do (use this in TypeORM)

- TypeORM is not the primary enforcement point for `business-logic-abuse`; load stack skill `security-business-logic-abuse` when you touch that layer.
- Keep TypeORM configuration aligned with requirements from `security-business-logic-abuse` (domain reference.md).

### Don't

- Do not duplicate `business-logic-abuse` controls only in TypeORM config while leaving security-business-logic-abuse misconfigured.
- Do not assume TypeORM defaults satisfy `security-business-logic-abuse` without verification.

### Verify

- Integration test the full path: TypeORM plus the system covered by `security-business-logic-abuse`.

