# Rules reference: File, blob, and object storage security

Uploads, downloads, signed URLs, and media pipelines.

## Upload validation

Sub-topics: MIME sniffing, Double extensions, Polyglot files, Size limits, Magic bytes

### Do

- Validate and canonicalize all inputs touching Upload validation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Upload validation.
- Keep dependencies patched; pin versions for Upload validation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Upload validation in Upload validation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Upload validation (File, blob, and object storage security).
- Require security review for material changes affecting Upload validation.

### Design

- Apply least privilege and defense in depth for Upload validation.
- Prefer established patterns and libraries over custom crypto or auth for Upload validation.
- Fail closed: deny by default when Upload validation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Upload validation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Upload validation.
- Keep dependencies patched; pin versions for Upload validation components.

### Verification

- Add automated tests and SAST/DAST coverage for Upload validation paths.
- Run dependency and secret scanning on every change touching Upload validation.
- Perform targeted manual tests (abuse cases) for Upload validation.

### Operations

- Log security-relevant events for Upload validation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Upload validation.
- Review access and configuration for Upload validation on a regular cadence.

## Malware scanning

Sub-topics: Async scan, Quarantine buckets, Bypass timing, ZIP bombs, Macro docs

### Do

- Validate and canonicalize all inputs touching Malware scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Malware scanning.
- Keep dependencies patched; pin versions for Malware scanning components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Malware scanning in Malware scanning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Malware scanning (File, blob, and object storage security).
- Require security review for material changes affecting Malware scanning.

### Design

- Apply least privilege and defense in depth for Malware scanning.
- Prefer established patterns and libraries over custom crypto or auth for Malware scanning.
- Fail closed: deny by default when Malware scanning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Malware scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Malware scanning.
- Keep dependencies patched; pin versions for Malware scanning components.

### Verification

- Add automated tests and SAST/DAST coverage for Malware scanning paths.
- Run dependency and secret scanning on every change touching Malware scanning.
- Perform targeted manual tests (abuse cases) for Malware scanning.

### Operations

- Log security-relevant events for Malware scanning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Malware scanning.
- Review access and configuration for Malware scanning on a regular cadence.

## Presigned URLs

Sub-topics: TTL, Method restriction, Object key guessing, Header signing, Revocation

### Do

- Validate and canonicalize all inputs touching Presigned URLs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Presigned URLs.
- Keep dependencies patched; pin versions for Presigned URLs components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Presigned URLs in Presigned URLs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Presigned URLs (File, blob, and object storage security).
- Require security review for material changes affecting Presigned URLs.

### Design

- Apply least privilege and defense in depth for Presigned URLs.
- Prefer established patterns and libraries over custom crypto or auth for Presigned URLs.
- Fail closed: deny by default when Presigned URLs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Presigned URLs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Presigned URLs.
- Keep dependencies patched; pin versions for Presigned URLs components.

### Verification

- Add automated tests and SAST/DAST coverage for Presigned URLs paths.
- Run dependency and secret scanning on every change touching Presigned URLs.
- Perform targeted manual tests (abuse cases) for Presigned URLs.

### Operations

- Log security-relevant events for Presigned URLs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Presigned URLs.
- Review access and configuration for Presigned URLs on a regular cadence.

## Bucket policies and ACLs

Sub-topics: Public read, ListBucket, AuthenticatedUsers, Policy wildcards, Cross-account

### Do

- Validate and canonicalize all inputs touching Bucket policies and ACLs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bucket policies and ACLs.
- Keep dependencies patched; pin versions for Bucket policies and ACLs components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Bucket policies and ACLs in Bucket policies and ACLs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Bucket policies and ACLs (File, blob, and object storage security).
- Require security review for material changes affecting Bucket policies and ACLs.

### Design

- Apply least privilege and defense in depth for Bucket policies and ACLs.
- Prefer established patterns and libraries over custom crypto or auth for Bucket policies and ACLs.
- Fail closed: deny by default when Bucket policies and ACLs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Bucket policies and ACLs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bucket policies and ACLs.
- Keep dependencies patched; pin versions for Bucket policies and ACLs components.

### Verification

- Add automated tests and SAST/DAST coverage for Bucket policies and ACLs paths.
- Run dependency and secret scanning on every change touching Bucket policies and ACLs.
- Perform targeted manual tests (abuse cases) for Bucket policies and ACLs.

### Operations

