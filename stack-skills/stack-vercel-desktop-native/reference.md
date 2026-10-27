# Vercel: Desktop and native application security

Stack-specific implementation for **Vercel** (Platform). Normative rules: domain skill `security-desktop-native` / `reference.md`.

## Electron hardening

**Sub-topics:** nodeIntegration, contextIsolation, Remote module, Preload scripts, Custom protocols

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Tauri and hybrid native

**Sub-topics:** IPC surface, Capability permissions, Rust side APIs, Webview updates, Deep links

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Auto-update channels

**Sub-topics:** Code signing, Update signatures, Downgrade attacks, CDN compromise, Delta patches

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## OS sandbox and permissions

**Sub-topics:** macOS sandbox, Windows capabilities, Linux portals, UAC prompts, TCC on macOS

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Local privilege escalation

**Sub-topics:** Installer perms, DLL hijacking, Setuid helpers, Symbolic links, Shatter attacks

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Clipboard and screen capture

**Sub-topics:** Sensitive copy, Overlay malware, Screen recording APIs, Notification leaks, Memory scraping

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## File handlers and URIs

**Sub-topics:** Custom scheme handlers, Path traversal open, Macro documents, Drag-drop, UNC paths

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## IPC between components

**Sub-topics:** Named pipes, DBus, XPC, COM objects, Message validation

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## OS credential storage

**Sub-topics:** Keychain, Credential Manager, Secret Service, Biometric APIs, Master password

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Debug symbols and dumps

**Sub-topics:** Crash reports PII, Core dumps, Symbol servers, Reversing resistance, Obfuscation limits

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Enterprise deployment

**Sub-topics:** MDM packages, Notarization, SmartScreen, Gatekeeper, AppLocker

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

## Offline-first apps

**Sub-topics:** Local DB encryption, Sync conflict, Cached tokens, Backup files, Shared machines

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `desktop-native`; load stack skill `security-desktop-native` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-desktop-native` (domain reference.md).

### Don't

- Do not duplicate `desktop-native` controls only in Vercel config while leaving security-desktop-native misconfigured.
- Do not assume Vercel defaults satisfy `security-desktop-native` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-desktop-native`.

