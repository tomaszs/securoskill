# Vercel: Desktop and native application security

Stack-specific implementation for **Vercel** (Platform). Normative rules: domain skill `security-desktop-native` / `reference.md`.

## Electron hardening

**Sub-topics:** nodeIntegration, contextIsolation, Remote module, Preload scripts, Custom protocols

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for electron controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Tauri and hybrid native

**Sub-topics:** IPC surface, Capability permissions, Rust side APIs, Webview updates, Deep links

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for tauri controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Auto-update channels

**Sub-topics:** Code signing, Update signatures, Downgrade attacks, CDN compromise, Delta patches

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for desktop_update controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## OS sandbox and permissions

**Sub-topics:** macOS sandbox, Windows capabilities, Linux portals, UAC prompts, TCC on macOS

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for os_sandbox controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Local privilege escalation

**Sub-topics:** Installer perms, DLL hijacking, Setuid helpers, Symbolic links, Shatter attacks

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for local_privesc controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Clipboard and screen capture

**Sub-topics:** Sensitive copy, Overlay malware, Screen recording APIs, Notification leaks, Memory scraping

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for clipboard controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## File handlers and URIs

**Sub-topics:** Custom scheme handlers, Path traversal open, Macro documents, Drag-drop, UNC paths

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for file_handlers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## IPC between components

**Sub-topics:** Named pipes, DBus, XPC, COM objects, Message validation

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for ipc controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## OS credential storage

**Sub-topics:** Keychain, Credential Manager, Secret Service, Biometric APIs, Master password

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for os_credential controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Debug symbols and dumps

**Sub-topics:** Crash reports PII, Core dumps, Symbol servers, Reversing resistance, Obfuscation limits

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for debug_symbols controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Enterprise deployment

**Sub-topics:** MDM packages, Notarization, SmartScreen, Gatekeeper, AppLocker

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for enterprise_desktop controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Offline-first apps

**Sub-topics:** Local DB encryption, Sync conflict, Cached tokens, Backup files, Shared machines

### Do (use this in Vercel)

- Apply domain skill `security-desktop-native` requirements using vercel supported APIs only.
- Use the official vercel security documentation for offline_desktop controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

