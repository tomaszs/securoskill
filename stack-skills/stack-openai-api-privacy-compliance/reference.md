# OpenAI API / Agents SDK: Privacy and compliance

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-privacy-compliance` / `reference.md`.

## Data subject rights

**Sub-topics:** Erasure, Export, Rectification, Threat modeling and trust boundaries (Data subject rights), Abuse cases and adversarial testing (Data subject rights)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Consent management

**Sub-topics:** Granularity, Withdrawal, Threat modeling and trust boundaries (Consent management), Abuse cases and adversarial testing (Consent management), Logging, audit, and detection (Consent management)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## DPIA and risk assessments

**Sub-topics:** High-risk processing, Threat modeling and trust boundaries (DPIA and risk assessments), Abuse cases and adversarial testing (DPIA and risk assessments), Logging, audit, and detection (DPIA and risk assessments), Access control and least privilege (DPIA and risk assessments)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Cross-border transfers

**Sub-topics:** SCCs, Adequacy, Threat modeling and trust boundaries (Cross-border transfers), Abuse cases and adversarial testing (Cross-border transfers), Logging, audit, and detection (Cross-border transfers)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## PCI DSS scope

**Sub-topics:** Card data, SAQ types, Threat modeling and trust boundaries (PCI DSS scope), Abuse cases and adversarial testing (PCI DSS scope), Logging, audit, and detection (PCI DSS scope)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## HIPAA-aligned controls

**Sub-topics:** PHI, BAAs, Threat modeling and trust boundaries (HIPAA-aligned controls), Abuse cases and adversarial testing (HIPAA-aligned controls), Logging, audit, and detection (HIPAA-aligned controls)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## SOC 2 trust principles

**Sub-topics:** Evidence, Controls, Threat modeling and trust boundaries (SOC 2 trust principles), Abuse cases and adversarial testing (SOC 2 trust principles), Logging, audit, and detection (SOC 2 trust principles)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Records of processing

**Sub-topics:** ROPA, Vendor maps, Threat modeling and trust boundaries (Records of processing), Abuse cases and adversarial testing (Records of processing), Logging, audit, and detection (Records of processing)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Children's data

**Sub-topics:** COPPA, Age gates, Threat modeling and trust boundaries (Children's data), Abuse cases and adversarial testing (Children's data), Logging, audit, and detection (Children's data)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Marketing and tracking

**Sub-topics:** Cookies, Opt-out, Threat modeling and trust boundaries (Marketing and tracking), Abuse cases and adversarial testing (Marketing and tracking), Logging, audit, and detection (Marketing and tracking)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## AI and profiling

**Sub-topics:** Automated decisions, Transparency, Threat modeling and trust boundaries (AI and profiling), Abuse cases and adversarial testing (AI and profiling), Logging, audit, and detection (AI and profiling)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Breach notification

**Sub-topics:** Timelines, Regulators, Threat modeling and trust boundaries (Breach notification), Abuse cases and adversarial testing (Breach notification), Logging, audit, and detection (Breach notification)

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

