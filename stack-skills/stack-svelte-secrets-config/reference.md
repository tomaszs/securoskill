# Svelte: Secrets and configuration

Stack-specific implementation for **Svelte** (Web UI). Normative rules: domain skill `security-secrets-config` / `reference.md`.

## Environment variables

**Sub-topics:** Leaks in logs, Client exposure, Threat modeling and trust boundaries (Environment variables), Abuse cases and adversarial testing (Environment variables), Logging, audit, and detection (Environment variables)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Environment variables; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Environment variables.
- Keep dependencies patched; pin versions for Environment variables components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Environment variables before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Environment variables paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Config separation

**Sub-topics:** Per-env files, Gitignore, Threat modeling and trust boundaries (Config separation), Abuse cases and adversarial testing (Config separation), Logging, audit, and detection (Config separation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Config separation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Config separation.
- Keep dependencies patched; pin versions for Config separation components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Config separation before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Config separation paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Feature flags

**Sub-topics:** Kill switches, Privileged features, Threat modeling and trust boundaries (Feature flags), Abuse cases and adversarial testing (Feature flags), Logging, audit, and detection (Feature flags)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Feature flags; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature flags.
- Keep dependencies patched; pin versions for Feature flags components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Feature flags before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Feature flags paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Secret rotation

**Sub-topics:** Dual-write, Breakage windows, Threat modeling and trust boundaries (Secret rotation), Abuse cases and adversarial testing (Secret rotation), Logging, audit, and detection (Secret rotation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secret rotation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secret rotation.
- Keep dependencies patched; pin versions for Secret rotation components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secret rotation before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secret rotation paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## .env handling

**Sub-topics:** Committed secrets, CI injection, Threat modeling and trust boundaries (.env handling), Abuse cases and adversarial testing (.env handling), Logging, audit, and detection (.env handling)

### Platform rules (summary)

- Validate and canonicalize all inputs touching .env handling.env handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to .env handling.
- Keep dependencies patched; pin versions for .env handling.env handling components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for .env handling before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for .env handling paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Config servers

**Sub-topics:** ACLs, Encryption, Threat modeling and trust boundaries (Config servers), Abuse cases and adversarial testing (Config servers), Logging, audit, and detection (Config servers)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Config servers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Config servers.
- Keep dependencies patched; pin versions for Config servers components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Config servers before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Config servers paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Hardcoded credentials

**Sub-topics:** Scanning, Prevention, Threat modeling and trust boundaries (Hardcoded credentials), Abuse cases and adversarial testing (Hardcoded credentials), Logging, audit, and detection (Hardcoded credentials)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Hardcoded credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Hardcoded credentials.
- Keep dependencies patched; pin versions for Hardcoded credentials components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Hardcoded credentials before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Hardcoded credentials paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Public vs confidential clients

**Sub-topics:** Mobile apps, SPAs, Threat modeling and trust boundaries (Public vs confidential clients), Abuse cases and adversarial testing (Public vs confidential clients), Logging, audit, and detection (Public vs confidential clients)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Public vs confidential clients; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Public vs confidential clients.
- Keep dependencies patched; pin versions for Public vs confidential clients components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Public vs confidential clients before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Public vs confidential clients paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Bootstrap secrets

**Sub-topics:** First deploy, Init containers, Threat modeling and trust boundaries (Bootstrap secrets), Abuse cases and adversarial testing (Bootstrap secrets), Logging, audit, and detection (Bootstrap secrets)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Bootstrap secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bootstrap secrets.
- Keep dependencies patched; pin versions for Bootstrap secrets components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Bootstrap secrets before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Bootstrap secrets paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Configuration audit

**Sub-topics:** Drift detection, Threat modeling and trust boundaries (Configuration audit), Abuse cases and adversarial testing (Configuration audit), Logging, audit, and detection (Configuration audit), Access control and least privilege (Configuration audit)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Configuration audit; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Configuration audit.
- Keep dependencies patched; pin versions for Configuration audit components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Configuration audit before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Configuration audit paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Insecure defaults

**Sub-topics:** Debug=true, Open admin, Threat modeling and trust boundaries (Insecure defaults), Abuse cases and adversarial testing (Insecure defaults), Logging, audit, and detection (Insecure defaults)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Insecure defaults; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insecure defaults.
- Keep dependencies patched; pin versions for Insecure defaults components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Insecure defaults before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Insecure defaults paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

## Split knowledge

**Sub-topics:** Shamir, M-of-N, Threat modeling and trust boundaries (Split knowledge), Abuse cases and adversarial testing (Split knowledge), Logging, audit, and detection (Split knowledge)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Split knowledge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Split knowledge.
- Keep dependencies patched; pin versions for Split knowledge components.

### How to do this in Svelte

- Keep secrets out of git; use env or secret manager integration native to Svelte.
- Read normative rules in domain skill `security-secrets-config` / `reference.md`, then apply them using Svelte APIs and deployment model.
- Prefer framework-maintained security features in Svelte over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Split knowledge before merge.
- Pin Svelte dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Split knowledge paths in Svelte.
- Run SAST/dependency scan configured for Web UI.

