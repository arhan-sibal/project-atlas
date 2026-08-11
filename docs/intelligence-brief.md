# Atlas Intelligence Brief

Status: v0.1 pilot completed; v0.2 specification ready for testing
Last updated: August 10, 2026

## Purpose

Given the information entering Arhan's environment, provide the smallest useful reading that explains what materially changed, what needs his attention, and which ideas are worth retaining.

The brief is an informational product. It must not automatically convert news or email into tasks.

## v0.2 output structure

1. **Needs You** — deadlines, anomalies, personal operational items, and decisions requiring input. This comes first because it can affect money, opportunities, or immediate obligations.
2. **Knowledge Executive Summary** — a ranked 100–200 word synthesis of the two or three learning developments that matter most. It should not be a prose table of contents.
3. **Topic sections** — each opens with a two-to-three-line navigation summary, followed by detailed cross-source synthesis.
4. **Worth Reading / Durable Ideas** — a selective list of originals worth reading and concepts worth remembering.

## Editorial requirements

- Synthesize overlapping coverage into underlying stories instead of summarizing newsletters one by one.
- Separate what happened, why it matters, and what to watch next.
- Explain source reliability: distinguish direct reporting, informed analysis, newsletter interpretation, and claims that need verification.
- Personal operational items and learning content are separate tracks; do not let either crowd out the other.
- Length may exceed ten minutes when useful, provided the executive and section summaries support fast skimming.
- Avoid an Atlas implication on every item. Include meta commentary only when it changes a product decision.
- Clearly label mailbox-only claims that have not been independently checked against primary or web sources.

## Current scope

- One connected university Gmail mailbox
- Recent-email retrieval performed manually through a tool-enabled assistant
- No Gmail writes or mailbox changes
- No scheduled run
- No multi-mailbox aggregation
- No raw-email storage in Notion
- No source-registry-driven routing yet

## Pilot result

The v0.1 pilot showed real value in cross-source synthesis, source-reliability commentary, and durable takeaways. It failed the broader user need by omitting important personal items from the same mailbox. It also demonstrated that the source registry had been created before it was required by the production workflow.

The user accepted a longer brief if the summary layers make it easy to navigate. The next run should test the v0.2 structure directly rather than add automation.

## Evaluation rubric for the next three reads

After each run, record:

- Were any important personal items missed?
- Were the top two or three learning developments correctly ranked?
- Which section was read in detail and which was skimmed?
- Which stories should have been merged, removed, or expanded?
- Were confidence and source-quality notes accurate?
- Was any factual claim presented more strongly than the evidence allowed?
- Did the brief make a next-day idea memorable?

## Exit criteria before automation

Do not invest in scheduling, multi-mailbox OAuth, memory, or a custom pipeline until three real v0.2 briefs have been read and the evidence shows that the structure is repeatedly useful.
