# Rules reference: Cryptography and key management

Algorithms, protocols, keys, and randomness.

## TLS and certificates

Sub-topics: mTLS, Pinning pitfalls, Cert rotation

### Policy

- Treat TLS and certificates in TLS and certificates as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for TLS and certificates (Cryptography and key management).
- Require security review for material changes affecting TLS and certificates.

### Design

- Apply least privilege and defense in depth for TLS and certificates.
- Prefer established patterns and libraries over custom crypto or auth for TLS and certificates.
- Fail closed: deny by default when TLS and certificates cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching TLS and certificates; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to TLS and certificates.
- Keep dependencies patched; pin versions for TLS and certificates components.

### Verification

- Add automated tests and SAST/DAST coverage for TLS and certificates paths.
- Run dependency and secret scanning on every change touching TLS and certificates.
- Perform targeted manual tests (abuse cases) for TLS and certificates.

### Operations

- Log security-relevant events for TLS and certificates without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in TLS and certificates.
- Review access and configuration for TLS and certificates on a regular cadence.

## Symmetric encryption

Sub-topics: AES-GCM, Nonce reuse, Key derivation

### Policy

- Treat Symmetric encryption in Symmetric encryption as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Symmetric encryption (Cryptography and key management).
- Require security review for material changes affecting Symmetric encryption.

### Design

- Apply least privilege and defense in depth for Symmetric encryption.
- Prefer established patterns and libraries over custom crypto or auth for Symmetric encryption.
- Fail closed: deny by default when Symmetric encryption cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Symmetric encryption; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Symmetric encryption.
- Keep dependencies patched; pin versions for Symmetric encryption components.

### Verification

- Add automated tests and SAST/DAST coverage for Symmetric encryption paths.
- Run dependency and secret scanning on every change touching Symmetric encryption.
- Perform targeted manual tests (abuse cases) for Symmetric encryption.

### Operations

- Log security-relevant events for Symmetric encryption without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Symmetric encryption.
- Review access and configuration for Symmetric encryption on a regular cadence.

## Asymmetric crypto

Sub-topics: RSA padding, ECDH, Signature algorithms

### Policy

- Treat Asymmetric crypto in Asymmetric crypto as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Asymmetric crypto (Cryptography and key management).
- Require security review for material changes affecting Asymmetric crypto.

### Design

- Apply least privilege and defense in depth for Asymmetric crypto.
- Prefer established patterns and libraries over custom crypto or auth for Asymmetric crypto.
- Fail closed: deny by default when Asymmetric crypto cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Asymmetric crypto; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Asymmetric crypto.
- Keep dependencies patched; pin versions for Asymmetric crypto components.

### Verification

- Add automated tests and SAST/DAST coverage for Asymmetric crypto paths.
- Run dependency and secret scanning on every change touching Asymmetric crypto.
- Perform targeted manual tests (abuse cases) for Asymmetric crypto.

### Operations

- Log security-relevant events for Asymmetric crypto without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Asymmetric crypto.
- Review access and configuration for Asymmetric crypto on a regular cadence.

## Hashing and passwords

Sub-topics: bcrypt/argon2, SHA-256 misuse

### Policy

- Treat Hashing and passwords in Hashing and passwords as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Hashing and passwords (Cryptography and key management).
- Require security review for material changes affecting Hashing and passwords.

### Design

- Apply least privilege and defense in depth for Hashing and passwords.
- Prefer established patterns and libraries over custom crypto or auth for Hashing and passwords.
- Fail closed: deny by default when Hashing and passwords cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Hashing and passwords; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Hashing and passwords.
- Keep dependencies patched; pin versions for Hashing and passwords components.

### Verification

- Add automated tests and SAST/DAST coverage for Hashing and passwords paths.
- Run dependency and secret scanning on every change touching Hashing and passwords.
- Perform targeted manual tests (abuse cases) for Hashing and passwords.

### Operations

- Log security-relevant events for Hashing and passwords without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Hashing and passwords.
- Review access and configuration for Hashing and passwords on a regular cadence.

## Randomness and IDs

Sub-topics: CSPRNG, Predictable UUIDs

### Policy

- Treat Randomness and IDs in Randomness and IDs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Randomness and IDs (Cryptography and key management).
- Require security review for material changes affecting Randomness and IDs.

### Design

- Apply least privilege and defense in depth for Randomness and IDs.
- Prefer established patterns and libraries over custom crypto or auth for Randomness and IDs.
- Fail closed: deny by default when Randomness and IDs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Randomness and IDs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Randomness and IDs.
- Keep dependencies patched; pin versions for Randomness and IDs components.

### Verification

- Add automated tests and SAST/DAST coverage for Randomness and IDs paths.
- Run dependency and secret scanning on every change touching Randomness and IDs.
- Perform targeted manual tests (abuse cases) for Randomness and IDs.

### Operations

- Log security-relevant events for Randomness and IDs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Randomness and IDs.
- Review access and configuration for Randomness and IDs on a regular cadence.

## KMS and HSM

Sub-topics: Envelope encryption, Cloud KMS policies

### Policy

- Treat KMS and HSM in KMS and HSM as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for KMS and HSM (Cryptography and key management).
- Require security review for material changes affecting KMS and HSM.

### Design

- Apply least privilege and defense in depth for KMS and HSM.
- Prefer established patterns and libraries over custom crypto or auth for KMS and HSM.
- Fail closed: deny by default when KMS and HSM cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching KMS and HSM; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to KMS and HSM.
- Keep dependencies patched; pin versions for KMS and HSM components.

### Verification

- Add automated tests and SAST/DAST coverage for KMS and HSM paths.
- Run dependency and secret scanning on every change touching KMS and HSM.
- Perform targeted manual tests (abuse cases) for KMS and HSM.

