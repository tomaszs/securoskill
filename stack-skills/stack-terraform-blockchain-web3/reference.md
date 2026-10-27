# Terraform: Blockchain, Web3, and smart contracts

Stack-specific implementation for **Terraform** (Infrastructure). Normative rules: domain skill `security-blockchain-web3` / `reference.md`.

## Smart contract vulnerabilities

**Sub-topics:** Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Do (use this in Terraform)

- Use Checks-Effects-Interactions; OpenZeppelin `ReentrancyGuard`.
- Run Slither/Mythril before deploy.

### Don't

- Do not use `tx.origin` for auth.
- Do not leave unprotected `selfdestruct` or `delegatecall` to user addresses.

### Verify

- Invariant tests with Foundry/Hardhat.

## On-chain access control

**Sub-topics:**  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Oracles and external data

**Sub-topics:** Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Wallet and key security

**Sub-topics:** Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## dApp frontends

**Sub-topics:** RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Token standards

**Sub-topics:** ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## DeFi composability

**Sub-topics:** Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## NFTs and metadata

**Sub-topics:** Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## L2 and bridges

**Sub-topics:** Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Audit and formal methods

**Sub-topics:** Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## On-chain privacy

**Sub-topics:** Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Compliance and sanctions

**Sub-topics:** OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

