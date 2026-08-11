# Project Atlas — Product Requirements Document

Version: 0.3
Updated: August 10, 2026
Status: Product validation and initial agent experiments
Primary user: Arhan Sibal

## 1. Vision

Build an AI-native personal operating partner that helps Arhan consistently identify, begin, and complete the highest-value work across career, learning, health, and relationships.

Atlas should reduce decision fatigue, compensate for inconsistent task initiation and tracking, detect execution drift, and make recovery easy. It should remain useful when Arhan does not proactively open it. Building Atlas should also produce practical AI product and agent-engineering knowledge.

## 2. Core problem

Arhan has many valuable, competing priorities but struggles with:

- deciding what to work on;
- beginning tasks despite understanding their importance;
- sustaining and recording focused work;
- seeing when low-output days accumulate;
- maintaining urgent and long-term commitments at once;
- returning to a system after a gap; and
- staying current on AI, technology, business, and important personal inbox items.

A conventional task manager may store work without changing behavior. Atlas must support action and re-entry, not merely organization.

## 3. Primary outcomes

1. **Secure a strong long-term role.** Support job discovery, applications, networking, interview preparation, follow-ups, and recruiting-process management.
2. **Become deeply current in AI, technology, and business.** Provide a sustainable information and learning system spanning current developments and durable ideas.
3. **Become organized and disciplined.** Make planning, starting, tracking, reviewing, and recovering from low-output periods easier.
4. **Build applied AI capability.** Use Atlas to learn AI product design, agents, context engineering, tools, APIs, evaluation, and human-in-the-loop systems.

## 4. Current operating model

- **Atlas construction is human-led.** AI guides, explains, reviews, verifies, and handles repetitive work only when it no longer provides learning value.
- **Atlas operation becomes progressively agentic.** Suggestions precede writes; consequential external actions require explicit approval.
- **GitHub is canonical** for the PRD, operating principles, experiment records, and code.
- **Notion is operational** for structured personal workflows and a readable PRD representation.
- **Gmail and Google Calendar remain authoritative** for email and calendar data.

The detailed rules live in [`docs/operating-principles.md`](operating-principles.md).

## 5. Current implemented state

### Capture Inbox v0.1

The Notion Atlas Inbox provides low-friction capture with optional Type, Area, and Source URL fields. Five real captures remain unprocessed. This is useful evidence that capture alone did not create a processing habit.

### Task execution v0.1

The Notion Atlas Tasks database has a small task schema, focused views, and a Standard Task template with Definition of Done, First Tiny Step, and Context prompts. It has not yet been validated with a real task and focus session.

### Intelligence Sources v0.1

The Notion source registry records known newsletters, sender patterns, categories, cadence, proposed brief route, and evaluation status. It is reference data, not yet a proven routing system.

### Atlas Intelligence Brief pilot

One mailbox-only pilot was generated manually with tool-enabled retrieval. Its cross-source synthesis and source-reliability commentary were valuable. It failed to surface important personal items and therefore did not fully meet the user need. The agreed v0.2 specification is documented in [`docs/intelligence-brief.md`](intelligence-brief.md).

### AI Engineering Lab

The first experiment record documents what the Intelligence Brief pilot tested, what failed, and the next evaluation criteria. Atlas should accumulate experiments only when they answer a real product or engineering question.

## 6. Near-term experience

### Needs You

Surface deadlines, anomalies, personal operational items, and decisions requiring Arhan before learning content.

### Knowledge briefing

Provide a ranked 100–200 word executive summary, navigable topic summaries, detailed cross-source synthesis, source-reliability notes, and selective recommendations for deeper reading.

### Execution support

Provide a very small set of priorities, a recommended first action, clear next steps, and a gentle re-entry path after gaps. Do not create punitive overdue backlogs.

## 7. Success criteria

Early success is behavioral evidence, not feature count:

- important personal inbox items are not missed;
- the brief is read and judged useful across three real runs;
- one captured item is processed into an intentional destination;
- one real task is started using a First Tiny Step;
- one focus session is completed and friction is recorded;
- returning after a gap feels easier than abandoning the system; and
- maintenance burden remains low.

Focused hours can be baseline telemetry, but Atlas must not optimize for hours or data entry at the expense of valuable outcomes.

## 8. Product principles

1. Execution over documentation.
2. Usage before expansion.
3. One sprint produces one observable outcome, normally in 10–20 minutes and no more than five steps.
4. Fewer visible choices when action is required.
5. Push mechanisms and re-entry are first-class requirements.
6. No scaffolding without observed pain.
7. Automate only understood workflows.
8. Consequential external actions require human approval; all automations must be observable and reversible.
9. One canonical source exists for each important data type.
10. Experiments have explicit questions, evidence, and exit criteria.

## 9. Constraints and non-goals

- Do not store raw email in Notion.
- Do not turn informational email into tasks automatically.
- Do not add Projects, Goals, habits, time tracking, recurring tasks, or complex relations until current workflows earn them through use.
- Do not make employer-controlled or temporary university mailboxes long-term dependencies without a deliberate decision.
- Do not build multi-mailbox OAuth, orchestration, or automation before the brief proves useful.
- Do not enable automated sending, deletion, financial actions, or other consequential actions in the early phase.

## 10. Next validation sequence

1. Run Atlas Intelligence Brief v0.2.
2. Repeat the brief for three real reads and capture concrete editorial feedback after each.
3. Process exactly one existing Inbox item.
4. Create or select exactly one real task with a First Tiny Step.
5. Complete one 25-minute focus session and record the friction and next step.

The next feature decision must follow from this evidence.

## 11. Open questions

- Which personal items belong in Needs You without creating noise?
- Which sources consistently improve the brief, and which should be excluded?
- What balance of AI, technology, business, world news, and career context is most useful?
- What re-entry prompt best helps after several days away?
- Does First Tiny Step materially reduce task-start latency?
- What is the simplest sustainable path from one mailbox to multiple mailboxes, if the brief earns that investment?

## Revision log

### v0.3 — August 10, 2026

- Added the canonical Tasks workflow and its current unvalidated status.
- Added human-led construction, usage-before-expansion, push, and re-entry principles.
- Added the Intelligence Brief pilot and v0.2 validation path.
- Reframed success around observed behavior and experiment evidence.
- Defined GitHub as canonical and Notion as the operational representation.

### v0.2 — July 17, 2026

- Added Capture Inbox as the first functional feature.
- Established low-friction capture as a foundational requirement.
- Deferred classification, prioritization, and automatic routing until real usage data exists.
- Required basic capture without optional fields.

### v0.1 — July 16, 2026

- Established the initial vision, outcomes, principles, constraints, and platform roles.
