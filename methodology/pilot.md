# Pilot guidance

The first pilot tests whether Raisin moves expensive discoveries from implementation into planning.

## During planning

For each Raisin session, the agent creates a concise record in `runs/`. The record is for learning, not for the engineer to complete.

Capture:

- the technical change and intended outcome;
- the final maturity assessment and why it was reached;
- assumptions explored and evidence considered;
- important decisions and remaining accepted uncertainty; and
- the engineering plan presented at the Raisin.

## After implementation begins

Add the outcome to the same record. A significant re-plan is any of the following:

- changing the chosen approach;
- discovering a dependency or constraint that changes the design;
- revising scope because an assumption was incorrect; or
- restarting work because an overlooked risk invalidated the plan.

For each significant re-plan, record its cause and whether the relevant uncertainty appeared during the Raisin conversation.

## Learn before building infrastructure

Use several real sessions to learn whether the maturity assessment and recorded reasoning explain later re-planning. Do not add telemetry infrastructure or treat the score as authoritative until pilot evidence shows which signals are useful.
