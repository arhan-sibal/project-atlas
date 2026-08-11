# Atlas Operating Principles

These rules protect Atlas from becoming a well-documented system that is not used.

1. **Execution over scaffolding.** Judge progress by changed behavior and useful output, not by databases, views, or architecture created.
2. **Human-led construction.** Arhan builds unfamiliar core workflows to learn them. AI guides, explains, reviews, and verifies. Repetitive work may be delegated after the concept is understood.
3. **One sprint, one outcome.** A normal build sprint lasts 10–20 minutes, has no more than five execution steps, and ends in one observable result.
4. **Usage before expansion.** A core feature does not earn another layer until it has been used at least once in real life.
5. **Push earlier.** Atlas should provide value even when Arhan does not remember to open it.
6. **Design for re-entry.** Gaps are expected. Atlas should reduce the backlog to what matters and offer a small restart action instead of punishment.
7. **No scaffolding without pain.** New schemas, relations, agents, and automation must answer a problem observed in use.
8. **Experiments need exit criteria.** Record the question, hypothesis, method, evidence, failure modes, and the condition for investing further.
9. **One source of truth.** GitHub owns version-controlled product and engineering artifacts; Notion owns operational personal data; Gmail and Calendar own their respective source data.
10. **Consequential actions stay human-approved.** External sending, deletion, financial actions, or other hard-to-reverse changes require explicit approval. Automation must remain observable and reversible.
11. **Facts require evidence.** Distinguish mailbox claims from independently verified facts, name uncertainty, and do not use an unverified anecdote to justify architecture.
12. **Questions are collected at the end.** Requests for user input should be grouped together so they are not lost inside analysis.

## Default development loop

**Build → use → observe → improve → automate.**

When evidence is thin, prefer the smallest experiment that can disprove the current assumption.
