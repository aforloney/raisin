# Raisin 🍇

Raisin helps engineers think through a technical change until it is solid enough to build.

It is a conversational methodology for an engineer and an AI assistant. The engineer brings the context and corrects the AI's understanding. The AI asks useful questions, makes its observations visible, and decides when the thinking is mature enough to turn into an engineering plan.

Raisin is for changes whose solution is not yet obvious, including architecture changes, migrations, refactors, dependency changes, and system modifications.

## How it works

The conversation starts with a shared understanding of the change, its outcome, its constraints, and what is still unclear. The AI then helps uncover what must be true for the approach to work, investigates the uncertainty most likely to change the plan, and reassesses after every meaningful answer.

When the AI determines that no remaining question is likely to materially change the engineering plan, it recommends a **Raisin**: the idea is ready to move from planning into implementation. It explains why, presents the engineering plan, and asks the engineer to confirm that transition.

Raisin does not require certainty. It requires that uncertainty which could still matter is visible, understood, and intentionally accepted.

## Use Raisin

Ask an AI assistant to help think through a technical change with Raisin. The agent guidance in this repository tells supported workflows how to run the conversation and assess maturity:

- [Raisin conversation guidance](methodology/raisin.md)
- [Maturity guidance](methodology/maturity.md)
- [Pilot guidance](methodology/pilot.md)

The primary pilot measure is whether implementation requires a significant re-plan after coding begins. Raisin is useful if it moves those discoveries into planning.

## Scope

v0.1 defines agent behavior and lightweight session records. It does not define a compliance model, autonomous execution system, universal reasoning standard, or telemetry infrastructure.
