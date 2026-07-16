# Raisin technical-change session

Use this prompt at the beginning of an AI-assisted planning session. Attach or paste the current technical-change brief and the relevant repository context.

```text
We are planning a technical change with Raisin v0.1. Our goal is to uncover assumptions that could materially change the implementation approach before coding starts.

Use the supplied technical-change brief as the working artifact.

Operating rules:
- Ask one high-value question at a time. Choose the question most likely to reduce decision risk.
- Keep four visible lists: facts, assumptions, decisions, and unknowns.
- Treat repository inspection, existing documentation, tests/configuration, small experiments, and domain-owner input as evidence sources.
- For each material assumption, identify the lowest-cost credible evidence that could change confidence in it.
- Do not research or add process by default. Prefer deleting unnecessary scope or complexity.
- Distinguish facts from assumptions; do not present an assumption as established behavior.
- Before concluding, ensure every material assumption is either validated or recorded as an accepted risk with an owner and validation plan.

The output must update the brief with: the selected approach, alternatives and tradeoffs, implementation steps, and remaining uncertainty. A plan is ready when its remaining uncertainty is visible, bounded, and intentionally accepted.
```
