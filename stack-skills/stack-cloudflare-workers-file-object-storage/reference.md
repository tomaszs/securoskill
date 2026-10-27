# Cloudflare Workers: File, blob, and object storage security

Stack-specific implementation for **Cloudflare Workers** (Platform). Normative rules: domain skill `security-file-object-storage` / `reference.md`.

## Upload validation

**Sub-topics:** MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for upload_validation controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Malware scanning

**Sub-topics:** Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for malware_scan controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Presigned URLs

**Sub-topics:** TTL, Method restriction, Object key guessing, Header signing, Revocation

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for presigned controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Bucket policies and ACLs

**Sub-topics:** Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for bucket_acl controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## CDN and origin access

**Sub-topics:** OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for cdn_origin controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Image and media processing

**Sub-topics:** ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for image_processing controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Document preview

**Sub-topics:** PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for doc_preview controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## User-generated content hosting

**Sub-topics:** Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for ugc_hosting controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Versioning and lifecycle

**Sub-topics:** Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for object_versioning controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Object encryption

**Sub-topics:** SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for object_encryption controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Metadata and headers

**Sub-topics:** x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for object_metadata controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

## Archives and backups

**Sub-topics:** Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Do (use this in Cloudflare Workers)

- Apply domain skill `security-file-object-storage` requirements using cloudflare-workers supported APIs only.
- Use the official cloudflare-workers security documentation for archive_security controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of cloudflare-workers for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on cloudflare-workers projects in CI.

