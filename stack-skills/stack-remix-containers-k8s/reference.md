# Remix: Containers and Kubernetes

Stack-specific implementation for **Remix** (Web UI). Normative rules: domain skill `security-containers-k8s` / `reference.md`.

## Container image security

**Sub-topics:** Base images, SBOM, Signing, Threat modeling and trust boundaries (Container image security), Abuse cases and adversarial testing (Container image security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Container image security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container image security.
- Keep dependencies patched; pin versions for Container image security components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Container image security before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Container image security paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Kubernetes RBAC

**Sub-topics:** Cluster-admin, Namespace isolation, Threat modeling and trust boundaries (Kubernetes RBAC), Abuse cases and adversarial testing (Kubernetes RBAC), Logging, audit, and detection (Kubernetes RBAC)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Kubernetes RBAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Kubernetes RBAC.
- Keep dependencies patched; pin versions for Kubernetes RBAC components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Kubernetes RBAC before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Kubernetes RBAC paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Network policies

**Sub-topics:** Default allow, Egress control, Threat modeling and trust boundaries (Network policies), Abuse cases and adversarial testing (Network policies), Logging, audit, and detection (Network policies)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Network policies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Network policies.
- Keep dependencies patched; pin versions for Network policies components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Network policies before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Network policies paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Kubernetes secrets

**Sub-topics:** etcd encryption, External secrets, Threat modeling and trust boundaries (Kubernetes secrets), Abuse cases and adversarial testing (Kubernetes secrets), Logging, audit, and detection (Kubernetes secrets)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Kubernetes secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Kubernetes secrets.
- Keep dependencies patched; pin versions for Kubernetes secrets components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Kubernetes secrets before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Kubernetes secrets paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Container runtime

**Sub-topics:** Privileged pods, Host mounts, Threat modeling and trust boundaries (Container runtime), Abuse cases and adversarial testing (Container runtime), Logging, audit, and detection (Container runtime)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Container runtime; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container runtime.
- Keep dependencies patched; pin versions for Container runtime components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Container runtime before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Container runtime paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Admission controllers

**Sub-topics:** OPA/Gatekeeper, Pod security, Threat modeling and trust boundaries (Admission controllers), Abuse cases and adversarial testing (Admission controllers), Logging, audit, and detection (Admission controllers)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Admission controllers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Admission controllers.
- Keep dependencies patched; pin versions for Admission controllers components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Admission controllers before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Admission controllers paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Helm charts

**Sub-topics:** Templated secrets, Chart provenance, Threat modeling and trust boundaries (Helm charts), Abuse cases and adversarial testing (Helm charts), Logging, audit, and detection (Helm charts)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Helm charts; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Helm charts.
- Keep dependencies patched; pin versions for Helm charts components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Helm charts before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Helm charts paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Container registries

**Sub-topics:** Pull secrets, Retention, Threat modeling and trust boundaries (Container registries), Abuse cases and adversarial testing (Container registries), Logging, audit, and detection (Container registries)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Container registries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container registries.
- Keep dependencies patched; pin versions for Container registries components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Container registries before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Container registries paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Sidecars and service mesh

**Sub-topics:** Token theft, Localhost trust, Threat modeling and trust boundaries (Sidecars and service mesh), Abuse cases and adversarial testing (Sidecars and service mesh), Logging, audit, and detection (Sidecars and service mesh)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Sidecars and service mesh; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Sidecars and service mesh.
- Keep dependencies patched; pin versions for Sidecars and service mesh components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Sidecars and service mesh before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Sidecars and service mesh paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Windows containers

**Sub-topics:** Isolation levels, Threat modeling and trust boundaries (Windows containers), Abuse cases and adversarial testing (Windows containers), Logging, audit, and detection (Windows containers), Access control and least privilege (Windows containers)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Windows containers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Windows containers.
- Keep dependencies patched; pin versions for Windows containers components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Windows containers before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Windows containers paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Docker Compose dev security

**Sub-topics:** Published ports, Volume mounts, Threat modeling and trust boundaries (Docker Compose dev security), Abuse cases and adversarial testing (Docker Compose dev security), Logging, audit, and detection (Docker Compose dev security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Docker Compose dev security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Docker Compose dev security.
- Keep dependencies patched; pin versions for Docker Compose dev security components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Docker Compose dev security before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Docker Compose dev security paths in Remix.
- Run SAST/dependency scan configured for Web UI.

## Container escape vectors

**Sub-topics:** Kernel CVEs, Capabilities, Threat modeling and trust boundaries (Container escape vectors), Abuse cases and adversarial testing (Container escape vectors), Logging, audit, and detection (Container escape vectors)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Container escape vectors; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container escape vectors.
- Keep dependencies patched; pin versions for Container escape vectors components.

### How to do this in Remix

- Read normative rules in domain skill `security-containers-k8s` / `reference.md`, then apply them using Remix APIs and deployment model.
- Prefer framework-maintained security features in Remix over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Container escape vectors before merge.
- Pin Remix dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Container escape vectors paths in Remix.
- Run SAST/dependency scan configured for Web UI.

