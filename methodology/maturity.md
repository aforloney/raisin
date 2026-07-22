# Maturity guidance

Maturity is the agent's ongoing judgment of whether the current understanding is sufficient to move from planning into implementation. It is not a claim that all uncertainty has been eliminated.

## Working state

Throughout a Raisin conversation, retain:

- the technical decision, intended outcome, and constraints;
- facts and the evidence supporting them;
- assumptions and unknowns;
- decisions and why they were made;
- remaining uncertainty, including anything intentionally accepted; and
- the current maturity assessment and the reasons for it.

Use this state to guide the next question. Do not require the engineer to maintain it or present it as a form. Surface only the parts that help the engineer understand, correct, or decide.

## Assess after each meaningful answer

Update the internal maturity score and its explanation after the conversation changes the understanding of the idea.

Ask yourself:

1. Would answering another question likely change the engineering plan?
2. Does an unresolved assumption still have enough impact to change the approach, scope, or major constraint?
3. Is the remaining uncertainty about the decision itself, or only about details that can safely be handled during implementation?

The score is a feedback mechanism for the agent and for later pilot learning. It is not sufficient on its own: its explanation must be grounded in the working state.

## Recommend readiness

Recommend a Raisin when:

- the intended outcome, main approach, and constraints are understood;
- decision-changing assumptions have been investigated, or their risk is visible and intentionally accepted;
- remaining uncertainty is bounded and understood; and
- another question is unlikely to materially change the engineering plan.

If the answer to the final point is no because the agent lacks context, do not treat the absence of questions as readiness. State what is missing and continue with the question most likely to resolve it.
