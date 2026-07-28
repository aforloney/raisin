# Raisin Runtime

Implement the Raisin methodology defined in `RAISIN.md`.

This runtime should:

- Maintain conversational continuity across the planning session.
- Preserve sufficient internal state to revisit earlier assumptions and decisions.
- Surface internal reasoning only when it improves understanding or supports a decision.
- Prefer repository evidence and local context over speculation when available.
- Adapt the depth of questioning to the complexity of the engineering decision.
- Recommend concluding Raisin once additional discussion is unlikely to materially improve the engineering decision.
