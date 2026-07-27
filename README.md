<h1 align="center">Sales Skills for Codex: List Builder</h1>

<p align="center">
  <strong>Build a targeted list of prospects or businesses from a natural-language brief using Explorium. Use when the user asks to "build a list", "find prospects", "pull a target account list", "give me contacts at", "show me companies that", or names titles, departments, industries, company size, location, tech stack, intent topics, or growth events.</strong>
</p>

---

## Overview

Drop this skill into Codex and your AI agent gains the ability to turn a natural-language audience brief into a clean, exportable prospect or business list backed by explorium data.

This skill is part of a 14-skill series covering the full B2B sales workflow, powered by the [Explorium AgentSource API](https://explorium.ai) — 350M+ people, 80M+ companies, real-time firmographics, technographics, funding signals, and verified contact data.

## Repository structure

```
.
├── SKILL.md     # Full skill definition — input, workflow, output format, limitations
├── llms.txt     # AI-readable summary of this skill and the full series
└── README.md
```

## Installation

### Codex

```bash
codex --context SKILL.md
```

### Claude Code / Cursor / Windsurf / any agent that reads Markdown

Point your agent at `SKILL.md` for the full skill instructions.

## Usage

```
Build a list of 100 VP of Engineering at Series B SaaS companies in the US that use Snowflake.
```

```
Find heads of demand gen at 200-1000 person fintech companies in NYC.
```

```
Give me 50 CFOs at public manufacturing companies that raised funding in the last 90 days.
```

```
Pull a target account list of cybersecurity companies under 500 employees in the UK with intent on zero trust.
```

## Related skills in this series

- [Account Contact Shortlist](https://github.com/haroExplorium/sales-skills-for-codex-account-contact-shortlist)
- [Account Fit Rank](https://github.com/haroExplorium/sales-skills-for-codex-account-fit-rank)
- [Account Research](https://github.com/haroExplorium/sales-skills-for-codex-account-research)
- [Clean Data](https://github.com/haroExplorium/sales-skills-for-codex-clean-data)
- [Competitor Research](https://github.com/haroExplorium/sales-skills-for-codex-competitor-research)
- [Decision Makers Map](https://github.com/haroExplorium/sales-skills-for-codex-decision-makers-map)
- [Enrich Company](https://github.com/haroExplorium/sales-skills-for-codex-enrich-company)
- [Enrich Contact](https://github.com/haroExplorium/sales-skills-for-codex-enrich-contact)
- [Lookalike Accounts](https://github.com/haroExplorium/sales-skills-for-codex-lookalike-accounts)
- [Market Sizing](https://github.com/haroExplorium/sales-skills-for-codex-market-sizing)
- [Meeting Prep](https://github.com/haroExplorium/sales-skills-for-codex-meeting-prep)
- [Personalize Email](https://github.com/haroExplorium/sales-skills-for-codex-personalize-email)
- [Score Leads](https://github.com/haroExplorium/sales-skills-for-codex-score-leads)

## License

MIT
