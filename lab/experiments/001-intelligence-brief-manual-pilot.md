# Experiment 001: Atlas Intelligence Brief manual pilot

Date: August 10, 2026
Status: Pilot completed; follow-up evaluation pending

## Question

Can a manual, tool-enabled agent turn recent email into a useful intelligence brief before Atlas invests in retrieval code, automation, memory, or multi-mailbox access?

## Hypothesis

A mailbox-only pilot will reveal the right editorial structure, ranking criteria, and failure modes faster than building infrastructure first.

## Method

- Used one connected university Gmail mailbox.
- Read substantive recent email bodies rather than relying only on subject lines.
- Consolidated overlapping stories across newsletters.
- Produced an approximately ten-minute mailbox-only brief.
- Did not independently verify all newsletter claims against primary or web sources.
- Made no Gmail changes and stored no raw email in Notion.
- Asked the user and a second reviewer to critique the result.

## Result

The experiment validated the value of cross-source synthesis, source-reliability commentary, and durable takeaways. The user specifically wanted those elements retained.

The pilot failed an essential requirement: it filtered out personal operational items that could affect money, opportunities, or immediate obligations. Examples found during review included an application outcome, a payroll anomaly, and a university invoice. The brief also used Atlas implications too frequently and was longer than its nominal ten-minute target, although the user accepted greater length if summaries support selective reading.

## Evidence and limitations

- One brief and one mailbox are insufficient to establish repeat value.
- Mailbox-only claims were not fully fact-checked against primary sources.
- The pilot did not use the newly built Intelligence Sources registry, so the registry's routing value remains unproven.
- The available critique surfaced disputed examples, reinforcing the need to retain message-level evidence for important claims.
- This record summarizes observed feedback; it is not a benchmark of model quality.

## Lessons learned

1. Prototype the product before automating the pipeline.
2. Needs You and knowledge synthesis are distinct tracks and require separate ranking logic.
3. Executive and section summaries serve different purposes: triage and navigation.
4. Cross-source synthesis is more valuable than serial newsletter summaries.
5. Source-reliability notes improve trust only when uncertainty is explicit and factual claims remain evidence-backed.
6. A registry is scaffolding until the workflow actually uses it.

## Next experiment

Run the v0.2 structure documented in `docs/intelligence-brief.md` for three real reads. After each run, capture misses, ranking quality, sections read, merge/split errors, confidence calibration, and memorable takeaways.

## Exit criteria

Invest in automation only if the v0.2 brief is repeatedly read, surfaces important personal items reliably, ranks learning content well, and produces feedback stable enough to encode as a workflow.
