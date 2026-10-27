# Docker: Containers and Kubernetes

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-containers-k8s` / `reference.md`.

## Container image security

**Sub-topics:** Base images, SBOM, Signing, Threat modeling and trust boundaries (Container image security), Abuse cases and adversarial testing (Container image security)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Kubernetes RBAC

**Sub-topics:** Cluster-admin, Namespace isolation, Threat modeling and trust boundaries (Kubernetes RBAC), Abuse cases and adversarial testing (Kubernetes RBAC), Logging, audit, and detection (Kubernetes RBAC)

### Do (use this in Docker)

- Map `Kubernetes RBAC` controls to Docker APIs documented for `security-containers-k8s`.
- Add an abuse-case test or check for `Kubernetes RBAC` before merge.

### Don't

- Do not ship `Kubernetes RBAC` work in Docker with only happy-path tests.
- Do not disable Docker security defaults to unblock `Kubernetes RBAC`.

### Verify

- Peer review `Kubernetes RBAC` against domain skill `security-containers-k8s`.

## Network policies

**Sub-topics:** Default allow, Egress control, Threat modeling and trust boundaries (Network policies), Abuse cases and adversarial testing (Network policies), Logging, audit, and detection (Network policies)

### Do (use this in Docker)

- Map `Network policies` controls to Docker APIs documented for `security-containers-k8s`.
- Add an abuse-case test or check for `Network policies` before merge.

### Don't

- Do not ship `Network policies` work in Docker with only happy-path tests.
- Do not disable Docker security defaults to unblock `Network policies`.

### Verify

- Peer review `Network policies` against domain skill `security-containers-k8s`.

## Kubernetes secrets

**Sub-topics:** etcd encryption, External secrets, Threat modeling and trust boundaries (Kubernetes secrets), Abuse cases and adversarial testing (Kubernetes secrets), Logging, audit, and detection (Kubernetes secrets)

### Do (use this in Docker)

- Map `Kubernetes secrets` controls to Docker APIs documented for `security-containers-k8s`.
- Add an abuse-case test or check for `Kubernetes secrets` before merge.

### Don't

- Do not ship `Kubernetes secrets` work in Docker with only happy-path tests.
- Do not disable Docker security defaults to unblock `Kubernetes secrets`.

### Verify

- Peer review `Kubernetes secrets` against domain skill `security-containers-k8s`.

## Container runtime

**Sub-topics:** Privileged pods, Host mounts, Threat modeling and trust boundaries (Container runtime), Abuse cases and adversarial testing (Container runtime), Logging, audit, and detection (Container runtime)

### Do (use this in Docker)

- Map `Container runtime` controls to Docker APIs documented for `security-containers-k8s`.
- Add an abuse-case test or check for `Container runtime` before merge.

### Don't

- Do not ship `Container runtime` work in Docker with only happy-path tests.
- Do not disable Docker security defaults to unblock `Container runtime`.

### Verify

- Peer review `Container runtime` against domain skill `security-containers-k8s`.

## Admission controllers

**Sub-topics:** OPA/Gatekeeper, Pod security, Threat modeling and trust boundaries (Admission controllers), Abuse cases and adversarial testing (Admission controllers), Logging, audit, and detection (Admission controllers)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Helm charts

**Sub-topics:** Templated secrets, Chart provenance, Threat modeling and trust boundaries (Helm charts), Abuse cases and adversarial testing (Helm charts), Logging, audit, and detection (Helm charts)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Container registries

**Sub-topics:** Pull secrets, Retention, Threat modeling and trust boundaries (Container registries), Abuse cases and adversarial testing (Container registries), Logging, audit, and detection (Container registries)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Sidecars and service mesh

**Sub-topics:** Token theft, Localhost trust, Threat modeling and trust boundaries (Sidecars and service mesh), Abuse cases and adversarial testing (Sidecars and service mesh), Logging, audit, and detection (Sidecars and service mesh)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Windows containers

**Sub-topics:** Isolation levels, Threat modeling and trust boundaries (Windows containers), Abuse cases and adversarial testing (Windows containers), Logging, audit, and detection (Windows containers), Access control and least privilege (Windows containers)

### Do (use this in Docker)

- Map `Windows containers` controls to Docker APIs documented for `security-containers-k8s`.
- Add an abuse-case test or check for `Windows containers` before merge.

### Don't

- Do not ship `Windows containers` work in Docker with only happy-path tests.
- Do not disable Docker security defaults to unblock `Windows containers`.

### Verify

- Peer review `Windows containers` against domain skill `security-containers-k8s`.

## Docker Compose dev security

**Sub-topics:** Published ports, Volume mounts, Threat modeling and trust boundaries (Docker Compose dev security), Abuse cases and adversarial testing (Docker Compose dev security), Logging, audit, and detection (Docker Compose dev security)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Container escape vectors

**Sub-topics:** Kernel CVEs, Capabilities, Threat modeling and trust boundaries (Container escape vectors), Abuse cases and adversarial testing (Container escape vectors), Logging, audit, and detection (Container escape vectors)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

