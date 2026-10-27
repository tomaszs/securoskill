# Spring Boot: Embedded, IoT, and operational technology

Stack-specific implementation for **Spring Boot** (Java). Normative rules: domain skill `security-embedded-iot-ot` / `reference.md`.

## Firmware update security

**Sub-topics:** Signed images, Rollback protection, OTA channels, Brick attacks, Dual bank

### Platform rules (summary)

- Validate and canonicalize all inputs touching Firmware update security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Firmware update security.
- Keep dependencies patched; pin versions for Firmware update security components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Firmware update security before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Firmware update security paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Secure boot and trust anchor

**Sub-topics:** TPM, eFuse, Chain of trust, JTAG disable, Debug ports

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secure boot and trust anchor; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secure boot and trust anchor.
- Keep dependencies patched; pin versions for Secure boot and trust anchor components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secure boot and trust anchor before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secure boot and trust anchor paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Device communications

**Sub-topics:** MQTT TLS, CoAP, BLE pairing, Zigbee keys, LoRaWAN

### Platform rules (summary)

- Validate and canonicalize all inputs touching Device communications; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Device communications.
- Keep dependencies patched; pin versions for Device communications components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Device communications before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Device communications paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Default credentials

**Sub-topics:** UART shells, Telnet, Hardcoded passwords, SNMP public, Web admin

### Platform rules (summary)

- Validate and canonicalize all inputs touching Default credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Default credentials.
- Keep dependencies patched; pin versions for Default credentials components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Default credentials before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Default credentials paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Physical tamper resistance

**Sub-topics:** Glitching, Side channels, Enclosures, Tamper switches, Key extraction

### Platform rules (summary)

- Validate and canonicalize all inputs touching Physical tamper resistance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Physical tamper resistance.
- Keep dependencies patched; pin versions for Physical tamper resistance components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Physical tamper resistance before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Physical tamper resistance paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## RTOS and bare metal

**Sub-topics:** Stack overflows, MPU config, ISR safety, Heap fragmentation, Watchdog

### Platform rules (summary)

- Validate and canonicalize all inputs touching RTOS and bare metal; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to RTOS and bare metal.
- Keep dependencies patched; pin versions for RTOS and bare metal components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for RTOS and bare metal before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for RTOS and bare metal paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Industrial OT and SCADA

**Sub-topics:** Modbus exposure, PLC programming, Safety systems, Air gap myths, Engineering workstations

### Platform rules (summary)

- Validate and canonicalize all inputs touching Industrial OT and SCADA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Industrial OT and SCADA.
- Keep dependencies patched; pin versions for Industrial OT and SCADA components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Industrial OT and SCADA before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Industrial OT and SCADA paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Medical and safety devices

**Sub-topics:** FDA cyber, Patient harm, Update windows, SBOM, Recall

### Platform rules (summary)

- Validate and canonicalize all inputs touching Medical and safety devices; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Medical and safety devices.
- Keep dependencies patched; pin versions for Medical and safety devices components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Medical and safety devices before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Medical and safety devices paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Automotive and CAN

**Sub-topics:** CAN injection, OBD ports, OTA vehicles, Infotainment bridge, Key fobs

### Platform rules (summary)

- Validate and canonicalize all inputs touching Automotive and CAN; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Automotive and CAN.
- Keep dependencies patched; pin versions for Automotive and CAN components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Automotive and CAN before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Automotive and CAN paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## IoT cloud backends

**Sub-topics:** Device provisioning, Certificate lifecycle, Fleet management, Shadow devices, Tenant isolation

### Platform rules (summary)

- Validate and canonicalize all inputs touching IoT cloud backends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IoT cloud backends.
- Keep dependencies patched; pin versions for IoT cloud backends components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for IoT cloud backends before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for IoT cloud backends paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Botnet and abuse

**Sub-topics:** Mirai patterns, Telnet scanning, Credential stuffing C2, DDoS enlistment, Cryptomining

### Platform rules (summary)

- Validate and canonicalize all inputs touching Botnet and abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Botnet and abuse.
- Keep dependencies patched; pin versions for Botnet and abuse components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Botnet and abuse before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Botnet and abuse paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Firmware supply chain

**Sub-topics:** Third-party SDKs, Chip vendor blobs, CI for embedded, Binary reproducibility, CVE in BSP

### Platform rules (summary)

- Validate and canonicalize all inputs touching Firmware supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Firmware supply chain.
- Keep dependencies patched; pin versions for Firmware supply chain components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-embedded-iot-ot` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Firmware supply chain before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Firmware supply chain paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

