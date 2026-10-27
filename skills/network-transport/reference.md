# Rules reference: Network and transport security

DNS, firewalls, proxies, and protocol hardening.

## DNS security

Sub-topics: DNSSEC, Subdomain takeover, CAA, Threat modeling and trust boundaries (DNS security), Abuse cases and adversarial testing (DNS security)

### Do

- Validate and canonicalize all inputs touching DNS security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DNS security.
- Keep dependencies patched; pin versions for DNS security components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat DNS security in DNS security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for DNS security (Network and transport security).
- Require security review for material changes affecting DNS security.

### Design

- Apply least privilege and defense in depth for DNS security.
- Prefer established patterns and libraries over custom crypto or auth for DNS security.
- Fail closed: deny by default when DNS security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching DNS security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DNS security.
- Keep dependencies patched; pin versions for DNS security components.

### Verification

- Add automated tests and SAST/DAST coverage for DNS security paths.
- Run dependency and secret scanning on every change touching DNS security.
- Perform targeted manual tests (abuse cases) for DNS security.

### Operations

- Log security-relevant events for DNS security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in DNS security.
- Review access and configuration for DNS security on a regular cadence.

## WAF and edge protection

Sub-topics: Rule tuning, Bypass, Threat modeling and trust boundaries (WAF and edge protection), Abuse cases and adversarial testing (WAF and edge protection), Logging, audit, and detection (WAF and edge protection)

### Do

- Validate and canonicalize all inputs touching WAF and edge protection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WAF and edge protection.
- Keep dependencies patched; pin versions for WAF and edge protection components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat WAF and edge protection in WAF and edge protection as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for WAF and edge protection (Network and transport security).
- Require security review for material changes affecting WAF and edge protection.

### Design

- Apply least privilege and defense in depth for WAF and edge protection.
- Prefer established patterns and libraries over custom crypto or auth for WAF and edge protection.
- Fail closed: deny by default when WAF and edge protection cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching WAF and edge protection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WAF and edge protection.
- Keep dependencies patched; pin versions for WAF and edge protection components.

### Verification

- Add automated tests and SAST/DAST coverage for WAF and edge protection paths.
- Run dependency and secret scanning on every change touching WAF and edge protection.
- Perform targeted manual tests (abuse cases) for WAF and edge protection.

### Operations

- Log security-relevant events for WAF and edge protection without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in WAF and edge protection.
- Review access and configuration for WAF and edge protection on a regular cadence.

## SSRF

Sub-topics: Metadata endpoints, URL parsers, Allowlists, Threat modeling and trust boundaries (SSRF), Abuse cases and adversarial testing (SSRF)

### Do

- Validate and canonicalize all inputs touching SSRF; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSRF.
- Keep dependencies patched; pin versions for SSRF components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SSRF in SSRF as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SSRF (Network and transport security).
- Require security review for material changes affecting SSRF.

### Design

- Apply least privilege and defense in depth for SSRF.
- Prefer established patterns and libraries over custom crypto or auth for SSRF.
- Fail closed: deny by default when SSRF cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SSRF; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSRF.
- Keep dependencies patched; pin versions for SSRF components.

### Verification

- Add automated tests and SAST/DAST coverage for SSRF paths.
- Run dependency and secret scanning on every change touching SSRF.
- Perform targeted manual tests (abuse cases) for SSRF.

### Operations

- Log security-relevant events for SSRF without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SSRF.
- Review access and configuration for SSRF on a regular cadence.

## Reverse proxies

Sub-topics: Header injection, Path normalization, Threat modeling and trust boundaries (Reverse proxies), Abuse cases and adversarial testing (Reverse proxies), Logging, audit, and detection (Reverse proxies)

### Do

- Validate and canonicalize all inputs touching Reverse proxies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Reverse proxies.
- Keep dependencies patched; pin versions for Reverse proxies components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Reverse proxies in Reverse proxies as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Reverse proxies (Network and transport security).
- Require security review for material changes affecting Reverse proxies.

### Design

- Apply least privilege and defense in depth for Reverse proxies.
- Prefer established patterns and libraries over custom crypto or auth for Reverse proxies.
- Fail closed: deny by default when Reverse proxies cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Reverse proxies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Reverse proxies.
- Keep dependencies patched; pin versions for Reverse proxies components.

### Verification

- Add automated tests and SAST/DAST coverage for Reverse proxies paths.
- Run dependency and secret scanning on every change touching Reverse proxies.
- Perform targeted manual tests (abuse cases) for Reverse proxies.

### Operations

- Log security-relevant events for Reverse proxies without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Reverse proxies.
- Review access and configuration for Reverse proxies on a regular cadence.

## VPN and private networking

Sub-topics: Split tunnel, Peering, Threat modeling and trust boundaries (VPN and private networking), Abuse cases and adversarial testing (VPN and private networking), Logging, audit, and detection (VPN and private networking)

### Do

- Validate and canonicalize all inputs touching VPN and private networking; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPN and private networking.
- Keep dependencies patched; pin versions for VPN and private networking components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat VPN and private networking in VPN and private networking as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for VPN and private networking (Network and transport security).
- Require security review for material changes affecting VPN and private networking.

