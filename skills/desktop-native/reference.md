# Rules reference: Desktop and native application security

Electron, Tauri, OS APIs, and installed software.

## Electron hardening

Sub-topics: nodeIntegration, contextIsolation, Remote module, Preload scripts, Custom protocols

### Policy

- Treat Electron hardening in Electron hardening as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Electron hardening (Desktop and native application security).
- Require security review for material changes affecting Electron hardening.

### Design

- Apply least privilege and defense in depth for Electron hardening.
- Prefer established patterns and libraries over custom crypto or auth for Electron hardening.
- Fail closed: deny by default when Electron hardening cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Electron hardening; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Electron hardening.
- Keep dependencies patched; pin versions for Electron hardening components.

### Verification

- Add automated tests and SAST/DAST coverage for Electron hardening paths.
- Run dependency and secret scanning on every change touching Electron hardening.
- Perform targeted manual tests (abuse cases) for Electron hardening.

### Operations

- Log security-relevant events for Electron hardening without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Electron hardening.
- Review access and configuration for Electron hardening on a regular cadence.

## Tauri and hybrid native

Sub-topics: IPC surface, Capability permissions, Rust side APIs, Webview updates, Deep links

### Policy

- Treat Tauri and hybrid native in Tauri and hybrid native as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tauri and hybrid native (Desktop and native application security).
- Require security review for material changes affecting Tauri and hybrid native.

### Design

- Apply least privilege and defense in depth for Tauri and hybrid native.
- Prefer established patterns and libraries over custom crypto or auth for Tauri and hybrid native.
- Fail closed: deny by default when Tauri and hybrid native cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tauri and hybrid native; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tauri and hybrid native.
- Keep dependencies patched; pin versions for Tauri and hybrid native components.

### Verification

- Add automated tests and SAST/DAST coverage for Tauri and hybrid native paths.
- Run dependency and secret scanning on every change touching Tauri and hybrid native.
- Perform targeted manual tests (abuse cases) for Tauri and hybrid native.

### Operations

- Log security-relevant events for Tauri and hybrid native without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tauri and hybrid native.
- Review access and configuration for Tauri and hybrid native on a regular cadence.

## Auto-update channels

Sub-topics: Code signing, Update signatures, Downgrade attacks, CDN compromise, Delta patches

### Policy

- Treat Auto-update channels in Auto-update channels as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Auto-update channels (Desktop and native application security).
- Require security review for material changes affecting Auto-update channels.

### Design

- Apply least privilege and defense in depth for Auto-update channels.
- Prefer established patterns and libraries over custom crypto or auth for Auto-update channels.
- Fail closed: deny by default when Auto-update channels cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Auto-update channels; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Auto-update channels.
- Keep dependencies patched; pin versions for Auto-update channels components.

### Verification

- Add automated tests and SAST/DAST coverage for Auto-update channels paths.
- Run dependency and secret scanning on every change touching Auto-update channels.
- Perform targeted manual tests (abuse cases) for Auto-update channels.

### Operations

- Log security-relevant events for Auto-update channels without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Auto-update channels.
- Review access and configuration for Auto-update channels on a regular cadence.

## OS sandbox and permissions

Sub-topics: macOS sandbox, Windows capabilities, Linux portals, UAC prompts, TCC on macOS

### Policy

- Treat OS sandbox and permissions in OS sandbox and permissions as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for OS sandbox and permissions (Desktop and native application security).
- Require security review for material changes affecting OS sandbox and permissions.

### Design

- Apply least privilege and defense in depth for OS sandbox and permissions.
- Prefer established patterns and libraries over custom crypto or auth for OS sandbox and permissions.
- Fail closed: deny by default when OS sandbox and permissions cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching OS sandbox and permissions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OS sandbox and permissions.
- Keep dependencies patched; pin versions for OS sandbox and permissions components.

### Verification

- Add automated tests and SAST/DAST coverage for OS sandbox and permissions paths.
- Run dependency and secret scanning on every change touching OS sandbox and permissions.
- Perform targeted manual tests (abuse cases) for OS sandbox and permissions.

### Operations

