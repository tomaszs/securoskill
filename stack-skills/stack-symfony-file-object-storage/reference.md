# Symfony: File, blob, and object storage security

Stack-specific implementation for **Symfony** (PHP). Normative rules: domain skill `security-file-object-storage` / `reference.md`.

## Upload validation

**Sub-topics:** MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Malware scanning

**Sub-topics:** Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Presigned URLs

**Sub-topics:** TTL, Method restriction, Object key guessing, Header signing, Revocation

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Bucket policies and ACLs

**Sub-topics:** Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## CDN and origin access

**Sub-topics:** OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Image and media processing

**Sub-topics:** ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Document preview

**Sub-topics:** PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## User-generated content hosting

**Sub-topics:** Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Versioning and lifecycle

**Sub-topics:** Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Object encryption

**Sub-topics:** SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Metadata and headers

**Sub-topics:** x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

## Archives and backups

**Sub-topics:** Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Do (use this in Symfony)

- Symfony is not the primary enforcement point for `file-object-storage`; load stack skill `security-file-object-storage` when you touch that layer.
- Keep Symfony configuration aligned with requirements from `security-file-object-storage` (domain reference.md).

### Don't

- Do not duplicate `file-object-storage` controls only in Symfony config while leaving security-file-object-storage misconfigured.
- Do not assume Symfony defaults satisfy `security-file-object-storage` without verification.

### Verify

- Integration test the full path: Symfony plus the system covered by `security-file-object-storage`.

