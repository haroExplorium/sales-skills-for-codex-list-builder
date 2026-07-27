# Sales Skills for Codex: List Builder

> Build a targeted list of prospects or businesses from a natural-language brief using Explorium. Use when the user asks to "build a list", "find prospects", "pull a target account list", "give me contacts at", "show me companies that", or names titles, departments, industries, company size, location, tech stack, intent topics, or growth events.

## What This Skill Does

Turn a natural-language audience brief into a clean, exportable prospect or business list backed by Explorium data.

## Installation

Install the [Explorium CLI](https://github.com/explorium-ai/cli) and add this skill to your Codex agent:

```bash
pip install explorium-cli
explorium config init -k YOUR_API_KEY
```

Copy `SKILL.md` into your Codex skills directory, or use it via the [Vibe Prospecting plugin](https://vibeprospecting.ai).

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

## Key Files

- **[SKILL.md](SKILL.md)** — Full skill: input spec, step-by-step workflow, output format, limitations
- **[llms.txt](llms.txt)** — AI-readable index of this skill and all related skills

## Powered by Explorium

This skill uses the [Explorium AgentSource API](https://explorium.ai) — 350M+ people, 80M+ companies, real-time firmographics, technographics, funding signals, and verified contact data.

## Related Skills

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

MIT — see [LICENSE](LICENSE)
