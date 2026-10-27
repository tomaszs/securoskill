# Rules reference: Containers and Kubernetes

Images, orchestration, and runtime isolation.

## Container image security

Sub-topics: Base images, SBOM, Signing

### Policy

- Treat Container image security in Container image security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Container image security (Containers and Kubernetes).
- Require security review for material changes affecting Container image security.

### Design

- Apply least privilege and defense in depth for Container image security.
- Prefer established patterns and libraries over custom crypto or auth for Container image security.
- Fail closed: deny by default when Container image security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Container image security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container image security.
- Keep dependencies patched; pin versions for Container image security components.

### Verification

- Add automated tests and SAST/DAST coverage for Container image security paths.
- Run dependency and secret scanning on every change touching Container image security.
- Perform targeted manual tests (abuse cases) for Container image security.

### Operations

- Log security-relevant events for Container image security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Container image security.
- Review access and configuration for Container image security on a regular cadence.

## Kubernetes RBAC

Sub-topics: Cluster-admin, Namespace isolation

### Policy

- Treat Kubernetes RBAC in Kubernetes RBAC as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Kubernetes RBAC (Containers and Kubernetes).
- Require security review for material changes affecting Kubernetes RBAC.

### Design

- Apply least privilege and defense in depth for Kubernetes RBAC.
- Prefer established patterns and libraries over custom crypto or auth for Kubernetes RBAC.
- Fail closed: deny by default when Kubernetes RBAC cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Kubernetes RBAC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Kubernetes RBAC.
- Keep dependencies patched; pin versions for Kubernetes RBAC components.

### Verification

- Add automated tests and SAST/DAST coverage for Kubernetes RBAC paths.
- Run dependency and secret scanning on every change touching Kubernetes RBAC.
- Perform targeted manual tests (abuse cases) for Kubernetes RBAC.

### Operations

- Log security-relevant events for Kubernetes RBAC without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Kubernetes RBAC.
- Review access and configuration for Kubernetes RBAC on a regular cadence.

## Network policies

Sub-topics: Default allow, Egress control

### Policy

- Treat Network policies in Network policies as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Network policies (Containers and Kubernetes).
- Require security review for material changes affecting Network policies.

### Design

- Apply least privilege and defense in depth for Network policies.
- Prefer established patterns and libraries over custom crypto or auth for Network policies.
- Fail closed: deny by default when Network policies cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Network policies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Network policies.
- Keep dependencies patched; pin versions for Network policies components.

### Verification

- Add automated tests and SAST/DAST coverage for Network policies paths.
- Run dependency and secret scanning on every change touching Network policies.
- Perform targeted manual tests (abuse cases) for Network policies.

### Operations

- Log security-relevant events for Network policies without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Network policies.
- Review access and configuration for Network policies on a regular cadence.

## Kubernetes secrets

Sub-topics: etcd encryption, External secrets

### Policy

- Treat Kubernetes secrets in Kubernetes secrets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Kubernetes secrets (Containers and Kubernetes).
- Require security review for material changes affecting Kubernetes secrets.

### Design

- Apply least privilege and defense in depth for Kubernetes secrets.
- Prefer established patterns and libraries over custom crypto or auth for Kubernetes secrets.
- Fail closed: deny by default when Kubernetes secrets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Kubernetes secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Kubernetes secrets.
- Keep dependencies patched; pin versions for Kubernetes secrets components.

### Verification

- Add automated tests and SAST/DAST coverage for Kubernetes secrets paths.
- Run dependency and secret scanning on every change touching Kubernetes secrets.
- Perform targeted manual tests (abuse cases) for Kubernetes secrets.

### Operations

- Log security-relevant events for Kubernetes secrets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Kubernetes secrets.
- Review access and configuration for Kubernetes secrets on a regular cadence.

## Container runtime

Sub-topics: Privileged pods, Host mounts

### Policy

- Treat Container runtime in Container runtime as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Container runtime (Containers and Kubernetes).
- Require security review for material changes affecting Container runtime.

### Design

- Apply least privilege and defense in depth for Container runtime.
- Prefer established patterns and libraries over custom crypto or auth for Container runtime.
- Fail closed: deny by default when Container runtime cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Container runtime; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container runtime.
- Keep dependencies patched; pin versions for Container runtime components.

### Verification

- Add automated tests and SAST/DAST coverage for Container runtime paths.
- Run dependency and secret scanning on every change touching Container runtime.
- Perform targeted manual tests (abuse cases) for Container runtime.

### Operations

- Log security-relevant events for Container runtime without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Container runtime.
- Review access and configuration for Container runtime on a regular cadence.

## Admission controllers

Sub-topics: OPA/Gatekeeper, Pod security

### Policy

- Treat Admission controllers in Admission controllers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Admission controllers (Containers and Kubernetes).
- Require security review for material changes affecting Admission controllers.

### Design

- Apply least privilege and defense in depth for Admission controllers.
- Prefer established patterns and libraries over custom crypto or auth for Admission controllers.
- Fail closed: deny by default when Admission controllers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Admission controllers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Admission controllers.
- Keep dependencies patched; pin versions for Admission controllers components.

### Verification

- Add automated tests and SAST/DAST coverage for Admission controllers paths.
- Run dependency and secret scanning on every change touching Admission controllers.
- Perform targeted manual tests (abuse cases) for Admission controllers.

### Operations

- Log security-relevant events for Admission controllers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Admission controllers.
- Review access and configuration for Admission controllers on a regular cadence.

