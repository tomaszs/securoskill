# Actix Web (Rust): Embedded, IoT, and operational technology

Stack-specific implementation for **Actix Web (Rust)** (Rust). Normative rules: domain skill `security-embedded-iot-ot` / `reference.md`.

## Firmware update security

**Sub-topics:** Signed images, Rollback protection, OTA channels, Brick attacks, Dual bank

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Secure boot and trust anchor

**Sub-topics:** TPM, eFuse, Chain of trust, JTAG disable, Debug ports

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Device communications

**Sub-topics:** MQTT TLS, CoAP, BLE pairing, Zigbee keys, LoRaWAN

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Default credentials

**Sub-topics:** UART shells, Telnet, Hardcoded passwords, SNMP public, Web admin

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Physical tamper resistance

**Sub-topics:** Glitching, Side channels, Enclosures, Tamper switches, Key extraction

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## RTOS and bare metal

**Sub-topics:** Stack overflows, MPU config, ISR safety, Heap fragmentation, Watchdog

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Industrial OT and SCADA

**Sub-topics:** Modbus exposure, PLC programming, Safety systems, Air gap myths, Engineering workstations

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Medical and safety devices

**Sub-topics:** FDA cyber, Patient harm, Update windows, SBOM, Recall

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Automotive and CAN

**Sub-topics:** CAN injection, OBD ports, OTA vehicles, Infotainment bridge, Key fobs

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## IoT cloud backends

**Sub-topics:** Device provisioning, Certificate lifecycle, Fleet management, Shadow devices, Tenant isolation

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Botnet and abuse

**Sub-topics:** Mirai patterns, Telnet scanning, Credential stuffing C2, DDoS enlistment, Cryptomining

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

## Firmware supply chain

**Sub-topics:** Third-party SDKs, Chip vendor blobs, CI for embedded, Binary reproducibility, CVE in BSP

### Do (use this in Actix Web (Rust))

- Actix Web (Rust) is not the primary enforcement point for `embedded-iot-ot`; load stack skill `security-embedded-iot-ot` when you touch that layer.
- Keep Actix Web (Rust) configuration aligned with requirements from `security-embedded-iot-ot` (domain reference.md).

### Don't

- Do not duplicate `embedded-iot-ot` controls only in Actix Web (Rust) config while leaving security-embedded-iot-ot misconfigured.
- Do not assume Actix Web (Rust) defaults satisfy `security-embedded-iot-ot` without verification.

### Verify

- Integration test the full path: Actix Web (Rust) plus the system covered by `security-embedded-iot-ot`.