### Design

- Apply least privilege and defense in depth for VPN and private networking.
- Prefer established patterns and libraries over custom crypto or auth for VPN and private networking.
- Fail closed: deny by default when VPN and private networking cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching VPN and private networking; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPN and private networking.
- Keep dependencies patched; pin versions for VPN and private networking components.

### Verification

- Add automated tests and SAST/DAST coverage for VPN and private networking paths.
- Run dependency and secret scanning on every change touching VPN and private networking.
- Perform targeted manual tests (abuse cases) for VPN and private networking.

### Operations

- Log security-relevant events for VPN and private networking without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in VPN and private networking.
- Review access and configuration for VPN and private networking on a regular cadence.

## DDoS and volumetric attacks

Sub-topics: Rate limits, Anycast, Threat modeling and trust boundaries (DDoS and volumetric attacks), Abuse cases and adversarial testing (DDoS and volumetric attacks), Logging, audit, and detection (DDoS and volumetric attacks)

### Do

- Validate and canonicalize all inputs touching DDoS and volumetric attacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DDoS and volumetric attacks.
- Keep dependencies patched; pin versions for DDoS and volumetric attacks components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat DDoS and volumetric attacks in DDoS and volumetric attacks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for DDoS and volumetric attacks (Network and transport security).
- Require security review for material changes affecting DDoS and volumetric attacks.

### Design

- Apply least privilege and defense in depth for DDoS and volumetric attacks.
- Prefer established patterns and libraries over custom crypto or auth for DDoS and volumetric attacks.
- Fail closed: deny by default when DDoS and volumetric attacks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching DDoS and volumetric attacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DDoS and volumetric attacks.
- Keep dependencies patched; pin versions for DDoS and volumetric attacks components.

### Verification

- Add automated tests and SAST/DAST coverage for DDoS and volumetric attacks paths.
- Run dependency and secret scanning on every change touching DDoS and volumetric attacks.
- Perform targeted manual tests (abuse cases) for DDoS and volumetric attacks.

### Operations

- Log security-relevant events for DDoS and volumetric attacks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in DDoS and volumetric attacks.
- Review access and configuration for DDoS and volumetric attacks on a regular cadence.

## IP allowlisting pitfalls

Sub-topics: Spoofing, Shared NAT, Threat modeling and trust boundaries (IP allowlisting pitfalls), Abuse cases and adversarial testing (IP allowlisting pitfalls), Logging, audit, and detection (IP allowlisting pitfalls)

### Do

- Validate and canonicalize all inputs touching IP allowlisting pitfalls; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IP allowlisting pitfalls.
- Keep dependencies patched; pin versions for IP allowlisting pitfalls components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat IP allowlisting pitfalls in IP allowlisting pitfalls as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for IP allowlisting pitfalls (Network and transport security).
- Require security review for material changes affecting IP allowlisting pitfalls.

### Design

- Apply least privilege and defense in depth for IP allowlisting pitfalls.
- Prefer established patterns and libraries over custom crypto or auth for IP allowlisting pitfalls.
- Fail closed: deny by default when IP allowlisting pitfalls cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching IP allowlisting pitfalls; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IP allowlisting pitfalls.
- Keep dependencies patched; pin versions for IP allowlisting pitfalls components.

### Verification

- Add automated tests and SAST/DAST coverage for IP allowlisting pitfalls paths.
- Run dependency and secret scanning on every change touching IP allowlisting pitfalls.
- Perform targeted manual tests (abuse cases) for IP allowlisting pitfalls.

### Operations

- Log security-relevant events for IP allowlisting pitfalls without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in IP allowlisting pitfalls.
- Review access and configuration for IP allowlisting pitfalls on a regular cadence.

## HTTP request smuggling

Sub-topics: Front/back desync, Threat modeling and trust boundaries (HTTP request smuggling), Abuse cases and adversarial testing (HTTP request smuggling), Logging, audit, and detection (HTTP request smuggling), Access control and least privilege (HTTP request smuggling)

### Do

- Validate and canonicalize all inputs touching HTTP request smuggling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to HTTP request smuggling.
- Keep dependencies patched; pin versions for HTTP request smuggling components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat HTTP request smuggling in HTTP request smuggling as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for HTTP request smuggling (Network and transport security).
- Require security review for material changes affecting HTTP request smuggling.

### Design

- Apply least privilege and defense in depth for HTTP request smuggling.
- Prefer established patterns and libraries over custom crypto or auth for HTTP request smuggling.
- Fail closed: deny by default when HTTP request smuggling cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching HTTP request smuggling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to HTTP request smuggling.
- Keep dependencies patched; pin versions for HTTP request smuggling components.

### Verification

- Add automated tests and SAST/DAST coverage for HTTP request smuggling paths.
- Run dependency and secret scanning on every change touching HTTP request smuggling.
- Perform targeted manual tests (abuse cases) for HTTP request smuggling.

### Operations

- Log security-relevant events for HTTP request smuggling without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in HTTP request smuggling.
- Review access and configuration for HTTP request smuggling on a regular cadence.

