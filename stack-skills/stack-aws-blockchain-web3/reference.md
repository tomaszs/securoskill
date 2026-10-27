# Amazon Web Services: Blockchain, Web3, and smart contracts

Stack-specific implementation for **Amazon Web Services** (Cloud). Normative rules: domain skill `security-blockchain-web3` / `reference.md`.

## Smart contract vulnerabilities

**Sub-topics:** Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Platform rules (summary)

- Validate and canonicalize all inputs touching Smart contract vulnerabilities; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Smart contract vulnerabilities.
- Keep dependencies patched; pin versions for Smart contract vulnerabilities components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Smart contract vulnerabilities before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Smart contract vulnerabilities paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## On-chain access control

**Sub-topics:**  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Platform rules (summary)

- Validate and canonicalize all inputs touching On-chain access control; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to On-chain access control.
- Keep dependencies patched; pin versions for On-chain access control components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for On-chain access control before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for On-chain access control paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Oracles and external data

**Sub-topics:** Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Platform rules (summary)

- Validate and canonicalize all inputs touching Oracles and external data; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Oracles and external data.
- Keep dependencies patched; pin versions for Oracles and external data components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Oracles and external data before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Oracles and external data paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Wallet and key security

**Sub-topics:** Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Platform rules (summary)

- Validate and canonicalize all inputs touching Wallet and key security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Wallet and key security.
- Keep dependencies patched; pin versions for Wallet and key security components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Wallet and key security before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Wallet and key security paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## dApp frontends

**Sub-topics:** RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Platform rules (summary)

- Validate and canonicalize all inputs touching dApp frontends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to dApp frontends.
- Keep dependencies patched; pin versions for dApp frontends components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for dApp frontends before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for dApp frontends paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Token standards

**Sub-topics:** ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Platform rules (summary)

- Validate and canonicalize all inputs touching Token standards; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Token standards.
- Keep dependencies patched; pin versions for Token standards components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Token standards before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Token standards paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## DeFi composability

**Sub-topics:** Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Platform rules (summary)

- Validate and canonicalize all inputs touching DeFi composability; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DeFi composability.
- Keep dependencies patched; pin versions for DeFi composability components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for DeFi composability before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for DeFi composability paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## NFTs and metadata

**Sub-topics:** Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Platform rules (summary)

- Validate and canonicalize all inputs touching NFTs and metadata; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NFTs and metadata.
- Keep dependencies patched; pin versions for NFTs and metadata components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for NFTs and metadata before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for NFTs and metadata paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## L2 and bridges

**Sub-topics:** Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Platform rules (summary)

- Validate and canonicalize all inputs touching L2 and bridges; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to L2 and bridges.
- Keep dependencies patched; pin versions for L2 and bridges components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for L2 and bridges before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for L2 and bridges paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Audit and formal methods

**Sub-topics:** Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Platform rules (summary)

- Validate and canonicalize all inputs touching Audit and formal methods; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Audit and formal methods.
- Keep dependencies patched; pin versions for Audit and formal methods components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Audit and formal methods before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Audit and formal methods paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## On-chain privacy

**Sub-topics:** Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Platform rules (summary)

- Validate and canonicalize all inputs touching On-chain privacy; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to On-chain privacy.
- Keep dependencies patched; pin versions for On-chain privacy components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for On-chain privacy before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for On-chain privacy paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

## Compliance and sanctions

**Sub-topics:** OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Platform rules (summary)

- Validate and canonicalize all inputs touching Compliance and sanctions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Compliance and sanctions.
- Keep dependencies patched; pin versions for Compliance and sanctions components.

### How to do this in Amazon Web Services

- Read normative rules in domain skill `security-blockchain-web3` / `reference.md`, then apply them using Amazon Web Services APIs and deployment model.
- Prefer framework-maintained security features in Amazon Web Services over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Compliance and sanctions before merge.
- Pin Amazon Web Services dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Compliance and sanctions paths in Amazon Web Services.
- Run SAST/dependency scan configured for Cloud.

