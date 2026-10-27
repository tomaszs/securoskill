# Ruby on Rails: Network and transport security

Stack-specific implementation for **Ruby on Rails** (Ruby). Normative rules: domain skill `security-network-transport` / `reference.md`.

## DNS security

**Sub-topics:** DNSSEC, Subdomain takeover, CAA, Threat modeling and trust boundaries (DNS security), Abuse cases and adversarial testing (DNS security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching DNS security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DNS security.
- Keep dependencies patched; pin versions for DNS security components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for DNS security before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for DNS security paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## WAF and edge protection

**Sub-topics:** Rule tuning, Bypass, Threat modeling and trust boundaries (WAF and edge protection), Abuse cases and adversarial testing (WAF and edge protection), Logging, audit, and detection (WAF and edge protection)

### Platform rules (summary)

- Validate and canonicalize all inputs touching WAF and edge protection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WAF and edge protection.
- Keep dependencies patched; pin versions for WAF and edge protection components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for WAF and edge protection before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for WAF and edge protection paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## SSRF

**Sub-topics:** Metadata endpoints, URL parsers, Allowlists, Threat modeling and trust boundaries (SSRF), Abuse cases and adversarial testing (SSRF)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SSRF; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSRF.
- Keep dependencies patched; pin versions for SSRF components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SSRF before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SSRF paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Reverse proxies

**Sub-topics:** Header injection, Path normalization, Threat modeling and trust boundaries (Reverse proxies), Abuse cases and adversarial testing (Reverse proxies), Logging, audit, and detection (Reverse proxies)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Reverse proxies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Reverse proxies.
- Keep dependencies patched; pin versions for Reverse proxies components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Reverse proxies before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Reverse proxies paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## VPN and private networking

**Sub-topics:** Split tunnel, Peering, Threat modeling and trust boundaries (VPN and private networking), Abuse cases and adversarial testing (VPN and private networking), Logging, audit, and detection (VPN and private networking)

### Platform rules (summary)

- Validate and canonicalize all inputs touching VPN and private networking; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to VPN and private networking.
- Keep dependencies patched; pin versions for VPN and private networking components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for VPN and private networking before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for VPN and private networking paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## DDoS and volumetric attacks

**Sub-topics:** Rate limits, Anycast, Threat modeling and trust boundaries (DDoS and volumetric attacks), Abuse cases and adversarial testing (DDoS and volumetric attacks), Logging, audit, and detection (DDoS and volumetric attacks)

### Platform rules (summary)

- Validate and canonicalize all inputs touching DDoS and volumetric attacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to DDoS and volumetric attacks.
- Keep dependencies patched; pin versions for DDoS and volumetric attacks components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for DDoS and volumetric attacks before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for DDoS and volumetric attacks paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## IP allowlisting pitfalls

**Sub-topics:** Spoofing, Shared NAT, Threat modeling and trust boundaries (IP allowlisting pitfalls), Abuse cases and adversarial testing (IP allowlisting pitfalls), Logging, audit, and detection (IP allowlisting pitfalls)

### Platform rules (summary)

- Validate and canonicalize all inputs touching IP allowlisting pitfalls; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IP allowlisting pitfalls.
- Keep dependencies patched; pin versions for IP allowlisting pitfalls components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for IP allowlisting pitfalls before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for IP allowlisting pitfalls paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## HTTP request smuggling

**Sub-topics:** Front/back desync, Threat modeling and trust boundaries (HTTP request smuggling), Abuse cases and adversarial testing (HTTP request smuggling), Logging, audit, and detection (HTTP request smuggling), Access control and least privilege (HTTP request smuggling)

### Platform rules (summary)

- Validate and canonicalize all inputs touching HTTP request smuggling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to HTTP request smuggling.
- Keep dependencies patched; pin versions for HTTP request smuggling components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for HTTP request smuggling before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for HTTP request smuggling paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## WebSocket transport

**Sub-topics:** Origin checks, TLS, Threat modeling and trust boundaries (WebSocket transport), Abuse cases and adversarial testing (WebSocket transport), Logging, audit, and detection (WebSocket transport)

### Platform rules (summary)

- Validate and canonicalize all inputs touching WebSocket transport; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebSocket transport.
- Keep dependencies patched; pin versions for WebSocket transport components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for WebSocket transport before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for WebSocket transport paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## SMTP security

**Sub-topics:** STARTTLS, SPF/DKIM/DMARC, Threat modeling and trust boundaries (SMTP security), Abuse cases and adversarial testing (SMTP security), Logging, audit, and detection (SMTP security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SMTP security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SMTP security.
- Keep dependencies patched; pin versions for SMTP security components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SMTP security before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SMTP security paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## IPv6 and dual stack

**Sub-topics:** Unexpected exposure, Threat modeling and trust boundaries (IPv6 and dual stack), Abuse cases and adversarial testing (IPv6 and dual stack), Logging, audit, and detection (IPv6 and dual stack), Access control and least privilege (IPv6 and dual stack)

### Platform rules (summary)

- Validate and canonicalize all inputs touching IPv6 and dual stack; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IPv6 and dual stack.
- Keep dependencies patched; pin versions for IPv6 and dual stack components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for IPv6 and dual stack before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for IPv6 and dual stack paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

## Service mesh mTLS

**Sub-topics:** Identity, Policy, Threat modeling and trust boundaries (Service mesh mTLS), Abuse cases and adversarial testing (Service mesh mTLS), Logging, audit, and detection (Service mesh mTLS)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Service mesh mTLS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Service mesh mTLS.
- Keep dependencies patched; pin versions for Service mesh mTLS components.

### How to do this in Ruby on Rails

- Read normative rules in domain skill `security-network-transport` / `reference.md`, then apply them using Ruby on Rails APIs and deployment model.
- Prefer framework-maintained security features in Ruby on Rails over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Service mesh mTLS before merge.
- Pin Ruby on Rails dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Service mesh mTLS paths in Ruby on Rails.
- Run SAST/dependency scan configured for Ruby.