- Log security-relevant events for OS sandbox and permissions without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in OS sandbox and permissions.
- Review access and configuration for OS sandbox and permissions on a regular cadence.

## Local privilege escalation

Sub-topics: Installer perms, DLL hijacking, Setuid helpers, Symbolic links, Shatter attacks

### Policy

- Treat Local privilege escalation in Local privilege escalation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Local privilege escalation (Desktop and native application security).
- Require security review for material changes affecting Local privilege escalation.

### Design

- Apply least privilege and defense in depth for Local privilege escalation.
- Prefer established patterns and libraries over custom crypto or auth for Local privilege escalation.
- Fail closed: deny by default when Local privilege escalation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Local privilege escalation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Local privilege escalation.
- Keep dependencies patched; pin versions for Local privilege escalation components.

### Verification

- Add automated tests and SAST/DAST coverage for Local privilege escalation paths.
- Run dependency and secret scanning on every change touching Local privilege escalation.
- Perform targeted manual tests (abuse cases) for Local privilege escalation.

### Operations

- Log security-relevant events for Local privilege escalation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Local privilege escalation.
- Review access and configuration for Local privilege escalation on a regular cadence.

## Clipboard and screen capture

Sub-topics: Sensitive copy, Overlay malware, Screen recording APIs, Notification leaks, Memory scraping

### Policy

- Treat Clipboard and screen capture in Clipboard and screen capture as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Clipboard and screen capture (Desktop and native application security).
- Require security review for material changes affecting Clipboard and screen capture.

### Design

- Apply least privilege and defense in depth for Clipboard and screen capture.
- Prefer established patterns and libraries over custom crypto or auth for Clipboard and screen capture.
- Fail closed: deny by default when Clipboard and screen capture cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Clipboard and screen capture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Clipboard and screen capture.
- Keep dependencies patched; pin versions for Clipboard and screen capture components.

### Verification

- Add automated tests and SAST/DAST coverage for Clipboard and screen capture paths.
- Run dependency and secret scanning on every change touching Clipboard and screen capture.
- Perform targeted manual tests (abuse cases) for Clipboard and screen capture.

### Operations

- Log security-relevant events for Clipboard and screen capture without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Clipboard and screen capture.
- Review access and configuration for Clipboard and screen capture on a regular cadence.

## File handlers and URIs

Sub-topics: Custom scheme handlers, Path traversal open, Macro documents, Drag-drop, UNC paths

### Policy

- Treat File handlers and URIs in File handlers and URIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for File handlers and URIs (Desktop and native application security).
- Require security review for material changes affecting File handlers and URIs.

### Design

- Apply least privilege and defense in depth for File handlers and URIs.
- Prefer established patterns and libraries over custom crypto or auth for File handlers and URIs.
- Fail closed: deny by default when File handlers and URIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching File handlers and URIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to File handlers and URIs.
- Keep dependencies patched; pin versions for File handlers and URIs components.

### Verification

- Add automated tests and SAST/DAST coverage for File handlers and URIs paths.
- Run dependency and secret scanning on every change touching File handlers and URIs.
- Perform targeted manual tests (abuse cases) for File handlers and URIs.

### Operations

- Log security-relevant events for File handlers and URIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in File handlers and URIs.
- Review access and configuration for File handlers and URIs on a regular cadence.

## IPC between components

Sub-topics: Named pipes, DBus, XPC, COM objects, Message validation

### Policy

- Treat IPC between components in IPC between components as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for IPC between components (Desktop and native application security).
- Require security review for material changes affecting IPC between components.

### Design

- Apply least privilege and defense in depth for IPC between components.
- Prefer established patterns and libraries over custom crypto or auth for IPC between components.
- Fail closed: deny by default when IPC between components cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching IPC between components; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IPC between components.
- Keep dependencies patched; pin versions for IPC between components components.

### Verification

- Add automated tests and SAST/DAST coverage for IPC between components paths.
- Run dependency and secret scanning on every change touching IPC between components.
- Perform targeted manual tests (abuse cases) for IPC between components.

### Operations

