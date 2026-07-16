# First Raisin pilot

Use Raisin for one upcoming technical change where the implementation approach is not obvious: an architecture change, system modification, migration, refactor, or new technical capability.

## Before coding

1. Copy the [technical-change brief](../templates/technical-change-brief.md) into the change's planning location.
2. Run an AI planning session using the [Raisin session prompt](../templates/raisin-session-prompt.md).
3. Name the decision owner and complete the readiness check.
4. Record these baseline observations:
   - Number of material assumptions identified.
   - Number validated before coding.
   - Number accepted as risks.
   - Time spent preparing the plan.
   - Engineer confidence before coding: low, medium, or high.

## During implementation

Record a significant re-plan if coding requires any of the following:

- changing the chosen approach;
- responding to a missing dependency or constraint that alters the design;
- revising scope because an assumption was incorrect; or
- restarting work because an overlooked risk invalidated the plan.

For each significant re-plan, record the missed assumption or constraint and whether it was present in the brief.

## Pilot record

| Field | Result |
| --- | --- |
| Change | |
| Decision owner | |
| Coding start date | |
| Material assumptions identified | |
| Validated before coding | |
| Accepted risks | |
| Significant re-plans after coding began | |
| Re-plan cause(s) | |
| Was the cause visible in the brief? | |
| Plan-preparation time | |
| Engineer confidence before coding | |
| Would Raisin be used again? Why? | |

## Interpretation

Raisin is valuable when it moves a decision-changing discovery from implementation into planning. The primary result is the count and cause of significant re-plans after coding begins; the other fields explain that result rather than serving as optimization targets.
