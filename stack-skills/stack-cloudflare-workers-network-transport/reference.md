# Cloudflare Workers: Network and transport security

Stack-specific implementation for **Cloudflare Workers** (Platform). Normative rules: domain skill `security-network-transport` / `reference.md`.

## DNS security

**Sub-topics:** DNSSEC, Subdomain takeover, CAA, Threat modeling and trust boundaries (DNS security), Abuse cases and adversarial testing (DNS security)

### Do (use this in Cloudflare Workers)

- Map `DNS security` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `DNS security` before merge.

### Don't

- Do not ship `DNS security` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `DNS security`.

### Verify

- Peer review `DNS security` against domain skill `security-network-transport`.

## WAF and edge protection

**Sub-topics:** Rule tuning, Bypass, Threat modeling and trust boundaries (WAF and edge protection), Abuse cases and adversarial testing (WAF and edge protection), Logging, audit, and detection (WAF and edge protection)

### Do (use this in Cloudflare Workers)

- Map `WAF and edge protection` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `WAF and edge protection` before merge.

### Don't

- Do not ship `WAF and edge protection` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `WAF and edge protection`.

### Verify

- Peer review `WAF and edge protection` against domain skill `security-network-transport`.

## SSRF

**Sub-topics:** Metadata endpoints, URL parsers, Allowlists, Threat modeling and trust boundaries (SSRF), Abuse cases and adversarial testing (SSRF)

### Do (use this in Cloudflare Workers)

- Map `SSRF` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `SSRF` before merge.

### Don't

- Do not ship `SSRF` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `SSRF`.

### Verify

- Peer review `SSRF` against domain skill `security-network-transport`.

## Reverse proxies

**Sub-topics:** Header injection, Path normalization, Threat modeling and trust boundaries (Reverse proxies), Abuse cases and adversarial testing (Reverse proxies), Logging, audit, and detection (Reverse proxies)

### Do (use this in Cloudflare Workers)

- Map `Reverse proxies` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `Reverse proxies` before merge.

### Don't

- Do not ship `Reverse proxies` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `Reverse proxies`.

### Verify

- Peer review `Reverse proxies` against domain skill `security-network-transport`.

## VPN and private networking

**Sub-topics:** Split tunnel, Peering, Threat modeling and trust boundaries (VPN and private networking), Abuse cases and adversarial testing (VPN and private networking), Logging, audit, and detection (VPN and private networking)

### Do (use this in Cloudflare Workers)

- Map `VPN and private networking` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `VPN and private networking` before merge.

### Don't

- Do not ship `VPN and private networking` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `VPN and private networking`.

### Verify

- Peer review `VPN and private networking` against domain skill `security-network-transport`.

## DDoS and volumetric attacks

**Sub-topics:** Rate limits, Anycast, Threat modeling and trust boundaries (DDoS and volumetric attacks), Abuse cases and adversarial testing (DDoS and volumetric attacks), Logging, audit, and detection (DDoS and volumetric attacks)

### Do (use this in Cloudflare Workers)

- Map `DDoS and volumetric attacks` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `DDoS and volumetric attacks` before merge.

### Don't

- Do not ship `DDoS and volumetric attacks` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `DDoS and volumetric attacks`.

### Verify

- Peer review `DDoS and volumetric attacks` against domain skill `security-network-transport`.

## IP allowlisting pitfalls

**Sub-topics:** Spoofing, Shared NAT, Threat modeling and trust boundaries (IP allowlisting pitfalls), Abuse cases and adversarial testing (IP allowlisting pitfalls), Logging, audit, and detection (IP allowlisting pitfalls)

### Do (use this in Cloudflare Workers)

- Map `IP allowlisting pitfalls` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `IP allowlisting pitfalls` before merge.

### Don't

- Do not ship `IP allowlisting pitfalls` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `IP allowlisting pitfalls`.

### Verify

- Peer review `IP allowlisting pitfalls` against domain skill `security-network-transport`.

## HTTP request smuggling

**Sub-topics:** Front/back desync, Threat modeling and trust boundaries (HTTP request smuggling), Abuse cases and adversarial testing (HTTP request smuggling), Logging, audit, and detection (HTTP request smuggling), Access control and least privilege (HTTP request smuggling)

### Do (use this in Cloudflare Workers)

- Map `HTTP request smuggling` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `HTTP request smuggling` before merge.

### Don't

- Do not ship `HTTP request smuggling` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `HTTP request smuggling`.

### Verify

- Peer review `HTTP request smuggling` against domain skill `security-network-transport`.

## WebSocket transport

**Sub-topics:** Origin checks, TLS, Threat modeling and trust boundaries (WebSocket transport), Abuse cases and adversarial testing (WebSocket transport), Logging, audit, and detection (WebSocket transport)

### Do (use this in Cloudflare Workers)

- Map `WebSocket transport` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `WebSocket transport` before merge.

### Don't

- Do not ship `WebSocket transport` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `WebSocket transport`.

### Verify

- Peer review `WebSocket transport` against domain skill `security-network-transport`.

## SMTP security

**Sub-topics:** STARTTLS, SPF/DKIM/DMARC, Threat modeling and trust boundaries (SMTP security), Abuse cases and adversarial testing (SMTP security), Logging, audit, and detection (SMTP security)

### Do (use this in Cloudflare Workers)

- Map `SMTP security` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `SMTP security` before merge.

### Don't

- Do not ship `SMTP security` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `SMTP security`.

### Verify

- Peer review `SMTP security` against domain skill `security-network-transport`.

## IPv6 and dual stack

**Sub-topics:** Unexpected exposure, Threat modeling and trust boundaries (IPv6 and dual stack), Abuse cases and adversarial testing (IPv6 and dual stack), Logging, audit, and detection (IPv6 and dual stack), Access control and least privilege (IPv6 and dual stack)

### Do (use this in Cloudflare Workers)

- Map `IPv6 and dual stack` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `IPv6 and dual stack` before merge.

### Don't

- Do not ship `IPv6 and dual stack` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `IPv6 and dual stack`.

### Verify

- Peer review `IPv6 and dual stack` against domain skill `security-network-transport`.

## Service mesh mTLS

**Sub-topics:** Identity, Policy, Threat modeling and trust boundaries (Service mesh mTLS), Abuse cases and adversarial testing (Service mesh mTLS), Logging, audit, and detection (Service mesh mTLS)

### Do (use this in Cloudflare Workers)

- Map `Service mesh mTLS` controls to Cloudflare Workers APIs documented for `security-network-transport`.
- Add an abuse-case test or check for `Service mesh mTLS` before merge.

### Don't

- Do not ship `Service mesh mTLS` work in Cloudflare Workers with only happy-path tests.
- Do not disable Cloudflare Workers security defaults to unblock `Service mesh mTLS`.

### Verify

- Peer review `Service mesh mTLS` against domain skill `security-network-transport`.