### Operations

- Log security-relevant events for KMS and HSM without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in KMS and HSM.
- Review access and configuration for KMS and HSM on a regular cadence.

## JWT and JOSE

Sub-topics: alg none, Key confusion, JWK sets

### Policy

- Treat JWT and JOSE in JWT and JOSE as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for JWT and JOSE (Cryptography and key management).
- Require security review for material changes affecting JWT and JOSE.

### Design

- Apply least privilege and defense in depth for JWT and JOSE.
- Prefer established patterns and libraries over custom crypto or auth for JWT and JOSE.
- Fail closed: deny by default when JWT and JOSE cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching JWT and JOSE; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to JWT and JOSE.
- Keep dependencies patched; pin versions for JWT and JOSE components.

### Verification

- Add automated tests and SAST/DAST coverage for JWT and JOSE paths.
- Run dependency and secret scanning on every change touching JWT and JOSE.
- Perform targeted manual tests (abuse cases) for JWT and JOSE.

### Operations

- Log security-relevant events for JWT and JOSE without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in JWT and JOSE.
- Review access and configuration for JWT and JOSE on a regular cadence.

## PGP and email crypto

Sub-topics: Key management, Ubiquitous encryption gaps

### Policy

- Treat PGP and email crypto in PGP and email crypto as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PGP and email crypto (Cryptography and key management).
- Require security review for material changes affecting PGP and email crypto.

### Design

- Apply least privilege and defense in depth for PGP and email crypto.
- Prefer established patterns and libraries over custom crypto or auth for PGP and email crypto.
- Fail closed: deny by default when PGP and email crypto cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PGP and email crypto; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PGP and email crypto.
- Keep dependencies patched; pin versions for PGP and email crypto components.

### Verification

- Add automated tests and SAST/DAST coverage for PGP and email crypto paths.
- Run dependency and secret scanning on every change touching PGP and email crypto.
- Perform targeted manual tests (abuse cases) for PGP and email crypto.

### Operations

- Log security-relevant events for PGP and email crypto without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PGP and email crypto.
- Review access and configuration for PGP and email crypto on a regular cadence.

## Specialized crypto uses

Sub-topics: Tokenization, Format-preserving

### Policy

- Treat Specialized crypto uses in Specialized crypto uses as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Specialized crypto uses (Cryptography and key management).
- Require security review for material changes affecting Specialized crypto uses.

### Design

- Apply least privilege and defense in depth for Specialized crypto uses.
- Prefer established patterns and libraries over custom crypto or auth for Specialized crypto uses.
- Fail closed: deny by default when Specialized crypto uses cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Specialized crypto uses; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Specialized crypto uses.
- Keep dependencies patched; pin versions for Specialized crypto uses components.

### Verification

- Add automated tests and SAST/DAST coverage for Specialized crypto uses paths.
- Run dependency and secret scanning on every change touching Specialized crypto uses.
- Perform targeted manual tests (abuse cases) for Specialized crypto uses.

### Operations

- Log security-relevant events for Specialized crypto uses without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Specialized crypto uses.
- Review access and configuration for Specialized crypto uses on a regular cadence.

## Crypto agility

Sub-topics: Algorithm deprecation, Inventory

### Policy

- Treat Crypto agility in Crypto agility as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Crypto agility (Cryptography and key management).
- Require security review for material changes affecting Crypto agility.

### Design

- Apply least privilege and defense in depth for Crypto agility.
- Prefer established patterns and libraries over custom crypto or auth for Crypto agility.
- Fail closed: deny by default when Crypto agility cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Crypto agility; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Crypto agility.
- Keep dependencies patched; pin versions for Crypto agility components.

### Verification

- Add automated tests and SAST/DAST coverage for Crypto agility paths.
- Run dependency and secret scanning on every change touching Crypto agility.
- Perform targeted manual tests (abuse cases) for Crypto agility.

### Operations

- Log security-relevant events for Crypto agility without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Crypto agility.
- Review access and configuration for Crypto agility on a regular cadence.

## Secrets derivation

Sub-topics: PBKDF2, scrypt, HKDF

### Policy

- Treat Secrets derivation in Secrets derivation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secrets derivation (Cryptography and key management).
- Require security review for material changes affecting Secrets derivation.

### Design

- Apply least privilege and defense in depth for Secrets derivation.
- Prefer established patterns and libraries over custom crypto or auth for Secrets derivation.
- Fail closed: deny by default when Secrets derivation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secrets derivation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secrets derivation.
- Keep dependencies patched; pin versions for Secrets derivation components.

### Verification

- Add automated tests and SAST/DAST coverage for Secrets derivation paths.
- Run dependency and secret scanning on every change touching Secrets derivation.
- Perform targeted manual tests (abuse cases) for Secrets derivation.

### Operations

- Log security-relevant events for Secrets derivation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secrets derivation.
- Review access and configuration for Secrets derivation on a regular cadence.

## Side channels

Sub-topics: Constant-time compare, Padding oracles

### Policy

- Treat Side channels in Side channels as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Side channels (Cryptography and key management).
- Require security review for material changes affecting Side channels.

### Design

- Apply least privilege and defense in depth for Side channels.
- Prefer established patterns and libraries over custom crypto or auth for Side channels.
- Fail closed: deny by default when Side channels cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Side channels; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Side channels.
- Keep dependencies patched; pin versions for Side channels components.

### Verification

- Add automated tests and SAST/DAST coverage for Side channels paths.
- Run dependency and secret scanning on every change touching Side channels.
- Perform targeted manual tests (abuse cases) for Side channels.

### Operations

- Log security-relevant events for Side channels without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Side channels.
- Review access and configuration for Side channels on a regular cadence.

