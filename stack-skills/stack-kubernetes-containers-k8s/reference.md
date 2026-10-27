# Kubernetes: Containers and Kubernetes

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-containers-k8s` / `reference.md`.

## Container image security

**Sub-topics:** Base images, SBOM, Signing, Threat modeling and trust boundaries (Container image security), Abuse cases and adversarial testing (Container image security)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Kubernetes RBAC

**Sub-topics:** Cluster-admin, Namespace isolation, Threat modeling and trust boundaries (Kubernetes RBAC), Abuse cases and adversarial testing (Kubernetes RBAC), Logging, audit, and detection (Kubernetes RBAC)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Network policies

**Sub-topics:** Default allow, Egress control, Threat modeling and trust boundaries (Network policies), Abuse cases and adversarial testing (Network policies), Logging, audit, and detection (Network policies)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Kubernetes secrets

**Sub-topics:** etcd encryption, External secrets, Threat modeling and trust boundaries (Kubernetes secrets), Abuse cases and adversarial testing (Kubernetes secrets), Logging, audit, and detection (Kubernetes secrets)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Container runtime

**Sub-topics:** Privileged pods, Host mounts, Threat modeling and trust boundaries (Container runtime), Abuse cases and adversarial testing (Container runtime), Logging, audit, and detection (Container runtime)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Admission controllers

**Sub-topics:** OPA/Gatekeeper, Pod security, Threat modeling and trust boundaries (Admission controllers), Abuse cases and adversarial testing (Admission controllers), Logging, audit, and detection (Admission controllers)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Helm charts

**Sub-topics:** Templated secrets, Chart provenance, Threat modeling and trust boundaries (Helm charts), Abuse cases and adversarial testing (Helm charts), Logging, audit, and detection (Helm charts)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Container registries

**Sub-topics:** Pull secrets, Retention, Threat modeling and trust boundaries (Container registries), Abuse cases and adversarial testing (Container registries), Logging, audit, and detection (Container registries)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Sidecars and service mesh

**Sub-topics:** Token theft, Localhost trust, Threat modeling and trust boundaries (Sidecars and service mesh), Abuse cases and adversarial testing (Sidecars and service mesh), Logging, audit, and detection (Sidecars and service mesh)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Windows containers

**Sub-topics:** Isolation levels, Threat modeling and trust boundaries (Windows containers), Abuse cases and adversarial testing (Windows containers), Logging, audit, and detection (Windows containers), Access control and least privilege (Windows containers)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Docker Compose dev security

**Sub-topics:** Published ports, Volume mounts, Threat modeling and trust boundaries (Docker Compose dev security), Abuse cases and adversarial testing (Docker Compose dev security), Logging, audit, and detection (Docker Compose dev security)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

## Container escape vectors

**Sub-topics:** Kernel CVEs, Capabilities, Threat modeling and trust boundaries (Container escape vectors), Abuse cases and adversarial testing (Container escape vectors), Logging, audit, and detection (Container escape vectors)

### Do (use this in Kubernetes)

- Apply `PodSecurity` restricted profile or equivalent.
- Use NetworkPolicy default-deny per namespace.

### Don't

- Do not mount host `/` or Docker socket into app pods.
- Do not store plaintext secrets in ConfigMaps.

### Verify

- kube-score, polaris, and OPA policies in admission.

