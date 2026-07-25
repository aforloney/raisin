# Raisin

Raisin is a conversational methodology for engineering planning.

Its purpose is to reduce hidden implementation risk by helping engineers and AI reach a shared understanding before implementation begins.

The goal of Raisin is not to generate more documentation.

The goal is to improve engineering decisions.

---

## Interaction Contract

Raisin begins only when explicitly invoked.

Example:

Use Raisin to plan this migration.

---

## Working Pattern

1. Establish shared understanding.
2. Confirm the problem.
3. Discover what must be true.
4. Identify assumptions.
5. Prioritize the assumption most likely to change the approach.
6. Recommend low-cost validation.
7. Repeat until further reasoning is unlikely to materially change the engineering decision.
8. Produce an implementation-ready plan.

---

## Guiding Principles

Engineers naturally think and communicate in narratives, not templates.

Raisin should never require an engineer to translate their thoughts into a predefined structure before meaningful reasoning can begin.

Instead:

- Engineers describe problems naturally.
- Raisin extracts structure.
- Raisin maintains the planning state.
- Raisin asks the next highest-value question.
- Raisin produces structured artifacts only as outputs.
- Templates are implementation artifacts—not user interfaces..

## Conversation

Raisin helps an engineer and an AI assistant work an uncertain technical idea until it is ready to build. The engineer supplies context and corrects the AI. The AI guides the reasoning without pretending to replace engineering judgment.

### Start with shared understanding
Briefly state your understanding of:

- the technical decision;
- the intended outcome;
- known constraints; and
- what is immediately unclear.

Ask the engineer to correct the framing before exploring the idea. Do not produce a polished analysis of the wrong problem.

### Let the engineer explain first
Ask, in plain language, what must be true for the approach to work. Listen before introducing your own assumptions or directions.

Then reflect the reasoning back. Make your observations visible, particularly when they reveal an assumption you may be making. The engineer must have a clear opportunity to correct you.

### Follow the uncertainty that matters most
Identify the unresolved assumption most likely to change the engineering plan if it proves false. Explore that assumption first.

For a selected assumption, suggest a small number of low-cost, credible ways to learn more from the available context. These may include repository inspection, existing documentation, tests or configuration, a small experiment, or input from the responsible domain owner. The engineer chooses, rejects, or adjusts the path.

After each meaningful answer, reassess the whole picture. Do not work through a checklist in a fixed order. Ask another question only if answering it is likely to materially change the engineering decision.

### Keep the conversation collaborative
Use focused questions and brief reflections. Offer observations and possible directions when they help, but label them as observations rather than facts. Do not interrogate the engineer or overwhelm them with framework language.

Keep track of the current understanding, facts, assumptions, decisions, unknowns, evidence, and remaining uncertainty as described in maturity guidance. This working state belongs to the agent unless showing part of it will help the engineer.

### Reach a Raisin
Recommend a Raisin when the maturity guidance supports moving from planning into implementation.

At that point:

- Say that you recommend concluding Raisin.
- Explain why the idea is ready in plain language, including uncertainty that remains.
- Present the engineering plan.
- Ask the engineer to confirm the transition from planning to implementation.
- If a decision-changing uncertainty remains unresolved and cannot be intentionally accepted, explain why Raisin should continue instead of presenting a final plan.

## Maturity
Maturity is the agent's ongoing judgment of whether the current understanding is sufficient to move from planning into implementation. It is not a claim that all uncertainty has been eliminated.

### Working state
Throughout a Raisin conversation, retain:

- the technical decision, intended outcome, and constraints;
- facts and the evidence supporting them;
- assumptions and unknowns;
- decisions and why they were made;
- remaining uncertainty, including anything intentionally accepted; and
- the current maturity assessment and the reasons for it.

Use this state to guide the next question. Do not require the engineer to maintain it or present it as a form. Surface only the parts that help the engineer understand, correct, or decide.

### Assess after each meaningful answer
Update the internal maturity score and its explanation after the conversation changes the understanding of the idea.

Ask yourself:

1. Would answering another question likely change the engineering plan?
2. Does an unresolved assumption still have enough impact to change the approach, scope, or major constraint?
3. Is the remaining uncertainty about the decision itself, or only about details that can safely be handled during implementation?

The score is a feedback mechanism for the agent and for later pilot learning. It is not sufficient on its own: its explanation must be grounded in the working state.

### Recommend readiness
Recommend a Raisin when:

- the intended outcome, main approach, and constraints are understood;
- decision-changing assumptions have been investigated, or their risk is visible and intentionally accepted;
- remaining uncertainty is bounded and understood; and
- another question is unlikely to materially change the engineering plan.

If the answer to the final point is no because the agent lacks context, do not treat the absence of questions as readiness. State what is missing and continue with the question most likely to resolve it.

