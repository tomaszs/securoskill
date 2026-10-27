# Cloudflare Workers: Secrets and configuration

Stack-specific implementation for **Cloudflare Workers** (Platform). Normative rules: domain skill `security-secrets-config` / `reference.md`.

## Environment variables

**Sub-topics:** Leaks in logs, Client exposure, Threat modeling and trust boundaries (Environment variables), Abuse cases and adversarial testing (Environment variables), Logging, audit, and detection (Environment variables)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Config separation

**Sub-topics:** Per-env files, Gitignore, Threat modeling and trust boundaries (Config separation), Abuse cases and adversarial testing (Config separation), Logging, audit, and detection (Config separation)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Feature flags

**Sub-topics:** Kill switches, Privileged features, Threat modeling and trust boundaries (Feature flags), Abuse cases and adversarial testing (Feature flags), Logging, audit, and detection (Feature flags)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Secret rotation

**Sub-topics:** Dual-write, Breakage windows, Threat modeling and trust boundaries (Secret rotation), Abuse cases and adversarial testing (Secret rotation), Logging, audit, and detection (Secret rotation)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## .env handling

**Sub-topics:** Committed secrets, CI injection, Threat modeling and trust boundaries (.env handling), Abuse cases and adversarial testing (.env handling), Logging, audit, and detection (.env handling)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Config servers

**Sub-topics:** ACLs, Encryption, Threat modeling and trust boundaries (Config servers), Abuse cases and adversarial testing (Config servers), Logging, audit, and detection (Config servers)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Hardcoded credentials

**Sub-topics:** Scanning, Prevention, Threat modeling and trust boundaries (Hardcoded credentials), Abuse cases and adversarial testing (Hardcoded credentials), Logging, audit, and detection (Hardcoded credentials)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Public vs confidential clients

**Sub-topics:** Mobile apps, SPAs, Threat modeling and trust boundaries (Public vs confidential clients), Abuse cases and adversarial testing (Public vs confidential clients), Logging, audit, and detection (Public vs confidential clients)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Bootstrap secrets

**Sub-topics:** First deploy, Init containers, Threat modeling and trust boundaries (Bootstrap secrets), Abuse cases and adversarial testing (Bootstrap secrets), Logging, audit, and detection (Bootstrap secrets)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Configuration audit

**Sub-topics:** Drift detection, Threat modeling and trust boundaries (Configuration audit), Abuse cases and adversarial testing (Configuration audit), Logging, audit, and detection (Configuration audit), Access control and least privilege (Configuration audit)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Insecure defaults

**Sub-topics:** Debug=true, Open admin, Threat modeling and trust boundaries (Insecure defaults), Abuse cases and adversarial testing (Insecure defaults), Logging, audit, and detection (Insecure defaults)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

## Split knowledge

**Sub-topics:** Shamir, M-of-N, Threat modeling and trust boundaries (Split knowledge), Abuse cases and adversarial testing (Split knowledge), Logging, audit, and detection (Split knowledge)

### Do (use this in Cloudflare Workers)

- Cloudflare Workers is not the primary enforcement point for `secrets-config`; load stack skill `security-secrets-config` when you touch that layer.
- Keep Cloudflare Workers configuration aligned with requirements from `security-secrets-config` (domain reference.md).

### Don't

- Do not duplicate `secrets-config` controls only in Cloudflare Workers config while leaving security-secrets-config misconfigured.
- Do not assume Cloudflare Workers defaults satisfy `security-secrets-config` without verification.

### Verify

- Integration test the full path: Cloudflare Workers plus the system covered by `security-secrets-config`.