## Helm charts

Sub-topics: Templated secrets, Chart provenance

### Policy

- Treat Helm charts in Helm charts as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Helm charts (Containers and Kubernetes).
- Require security review for material changes affecting Helm charts.

### Design

- Apply least privilege and defense in depth for Helm charts.
- Prefer established patterns and libraries over custom crypto or auth for Helm charts.
- Fail closed: deny by default when Helm charts cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Helm charts; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Helm charts.
- Keep dependencies patched; pin versions for Helm charts components.

### Verification

- Add automated tests and SAST/DAST coverage for Helm charts paths.
- Run dependency and secret scanning on every change touching Helm charts.
- Perform targeted manual tests (abuse cases) for Helm charts.

### Operations

- Log security-relevant events for Helm charts without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Helm charts.
- Review access and configuration for Helm charts on a regular cadence.

## Container registries

Sub-topics: Pull secrets, Retention

### Policy

- Treat Container registries in Container registries as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Container registries (Containers and Kubernetes).
- Require security review for material changes affecting Container registries.

### Design

- Apply least privilege and defense in depth for Container registries.
- Prefer established patterns and libraries over custom crypto or auth for Container registries.
- Fail closed: deny by default when Container registries cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Container registries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container registries.
- Keep dependencies patched; pin versions for Container registries components.

### Verification

- Add automated tests and SAST/DAST coverage for Container registries paths.
- Run dependency and secret scanning on every change touching Container registries.
- Perform targeted manual tests (abuse cases) for Container registries.

### Operations

- Log security-relevant events for Container registries without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Container registries.
- Review access and configuration for Container registries on a regular cadence.

## Sidecars and service mesh

Sub-topics: Token theft, Localhost trust

### Policy

- Treat Sidecars and service mesh in Sidecars and service mesh as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Sidecars and service mesh (Containers and Kubernetes).
- Require security review for material changes affecting Sidecars and service mesh.

### Design

- Apply least privilege and defense in depth for Sidecars and service mesh.
- Prefer established patterns and libraries over custom crypto or auth for Sidecars and service mesh.
- Fail closed: deny by default when Sidecars and service mesh cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Sidecars and service mesh; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Sidecars and service mesh.
- Keep dependencies patched; pin versions for Sidecars and service mesh components.

### Verification

- Add automated tests and SAST/DAST coverage for Sidecars and service mesh paths.
- Run dependency and secret scanning on every change touching Sidecars and service mesh.
- Perform targeted manual tests (abuse cases) for Sidecars and service mesh.

### Operations

- Log security-relevant events for Sidecars and service mesh without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Sidecars and service mesh.
- Review access and configuration for Sidecars and service mesh on a regular cadence.

## Windows containers

Sub-topics: Isolation levels

### Policy

- Treat Windows containers in Windows containers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Windows containers (Containers and Kubernetes).
- Require security review for material changes affecting Windows containers.

### Design

- Apply least privilege and defense in depth for Windows containers.
- Prefer established patterns and libraries over custom crypto or auth for Windows containers.
- Fail closed: deny by default when Windows containers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Windows containers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Windows containers.
- Keep dependencies patched; pin versions for Windows containers components.

### Verification

- Add automated tests and SAST/DAST coverage for Windows containers paths.
- Run dependency and secret scanning on every change touching Windows containers.
- Perform targeted manual tests (abuse cases) for Windows containers.

### Operations

- Log security-relevant events for Windows containers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Windows containers.
- Review access and configuration for Windows containers on a regular cadence.

## Docker Compose dev security

Sub-topics: Published ports, Volume mounts

### Policy

- Treat Docker Compose dev security in Docker Compose dev security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Docker Compose dev security (Containers and Kubernetes).
- Require security review for material changes affecting Docker Compose dev security.

### Design

- Apply least privilege and defense in depth for Docker Compose dev security.
- Prefer established patterns and libraries over custom crypto or auth for Docker Compose dev security.
- Fail closed: deny by default when Docker Compose dev security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Docker Compose dev security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Docker Compose dev security.
- Keep dependencies patched; pin versions for Docker Compose dev security components.

### Verification

- Add automated tests and SAST/DAST coverage for Docker Compose dev security paths.
- Run dependency and secret scanning on every change touching Docker Compose dev security.
- Perform targeted manual tests (abuse cases) for Docker Compose dev security.

### Operations

- Log security-relevant events for Docker Compose dev security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Docker Compose dev security.
- Review access and configuration for Docker Compose dev security on a regular cadence.

## Container escape vectors

Sub-topics: Kernel CVEs, Capabilities

### Policy

- Treat Container escape vectors in Container escape vectors as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Container escape vectors (Containers and Kubernetes).
- Require security review for material changes affecting Container escape vectors.

### Design

- Apply least privilege and defense in depth for Container escape vectors.
- Prefer established patterns and libraries over custom crypto or auth for Container escape vectors.
- Fail closed: deny by default when Container escape vectors cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Container escape vectors; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container escape vectors.
- Keep dependencies patched; pin versions for Container escape vectors components.

### Verification

- Add automated tests and SAST/DAST coverage for Container escape vectors paths.
- Run dependency and secret scanning on every change touching Container escape vectors.
- Perform targeted manual tests (abuse cases) for Container escape vectors.

### Operations

- Log security-relevant events for Container escape vectors without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Container escape vectors.
- Review access and configuration for Container escape vectors on a regular cadence.

