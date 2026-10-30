# Web application

## Initial intention

A small team wants a multi-tenant SaaS for appointment scheduling, staff accounts, billing, and audit history.

## Architectural decisions

Inspect current repository and deployment first. Keep API, identity, scheduling, billing, and audit boundaries explicit. Select a familiar web stack compatible with existing assets; use a relational database if transactional scheduling and tenant constraints dominate, documenting alternatives.

## Phases

1. Audit requirements and data boundaries. 2. Define tenancy, identity, and API contracts. 3. Implement scheduling and audit foundations. 4. Add billing integration. 5. Deploy behind staged rollout.

## Agent allocation

Orchestrator defines API and data contracts; UI, scheduling, and integration specialists own disjoint modules after contracts stabilize.

## Validation criteria

Unit and integration tests for tenant isolation, booking conflicts, authorization, and billing webhooks; migration and deployment review.

## Expected outputs

Architecture note, decision log, dependency graph, phase prompts, acceptance checklist.

*Illustrative planning example; no implementation is claimed.*
