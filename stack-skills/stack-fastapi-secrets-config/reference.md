# FastAPI: Secrets and configuration

Stack-specific implementation for **FastAPI** (Python). Normative rules: domain skill `security-secrets-config` / `reference.md`.

## Environment variables

**Sub-topics:** Leaks in logs, Client exposure, Threat modeling and trust boundaries (Environment variables), Abuse cases and adversarial testing (Environment variables), Logging, audit, and detection (Environment variables)

### Do (use this in FastAPI)

- Map `Environment variables` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Environment variables` before merge.

### Don't

- Do not ship `Environment variables` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Environment variables`.

### Verify

- Peer review `Environment variables` against domain skill `security-secrets-config`.

## Config separation

**Sub-topics:** Per-env files, Gitignore, Threat modeling and trust boundaries (Config separation), Abuse cases and adversarial testing (Config separation), Logging, audit, and detection (Config separation)

### Do (use this in FastAPI)

- Map `Config separation` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Config separation` before merge.

### Don't

- Do not ship `Config separation` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Config separation`.

### Verify

- Peer review `Config separation` against domain skill `security-secrets-config`.

## Feature flags

**Sub-topics:** Kill switches, Privileged features, Threat modeling and trust boundaries (Feature flags), Abuse cases and adversarial testing (Feature flags), Logging, audit, and detection (Feature flags)

### Do (use this in FastAPI)

- Map `Feature flags` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Feature flags` before merge.

### Don't

- Do not ship `Feature flags` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Feature flags`.

### Verify

- Peer review `Feature flags` against domain skill `security-secrets-config`.

## Secret rotation

**Sub-topics:** Dual-write, Breakage windows, Threat modeling and trust boundaries (Secret rotation), Abuse cases and adversarial testing (Secret rotation), Logging, audit, and detection (Secret rotation)

### Do (use this in FastAPI)

- Map `Secret rotation` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Secret rotation` before merge.

### Don't

- Do not ship `Secret rotation` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Secret rotation`.

### Verify

- Peer review `Secret rotation` against domain skill `security-secrets-config`.

## .env handling

**Sub-topics:** Committed secrets, CI injection, Threat modeling and trust boundaries (.env handling), Abuse cases and adversarial testing (.env handling), Logging, audit, and detection (.env handling)

### Do (use this in FastAPI)

- Map `.env handling` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `.env handling` before merge.

### Don't

- Do not ship `.env handling` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `.env handling`.

### Verify

- Peer review `.env handling` against domain skill `security-secrets-config`.

## Config servers

**Sub-topics:** ACLs, Encryption, Threat modeling and trust boundaries (Config servers), Abuse cases and adversarial testing (Config servers), Logging, audit, and detection (Config servers)

### Do (use this in FastAPI)

- Map `Config servers` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Config servers` before merge.

### Don't

- Do not ship `Config servers` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Config servers`.

### Verify

- Peer review `Config servers` against domain skill `security-secrets-config`.

## Hardcoded credentials

**Sub-topics:** Scanning, Prevention, Threat modeling and trust boundaries (Hardcoded credentials), Abuse cases and adversarial testing (Hardcoded credentials), Logging, audit, and detection (Hardcoded credentials)

### Do (use this in FastAPI)

- Map `Hardcoded credentials` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Hardcoded credentials` before merge.

### Don't

- Do not ship `Hardcoded credentials` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Hardcoded credentials`.

### Verify

- Peer review `Hardcoded credentials` against domain skill `security-secrets-config`.

## Public vs confidential clients

**Sub-topics:** Mobile apps, SPAs, Threat modeling and trust boundaries (Public vs confidential clients), Abuse cases and adversarial testing (Public vs confidential clients), Logging, audit, and detection (Public vs confidential clients)

### Do (use this in FastAPI)

- Map `Public vs confidential clients` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Public vs confidential clients` before merge.

### Don't

- Do not ship `Public vs confidential clients` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Public vs confidential clients`.

### Verify

- Peer review `Public vs confidential clients` against domain skill `security-secrets-config`.

## Bootstrap secrets

**Sub-topics:** First deploy, Init containers, Threat modeling and trust boundaries (Bootstrap secrets), Abuse cases and adversarial testing (Bootstrap secrets), Logging, audit, and detection (Bootstrap secrets)

### Do (use this in FastAPI)

- Map `Bootstrap secrets` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Bootstrap secrets` before merge.

### Don't

- Do not ship `Bootstrap secrets` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Bootstrap secrets`.

### Verify

- Peer review `Bootstrap secrets` against domain skill `security-secrets-config`.

## Configuration audit

**Sub-topics:** Drift detection, Threat modeling and trust boundaries (Configuration audit), Abuse cases and adversarial testing (Configuration audit), Logging, audit, and detection (Configuration audit), Access control and least privilege (Configuration audit)

### Do (use this in FastAPI)

- Map `Configuration audit` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Configuration audit` before merge.

### Don't

- Do not ship `Configuration audit` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Configuration audit`.

### Verify

- Peer review `Configuration audit` against domain skill `security-secrets-config`.

## Insecure defaults

**Sub-topics:** Debug=true, Open admin, Threat modeling and trust boundaries (Insecure defaults), Abuse cases and adversarial testing (Insecure defaults), Logging, audit, and detection (Insecure defaults)

### Do (use this in FastAPI)

- Map `Insecure defaults` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Insecure defaults` before merge.

### Don't

- Do not ship `Insecure defaults` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Insecure defaults`.

### Verify

- Peer review `Insecure defaults` against domain skill `security-secrets-config`.

## Split knowledge

**Sub-topics:** Shamir, M-of-N, Threat modeling and trust boundaries (Split knowledge), Abuse cases and adversarial testing (Split knowledge), Logging, audit, and detection (Split knowledge)

### Do (use this in FastAPI)

- Map `Split knowledge` controls to FastAPI APIs documented for `security-secrets-config`.
- Add an abuse-case test or check for `Split knowledge` before merge.

### Don't

- Do not ship `Split knowledge` work in FastAPI with only happy-path tests.
- Do not disable FastAPI security defaults to unblock `Split knowledge`.

### Verify

- Peer review `Split knowledge` against domain skill `security-secrets-config`.