## WebSocket transport

Sub-topics: Origin checks, TLS, Threat modeling and trust boundaries (WebSocket transport), Abuse cases and adversarial testing (WebSocket transport), Logging, audit, and detection (WebSocket transport)

### Do

- Validate and canonicalize all inputs touching WebSocket transport; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebSocket transport.
- Keep dependencies patched; pin versions for WebSocket transport components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat WebSocket transport in WebSocket transport as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for WebSocket transport (Network and transport security).
- Require security review for material changes affecting WebSocket transport.

### Design

- Apply least privilege and defense in depth for WebSocket transport.
- Prefer established patterns and libraries over custom crypto or auth for WebSocket transport.
- Fail closed: deny by default when WebSocket transport cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching WebSocket transport; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebSocket transport.
- Keep dependencies patched; pin versions for WebSocket transport components.

### Verification

- Add automated tests and SAST/DAST coverage for WebSocket transport paths.
- Run dependency and secret scanning on every change touching WebSocket transport.
- Perform targeted manual tests (abuse cases) for WebSocket transport.

### Operations

- Log security-relevant events for WebSocket transport without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in WebSocket transport.
- Review access and configuration for WebSocket transport on a regular cadence.

## SMTP security

Sub-topics: STARTTLS, SPF/DKIM/DMARC, Threat modeling and trust boundaries (SMTP security), Abuse cases and adversarial testing (SMTP security), Logging, audit, and detection (SMTP security)

### Do

- Validate and canonicalize all inputs touching SMTP security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SMTP security.
- Keep dependencies patched; pin versions for SMTP security components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SMTP security in SMTP security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SMTP security (Network and transport security).
- Require security review for material changes affecting SMTP security.

### Design

- Apply least privilege and defense in depth for SMTP security.
- Prefer established patterns and libraries over custom crypto or auth for SMTP security.
- Fail closed: deny by default when SMTP security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SMTP security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SMTP security.
- Keep dependencies patched; pin versions for SMTP security components.

### Verification

- Add automated tests and SAST/DAST coverage for SMTP security paths.
- Run dependency and secret scanning on every change touching SMTP security.
- Perform targeted manual tests (abuse cases) for SMTP security.

### Operations

- Log security-relevant events for SMTP security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SMTP security.
- Review access and configuration for SMTP security on a regular cadence.

## IPv6 and dual stack

Sub-topics: Unexpected exposure, Threat modeling and trust boundaries (IPv6 and dual stack), Abuse cases and adversarial testing (IPv6 and dual stack), Logging, audit, and detection (IPv6 and dual stack), Access control and least privilege (IPv6 and dual stack)

### Do

- Validate and canonicalize all inputs touching IPv6 and dual stack; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IPv6 and dual stack.
- Keep dependencies patched; pin versions for IPv6 and dual stack components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat IPv6 and dual stack in IPv6 and dual stack as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for IPv6 and dual stack (Network and transport security).
- Require security review for material changes affecting IPv6 and dual stack.

### Design

- Apply least privilege and defense in depth for IPv6 and dual stack.
- Prefer established patterns and libraries over custom crypto or auth for IPv6 and dual stack.
- Fail closed: deny by default when IPv6 and dual stack cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching IPv6 and dual stack; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IPv6 and dual stack.
- Keep dependencies patched; pin versions for IPv6 and dual stack components.

### Verification

- Add automated tests and SAST/DAST coverage for IPv6 and dual stack paths.
- Run dependency and secret scanning on every change touching IPv6 and dual stack.
- Perform targeted manual tests (abuse cases) for IPv6 and dual stack.

### Operations

- Log security-relevant events for IPv6 and dual stack without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in IPv6 and dual stack.
- Review access and configuration for IPv6 and dual stack on a regular cadence.

## Service mesh mTLS

Sub-topics: Identity, Policy, Threat modeling and trust boundaries (Service mesh mTLS), Abuse cases and adversarial testing (Service mesh mTLS), Logging, audit, and detection (Service mesh mTLS)

### Do

- Validate and canonicalize all inputs touching Service mesh mTLS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service mesh mTLS.
- Keep dependencies patched; pin versions for Service mesh mTLS components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Service mesh mTLS in Service mesh mTLS as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Service mesh mTLS (Network and transport security).
- Require security review for material changes affecting Service mesh mTLS.

### Design

- Apply least privilege and defense in depth for Service mesh mTLS.
- Prefer established patterns and libraries over custom crypto or auth for Service mesh mTLS.
- Fail closed: deny by default when Service mesh mTLS cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Service mesh mTLS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service mesh mTLS.
- Keep dependencies patched; pin versions for Service mesh mTLS components.

### Verification

- Add automated tests and SAST/DAST coverage for Service mesh mTLS paths.
- Run dependency and secret scanning on every change touching Service mesh mTLS.
- Perform targeted manual tests (abuse cases) for Service mesh mTLS.

### Operations

- Log security-relevant events for Service mesh mTLS without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Service mesh mTLS.
- Review access and configuration for Service mesh mTLS on a regular cadence.

