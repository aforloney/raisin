# Raisin 🍇

Turn grape ideas into Raisins.

Raisin is a conversational methodology that helps engineers and AI reduce uncertainty before implementation through shared understanding, deliberate questioning, and evidence-driven reasoning.

The goal isn't more process.

The goal is helping engineering ideas reach a Raisin.

## Why?

Most implementation problems aren't caused by writing bad code.

They're caused by discovering important assumptions after coding has already started.

Raisin moves those discoveries earlier.

## What makes Raisin different?

Raisin isn't another planning template.

Instead, it changes the conversation.

Rather than jumping directly to solutions, Raisin helps engineers and AI:

- establish shared understanding
- uncover hidden assumptions
- validate the highest-risk uncertainty
- know when enough is known to start building

## Philosophy

Raisin is built around one belief:

> Engineering improves when uncertainty is reduced before implementation—not when documentation increases.

## When should I use Raisin?

Use Raisin when:

- architectural decisions
- migrations
- refactors
- technical planning
- system design

Skip Raisin when:

- you need syntax
- the solution is already obvious
- the decision has already been made

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
