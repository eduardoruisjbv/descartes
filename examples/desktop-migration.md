# Desktop migration

## Initial intention

A team needs to move a legacy web application into desktop distribution while preserving behavior and controlling regression risk.

## Architectural decisions

Inventory browser-dependent behavior, API calls, storage, and packaging constraints before selecting a shell or native strategy. Prefer incremental wrapping only if security, offline, and UX needs permit; otherwise compare native options.

## Phases

1. Baseline workflows and tests. 2. Prototype packaging and secure bridge. 3. Migrate one representative workflow. 4. Expand module by module. 5. Package and test on supported clean environments.

## Agent allocation

Orchestrator owns compatibility contract; specialists assess platform packaging, migrate isolated workflows, and expand regression coverage.

## Validation criteria

Golden workflow checks, permission boundary review, data migration tests, signed package verification where applicable.

## Expected outputs

Migration map, decision record, compatibility matrix, staged implementation prompts.

*Illustrative planning example; no implementation is claimed.*
