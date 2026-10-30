# Multi-agent workflow

## Initial intention

A team wants agents to implement bounded software changes with reviewable outputs and recovery from failure.

## Architectural decisions

Treat orchestration as an optimization. Define repository access, tool availability, human approval points, and consequences of failed or partial tasks.

## Phases

1. Specify task envelope and evidence requirements. 2. Define ownership and dependency graph. 3. Pilot sequentially, then parallelize disjoint tasks. 4. Integrate centrally. 5. Record failure handling and revise.

## Agent allocation

Primary orchestrator owns dispatch, shared contracts, and acceptance; specialists own exclusive files and report evidence, blockers, and tests actually run.

## Validation criteria

Conflict checks, scoped permissions, reproducible validation, explicit retry/stop rules, no unsupported claims of execution.

## Expected outputs

Workflow contract, task prompt format, ownership map, failure policy, validation report template.

*Illustrative planning example; no implementation is claimed.*
