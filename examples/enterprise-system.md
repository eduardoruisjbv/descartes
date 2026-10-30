# Enterprise system

## Initial intention

An organization plans an ERP covering identity, finance, inventory, integrations, and controlled deployment.

## Architectural decisions

Map business processes, regulatory constraints, source systems, data ownership, and availability before selecting architecture. Start with modular boundaries and integration contracts; justify service decomposition with operational needs.

## Phases

1. Domain and threat discovery. 2. Identity, data, and audit foundations. 3. Core finance/inventory slices. 4. Integrations and reconciliation. 5. Staged rollout and operational readiness.

## Agent allocation

Specialists own identity/security, domain modules, integrations, and operations; orchestrator controls shared schemas and integration gates.

## Validation criteria

Authorization matrix, accounting invariants, reconciliation, audit retention, recovery exercises, threat review.

## Expected outputs

Context map, architecture decisions, migration and rollout plan, phase prompts, evidence checklist.

*Illustrative planning example; no implementation is claimed.*
