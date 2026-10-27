# Ruby on Rails: Software supply chain

Stack-specific implementation for **Ruby on Rails** (Ruby). Normative rules: domain skill `security-supply-chain` / `reference.md`.

## Package registries

**Sub-topics:** Typosquatting, Maintainer takeover, Threat modeling and trust boundaries (Package registries), Abuse cases and adversarial testing (Package registries), Logging, audit, and detection (Package registries)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Package registries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Package registries.
- Keep dependencies patched; pin versions for Package registries components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Package registries before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Package registries paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Lockfiles and reproducibility

**Sub-topics:** Integrity hashes, Threat modeling and trust boundaries (Lockfiles and reproducibility), Abuse cases and adversarial testing (Lockfiles and reproducibility), Logging, audit, and detection (Lockfiles and reproducibility), Access control and least privilege (Lockfiles and reproducibility)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Lockfiles and reproducibility; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Lockfiles and reproducibility.
- Keep dependencies patched; pin versions for Lockfiles and reproducibility components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Lockfiles and reproducibility before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Lockfiles and reproducibility paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Vendoring

**Sub-topics:** Fork drift, Patch review, Threat modeling and trust boundaries (Vendoring), Abuse cases and adversarial testing (Vendoring), Logging, audit, and detection (Vendoring)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Vendoring; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vendoring.
- Keep dependencies patched; pin versions for Vendoring components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Vendoring before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Vendoring paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Build integrity

**Sub-topics:** SLSA levels, Hermetic builds, Threat modeling and trust boundaries (Build integrity), Abuse cases and adversarial testing (Build integrity), Logging, audit, and detection (Build integrity)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Build integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Build integrity.
- Keep dependencies patched; pin versions for Build integrity components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Build integrity before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Build integrity paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Third-party SaaS

**Sub-topics:** DPAs, Subprocessors, Threat modeling and trust boundaries (Third-party SaaS), Abuse cases and adversarial testing (Third-party SaaS), Logging, audit, and detection (Third-party SaaS)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Third-party SaaS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party SaaS.
- Keep dependencies patched; pin versions for Third-party SaaS components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Third-party SaaS before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Third-party SaaS paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## License compliance

**Sub-topics:** Copyleft in SaaS, Threat modeling and trust boundaries (License compliance), Abuse cases and adversarial testing (License compliance), Logging, audit, and detection (License compliance), Access control and least privilege (License compliance)

### Platform rules (summary)

- Validate and canonicalize all inputs touching License compliance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to License compliance.
- Keep dependencies patched; pin versions for License compliance components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for License compliance before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for License compliance paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Binary dependencies

**Sub-topics:** Provenance, Checksums, Threat modeling and trust boundaries (Binary dependencies), Abuse cases and adversarial testing (Binary dependencies), Logging, audit, and detection (Binary dependencies)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Binary dependencies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Binary dependencies.
- Keep dependencies patched; pin versions for Binary dependencies components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Binary dependencies before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Binary dependencies paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Git submodules

**Sub-topics:** Pinned refs, URL hijack, Threat modeling and trust boundaries (Git submodules), Abuse cases and adversarial testing (Git submodules), Logging, audit, and detection (Git submodules)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Git submodules; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Git submodules.
- Keep dependencies patched; pin versions for Git submodules components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Git submodules before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Git submodules paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Internal packages

**Sub-topics:** Namespace, Publishing tokens, Threat modeling and trust boundaries (Internal packages), Abuse cases and adversarial testing (Internal packages), Logging, audit, and detection (Internal packages)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Internal packages; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Internal packages.
- Keep dependencies patched; pin versions for Internal packages components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Internal packages before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Internal packages paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## CVE response

**Sub-topics:** Triage, Emergency patches, Threat modeling and trust boundaries (CVE response), Abuse cases and adversarial testing (CVE response), Logging, audit, and detection (CVE response)

### Platform rules (summary)

- Validate and canonicalize all inputs touching CVE response; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CVE response.
- Keep dependencies patched; pin versions for CVE response components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CVE response before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CVE response paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Malware in repos

**Sub-topics:** Obfuscated scripts, Postinstall, Threat modeling and trust boundaries (Malware in repos), Abuse cases and adversarial testing (Malware in repos), Logging, audit, and detection (Malware in repos)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Malware in repos; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Malware in repos.
- Keep dependencies patched; pin versions for Malware in repos components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Malware in repos before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Malware in repos paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## SBOM distribution

**Sub-topics:** VEX, Consumer updates, Threat modeling and trust boundaries (SBOM distribution), Abuse cases and adversarial testing (SBOM distribution), Logging, audit, and detection (SBOM distribution)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SBOM distribution; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SBOM distribution.
- Keep dependencies patched; pin versions for SBOM distribution components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-supply-chain` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SBOM distribution before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SBOM distribution paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

