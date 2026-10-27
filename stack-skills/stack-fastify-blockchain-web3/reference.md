# Fastify: Blockchain, Web3, and smart contracts

Stack-specific implementation for **Fastify** (Node.js server). Normative rules: domain skill `security-blockchain-web3` / `reference.md`.

## Smart contract vulnerabilities

**Sub-topics:** Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## On-chain access control

**Sub-topics:**  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## Oracles and external data

**Sub-topics:** Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## Wallet and key security

**Sub-topics:** Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## dApp frontends

**Sub-topics:** RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## Token standards

**Sub-topics:** ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## DeFi composability

**Sub-topics:** Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## NFTs and metadata

**Sub-topics:** Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## L2 and bridges

**Sub-topics:** Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## Audit and formal methods

**Sub-topics:** Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## On-chain privacy

**Sub-topics:** Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

## Compliance and sanctions

**Sub-topics:** OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Do (use this in Fastify)

- Fastify is not the primary enforcement point for `blockchain-web3`; load stack skill `security-blockchain-web3` when you touch that layer.
- Keep Fastify configuration aligned with requirements from `security-blockchain-web3` (domain reference.md).

### Don't

- Do not duplicate `blockchain-web3` controls only in Fastify config while leaving security-blockchain-web3 misconfigured.
- Do not assume Fastify defaults satisfy `security-blockchain-web3` without verification.

### Verify

- Integration test the full path: Fastify plus the system covered by `security-blockchain-web3`.

