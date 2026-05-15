# Project Card Template

Use this template when adapting a project for a Russian-speaking practical audience.

## Quick Labels

- Difficulty: `beginner`, `intermediate`, `advanced`
- Cost: `local`, `free`, `freemium`, `paid`
- Run mode: `notebook`, `script`, `app`, `api`, `agent`, `mcp`
- Audience: `vibe-coder`, `developer`, `founder`, `researcher`
- Infra: `local`, `docker`, `cloud`, `hybrid`
- Risk level: `low`, `medium`, `high`

## Card Template

```md
# Project Name

- Original title:
- Folder:
- Difficulty:
- Cost:
- Run mode:
- Audience:
- Infra:
- Risk level:

## What It Is
A short plain-language description of the project.

## Why It Matters
Explain the practical outcome. Focus on what the user will be able to build, test, or learn after running it.

## One-Evening Outcome
Describe the smallest successful result someone can get in one sitting.

## Stack
List the core libraries, models, and services.

## What Can Break
Call out the parts most likely to fail: API access, model size, OS assumptions, missing keys, rate limits, unstable setup, or unclear docs.

## RU-Friendly Notes
List substitutions that make the project more realistic for a RU audience.
Examples:
- hosted model to open-weight local model
- Zapier to n8n
- cloud vector DB to local Qdrant
- web app to Telegram bot

## Launch Notes
Write the shortest path to first success.

## Where To Extend It
Suggest 2 or 3 realistic follow-up directions.

## Verdict
State clearly whether the project is worth promoting, who it is for, and when it should be skipped.
```

## Editorial Rules

- Do not repeat the upstream README in different words. Add selection, explanation, and friction-reduction.
- Prefer concrete claims over hype.
- Mention costs and setup pain explicitly.
- If a project depends on region-sensitive or paid tooling, say so directly.
- If a local-first substitute exists, mention it.
- Keep the card readable in under two minutes.

## Minimum Quality Bar

A project should not be promoted on the main page until its card answers all of these:

- What does it actually do?
- Why would a practical builder care?
- Can someone get a visible result quickly?
- Is it cheap, local, or at least honest about cost?
- What breaks first?
- What is the RU-friendly replacement path?