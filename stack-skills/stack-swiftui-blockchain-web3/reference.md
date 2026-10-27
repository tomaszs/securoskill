# SwiftUI (iOS): Blockchain, Web3, and smart contracts

Stack-specific implementation for **SwiftUI (iOS)** (Mobile). Normative rules: domain skill `security-blockchain-web3` / `reference.md`.

## Smart contract vulnerabilities

**Sub-topics:** Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Do (use this in SwiftUI (iOS))

- Use Checks-Effects-Interactions; OpenZeppelin `ReentrancyGuard`.
- Run Slither/Mythril before deploy.

### Don't

- Do not use `tx.origin` for auth.
- Do not leave unprotected `selfdestruct` or `delegatecall` to user addresses.

### Verify

- Invariant tests with Foundry/Hardhat.

## On-chain access control

**Sub-topics:**  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Oracles and external data

**Sub-topics:** Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Wallet and key security

**Sub-topics:** Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## dApp frontends

**Sub-topics:** RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Token standards

**Sub-topics:** ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## DeFi composability

**Sub-topics:** Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## NFTs and metadata

**Sub-topics:** Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## L2 and bridges

**Sub-topics:** Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Audit and formal methods

**Sub-topics:** Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## On-chain privacy

**Sub-topics:** Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Compliance and sanctions

**Sub-topics:** OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

