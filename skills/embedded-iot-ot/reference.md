# Rules reference: Embedded, IoT, and operational technology

Firmware, devices, industrial systems, and constrained environments.

## Firmware update security

Sub-topics: Signed images, Rollback protection, OTA channels, Brick attacks, Dual bank

### Policy

- Treat Firmware update security in Firmware update security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Firmware update security (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Firmware update security.

### Design

- Apply least privilege and defense in depth for Firmware update security.
- Prefer established patterns and libraries over custom crypto or auth for Firmware update security.
- Fail closed: deny by default when Firmware update security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Firmware update security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Firmware update security.
- Keep dependencies patched; pin versions for Firmware update security components.

### Verification

- Add automated tests and SAST/DAST coverage for Firmware update security paths.
- Run dependency and secret scanning on every change touching Firmware update security.
- Perform targeted manual tests (abuse cases) for Firmware update security.

### Operations

- Log security-relevant events for Firmware update security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Firmware update security.
- Review access and configuration for Firmware update security on a regular cadence.

## Secure boot and trust anchor

Sub-topics: TPM, eFuse, Chain of trust, JTAG disable, Debug ports

### Policy

- Treat Secure boot and trust anchor in Secure boot and trust anchor as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secure boot and trust anchor (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Secure boot and trust anchor.

### Design

- Apply least privilege and defense in depth for Secure boot and trust anchor.
- Prefer established patterns and libraries over custom crypto or auth for Secure boot and trust anchor.
- Fail closed: deny by default when Secure boot and trust anchor cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secure boot and trust anchor; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secure boot and trust anchor.
- Keep dependencies patched; pin versions for Secure boot and trust anchor components.

### Verification

- Add automated tests and SAST/DAST coverage for Secure boot and trust anchor paths.
- Run dependency and secret scanning on every change touching Secure boot and trust anchor.
- Perform targeted manual tests (abuse cases) for Secure boot and trust anchor.

### Operations

- Log security-relevant events for Secure boot and trust anchor without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secure boot and trust anchor.
- Review access and configuration for Secure boot and trust anchor on a regular cadence.

## Device communications

Sub-topics: MQTT TLS, CoAP, BLE pairing, Zigbee keys, LoRaWAN

### Policy

- Treat Device communications in Device communications as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Device communications (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Device communications.

### Design

- Apply least privilege and defense in depth for Device communications.
- Prefer established patterns and libraries over custom crypto or auth for Device communications.
- Fail closed: deny by default when Device communications cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Device communications; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Device communications.
- Keep dependencies patched; pin versions for Device communications components.

### Verification

- Add automated tests and SAST/DAST coverage for Device communications paths.
- Run dependency and secret scanning on every change touching Device communications.
- Perform targeted manual tests (abuse cases) for Device communications.

### Operations

- Log security-relevant events for Device communications without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Device communications.
- Review access and configuration for Device communications on a regular cadence.

## Default credentials

Sub-topics: UART shells, Telnet, Hardcoded passwords, SNMP public, Web admin

### Policy

- Treat Default credentials in Default credentials as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Default credentials (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Default credentials.

### Design

- Apply least privilege and defense in depth for Default credentials.
- Prefer established patterns and libraries over custom crypto or auth for Default credentials.
- Fail closed: deny by default when Default credentials cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Default credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Default credentials.
- Keep dependencies patched; pin versions for Default credentials components.

### Verification

- Add automated tests and SAST/DAST coverage for Default credentials paths.
- Run dependency and secret scanning on every change touching Default credentials.
- Perform targeted manual tests (abuse cases) for Default credentials.

### Operations

- Log security-relevant events for Default credentials without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Default credentials.
- Review access and configuration for Default credentials on a regular cadence.

## Physical tamper resistance

Sub-topics: Glitching, Side channels, Enclosures, Tamper switches, Key extraction

### Policy

- Treat Physical tamper resistance in Physical tamper resistance as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Physical tamper resistance (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Physical tamper resistance.

### Design

- Apply least privilege and defense in depth for Physical tamper resistance.
- Prefer established patterns and libraries over custom crypto or auth for Physical tamper resistance.
- Fail closed: deny by default when Physical tamper resistance cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Physical tamper resistance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Physical tamper resistance.
- Keep dependencies patched; pin versions for Physical tamper resistance components.

### Verification

- Add automated tests and SAST/DAST coverage for Physical tamper resistance paths.
- Run dependency and secret scanning on every change touching Physical tamper resistance.
- Perform targeted manual tests (abuse cases) for Physical tamper resistance.

### Operations

- Log security-relevant events for Physical tamper resistance without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Physical tamper resistance.
- Review access and configuration for Physical tamper resistance on a regular cadence.

## RTOS and bare metal

Sub-topics: Stack overflows, MPU config, ISR safety, Heap fragmentation, Watchdog

### Policy

- Treat RTOS and bare metal in RTOS and bare metal as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for RTOS and bare metal (Embedded, IoT, and operational technology).
- Require security review for material changes affecting RTOS and bare metal.

### Design

- Apply least privilege and defense in depth for RTOS and bare metal.
- Prefer established patterns and libraries over custom crypto or auth for RTOS and bare metal.
- Fail closed: deny by default when RTOS and bare metal cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching RTOS and bare metal; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RTOS and bare metal.
- Keep dependencies patched; pin versions for RTOS and bare metal components.

### Verification

- Add automated tests and SAST/DAST coverage for RTOS and bare metal paths.
- Run dependency and secret scanning on every change touching RTOS and bare metal.
- Perform targeted manual tests (abuse cases) for RTOS and bare metal.

### Operations

- Log security-relevant events for RTOS and bare metal without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in RTOS and bare metal.
- Review access and configuration for RTOS and bare metal on a regular cadence.

## Industrial OT and SCADA

Sub-topics: Modbus exposure, PLC programming, Safety systems, Air gap myths, Engineering workstations

### Policy

- Treat Industrial OT and SCADA in Industrial OT and SCADA as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Industrial OT and SCADA (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Industrial OT and SCADA.

### Design

- Apply least privilege and defense in depth for Industrial OT and SCADA.
- Prefer established patterns and libraries over custom crypto or auth for Industrial OT and SCADA.
- Fail closed: deny by default when Industrial OT and SCADA cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Industrial OT and SCADA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Industrial OT and SCADA.
- Keep dependencies patched; pin versions for Industrial OT and SCADA components.

### Verification

- Add automated tests and SAST/DAST coverage for Industrial OT and SCADA paths.
- Run dependency and secret scanning on every change touching Industrial OT and SCADA.
- Perform targeted manual tests (abuse cases) for Industrial OT and SCADA.

### Operations

- Log security-relevant events for Industrial OT and SCADA without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Industrial OT and SCADA.
- Review access and configuration for Industrial OT and SCADA on a regular cadence.

## Medical and safety devices

Sub-topics: FDA cyber, Patient harm, Update windows, SBOM, Recall

### Policy

- Treat Medical and safety devices in Medical and safety devices as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Medical and safety devices (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Medical and safety devices.

### Design

- Apply least privilege and defense in depth for Medical and safety devices.
- Prefer established patterns and libraries over custom crypto or auth for Medical and safety devices.
- Fail closed: deny by default when Medical and safety devices cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Medical and safety devices; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Medical and safety devices.
- Keep dependencies patched; pin versions for Medical and safety devices components.

### Verification

- Add automated tests and SAST/DAST coverage for Medical and safety devices paths.
- Run dependency and secret scanning on every change touching Medical and safety devices.
- Perform targeted manual tests (abuse cases) for Medical and safety devices.

### Operations

- Log security-relevant events for Medical and safety devices without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Medical and safety devices.
- Review access and configuration for Medical and safety devices on a regular cadence.

## Automotive and CAN

Sub-topics: CAN injection, OBD ports, OTA vehicles, Infotainment bridge, Key fobs

### Policy

- Treat Automotive and CAN in Automotive and CAN as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Automotive and CAN (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Automotive and CAN.

### Design

- Apply least privilege and defense in depth for Automotive and CAN.
- Prefer established patterns and libraries over custom crypto or auth for Automotive and CAN.
- Fail closed: deny by default when Automotive and CAN cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Automotive and CAN; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Automotive and CAN.
- Keep dependencies patched; pin versions for Automotive and CAN components.

### Verification

- Add automated tests and SAST/DAST coverage for Automotive and CAN paths.
- Run dependency and secret scanning on every change touching Automotive and CAN.
- Perform targeted manual tests (abuse cases) for Automotive and CAN.

### Operations

- Log security-relevant events for Automotive and CAN without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Automotive and CAN.
- Review access and configuration for Automotive and CAN on a regular cadence.

## IoT cloud backends

Sub-topics: Device provisioning, Certificate lifecycle, Fleet management, Shadow devices, Tenant isolation

### Policy

- Treat IoT cloud backends in IoT cloud backends as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for IoT cloud backends (Embedded, IoT, and operational technology).
- Require security review for material changes affecting IoT cloud backends.

### Design

- Apply least privilege and defense in depth for IoT cloud backends.
- Prefer established patterns and libraries over custom crypto or auth for IoT cloud backends.
- Fail closed: deny by default when IoT cloud backends cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching IoT cloud backends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IoT cloud backends.
- Keep dependencies patched; pin versions for IoT cloud backends components.

### Verification

- Add automated tests and SAST/DAST coverage for IoT cloud backends paths.
- Run dependency and secret scanning on every change touching IoT cloud backends.
- Perform targeted manual tests (abuse cases) for IoT cloud backends.

### Operations

- Log security-relevant events for IoT cloud backends without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in IoT cloud backends.
- Review access and configuration for IoT cloud backends on a regular cadence.

## Botnet and abuse

Sub-topics: Mirai patterns, Telnet scanning, Credential stuffing C2, DDoS enlistment, Cryptomining

### Policy

- Treat Botnet and abuse in Botnet and abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Botnet and abuse (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Botnet and abuse.

### Design

- Apply least privilege and defense in depth for Botnet and abuse.
- Prefer established patterns and libraries over custom crypto or auth for Botnet and abuse.
- Fail closed: deny by default when Botnet and abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Botnet and abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Botnet and abuse.
- Keep dependencies patched; pin versions for Botnet and abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Botnet and abuse paths.
- Run dependency and secret scanning on every change touching Botnet and abuse.
- Perform targeted manual tests (abuse cases) for Botnet and abuse.

### Operations

- Log security-relevant events for Botnet and abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Botnet and abuse.
- Review access and configuration for Botnet and abuse on a regular cadence.

## Firmware supply chain

Sub-topics: Third-party SDKs, Chip vendor blobs, CI for embedded, Binary reproducibility, CVE in BSP

### Policy

- Treat Firmware supply chain in Firmware supply chain as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Firmware supply chain (Embedded, IoT, and operational technology).
- Require security review for material changes affecting Firmware supply chain.

### Design

- Apply least privilege and defense in depth for Firmware supply chain.
- Prefer established patterns and libraries over custom crypto or auth for Firmware supply chain.
- Fail closed: deny by default when Firmware supply chain cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Firmware supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Firmware supply chain.
- Keep dependencies patched; pin versions for Firmware supply chain components.

### Verification

- Add automated tests and SAST/DAST coverage for Firmware supply chain paths.
- Run dependency and secret scanning on every change touching Firmware supply chain.
- Perform targeted manual tests (abuse cases) for Firmware supply chain.

### Operations

- Log security-relevant events for Firmware supply chain without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Firmware supply chain.
- Review access and configuration for Firmware supply chain on a regular cadence.

