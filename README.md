# Raisin 🍇

Raisin is a lightweight planning loop for engineers designing a technical change whose solution is not yet obvious.

It helps an engineer using Codex, Cursor, or Claude expose assumptions that could change the approach before implementation starts.

Raisin v0.1 is deliberately small:

1. Frame the decision and constraints.
2. Make assumptions visible.
3. Validate the assumptions that could materially change the approach.
4. Record the decision, remaining risks, and an executable plan.

A plan is ready when remaining uncertainty is visible, bounded, and intentionally accepted—not when all uncertainty has been eliminated.

## Run a pilot

1. Copy [the technical-change brief](templates/technical-change-brief.md) for one upcoming architecture change, migration, refactor, or system modification.
2. Start an AI planning session with [the Raisin session prompt](templates/raisin-session-prompt.md), providing the brief and relevant repository context.
3. Follow [the pilot guide](docs/first-pilot.md) to record the outcome after implementation begins.

The primary pilot measure is whether the change requires a significant re-plan after coding starts. Raisin is useful if it moves those discoveries into planning.

## Scope

v0.1 is an interaction pattern and two small templates. It does not define a reasoning standard, compliance model, integration protocol, maturity score, or generalized reasoning graph.
