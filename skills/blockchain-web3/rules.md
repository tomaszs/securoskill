# Rules reference: Blockchain, Web3, and smart contracts

On-chain logic, wallets, and decentralized apps.

## Smart contract vulnerabilities

Sub-topics: Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Policy

- Treat Smart contract vulnerabilities in Smart contract vulnerabilities as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Smart contract vulnerabilities (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting Smart contract vulnerabilities.

### Design

- Apply least privilege and defense in depth for Smart contract vulnerabilities.
- Prefer established patterns and libraries over custom crypto or auth for Smart contract vulnerabilities.
- Fail closed: deny by default when Smart contract vulnerabilities cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Smart contract vulnerabilities; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Smart contract vulnerabilities.
- Keep dependencies patched; pin versions for Smart contract vulnerabilities components.

### Verification

- Add automated tests and SAST/DAST coverage for Smart contract vulnerabilities paths.
- Run dependency and secret scanning on every change touching Smart contract vulnerabilities.
- Perform targeted manual tests (abuse cases) for Smart contract vulnerabilities.

### Operations

- Log security-relevant events for Smart contract vulnerabilities without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Smart contract vulnerabilities.
- Review access and configuration for Smart contract vulnerabilities on a regular cadence.

## On-chain access control

Sub-topics:  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Policy

- Treat On-chain access control in On-chain access control as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for On-chain access control (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting On-chain access control.

### Design

- Apply least privilege and defense in depth for On-chain access control.
- Prefer established patterns and libraries over custom crypto or auth for On-chain access control.
- Fail closed: deny by default when On-chain access control cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching On-chain access control; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to On-chain access control.
- Keep dependencies patched; pin versions for On-chain access control components.

### Verification

- Add automated tests and SAST/DAST coverage for On-chain access control paths.
- Run dependency and secret scanning on every change touching On-chain access control.
- Perform targeted manual tests (abuse cases) for On-chain access control.

### Operations

- Log security-relevant events for On-chain access control without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in On-chain access control.
- Review access and configuration for On-chain access control on a regular cadence.

## Oracles and external data

Sub-topics: Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Policy

- Treat Oracles and external data in Oracles and external data as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Oracles and external data (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting Oracles and external data.

### Design

- Apply least privilege and defense in depth for Oracles and external data.
- Prefer established patterns and libraries over custom crypto or auth for Oracles and external data.
- Fail closed: deny by default when Oracles and external data cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Oracles and external data; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Oracles and external data.
- Keep dependencies patched; pin versions for Oracles and external data components.

### Verification

- Add automated tests and SAST/DAST coverage for Oracles and external data paths.
- Run dependency and secret scanning on every change touching Oracles and external data.
- Perform targeted manual tests (abuse cases) for Oracles and external data.

### Operations

- Log security-relevant events for Oracles and external data without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Oracles and external data.
- Review access and configuration for Oracles and external data on a regular cadence.

## Wallet and key security

Sub-topics: Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Policy

- Treat Wallet and key security in Wallet and key security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Wallet and key security (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting Wallet and key security.

### Design

- Apply least privilege and defense in depth for Wallet and key security.
- Prefer established patterns and libraries over custom crypto or auth for Wallet and key security.
- Fail closed: deny by default when Wallet and key security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Wallet and key security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Wallet and key security.
- Keep dependencies patched; pin versions for Wallet and key security components.

### Verification

- Add automated tests and SAST/DAST coverage for Wallet and key security paths.
- Run dependency and secret scanning on every change touching Wallet and key security.
- Perform targeted manual tests (abuse cases) for Wallet and key security.

### Operations

- Log security-relevant events for Wallet and key security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Wallet and key security.
- Review access and configuration for Wallet and key security on a regular cadence.

## dApp frontends

Sub-topics: RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Policy

- Treat dApp frontends in dApp frontends as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for dApp frontends (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting dApp frontends.

### Design

- Apply least privilege and defense in depth for dApp frontends.
- Prefer established patterns and libraries over custom crypto or auth for dApp frontends.
- Fail closed: deny by default when dApp frontends cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching dApp frontends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to dApp frontends.
- Keep dependencies patched; pin versions for dApp frontends components.

### Verification

- Add automated tests and SAST/DAST coverage for dApp frontends paths.
- Run dependency and secret scanning on every change touching dApp frontends.
- Perform targeted manual tests (abuse cases) for dApp frontends.

### Operations

- Log security-relevant events for dApp frontends without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in dApp frontends.
- Review access and configuration for dApp frontends on a regular cadence.

## Token standards

Sub-topics: ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Policy

- Treat Token standards in Token standards as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Token standards (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting Token standards.

### Design

- Apply least privilege and defense in depth for Token standards.
- Prefer established patterns and libraries over custom crypto or auth for Token standards.
- Fail closed: deny by default when Token standards cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Token standards; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Token standards.
- Keep dependencies patched; pin versions for Token standards components.

### Verification

- Add automated tests and SAST/DAST coverage for Token standards paths.
- Run dependency and secret scanning on every change touching Token standards.
- Perform targeted manual tests (abuse cases) for Token standards.

### Operations

- Log security-relevant events for Token standards without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Token standards.
- Review access and configuration for Token standards on a regular cadence.

## DeFi composability

Sub-topics: Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Policy

- Treat DeFi composability in DeFi composability as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for DeFi composability (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting DeFi composability.

### Design

- Apply least privilege and defense in depth for DeFi composability.
- Prefer established patterns and libraries over custom crypto or auth for DeFi composability.
- Fail closed: deny by default when DeFi composability cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching DeFi composability; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DeFi composability.
- Keep dependencies patched; pin versions for DeFi composability components.

### Verification

- Add automated tests and SAST/DAST coverage for DeFi composability paths.
- Run dependency and secret scanning on every change touching DeFi composability.
- Perform targeted manual tests (abuse cases) for DeFi composability.

### Operations

- Log security-relevant events for DeFi composability without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in DeFi composability.
- Review access and configuration for DeFi composability on a regular cadence.

## NFTs and metadata

Sub-topics: Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Policy

- Treat NFTs and metadata in NFTs and metadata as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for NFTs and metadata (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting NFTs and metadata.

### Design

- Apply least privilege and defense in depth for NFTs and metadata.
- Prefer established patterns and libraries over custom crypto or auth for NFTs and metadata.
- Fail closed: deny by default when NFTs and metadata cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching NFTs and metadata; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NFTs and metadata.
- Keep dependencies patched; pin versions for NFTs and metadata components.

### Verification

- Add automated tests and SAST/DAST coverage for NFTs and metadata paths.
- Run dependency and secret scanning on every change touching NFTs and metadata.
- Perform targeted manual tests (abuse cases) for NFTs and metadata.

### Operations

- Log security-relevant events for NFTs and metadata without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in NFTs and metadata.
- Review access and configuration for NFTs and metadata on a regular cadence.

## L2 and bridges

Sub-topics: Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Policy

- Treat L2 and bridges in L2 and bridges as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for L2 and bridges (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting L2 and bridges.

### Design

- Apply least privilege and defense in depth for L2 and bridges.
- Prefer established patterns and libraries over custom crypto or auth for L2 and bridges.
- Fail closed: deny by default when L2 and bridges cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching L2 and bridges; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to L2 and bridges.
- Keep dependencies patched; pin versions for L2 and bridges components.

### Verification

- Add automated tests and SAST/DAST coverage for L2 and bridges paths.
- Run dependency and secret scanning on every change touching L2 and bridges.
- Perform targeted manual tests (abuse cases) for L2 and bridges.

### Operations

- Log security-relevant events for L2 and bridges without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in L2 and bridges.
- Review access and configuration for L2 and bridges on a regular cadence.

## Audit and formal methods

Sub-topics: Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Policy

- Treat Audit and formal methods in Audit and formal methods as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Audit and formal methods (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting Audit and formal methods.

### Design

- Apply least privilege and defense in depth for Audit and formal methods.
- Prefer established patterns and libraries over custom crypto or auth for Audit and formal methods.
- Fail closed: deny by default when Audit and formal methods cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Audit and formal methods; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Audit and formal methods.
- Keep dependencies patched; pin versions for Audit and formal methods components.

### Verification

- Add automated tests and SAST/DAST coverage for Audit and formal methods paths.
- Run dependency and secret scanning on every change touching Audit and formal methods.
- Perform targeted manual tests (abuse cases) for Audit and formal methods.

### Operations

- Log security-relevant events for Audit and formal methods without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Audit and formal methods.
- Review access and configuration for Audit and formal methods on a regular cadence.

## On-chain privacy

Sub-topics: Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Policy

- Treat On-chain privacy in On-chain privacy as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for On-chain privacy (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting On-chain privacy.

### Design

- Apply least privilege and defense in depth for On-chain privacy.
- Prefer established patterns and libraries over custom crypto or auth for On-chain privacy.
- Fail closed: deny by default when On-chain privacy cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching On-chain privacy; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to On-chain privacy.
- Keep dependencies patched; pin versions for On-chain privacy components.

### Verification

- Add automated tests and SAST/DAST coverage for On-chain privacy paths.
- Run dependency and secret scanning on every change touching On-chain privacy.
- Perform targeted manual tests (abuse cases) for On-chain privacy.

### Operations

- Log security-relevant events for On-chain privacy without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in On-chain privacy.
- Review access and configuration for On-chain privacy on a regular cadence.

## Compliance and sanctions

Sub-topics: OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Policy

- Treat Compliance and sanctions in Compliance and sanctions as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Compliance and sanctions (Blockchain, Web3, and smart contracts).
- Require security review for material changes affecting Compliance and sanctions.

### Design

- Apply least privilege and defense in depth for Compliance and sanctions.
- Prefer established patterns and libraries over custom crypto or auth for Compliance and sanctions.
- Fail closed: deny by default when Compliance and sanctions cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Compliance and sanctions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Compliance and sanctions.
- Keep dependencies patched; pin versions for Compliance and sanctions components.

### Verification

- Add automated tests and SAST/DAST coverage for Compliance and sanctions paths.
- Run dependency and secret scanning on every change touching Compliance and sanctions.
- Perform targeted manual tests (abuse cases) for Compliance and sanctions.

### Operations

- Log security-relevant events for Compliance and sanctions without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Compliance and sanctions.
- Review access and configuration for Compliance and sanctions on a regular cadence.

