# Fastify: Blockchain, Web3, and smart contracts

Stack-specific implementation for **Fastify** (Node.js server). Normative rules: domain skill `security-blockchain-web3` / `reference.md`.

## Smart contract vulnerabilities

**Sub-topics:** Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Do (use this in Fastify)

- Use Checks-Effects-Interactions; OpenZeppelin `ReentrancyGuard`.
- Run Slither/Mythril before deploy.

### Don't

- Do not use `tx.origin` for auth.
- Do not leave unprotected `selfdestruct` or `delegatecall` to user addresses.

### Verify

- Invariant tests with Foundry/Hardhat.

## On-chain access control

**Sub-topics:**  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for onchain_acl controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## Oracles and external data

**Sub-topics:** Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for oracles controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## Wallet and key security

**Sub-topics:** Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for wallet controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## dApp frontends

**Sub-topics:** RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for dapp controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## Token standards

**Sub-topics:** ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for tokens controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## DeFi composability

**Sub-topics:** Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for defi controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## NFTs and metadata

**Sub-topics:** Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for nft controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## L2 and bridges

**Sub-topics:** Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for l2 controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## Audit and formal methods

**Sub-topics:** Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for contract_audit controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## On-chain privacy

**Sub-topics:** Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for chain_privacy controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

## Compliance and sanctions

**Sub-topics:** OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Do (use this in Fastify)

- Apply domain skill `security-blockchain-web3` requirements using fastify supported APIs only.
- Use the official fastify security documentation for web3_compliance controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of fastify for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on fastify projects in CI.