- Log security-relevant events for IPC between components without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in IPC between components.
- Review access and configuration for IPC between components on a regular cadence.

## OS credential storage

Sub-topics: Keychain, Credential Manager, Secret Service, Biometric APIs, Master password

### Policy

- Treat OS credential storage in OS credential storage as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for OS credential storage (Desktop and native application security).
- Require security review for material changes affecting OS credential storage.

### Design

- Apply least privilege and defense in depth for OS credential storage.
- Prefer established patterns and libraries over custom crypto or auth for OS credential storage.
- Fail closed: deny by default when OS credential storage cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching OS credential storage; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to OS credential storage.
- Keep dependencies patched; pin versions for OS credential storage components.

### Verification

- Add automated tests and SAST/DAST coverage for OS credential storage paths.
- Run dependency and secret scanning on every change touching OS credential storage.
- Perform targeted manual tests (abuse cases) for OS credential storage.

### Operations

- Log security-relevant events for OS credential storage without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in OS credential storage.
- Review access and configuration for OS credential storage on a regular cadence.

## Debug symbols and dumps

Sub-topics: Crash reports PII, Core dumps, Symbol servers, Reversing resistance, Obfuscation limits

### Policy

- Treat Debug symbols and dumps in Debug symbols and dumps as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Debug symbols and dumps (Desktop and native application security).
- Require security review for material changes affecting Debug symbols and dumps.

### Design

- Apply least privilege and defense in depth for Debug symbols and dumps.
- Prefer established patterns and libraries over custom crypto or auth for Debug symbols and dumps.
- Fail closed: deny by default when Debug symbols and dumps cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Debug symbols and dumps; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Debug symbols and dumps.
- Keep dependencies patched; pin versions for Debug symbols and dumps components.

### Verification

- Add automated tests and SAST/DAST coverage for Debug symbols and dumps paths.
- Run dependency and secret scanning on every change touching Debug symbols and dumps.
- Perform targeted manual tests (abuse cases) for Debug symbols and dumps.

### Operations

- Log security-relevant events for Debug symbols and dumps without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Debug symbols and dumps.
- Review access and configuration for Debug symbols and dumps on a regular cadence.

## Enterprise deployment

Sub-topics: MDM packages, Notarization, SmartScreen, Gatekeeper, AppLocker

### Policy

- Treat Enterprise deployment in Enterprise deployment as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Enterprise deployment (Desktop and native application security).
- Require security review for material changes affecting Enterprise deployment.

### Design

- Apply least privilege and defense in depth for Enterprise deployment.
- Prefer established patterns and libraries over custom crypto or auth for Enterprise deployment.
- Fail closed: deny by default when Enterprise deployment cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Enterprise deployment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Enterprise deployment.
- Keep dependencies patched; pin versions for Enterprise deployment components.

### Verification

- Add automated tests and SAST/DAST coverage for Enterprise deployment paths.
- Run dependency and secret scanning on every change touching Enterprise deployment.
- Perform targeted manual tests (abuse cases) for Enterprise deployment.

### Operations

- Log security-relevant events for Enterprise deployment without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Enterprise deployment.
- Review access and configuration for Enterprise deployment on a regular cadence.

## Offline-first apps

Sub-topics: Local DB encryption, Sync conflict, Cached tokens, Backup files, Shared machines

### Policy

- Treat Offline-first apps in Offline-first apps as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Offline-first apps (Desktop and native application security).
- Require security review for material changes affecting Offline-first apps.

### Design

- Apply least privilege and defense in depth for Offline-first apps.
- Prefer established patterns and libraries over custom crypto or auth for Offline-first apps.
- Fail closed: deny by default when Offline-first apps cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Offline-first apps; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Offline-first apps.
- Keep dependencies patched; pin versions for Offline-first apps components.

### Verification

- Add automated tests and SAST/DAST coverage for Offline-first apps paths.
- Run dependency and secret scanning on every change touching Offline-first apps.
- Perform targeted manual tests (abuse cases) for Offline-first apps.

### Operations

- Log security-relevant events for Offline-first apps without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Offline-first apps.
- Review access and configuration for Offline-first apps on a regular cadence.

