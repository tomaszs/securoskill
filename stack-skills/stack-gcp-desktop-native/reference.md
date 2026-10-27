# Google Cloud: Desktop and native application security

Stack-specific implementation for **Google Cloud** (Cloud). Normative rules: domain skill `security-desktop-native` / `reference.md`.

## Electron hardening

**Sub-topics:** nodeIntegration, contextIsolation, Remote module, Preload scripts, Custom protocols

### Platform rules (summary)

- Validate and canonicalize all inputs touching Electron hardening; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Electron hardening.
- Keep dependencies patched; pin versions for Electron hardening components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Electron hardening before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Electron hardening paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Tauri and hybrid native

**Sub-topics:** IPC surface, Capability permissions, Rust side APIs, Webview updates, Deep links

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tauri and hybrid native; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tauri and hybrid native.
- Keep dependencies patched; pin versions for Tauri and hybrid native components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tauri and hybrid native before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tauri and hybrid native paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Auto-update channels

**Sub-topics:** Code signing, Update signatures, Downgrade attacks, CDN compromise, Delta patches

### Platform rules (summary)

- Validate and canonicalize all inputs touching Auto-update channels; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Auto-update channels.
- Keep dependencies patched; pin versions for Auto-update channels components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Auto-update channels before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Auto-update channels paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## OS sandbox and permissions

**Sub-topics:** macOS sandbox, Windows capabilities, Linux portals, UAC prompts, TCC on macOS

### Platform rules (summary)

- Validate and canonicalize all inputs touching OS sandbox and permissions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OS sandbox and permissions.
- Keep dependencies patched; pin versions for OS sandbox and permissions components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for OS sandbox and permissions before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for OS sandbox and permissions paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Local privilege escalation

**Sub-topics:** Installer perms, DLL hijacking, Setuid helpers, Symbolic links, Shatter attacks

### Platform rules (summary)

- Validate and canonicalize all inputs touching Local privilege escalation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Local privilege escalation.
- Keep dependencies patched; pin versions for Local privilege escalation components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Local privilege escalation before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Local privilege escalation paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Clipboard and screen capture

**Sub-topics:** Sensitive copy, Overlay malware, Screen recording APIs, Notification leaks, Memory scraping

### Platform rules (summary)

- Validate and canonicalize all inputs touching Clipboard and screen capture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Clipboard and screen capture.
- Keep dependencies patched; pin versions for Clipboard and screen capture components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Clipboard and screen capture before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Clipboard and screen capture paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## File handlers and URIs

**Sub-topics:** Custom scheme handlers, Path traversal open, Macro documents, Drag-drop, UNC paths

### Platform rules (summary)

- Validate and canonicalize all inputs touching File handlers and URIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to File handlers and URIs.
- Keep dependencies patched; pin versions for File handlers and URIs components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for File handlers and URIs before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for File handlers and URIs paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## IPC between components

**Sub-topics:** Named pipes, DBus, XPC, COM objects, Message validation

### Platform rules (summary)

- Validate and canonicalize all inputs touching IPC between components; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IPC between components.
- Keep dependencies patched; pin versions for IPC between components components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for IPC between components before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for IPC between components paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## OS credential storage

**Sub-topics:** Keychain, Credential Manager, Secret Service, Biometric APIs, Master password

### Platform rules (summary)

- Validate and canonicalize all inputs touching OS credential storage; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OS credential storage.
- Keep dependencies patched; pin versions for OS credential storage components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for OS credential storage before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for OS credential storage paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Debug symbols and dumps

**Sub-topics:** Crash reports PII, Core dumps, Symbol servers, Reversing resistance, Obfuscation limits

### Platform rules (summary)

- Validate and canonicalize all inputs touching Debug symbols and dumps; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Debug symbols and dumps.
- Keep dependencies patched; pin versions for Debug symbols and dumps components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Debug symbols and dumps before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Debug symbols and dumps paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Enterprise deployment

**Sub-topics:** MDM packages, Notarization, SmartScreen, Gatekeeper, AppLocker

### Platform rules (summary)

- Validate and canonicalize all inputs touching Enterprise deployment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Enterprise deployment.
- Keep dependencies patched; pin versions for Enterprise deployment components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Enterprise deployment before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Enterprise deployment paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

## Offline-first apps

**Sub-topics:** Local DB encryption, Sync conflict, Cached tokens, Backup files, Shared machines

### Platform rules (summary)

- Validate and canonicalize all inputs touching Offline-first apps; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Offline-first apps.
- Keep dependencies patched; pin versions for Offline-first apps components.

### How to do this in Google Cloud

- Read normative rules in domain skill `security-desktop-native` / `reference.md`, then apply them using Google Cloud APIs and deployment model.
- Prefer framework-maintained security features in Google Cloud over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Offline-first apps before merge.
- Pin Google Cloud dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Offline-first apps paths in Google Cloud.
- Run SAST/dependency scan configured for Cloud.

