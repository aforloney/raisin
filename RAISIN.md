# Raisin

> A conversational methodology for engineering decisions.

## Purpose

Every engineering idea starts as a grape.

It has potential, but it also contains uncertainty.

Raisin helps engineers and AI work together to reduce that uncertainty until the idea is concentrated enough to build with confidence.

Raisin is not a planning template.

It is a way of reasoning together before implementation begins.

The goal is not to eliminate uncertainty.

The goal is to understand it well enough to make a responsible engineering decision.

---

# Interaction Contract

Raisin is an explicit mode of collaboration.

It begins only when the engineer invokes it.

Examples:

- "Use Raisin to plan this migration."
- "Let's Raisin this design."
- "Use Raisin for this architecture decision."

Outside of explicit invocation, normal conversation continues.

---

# Principles

## Shared understanding before solutions

Before exploring solutions, establish a shared understanding of:

- the technical decision;
- the intended outcome;
- known constraints; and
- what is currently uncertain.

Allow the engineer to correct this understanding before reasoning continues.

Never optimize a misunderstood problem.

---

## Elicit before you infer

The engineer explains their reasoning first.

Raisin listens, reflects, organizes, and identifies gaps before introducing new assumptions or recommendations.

The purpose is to understand the engineer's reasoning—not replace it.

---

## Follow the highest-leverage uncertainty

Not every uncertainty deserves equal attention.

At each step, identify the unresolved uncertainty most likely to change the engineering decision if it proves false.

Explore that uncertainty before moving to lower-impact questions.

Raisin optimizes for information gain rather than checklist completion.

---

## Ask intentional questions

Every question should have a purpose.

Ask another question only when its answer is likely to materially change the engineering decision.

Prefer fewer, higher-value questions over exhaustive exploration.

---

## Build confidence deliberately

Conversation creates understanding, not proof.

When an assumption materially influences sequencing, architecture, or success criteria, prefer increasing confidence through the smallest credible artifact available.

Examples include:

- repository inspection;
- existing documentation;
- configuration;
- tests;
- dashboards or logs;
- a small experiment; or
- consultation with the appropriate domain expert.

If evidence cannot be gathered during the conversation, carry the assumption forward explicitly as an accepted hypothesis rather than an established fact.

The engineer chooses how to proceed.

---

## Managed uncertainty

Perfect certainty is not required.

Implementation may begin when remaining uncertainty is:

- visible;
- understood;
- intentionally accepted; and
- unlikely to materially change the engineering approach.

---

## Convergence before completeness

The purpose of Raisin is not to answer every possible question.

The purpose is to answer enough of the right questions that implementation can begin responsibly.

If another question is unlikely to materially change the engineering decision, recommend convergence.

---

# Conversation Pattern

A typical Raisin session follows this rhythm:

Engineer invokes Raisin

↓

Shared understanding

↓

Engineer confirms or corrects

↓

Engineer explains reasoning

↓

Material assumptions emerge

↓

Highest-leverage uncertainty explored

↓

Confidence increased through credible evidence where valuable

↓

Engineer challenges the recommendation

↓

Implementation-ready plan

The conversation is adaptive.

The next question is determined by the current understanding—not by a predefined sequence.

---

# Reaching a Raisin

A conversation has reached a Raisin when:

- the technical decision is understood;
- the intended outcome is clear;
- decision-changing assumptions have been investigated or intentionally accepted;
- remaining uncertainty is visible and understood; and
- further reasoning is unlikely to materially change the engineering decision.

Before recommending implementation, ask one final question intended to challenge the recommendation.

For example:

> What would make this plan wrong?

If the answer reveals a decision-changing uncertainty, continue reasoning.

Otherwise recommend concluding Raisin.

A Raisin is not perfect certainty.

A Raisin is a plan that is mature enough to build responsibly.

---

# Invariants

Every implementation of Raisin should preserve these observable behaviors:

- Engineers communicate naturally instead of filling out templates.
- The methodology adapts to the conversation rather than following rigid checklists.
- The AI helps engineers think without replacing engineering judgment.
- Decision-changing assumptions become visible before commitments are made.
- Recommendations distinguish between evidence, hypotheses, and accepted uncertainty.
- The conversation concludes when additional reasoning is unlikely to materially improve the engineering decision.

How these behaviors are implemented is intentionally left to each runtime.

---

# What Raisin Is Not

Raisin is not:

- a project management process;
- an RFC template;
- an ADR replacement;
- a documentation standard;
- a maturity model; or
- an autonomous decision maker.

Raisin is a conversational methodology for helping engineers and AI reach better engineering decisions together.

---

> Every engineering idea starts as a grape.
>
> Raisin helps it become ready to build.

---

# Implementation

Raisin defines the interaction contract and observable behaviors of the methodology.

Individual runtimes are responsible for preserving these behaviors while adapting to the capabilities of their environment.

Different implementations may vary internally while remaining faithful to the Raisin methodology.
