# Kotlin / Jetpack Compose: Embedded, IoT, and operational technology

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-embedded-iot-ot` / `reference.md`.

## Firmware update security

**Sub-topics:** Signed images, Rollback protection, OTA channels, Brick attacks, Dual bank

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Secure boot and trust anchor

**Sub-topics:** TPM, eFuse, Chain of trust, JTAG disable, Debug ports

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Device communications

**Sub-topics:** MQTT TLS, CoAP, BLE pairing, Zigbee keys, LoRaWAN

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Default credentials

**Sub-topics:** UART shells, Telnet, Hardcoded passwords, SNMP public, Web admin

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Physical tamper resistance

**Sub-topics:** Glitching, Side channels, Enclosures, Tamper switches, Key extraction

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## RTOS and bare metal

**Sub-topics:** Stack overflows, MPU config, ISR safety, Heap fragmentation, Watchdog

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Industrial OT and SCADA

**Sub-topics:** Modbus exposure, PLC programming, Safety systems, Air gap myths, Engineering workstations

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Medical and safety devices

**Sub-topics:** FDA cyber, Patient harm, Update windows, SBOM, Recall

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Automotive and CAN

**Sub-topics:** CAN injection, OBD ports, OTA vehicles, Infotainment bridge, Key fobs

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## IoT cloud backends

**Sub-topics:** Device provisioning, Certificate lifecycle, Fleet management, Shadow devices, Tenant isolation

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Botnet and abuse

**Sub-topics:** Mirai patterns, Telnet scanning, Credential stuffing C2, DDoS enlistment, Cryptomining

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Firmware supply chain

**Sub-topics:** Third-party SDKs, Chip vendor blobs, CI for embedded, Binary reproducibility, CVE in BSP

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

