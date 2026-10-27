# Spring Boot: Business logic and abuse prevention

Stack-specific implementation for **Spring Boot** (Java). Normative rules: domain skill `security-business-logic-abuse` / `reference.md`.

## Payment and checkout abuse

**Sub-topics:** Coupon stacking, Currency, Threat modeling and trust boundaries (Payment and checkout abuse), Abuse cases and adversarial testing (Payment and checkout abuse), Logging, audit, and detection (Payment and checkout abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Payment and checkout abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payment and checkout abuse.
- Keep dependencies patched; pin versions for Payment and checkout abuse components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Payment and checkout abuse before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Payment and checkout abuse paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Workflow bypass

**Sub-topics:** State machine skips, Threat modeling and trust boundaries (Workflow bypass), Abuse cases and adversarial testing (Workflow bypass), Logging, audit, and detection (Workflow bypass), Access control and least privilege (Workflow bypass)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Workflow bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Workflow bypass.
- Keep dependencies patched; pin versions for Workflow bypass components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Workflow bypass before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Workflow bypass paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Insecure direct object references

**Sub-topics:** UUID guessing, IDOR in APIs, Threat modeling and trust boundaries (Insecure direct object references), Abuse cases and adversarial testing (Insecure direct object references), Logging, audit, and detection (Insecure direct object references)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Insecure direct object references; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insecure direct object references.
- Keep dependencies patched; pin versions for Insecure direct object references components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Insecure direct object references before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Insecure direct object references paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Mass assignment

**Sub-topics:** Hidden fields, DTO allowlists, Threat modeling and trust boundaries (Mass assignment), Abuse cases and adversarial testing (Mass assignment), Logging, audit, and detection (Mass assignment)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Mass assignment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mass assignment.
- Keep dependencies patched; pin versions for Mass assignment components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Mass assignment before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Mass assignment paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Bots and automation

**Sub-topics:** CAPTCHA alternatives, Behavior, Threat modeling and trust boundaries (Bots and automation), Abuse cases and adversarial testing (Bots and automation), Logging, audit, and detection (Bots and automation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Bots and automation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bots and automation.
- Keep dependencies patched; pin versions for Bots and automation components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Bots and automation before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Bots and automation paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Referral and loyalty abuse

**Sub-topics:** Self-referral, Threat modeling and trust boundaries (Referral and loyalty abuse), Abuse cases and adversarial testing (Referral and loyalty abuse), Logging, audit, and detection (Referral and loyalty abuse), Access control and least privilege (Referral and loyalty abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Referral and loyalty abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Referral and loyalty abuse.
- Keep dependencies patched; pin versions for Referral and loyalty abuse components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Referral and loyalty abuse before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Referral and loyalty abuse paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Marketplace trust

**Sub-topics:** Chargeback, Escrow, Threat modeling and trust boundaries (Marketplace trust), Abuse cases and adversarial testing (Marketplace trust), Logging, audit, and detection (Marketplace trust)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Marketplace trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Marketplace trust.
- Keep dependencies patched; pin versions for Marketplace trust components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Marketplace trust before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Marketplace trust paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Content abuse

**Sub-topics:** Spam, Illegal content, Threat modeling and trust boundaries (Content abuse), Abuse cases and adversarial testing (Content abuse), Logging, audit, and detection (Content abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Content abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Content abuse.
- Keep dependencies patched; pin versions for Content abuse components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Content abuse before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Content abuse paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Quota and limit bypass

**Sub-topics:** Parallel requests, Threat modeling and trust boundaries (Quota and limit bypass), Abuse cases and adversarial testing (Quota and limit bypass), Logging, audit, and detection (Quota and limit bypass), Access control and least privilege (Quota and limit bypass)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Quota and limit bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Quota and limit bypass.
- Keep dependencies patched; pin versions for Quota and limit bypass components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Quota and limit bypass before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Quota and limit bypass paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Admin misuse

**Sub-topics:** Separation of duties, Threat modeling and trust boundaries (Admin misuse), Abuse cases and adversarial testing (Admin misuse), Logging, audit, and detection (Admin misuse), Access control and least privilege (Admin misuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Admin misuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Admin misuse.
- Keep dependencies patched; pin versions for Admin misuse components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Admin misuse before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Admin misuse paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Time-based logic

**Sub-topics:** Timezone, Leap seconds, Threat modeling and trust boundaries (Time-based logic), Abuse cases and adversarial testing (Time-based logic), Logging, audit, and detection (Time-based logic)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Time-based logic; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Time-based logic.
- Keep dependencies patched; pin versions for Time-based logic components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Time-based logic before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Time-based logic paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Feature gating bypass

**Sub-topics:** Client flags, Threat modeling and trust boundaries (Feature gating bypass), Abuse cases and adversarial testing (Feature gating bypass), Logging, audit, and detection (Feature gating bypass), Access control and least privilege (Feature gating bypass)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Feature gating bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature gating bypass.
- Keep dependencies patched; pin versions for Feature gating bypass components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-business-logic-abuse` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Feature gating bypass before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Feature gating bypass paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

