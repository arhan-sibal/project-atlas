# Project Atlas

Project Atlas is an AI-native personal operating partner designed to help Arhan identify, begin, track, and complete his highest-value work. It is also an applied AI Engineering Lab: each useful feature should produce evidence about product design, agents, context, tools, evaluation, and human oversight.

## Current phase

Product validation and initial agent experiments.

The current system is deliberately small:

- **Notion** is the operational layer for capture, tasks, and the source registry.
- **GitHub** is the canonical source for the PRD, operating principles, experiment records, and future code.
- **Gmail** remains the authoritative email source; Atlas does not copy raw email into Notion.
- **Google Calendar** remains the authoritative calendar.
- **ChatGPT** currently provides guided reasoning and manual, tool-enabled prototypes.

## What exists now

- Atlas Inbox v0.1 with five real, unprocessed captures
- Atlas Tasks v0.1 schema, views, and a standard task template; real-life execution testing is still pending
- Intelligence Sources registry for known newsletter inputs
- Atlas Intelligence Brief v0.1 pilot and an agreed v0.2 editorial specification
- AI Engineering Lab experiment documentation for the brief pilot

## What is intentionally not built

- Autonomous email actions
- Automatic calendar changes
- Multi-mailbox retrieval
- Multi-agent orchestration
- A custom application
- Additional Notion databases without observed need

## Build loop

**Build → use → observe → improve → automate.**

Start with [the PRD](docs/prd.md), then read the [operating principles](docs/operating-principles.md), [Intelligence Brief specification](docs/intelligence-brief.md), and [AI Engineering Lab](lab/README.md).
