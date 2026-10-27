# Prisma: File, blob, and object storage security

Stack-specific implementation for **Prisma** (ORM / data access). Normative rules: domain skill `security-file-object-storage` / `reference.md`.

## Upload validation

**Sub-topics:** MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Platform rules (summary)

- Validate and canonicalize all inputs touching Upload validation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Upload validation.
- Keep dependencies patched; pin versions for Upload validation components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Upload validation before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Upload validation paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Malware scanning

**Sub-topics:** Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Platform rules (summary)

- Validate and canonicalize all inputs touching Malware scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Malware scanning.
- Keep dependencies patched; pin versions for Malware scanning components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Malware scanning before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Malware scanning paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Presigned URLs

**Sub-topics:** TTL, Method restriction, Object key guessing, Header signing, Revocation

### Platform rules (summary)

- Validate and canonicalize all inputs touching Presigned URLs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Presigned URLs.
- Keep dependencies patched; pin versions for Presigned URLs components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Presigned URLs before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Presigned URLs paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Bucket policies and ACLs

**Sub-topics:** Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Platform rules (summary)

- Validate and canonicalize all inputs touching Bucket policies and ACLs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bucket policies and ACLs.
- Keep dependencies patched; pin versions for Bucket policies and ACLs components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Bucket policies and ACLs before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Bucket policies and ACLs paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## CDN and origin access

**Sub-topics:** OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Platform rules (summary)

- Validate and canonicalize all inputs touching CDN and origin access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CDN and origin access.
- Keep dependencies patched; pin versions for CDN and origin access components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CDN and origin access before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CDN and origin access paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Image and media processing

**Sub-topics:** ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Platform rules (summary)

- Validate and canonicalize all inputs touching Image and media processing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Image and media processing.
- Keep dependencies patched; pin versions for Image and media processing components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Image and media processing before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Image and media processing paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Document preview

**Sub-topics:** PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Platform rules (summary)

- Validate and canonicalize all inputs touching Document preview; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Document preview.
- Keep dependencies patched; pin versions for Document preview components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Document preview before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Document preview paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## User-generated content hosting

**Sub-topics:** Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Platform rules (summary)

- Validate and canonicalize all inputs touching User-generated content hosting; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to User-generated content hosting.
- Keep dependencies patched; pin versions for User-generated content hosting components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for User-generated content hosting before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for User-generated content hosting paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Versioning and lifecycle

**Sub-topics:** Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Platform rules (summary)

- Validate and canonicalize all inputs touching Versioning and lifecycle; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Versioning and lifecycle.
- Keep dependencies patched; pin versions for Versioning and lifecycle components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Versioning and lifecycle before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Versioning and lifecycle paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Object encryption

**Sub-topics:** SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Platform rules (summary)

- Validate and canonicalize all inputs touching Object encryption; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Object encryption.
- Keep dependencies patched; pin versions for Object encryption components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Object encryption before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Object encryption paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Metadata and headers

**Sub-topics:** x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Platform rules (summary)

- Validate and canonicalize all inputs touching Metadata and headers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Metadata and headers.
- Keep dependencies patched; pin versions for Metadata and headers components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Metadata and headers before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Metadata and headers paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Archives and backups

**Sub-topics:** Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Platform rules (summary)

- Validate and canonicalize all inputs touching Archives and backups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Archives and backups.
- Keep dependencies patched; pin versions for Archives and backups components.

### How to do this in Prisma

- Read normative rules in domain skill `security-file-object-storage` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Archives and backups before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Archives and backups paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

