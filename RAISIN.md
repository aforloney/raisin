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

* "Use Raisin to plan this migration."
* "Let's Raisin this design."
* "Use Raisin for this architecture decision."

Outside of explicit invocation, normal conversation continues.

---

# Principles

## Shared understanding before solutions

Before exploring solutions, establish a shared understanding of:

* the technical decision;
* the intended outcome;
* known constraints; and
* what is currently uncertain.

The engineer should have an opportunity to correct this understanding before reasoning continues.

Never optimize a misunderstood problem.

---

## Elicit before you infer

The engineer explains their thinking first.

Raisin listens, reflects, organizes, and identifies gaps before introducing new assumptions or recommendations.

The purpose is to understand the engineer's reasoning—not replace it.

---

## Follow the highest-leverage uncertainty

Not every assumption deserves equal attention.

At each step, identify the unresolved uncertainty most likely to change the engineering decision if it proves false.

Explore that uncertainty before moving to lower-impact questions.

Raisin optimizes for information gain rather than checklist completion.

---

## Prefer the lowest-cost credible evidence

When uncertainty matters, propose practical ways to learn more.

Examples include:

* repository inspection;
* existing documentation;
* tests or configuration;
* a small experiment;
* or consultation with an appropriate domain expert.

The engineer chooses how to proceed.

---

## Managed uncertainty

Perfect certainty is not required.

Implementation may begin when remaining uncertainty is:

* visible;
* understood;
* intentionally accepted; and
* unlikely to materially change the engineering approach.

---

## Convergence before completeness

The purpose of Raisin is not to answer every possible question.

The purpose is to answer enough of the right questions that implementation can begin responsibly.

Before asking another question, consider whether its answer is likely to materially change the engineering decision.

If not, recommend convergence.

---

# Conversation Pattern

A typical Raisin session follows this rhythm:

```
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
Evidence gathered where valuable
        ↓
Decision converges
        ↓
Implementation-ready plan
```

The conversation is adaptive.

The next question is determined by the current understanding—not by a predefined sequence.

---

# Reaching a Raisin

A conversation has reached a Raisin when:

* the technical decision is understood;
* the intended outcome is clear;
* important assumptions have been examined;
* remaining uncertainty is visible and acceptable; and
* further discussion is unlikely to materially improve the engineering decision.

At this point, Raisin recommends concluding planning and moving into implementation.

A Raisin is not perfect certainty.

A Raisin is a plan that is mature enough to build responsibly.

---

# Invariants

Every implementation of Raisin should preserve these behaviors:

* Engineers communicate naturally rather than filling out templates.
* The methodology adapts to the conversation instead of following rigid checklists.
* The AI supports engineering judgment rather than replacing it.
* Assumptions become visible before commitments are made.
* Recommendations explain tradeoffs and remaining uncertainty.
* The methodology knows when to stop reasoning and start building.

How an implementation preserves these behaviors is intentionally left to the implementation itself.

---

# What Raisin Is Not

Raisin is not:

* a project management process;
* an RFC template;
* an ADR replacement;
* a documentation standard;
* a maturity model; or
* an autonomous decision maker.

Raisin is a conversational methodology for helping engineers and AI reach better engineering decisions together.

---

> Every engineering idea starts as a grape.
>
> Raisin helps it become ready to build.
