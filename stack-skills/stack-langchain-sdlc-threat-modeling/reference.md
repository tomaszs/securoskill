# LangChain / LangGraph: SDLC, threat modeling, and secure design

Stack-specific implementation for **LangChain / LangGraph** (AI). Normative rules: domain skill `security-sdlc-threat-modeling` / `reference.md`.

## STRIDE and threat models

**Sub-topics:** Diagrams, Trust boundaries, Threat modeling and trust boundaries (STRIDE and threat models), Abuse cases and adversarial testing (STRIDE and threat models), Logging, audit, and detection (STRIDE and threat models)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Security requirements

**Sub-topics:** Non-functionals, Acceptance, Threat modeling and trust boundaries (Security requirements), Abuse cases and adversarial testing (Security requirements), Logging, audit, and detection (Security requirements)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Design review

**Sub-topics:** Checklists, Sign-off, Threat modeling and trust boundaries (Design review), Abuse cases and adversarial testing (Design review), Logging, audit, and detection (Design review)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Security-focused code review

**Sub-topics:** Hotspots, Threat modeling and trust boundaries (Security-focused code review), Abuse cases and adversarial testing (Security-focused code review), Logging, audit, and detection (Security-focused code review), Access control and least privilege (Security-focused code review)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Security test planning

**Sub-topics:** Coverage maps, Threat modeling and trust boundaries (Security test planning), Abuse cases and adversarial testing (Security test planning), Logging, audit, and detection (Security test planning), Access control and least privilege (Security test planning)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Secure defaults culture

**Sub-topics:** Templates, Golden paths, Threat modeling and trust boundaries (Secure defaults culture), Abuse cases and adversarial testing (Secure defaults culture), Logging, audit, and detection (Secure defaults culture)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Developer education

**Sub-topics:** Labs, Phishing sims, Threat modeling and trust boundaries (Developer education), Abuse cases and adversarial testing (Developer education), Logging, audit, and detection (Developer education)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Vendor security assessment

**Sub-topics:** Questionnaires, Threat modeling and trust boundaries (Vendor security assessment), Abuse cases and adversarial testing (Vendor security assessment), Logging, audit, and detection (Vendor security assessment), Access control and least privilege (Vendor security assessment)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Architecture decision records

**Sub-topics:** Security ADRs, Threat modeling and trust boundaries (Architecture decision records), Abuse cases and adversarial testing (Architecture decision records), Logging, audit, and detection (Architecture decision records), Access control and least privilege (Architecture decision records)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Attack surface management

**Sub-topics:** Inventory, Exposure, Threat modeling and trust boundaries (Attack surface management), Abuse cases and adversarial testing (Attack surface management), Logging, audit, and detection (Attack surface management)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Purple team exercises

**Sub-topics:** Scenarios, Threat modeling and trust boundaries (Purple team exercises), Abuse cases and adversarial testing (Purple team exercises), Logging, audit, and detection (Purple team exercises), Access control and least privilege (Purple team exercises)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## SDL metrics

**Sub-topics:** Defect density, Lead time, Threat modeling and trust boundaries (SDL metrics), Abuse cases and adversarial testing (SDL metrics), Logging, audit, and detection (SDL metrics)

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

