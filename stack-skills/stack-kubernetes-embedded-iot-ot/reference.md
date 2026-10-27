# Kubernetes: Embedded, IoT, and operational technology

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-embedded-iot-ot` / `reference.md`.

## Firmware update security

**Sub-topics:** Signed images, Rollback protection, OTA channels, Brick attacks, Dual bank

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for firmware controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Secure boot and trust anchor

**Sub-topics:** TPM, eFuse, Chain of trust, JTAG disable, Debug ports

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for secure_boot controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Device communications

**Sub-topics:** MQTT TLS, CoAP, BLE pairing, Zigbee keys, LoRaWAN

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for iot_comm controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Default credentials

**Sub-topics:** UART shells, Telnet, Hardcoded passwords, SNMP public, Web admin

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for default_creds controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Physical tamper resistance

**Sub-topics:** Glitching, Side channels, Enclosures, Tamper switches, Key extraction

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for physical_tamper controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## RTOS and bare metal

**Sub-topics:** Stack overflows, MPU config, ISR safety, Heap fragmentation, Watchdog

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for rtos controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Industrial OT and SCADA

**Sub-topics:** Modbus exposure, PLC programming, Safety systems, Air gap myths, Engineering workstations

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for ot controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Medical and safety devices

**Sub-topics:** FDA cyber, Patient harm, Update windows, SBOM, Recall

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for medical controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Automotive and CAN

**Sub-topics:** CAN injection, OBD ports, OTA vehicles, Infotainment bridge, Key fobs

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for automotive controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## IoT cloud backends

**Sub-topics:** Device provisioning, Certificate lifecycle, Fleet management, Shadow devices, Tenant isolation

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for iot_cloud controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Botnet and abuse

**Sub-topics:** Mirai patterns, Telnet scanning, Credential stuffing C2, DDoS enlistment, Cryptomining

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for iot_botnet controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

## Firmware supply chain

**Sub-topics:** Third-party SDKs, Chip vendor blobs, CI for embedded, Binary reproducibility, CVE in BSP

### Do (use this in Kubernetes)

- Apply domain skill `security-embedded-iot-ot` requirements using kubernetes supported APIs only.
- Use the official kubernetes security documentation for firmware_supply controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of kubernetes for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on kubernetes projects in CI.

