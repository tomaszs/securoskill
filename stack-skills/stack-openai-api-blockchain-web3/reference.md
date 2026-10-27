# OpenAI API / Agents SDK: Blockchain, Web3, and smart contracts

Stack-specific implementation for **OpenAI API / Agents SDK** (AI). Normative rules: domain skill `security-blockchain-web3` / `reference.md`.

## Smart contract vulnerabilities

**Sub-topics:** Reentrancy, Integer overflow, Unchecked calls, Delegatecall, Tx.origin auth

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## On-chain access control

**Sub-topics:**  Ownable, Roles, Timelocks, Multisig, Upgrade proxies

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Oracles and external data

**Sub-topics:** Price manipulation, Stale data, Flash loans, Bridge trust, Signature replay

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Wallet and key security

**Sub-topics:** Seed phrases, Hardware wallets, Browser extensions, Phishing sites, Clipboard malware

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## dApp frontends

**Sub-topics:** RPC endpoints, Chain ID, Wallet connect, Transaction preview, Malicious approvals

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Token standards

**Sub-topics:** ERC-20 quirks, ERC-721 callbacks, Permit signatures, Infinite approve, Fee-on-transfer

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## DeFi composability

**Sub-topics:** Liquidity pools, Governance attacks, MEV, Sandwiching, Rug patterns

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## NFTs and metadata

**Sub-topics:** Off-chain metadata, IPFS pinning, Royalty bypass, Signature mint, Open redirects

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## L2 and bridges

**Sub-topics:** Withdrawal delays, Sequencer trust, Bridge exploits, Finality, Replay across chains

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Audit and formal methods

**Sub-topics:** Slither, Mythril, Invariant tests, Bug bounty, Immunefi

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## On-chain privacy

**Sub-topics:** Address linking, Mixer legal risk, ZK proofs, Metadata leaks, KYC on ramps

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

## Compliance and sanctions

**Sub-topics:** OFAC lists, Travel rule, Geoblocking, Securities law, Tax reporting

### Do (use this in OpenAI API / Agents SDK)

- Use Structured Outputs / JSON schema for tool parameters.
- Set per-user rate limits and `max_tokens` ceilings in API gateway.

### Don't

- Do not send API keys to browsers; proxy via your backend.
- Do not auto-run tool results that contain `rm`, `DROP`, or `curl` without approval.

### Verify

- Log prompt injections attempts; alert on repeated jailbreak patterns.