- Log security-relevant events for Bucket policies and ACLs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Bucket policies and ACLs.
- Review access and configuration for Bucket policies and ACLs on a regular cadence.

## CDN and origin access

Sub-topics: OAC/OAI, Hotlinking, Cache key abuse, Range requests, Signed cookies

### Do

- Validate and canonicalize all inputs touching CDN and origin access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CDN and origin access.
- Keep dependencies patched; pin versions for CDN and origin access components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat CDN and origin access in CDN and origin access as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CDN and origin access (File, blob, and object storage security).
- Require security review for material changes affecting CDN and origin access.

### Design

- Apply least privilege and defense in depth for CDN and origin access.
- Prefer established patterns and libraries over custom crypto or auth for CDN and origin access.
- Fail closed: deny by default when CDN and origin access cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CDN and origin access; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CDN and origin access.
- Keep dependencies patched; pin versions for CDN and origin access components.

### Verification

- Add automated tests and SAST/DAST coverage for CDN and origin access paths.
- Run dependency and secret scanning on every change touching CDN and origin access.
- Perform targeted manual tests (abuse cases) for CDN and origin access.

### Operations

- Log security-relevant events for CDN and origin access without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CDN and origin access.
- Review access and configuration for CDN and origin access on a regular cadence.

## Image and media processing

Sub-topics: ImageTragick class bugs, SVG uploads, EXIF leaks, Thumbnails, Server-side render

### Do

- Validate and canonicalize all inputs touching Image and media processing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Image and media processing.
- Keep dependencies patched; pin versions for Image and media processing components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Image and media processing in Image and media processing as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Image and media processing (File, blob, and object storage security).
- Require security review for material changes affecting Image and media processing.

### Design

- Apply least privilege and defense in depth for Image and media processing.
- Prefer established patterns and libraries over custom crypto or auth for Image and media processing.
- Fail closed: deny by default when Image and media processing cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Image and media processing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Image and media processing.
- Keep dependencies patched; pin versions for Image and media processing components.

### Verification

- Add automated tests and SAST/DAST coverage for Image and media processing paths.
- Run dependency and secret scanning on every change touching Image and media processing.
- Perform targeted manual tests (abuse cases) for Image and media processing.

### Operations

- Log security-relevant events for Image and media processing without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Image and media processing.
- Review access and configuration for Image and media processing on a regular cadence.

## Document preview

Sub-topics: PDF JS, Office macros, HTML conversion, Sandbox viewers, SSRF fetchers

### Do

- Validate and canonicalize all inputs touching Document preview; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Document preview.
- Keep dependencies patched; pin versions for Document preview components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Document preview in Document preview as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Document preview (File, blob, and object storage security).
- Require security review for material changes affecting Document preview.

### Design

- Apply least privilege and defense in depth for Document preview.
- Prefer established patterns and libraries over custom crypto or auth for Document preview.
- Fail closed: deny by default when Document preview cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Document preview; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Document preview.
- Keep dependencies patched; pin versions for Document preview components.

### Verification

- Add automated tests and SAST/DAST coverage for Document preview paths.
- Run dependency and secret scanning on every change touching Document preview.
- Perform targeted manual tests (abuse cases) for Document preview.

### Operations

- Log security-relevant events for Document preview without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Document preview.
- Review access and configuration for Document preview on a regular cadence.

## User-generated content hosting

Sub-topics: Separate domain, CSP on static, COEP/COOP, Phishing pages, DMCA

### Do

- Validate and canonicalize all inputs touching User-generated content hosting; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to User-generated content hosting.
- Keep dependencies patched; pin versions for User-generated content hosting components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat User-generated content hosting in User-generated content hosting as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for User-generated content hosting (File, blob, and object storage security).
- Require security review for material changes affecting User-generated content hosting.

### Design

- Apply least privilege and defense in depth for User-generated content hosting.
- Prefer established patterns and libraries over custom crypto or auth for User-generated content hosting.
- Fail closed: deny by default when User-generated content hosting cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching User-generated content hosting; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to User-generated content hosting.
- Keep dependencies patched; pin versions for User-generated content hosting components.

### Verification

- Add automated tests and SAST/DAST coverage for User-generated content hosting paths.
- Run dependency and secret scanning on every change touching User-generated content hosting.
- Perform targeted manual tests (abuse cases) for User-generated content hosting.

### Operations

- Log security-relevant events for User-generated content hosting without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in User-generated content hosting.
- Review access and configuration for User-generated content hosting on a regular cadence.

