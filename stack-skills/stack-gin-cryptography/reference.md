# Gin (Go): Cryptography and key management

Stack-specific implementation for **Gin (Go)** (Go). Normative rules: domain skill `security-cryptography` / `reference.md`.

## TLS and certificates

**Sub-topics:** mTLS, Pinning pitfalls, Cert rotation, Threat modeling and trust boundaries (TLS and certificates), Abuse cases and adversarial testing (TLS and certificates)

### Platform rules (summary)

- Validate and canonicalize all inputs touching TLS and certificates; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to TLS and certificates.
- Keep dependencies patched; pin versions for TLS and certificates components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for TLS and certificates before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for TLS and certificates paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Symmetric encryption

**Sub-topics:** AES-GCM, Nonce reuse, Key derivation, Threat modeling and trust boundaries (Symmetric encryption), Abuse cases and adversarial testing (Symmetric encryption)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Symmetric encryption; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Symmetric encryption.
- Keep dependencies patched; pin versions for Symmetric encryption components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Symmetric encryption before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Symmetric encryption paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Asymmetric crypto

**Sub-topics:** RSA padding, ECDH, Signature algorithms, Threat modeling and trust boundaries (Asymmetric crypto), Abuse cases and adversarial testing (Asymmetric crypto)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Asymmetric crypto; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Asymmetric crypto.
- Keep dependencies patched; pin versions for Asymmetric crypto components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Asymmetric crypto before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Asymmetric crypto paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Hashing and passwords

**Sub-topics:** bcrypt/argon2, SHA-256 misuse, Threat modeling and trust boundaries (Hashing and passwords), Abuse cases and adversarial testing (Hashing and passwords), Logging, audit, and detection (Hashing and passwords)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Hashing and passwords; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Hashing and passwords.
- Keep dependencies patched; pin versions for Hashing and passwords components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Hashing and passwords before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Hashing and passwords paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Randomness and IDs

**Sub-topics:** CSPRNG, Predictable UUIDs, Threat modeling and trust boundaries (Randomness and IDs), Abuse cases and adversarial testing (Randomness and IDs), Logging, audit, and detection (Randomness and IDs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Randomness and IDs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Randomness and IDs.
- Keep dependencies patched; pin versions for Randomness and IDs components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Randomness and IDs before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Randomness and IDs paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## KMS and HSM

**Sub-topics:** Envelope encryption, Cloud KMS policies, Threat modeling and trust boundaries (KMS and HSM), Abuse cases and adversarial testing (KMS and HSM), Logging, audit, and detection (KMS and HSM)

### Platform rules (summary)

- Validate and canonicalize all inputs touching KMS and HSM; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to KMS and HSM.
- Keep dependencies patched; pin versions for KMS and HSM components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for KMS and HSM before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for KMS and HSM paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## JWT and JOSE

**Sub-topics:** alg none, Key confusion, JWK sets, Threat modeling and trust boundaries (JWT and JOSE), Abuse cases and adversarial testing (JWT and JOSE)

### Platform rules (summary)

- Validate and canonicalize all inputs touching JWT and JOSE; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to JWT and JOSE.
- Keep dependencies patched; pin versions for JWT and JOSE components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for JWT and JOSE before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for JWT and JOSE paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## PGP and email crypto

**Sub-topics:** Key management, Ubiquitous encryption gaps, Threat modeling and trust boundaries (PGP and email crypto), Abuse cases and adversarial testing (PGP and email crypto), Logging, audit, and detection (PGP and email crypto)

### Platform rules (summary)

- Validate and canonicalize all inputs touching PGP and email crypto; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PGP and email crypto.
- Keep dependencies patched; pin versions for PGP and email crypto components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PGP and email crypto before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PGP and email crypto paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Specialized crypto uses

**Sub-topics:** Tokenization, Format-preserving, Threat modeling and trust boundaries (Specialized crypto uses), Abuse cases and adversarial testing (Specialized crypto uses), Logging, audit, and detection (Specialized crypto uses)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Specialized crypto uses; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Specialized crypto uses.
- Keep dependencies patched; pin versions for Specialized crypto uses components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Specialized crypto uses before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Specialized crypto uses paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Crypto agility

**Sub-topics:** Algorithm deprecation, Inventory, Threat modeling and trust boundaries (Crypto agility), Abuse cases and adversarial testing (Crypto agility), Logging, audit, and detection (Crypto agility)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Crypto agility; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Crypto agility.
- Keep dependencies patched; pin versions for Crypto agility components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Crypto agility before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Crypto agility paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Secrets derivation

**Sub-topics:** PBKDF2, scrypt, HKDF, Threat modeling and trust boundaries (Secrets derivation), Abuse cases and adversarial testing (Secrets derivation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secrets derivation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secrets derivation.
- Keep dependencies patched; pin versions for Secrets derivation components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secrets derivation before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secrets derivation paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Side channels

**Sub-topics:** Constant-time compare, Padding oracles, Threat modeling and trust boundaries (Side channels), Abuse cases and adversarial testing (Side channels), Logging, audit, and detection (Side channels)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Side channels; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Side channels.
- Keep dependencies patched; pin versions for Side channels components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-cryptography` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Side channels before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Side channels paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

