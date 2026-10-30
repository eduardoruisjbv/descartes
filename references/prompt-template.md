# [PROJECT] — [PHASE]: [OBJECTIVE]

## Mission
[Precise outcome and why it matters.]

## Verified context and source of truth
- Target repository/path: [verify, do not invent]
- Reference version: [if any]
- Existing completed capabilities: [verified vs user-reported]
- Invariants: [what must not change]

## Scope and non-goals
**Implement:** [bounded capabilities]
**Do not implement:** [explicit exclusions]

## Technology decisions
| Subsystem | Language/technology | Why | Constraints |
|---|---|---|---|

## Architecture and contracts
[Integration boundaries, interfaces, state, persistence, compatibility, security.]

## Multi-agent execution
**Primary orchestrator:** audit, shared contracts, file ownership, integration, validation.
**Specialist A:** [task, read/write scope, deliverable]
**Specialist B:** [task, read/write scope, deliverable]
**Specialist C (optional):** [task, read/write scope, deliverable]

Rules: use minimum useful agents; inspect first; parallel read-only audits; stabilize contracts before parallel writes; disjoint ownership; serialize shared files; integrate centrally; fall back to sequential if needed; no invented agent capabilities.

## Phased execution
1. Audit and baseline
2. Contracts and dependencies
3. Isolated implementation
4. Integration
5. Regression and performance checks
6. Packaging/distribution checks if in scope

## Validation and acceptance criteria
[Explicit tests, builds, user-visible checks, measurable thresholds if supported. Distinguish executed from planned tests.]

## Stop conditions
[Missing reference, incompatible contracts, unapproved destructive changes, unverifiable requirements, security blockers.]

## Final report
- Changes and files
- Work per agent
- Tests actually executed and results
- Builds/packages actually generated and verified
- Known limitations and risks
- Recommended next smallest phase

**Priority:** correctness > regression safety > maintainability > performance > cost/token efficiency, adjusted to the user's explicit goals.
