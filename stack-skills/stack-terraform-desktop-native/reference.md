# Terraform: Desktop and native application security

Stack-specific implementation for **Terraform** (Infrastructure). Normative rules: domain skill `security-desktop-native` / `reference.md`.

## Electron hardening

**Sub-topics:** nodeIntegration, contextIsolation, Remote module, Preload scripts, Custom protocols

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Tauri and hybrid native

**Sub-topics:** IPC surface, Capability permissions, Rust side APIs, Webview updates, Deep links

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Auto-update channels

**Sub-topics:** Code signing, Update signatures, Downgrade attacks, CDN compromise, Delta patches

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## OS sandbox and permissions

**Sub-topics:** macOS sandbox, Windows capabilities, Linux portals, UAC prompts, TCC on macOS

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Local privilege escalation

**Sub-topics:** Installer perms, DLL hijacking, Setuid helpers, Symbolic links, Shatter attacks

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Clipboard and screen capture

**Sub-topics:** Sensitive copy, Overlay malware, Screen recording APIs, Notification leaks, Memory scraping

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## File handlers and URIs

**Sub-topics:** Custom scheme handlers, Path traversal open, Macro documents, Drag-drop, UNC paths

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## IPC between components

**Sub-topics:** Named pipes, DBus, XPC, COM objects, Message validation

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## OS credential storage

**Sub-topics:** Keychain, Credential Manager, Secret Service, Biometric APIs, Master password

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Debug symbols and dumps

**Sub-topics:** Crash reports PII, Core dumps, Symbol servers, Reversing resistance, Obfuscation limits

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Enterprise deployment

**Sub-topics:** MDM packages, Notarization, SmartScreen, Gatekeeper, AppLocker

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Offline-first apps

**Sub-topics:** Local DB encryption, Sync conflict, Cached tokens, Backup files, Shared machines

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

