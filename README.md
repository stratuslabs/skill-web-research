# 🔍 skill-web-research

> Structured web research with citations.

A **skill** for [StratusOS](https://stratuslabs.io) — the AI operating system for Mac.

---

## What it does

Teaches any agent how to do thorough web research — search, fetch, cross-reference, summarize, and cite sources. Includes prompt templates for quick lookups, deep dives, comparative analysis, and controversial topics. Plug it into any agent and they'll research like an analyst, not a chatbot.

## Installation

```bash
# From StratusOS Marketplace (recommended)
# Open StratusOS → Marketplace → Skills → Web Research → Install

# Or manual:
git clone https://github.com/stratuslabs/skill-web-research.git ~/.stratusos/skills/web-research
```

## What's included

```
SKILL.md              — Core research methodology + patterns
templates/
  quick-lookup.md     — Fast answer with 2-3 sources
  deep-dive.md        — Comprehensive research report
  comparative.md      — Side-by-side comparison format
  controversial.md    — Balanced analysis of disputed topics
examples/
  01-quick-lookup.md  — Example: "What's the latest on Apple Containers?"
  02-comparative.md   — Example: "Compare Cursor vs Windsurf vs Claude Code"
  03-controversial.md — Example: "Is AI replacing developers?"
```

## How skills work

Skills are pure knowledge — no binaries, no APIs. When loaded, the skill's `SKILL.md` and templates are injected into the agent's context. The agent learns the research methodology and applies it automatically.

## Compatible tools

- `agent-browser` — for JavaScript-rendered pages
- Web Fetch (built-in) — for static page extraction
- Web Search (built-in) — for Brave API search

## Requirements

- StratusOS v0.2.0+

---

<p align="center">
  <br>
  Built for <a href="https://stratuslabs.io"><strong>StratusOS</strong></a> — your AI operating system.
  <br>
  <a href="https://github.com/stratuslabs">GitHub</a> · <a href="https://discord.gg/stratuslabs">Discord</a>
  <br>
  <br>
  <sub>Made by <a href="https://github.com/stratuslabs">Stratus Labs</a></sub>
</p>
