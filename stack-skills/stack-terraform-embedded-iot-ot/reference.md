# Terraform: Embedded, IoT, and operational technology

Stack-specific implementation for **Terraform** (Infrastructure). Normative rules: domain skill `security-embedded-iot-ot` / `reference.md`.

## Firmware update security

**Sub-topics:** Signed images, Rollback protection, OTA channels, Brick attacks, Dual bank

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Secure boot and trust anchor

**Sub-topics:** TPM, eFuse, Chain of trust, JTAG disable, Debug ports

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Device communications

**Sub-topics:** MQTT TLS, CoAP, BLE pairing, Zigbee keys, LoRaWAN

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Default credentials

**Sub-topics:** UART shells, Telnet, Hardcoded passwords, SNMP public, Web admin

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Physical tamper resistance

**Sub-topics:** Glitching, Side channels, Enclosures, Tamper switches, Key extraction

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## RTOS and bare metal

**Sub-topics:** Stack overflows, MPU config, ISR safety, Heap fragmentation, Watchdog

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Industrial OT and SCADA

**Sub-topics:** Modbus exposure, PLC programming, Safety systems, Air gap myths, Engineering workstations

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Medical and safety devices

**Sub-topics:** FDA cyber, Patient harm, Update windows, SBOM, Recall

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Automotive and CAN

**Sub-topics:** CAN injection, OBD ports, OTA vehicles, Infotainment bridge, Key fobs

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## IoT cloud backends

**Sub-topics:** Device provisioning, Certificate lifecycle, Fleet management, Shadow devices, Tenant isolation

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Botnet and abuse

**Sub-topics:** Mirai patterns, Telnet scanning, Credential stuffing C2, DDoS enlistment, Cryptomining

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Firmware supply chain

**Sub-topics:** Third-party SDKs, Chip vendor blobs, CI for embedded, Binary reproducibility, CVE in BSP

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