## Versioning and lifecycle

Sub-topics: Deleted object recovery, Retention locks, Legal hold, Ransomware, Replication

### Do

- Validate and canonicalize all inputs touching Versioning and lifecycle; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Versioning and lifecycle.
- Keep dependencies patched; pin versions for Versioning and lifecycle components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Versioning and lifecycle in Versioning and lifecycle as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Versioning and lifecycle (File, blob, and object storage security).
- Require security review for material changes affecting Versioning and lifecycle.

### Design

- Apply least privilege and defense in depth for Versioning and lifecycle.
- Prefer established patterns and libraries over custom crypto or auth for Versioning and lifecycle.
- Fail closed: deny by default when Versioning and lifecycle cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Versioning and lifecycle; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Versioning and lifecycle.
- Keep dependencies patched; pin versions for Versioning and lifecycle components.

### Verification

- Add automated tests and SAST/DAST coverage for Versioning and lifecycle paths.
- Run dependency and secret scanning on every change touching Versioning and lifecycle.
- Perform targeted manual tests (abuse cases) for Versioning and lifecycle.

### Operations

- Log security-relevant events for Versioning and lifecycle without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Versioning and lifecycle.
- Review access and configuration for Versioning and lifecycle on a regular cadence.

## Object encryption

Sub-topics: SSE-KMS, Client-side keys, Bucket keys, Key policy, Cross-region keys

### Do

- Validate and canonicalize all inputs touching Object encryption; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Object encryption.
- Keep dependencies patched; pin versions for Object encryption components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Object encryption in Object encryption as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Object encryption (File, blob, and object storage security).
- Require security review for material changes affecting Object encryption.

### Design

- Apply least privilege and defense in depth for Object encryption.
- Prefer established patterns and libraries over custom crypto or auth for Object encryption.
- Fail closed: deny by default when Object encryption cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Object encryption; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Object encryption.
- Keep dependencies patched; pin versions for Object encryption components.

### Verification

- Add automated tests and SAST/DAST coverage for Object encryption paths.
- Run dependency and secret scanning on every change touching Object encryption.
- Perform targeted manual tests (abuse cases) for Object encryption.

### Operations

- Log security-relevant events for Object encryption without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Object encryption.
- Review access and configuration for Object encryption on a regular cadence.

## Metadata and headers

Sub-topics: x-amz-meta PII, Directory listings, Error XML, ETag leaks, Object tags

### Do

- Validate and canonicalize all inputs touching Metadata and headers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Metadata and headers.
- Keep dependencies patched; pin versions for Metadata and headers components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Metadata and headers in Metadata and headers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Metadata and headers (File, blob, and object storage security).
- Require security review for material changes affecting Metadata and headers.

### Design

- Apply least privilege and defense in depth for Metadata and headers.
- Prefer established patterns and libraries over custom crypto or auth for Metadata and headers.
- Fail closed: deny by default when Metadata and headers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Metadata and headers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Metadata and headers.
- Keep dependencies patched; pin versions for Metadata and headers components.

### Verification

- Add automated tests and SAST/DAST coverage for Metadata and headers paths.
- Run dependency and secret scanning on every change touching Metadata and headers.
- Perform targeted manual tests (abuse cases) for Metadata and headers.

### Operations

- Log security-relevant events for Metadata and headers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Metadata and headers.
- Review access and configuration for Metadata and headers on a regular cadence.

## Archives and backups

Sub-topics: Tar paths, Encrypted backups, Offsite sync, Restore testing, Access logging

### Do

- Validate and canonicalize all inputs touching Archives and backups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Archives and backups.
- Keep dependencies patched; pin versions for Archives and backups components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Archives and backups in Archives and backups as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Archives and backups (File, blob, and object storage security).
- Require security review for material changes affecting Archives and backups.

### Design

- Apply least privilege and defense in depth for Archives and backups.
- Prefer established patterns and libraries over custom crypto or auth for Archives and backups.
- Fail closed: deny by default when Archives and backups cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Archives and backups; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Archives and backups.
- Keep dependencies patched; pin versions for Archives and backups components.

### Verification

- Add automated tests and SAST/DAST coverage for Archives and backups paths.
- Run dependency and secret scanning on every change touching Archives and backups.
- Perform targeted manual tests (abuse cases) for Archives and backups.

### Operations

- Log security-relevant events for Archives and backups without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Archives and backups.
- Review access and configuration for Archives and backups on a regular cadence.

