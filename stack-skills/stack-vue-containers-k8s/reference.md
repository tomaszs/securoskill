# Vue.js: Containers and Kubernetes

Stack-specific implementation for **Vue.js** (Web UI). Normative rules: domain skill `security-containers-k8s` / `reference.md`.

## Container image security

**Sub-topics:** Base images, SBOM, Signing, Threat modeling and trust boundaries (Container image security), Abuse cases and adversarial testing (Container image security)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Kubernetes RBAC

**Sub-topics:** Cluster-admin, Namespace isolation, Threat modeling and trust boundaries (Kubernetes RBAC), Abuse cases and adversarial testing (Kubernetes RBAC), Logging, audit, and detection (Kubernetes RBAC)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Network policies

**Sub-topics:** Default allow, Egress control, Threat modeling and trust boundaries (Network policies), Abuse cases and adversarial testing (Network policies), Logging, audit, and detection (Network policies)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Kubernetes secrets

**Sub-topics:** etcd encryption, External secrets, Threat modeling and trust boundaries (Kubernetes secrets), Abuse cases and adversarial testing (Kubernetes secrets), Logging, audit, and detection (Kubernetes secrets)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Container runtime

**Sub-topics:** Privileged pods, Host mounts, Threat modeling and trust boundaries (Container runtime), Abuse cases and adversarial testing (Container runtime), Logging, audit, and detection (Container runtime)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Admission controllers

**Sub-topics:** OPA/Gatekeeper, Pod security, Threat modeling and trust boundaries (Admission controllers), Abuse cases and adversarial testing (Admission controllers), Logging, audit, and detection (Admission controllers)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Helm charts

**Sub-topics:** Templated secrets, Chart provenance, Threat modeling and trust boundaries (Helm charts), Abuse cases and adversarial testing (Helm charts), Logging, audit, and detection (Helm charts)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Container registries

**Sub-topics:** Pull secrets, Retention, Threat modeling and trust boundaries (Container registries), Abuse cases and adversarial testing (Container registries), Logging, audit, and detection (Container registries)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Sidecars and service mesh

**Sub-topics:** Token theft, Localhost trust, Threat modeling and trust boundaries (Sidecars and service mesh), Abuse cases and adversarial testing (Sidecars and service mesh), Logging, audit, and detection (Sidecars and service mesh)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Windows containers

**Sub-topics:** Isolation levels, Threat modeling and trust boundaries (Windows containers), Abuse cases and adversarial testing (Windows containers), Logging, audit, and detection (Windows containers), Access control and least privilege (Windows containers)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Docker Compose dev security

**Sub-topics:** Published ports, Volume mounts, Threat modeling and trust boundaries (Docker Compose dev security), Abuse cases and adversarial testing (Docker Compose dev security), Logging, audit, and detection (Docker Compose dev security)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

## Container escape vectors

**Sub-topics:** Kernel CVEs, Capabilities, Threat modeling and trust boundaries (Container escape vectors), Abuse cases and adversarial testing (Container escape vectors), Logging, audit, and detection (Container escape vectors)

### Do (use this in Vue.js)

- Vue.js is not the primary enforcement point for `containers-k8s`; load stack skill `stack-kubernetes-containers-k8s` when you touch that layer.
- Keep Vue.js configuration aligned with requirements from `security-containers-k8s` (domain reference.md).

### Don't

- Do not duplicate `containers-k8s` controls only in Vue.js config while leaving stack-kubernetes-containers-k8s misconfigured.
- Do not assume Vue.js defaults satisfy `security-containers-k8s` without verification.

### Verify

- Integration test the full path: Vue.js plus the system covered by `stack-kubernetes-containers-k8s`.

