# Google Cloud: File, blob, and object storage security

Stack-specific implementation for **Google Cloud** (Cloud). Normative rules: domain skill `security-file-object-storage` / `reference.md`.

## Upload validation

**Sub-topics:** MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Do (use this in Google Cloud)

- Map `Upload validation` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Upload validation` before merge.

### Don't

- Do not ship `Upload validation` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Upload validation`.

### Verify

- Peer review `Upload validation` against domain skill `security-file-object-storage`.

## Malware scanning

**Sub-topics:** Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Do (use this in Google Cloud)

- Map `Malware scanning` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Malware scanning` before merge.

### Don't

- Do not ship `Malware scanning` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Malware scanning`.

### Verify

- Peer review `Malware scanning` against domain skill `security-file-object-storage`.

## Presigned URLs

**Sub-topics:** TTL, Method restriction, Object key guessing, Header signing, Revocation

### Do (use this in Google Cloud)

- Map `Presigned URLs` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Presigned URLs` before merge.

### Don't

- Do not ship `Presigned URLs` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Presigned URLs`.

### Verify

- Peer review `Presigned URLs` against domain skill `security-file-object-storage`.

## Bucket policies and ACLs

**Sub-topics:** Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Do (use this in Google Cloud)

- Map `Bucket policies and ACLs` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Bucket policies and ACLs` before merge.

### Don't

- Do not ship `Bucket policies and ACLs` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Bucket policies and ACLs`.

### Verify

- Peer review `Bucket policies and ACLs` against domain skill `security-file-object-storage`.

## CDN and origin access

**Sub-topics:** OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Do (use this in Google Cloud)

- Map `CDN and origin access` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `CDN and origin access` before merge.

### Don't

- Do not ship `CDN and origin access` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `CDN and origin access`.

### Verify

- Peer review `CDN and origin access` against domain skill `security-file-object-storage`.

## Image and media processing

**Sub-topics:** ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Do (use this in Google Cloud)

- Map `Image and media processing` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Image and media processing` before merge.

### Don't

- Do not ship `Image and media processing` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Image and media processing`.

### Verify

- Peer review `Image and media processing` against domain skill `security-file-object-storage`.

## Document preview

**Sub-topics:** PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Do (use this in Google Cloud)

- Map `Document preview` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Document preview` before merge.

### Don't

- Do not ship `Document preview` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Document preview`.

### Verify

- Peer review `Document preview` against domain skill `security-file-object-storage`.

## User-generated content hosting

**Sub-topics:** Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Do (use this in Google Cloud)

- Map `User-generated content hosting` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `User-generated content hosting` before merge.

### Don't

- Do not ship `User-generated content hosting` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `User-generated content hosting`.

### Verify

- Peer review `User-generated content hosting` against domain skill `security-file-object-storage`.

## Versioning and lifecycle

**Sub-topics:** Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Do (use this in Google Cloud)

- Map `Versioning and lifecycle` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Versioning and lifecycle` before merge.

### Don't

- Do not ship `Versioning and lifecycle` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Versioning and lifecycle`.

### Verify

- Peer review `Versioning and lifecycle` against domain skill `security-file-object-storage`.

## Object encryption

**Sub-topics:** SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Do (use this in Google Cloud)

- Map `Object encryption` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Object encryption` before merge.

### Don't

- Do not ship `Object encryption` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Object encryption`.

### Verify

- Peer review `Object encryption` against domain skill `security-file-object-storage`.

## Metadata and headers

**Sub-topics:** x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Do (use this in Google Cloud)

- Map `Metadata and headers` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Metadata and headers` before merge.

### Don't

- Do not ship `Metadata and headers` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Metadata and headers`.

### Verify

- Peer review `Metadata and headers` against domain skill `security-file-object-storage`.

## Archives and backups

**Sub-topics:** Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Do (use this in Google Cloud)

- Map `Archives and backups` controls to Google Cloud APIs documented for `security-file-object-storage`.
- Add an abuse-case test or check for `Archives and backups` before merge.

### Don't

- Do not ship `Archives and backups` work in Google Cloud with only happy-path tests.
- Do not disable Google Cloud security defaults to unblock `Archives and backups`.

### Verify

- Peer review `Archives and backups` against domain skill `security-file-object-storage`.

