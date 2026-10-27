# Docker: File, blob, and object storage security

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-file-object-storage` / `reference.md`.

## Upload validation

**Sub-topics:** MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Malware scanning

**Sub-topics:** Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Presigned URLs

**Sub-topics:** TTL, Method restriction, Object key guessing, Header signing, Revocation

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Bucket policies and ACLs

**Sub-topics:** Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## CDN and origin access

**Sub-topics:** OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Image and media processing

**Sub-topics:** ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Document preview

**Sub-topics:** PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## User-generated content hosting

**Sub-topics:** Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Versioning and lifecycle

**Sub-topics:** Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Object encryption

**Sub-topics:** SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Metadata and headers

**Sub-topics:** x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Archives and backups

**Sub-topics:** Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

