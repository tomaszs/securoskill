# Docker: Privacy and compliance

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-privacy-compliance` / `reference.md`.

## Data subject rights

**Sub-topics:** Erasure, Export, Rectification, Threat modeling and trust boundaries (Data subject rights), Abuse cases and adversarial testing (Data subject rights)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Consent management

**Sub-topics:** Granularity, Withdrawal, Threat modeling and trust boundaries (Consent management), Abuse cases and adversarial testing (Consent management), Logging, audit, and detection (Consent management)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## DPIA and risk assessments

**Sub-topics:** High-risk processing, Threat modeling and trust boundaries (DPIA and risk assessments), Abuse cases and adversarial testing (DPIA and risk assessments), Logging, audit, and detection (DPIA and risk assessments), Access control and least privilege (DPIA and risk assessments)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Cross-border transfers

**Sub-topics:** SCCs, Adequacy, Threat modeling and trust boundaries (Cross-border transfers), Abuse cases and adversarial testing (Cross-border transfers), Logging, audit, and detection (Cross-border transfers)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## PCI DSS scope

**Sub-topics:** Card data, SAQ types, Threat modeling and trust boundaries (PCI DSS scope), Abuse cases and adversarial testing (PCI DSS scope), Logging, audit, and detection (PCI DSS scope)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## HIPAA-aligned controls

**Sub-topics:** PHI, BAAs, Threat modeling and trust boundaries (HIPAA-aligned controls), Abuse cases and adversarial testing (HIPAA-aligned controls), Logging, audit, and detection (HIPAA-aligned controls)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## SOC 2 trust principles

**Sub-topics:** Evidence, Controls, Threat modeling and trust boundaries (SOC 2 trust principles), Abuse cases and adversarial testing (SOC 2 trust principles), Logging, audit, and detection (SOC 2 trust principles)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Records of processing

**Sub-topics:** ROPA, Vendor maps, Threat modeling and trust boundaries (Records of processing), Abuse cases and adversarial testing (Records of processing), Logging, audit, and detection (Records of processing)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Children's data

**Sub-topics:** COPPA, Age gates, Threat modeling and trust boundaries (Children's data), Abuse cases and adversarial testing (Children's data), Logging, audit, and detection (Children's data)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Marketing and tracking

**Sub-topics:** Cookies, Opt-out, Threat modeling and trust boundaries (Marketing and tracking), Abuse cases and adversarial testing (Marketing and tracking), Logging, audit, and detection (Marketing and tracking)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## AI and profiling

**Sub-topics:** Automated decisions, Transparency, Threat modeling and trust boundaries (AI and profiling), Abuse cases and adversarial testing (AI and profiling), Logging, audit, and detection (AI and profiling)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Breach notification

**Sub-topics:** Timelines, Regulators, Threat modeling and trust boundaries (Breach notification), Abuse cases and adversarial testing (Breach notification), Logging, audit, and detection (Breach notification)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

