# Astro: Software supply chain

Stack-specific implementation for **Astro** (Web UI). Normative rules: domain skill `security-supply-chain` / `reference.md`.

## Package registries

**Sub-topics:** Typosquatting, Maintainer takeover, Threat modeling and trust boundaries (Package registries), Abuse cases and adversarial testing (Package registries), Logging, audit, and detection (Package registries)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for package_registries controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Lockfiles and reproducibility

**Sub-topics:** Integrity hashes, Threat modeling and trust boundaries (Lockfiles and reproducibility), Abuse cases and adversarial testing (Lockfiles and reproducibility), Logging, audit, and detection (Lockfiles and reproducibility), Access control and least privilege (Lockfiles and reproducibility)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for lockfiles controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Vendoring

**Sub-topics:** Fork drift, Patch review, Threat modeling and trust boundaries (Vendoring), Abuse cases and adversarial testing (Vendoring), Logging, audit, and detection (Vendoring)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for vendoring controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Build integrity

**Sub-topics:** SLSA levels, Hermetic builds, Threat modeling and trust boundaries (Build integrity), Abuse cases and adversarial testing (Build integrity), Logging, audit, and detection (Build integrity)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for build_integrity controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Third-party SaaS

**Sub-topics:** DPAs, Subprocessors, Threat modeling and trust boundaries (Third-party SaaS), Abuse cases and adversarial testing (Third-party SaaS), Logging, audit, and detection (Third-party SaaS)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for third_party_saas controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## License compliance

**Sub-topics:** Copyleft in SaaS, Threat modeling and trust boundaries (License compliance), Abuse cases and adversarial testing (License compliance), Logging, audit, and detection (License compliance), Access control and least privilege (License compliance)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for license controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Binary dependencies

**Sub-topics:** Provenance, Checksums, Threat modeling and trust boundaries (Binary dependencies), Abuse cases and adversarial testing (Binary dependencies), Logging, audit, and detection (Binary dependencies)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for binary_deps controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Git submodules

**Sub-topics:** Pinned refs, URL hijack, Threat modeling and trust boundaries (Git submodules), Abuse cases and adversarial testing (Git submodules), Logging, audit, and detection (Git submodules)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for submodules controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Internal packages

**Sub-topics:** Namespace, Publishing tokens, Threat modeling and trust boundaries (Internal packages), Abuse cases and adversarial testing (Internal packages), Logging, audit, and detection (Internal packages)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for internal_packages controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## CVE response

**Sub-topics:** Triage, Emergency patches, Threat modeling and trust boundaries (CVE response), Abuse cases and adversarial testing (CVE response), Logging, audit, and detection (CVE response)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for cve controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## Malware in repos

**Sub-topics:** Obfuscated scripts, Postinstall, Threat modeling and trust boundaries (Malware in repos), Abuse cases and adversarial testing (Malware in repos), Logging, audit, and detection (Malware in repos)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for malware_repo controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

## SBOM distribution

**Sub-topics:** VEX, Consumer updates, Threat modeling and trust boundaries (SBOM distribution), Abuse cases and adversarial testing (SBOM distribution), Logging, audit, and detection (SBOM distribution)

### Do (use this in Astro)

- Apply domain skill `security-supply-chain` requirements using astro supported APIs only.
- Use the official astro security documentation for sbom controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of astro for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on astro projects in CI.

