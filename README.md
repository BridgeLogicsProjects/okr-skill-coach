# OKR Strategy Coach — A Claude Skill Suite

A suite of five coaching skills for Claude that helps product leaders, teams, and individuals write, run, and improve OKRs across the full cycle — from writing to check-in to retrospective.

Built by **Keeya Wang-Jones** | Product Leadership | AI Product Management

---

## What This Suite Does

Most OKR processes fail at the same places: objectives that describe activity instead of ambition, key results that measure what was shipped instead of what changed, and goals written without the people who have to execute them.

Then the cycle starts. No one checks in. The quarter ends. The team scores the OKRs in a hurry and starts the next cycle without learning anything.

This suite coaches every phase — not just the writing.

---

## The Five Skills

| Skill | What It Does | When to Use |
|-------|-------------|-------------|
| `okr-coach` | Write, validate, and stress-test OKRs from scratch or from a draft | Starting a new cycle, improving existing OKRs |
| `okr-check-in-coach` | Run bi-weekly confidence updates, triage blockers, adjust mid-cycle | During the cycle, every two weeks |
| `okr-retrospective-coach` | Score OKRs 0.0 to 1.0, extract learning, carry forward what matters | End of cycle |
| `okr-workshop` | Facilitate group OKR planning sessions from pre-work to post-session output | Team or leadership planning sessions |
| `okr-ai-product-teams` | Write OKRs for AI features — trust metrics, probabilistic outputs, responsible AI gates | Any team building AI-powered products |

---

## Skill Structure

```
okr-skill-coach/
├── okr-coach/
│   ├── SKILL.md                   — Core OKR writing, stress-testing, outputs vs outcomes
│   ├── okr-examples.md            — Real OKR examples by function
│   └── common-mistakes.md         — 10 most common OKR mistakes and fixes
├── okr-check-in-coach/
│   └── SKILL.md                   — Bi-weekly check-in protocol, blocker triage, mid-cycle adjustments
├── okr-retrospective-coach/
│   └── SKILL.md                   — End-of-cycle scoring, keep/stop/try, carry-forward protocol
├── okr-workshop/
│   └── SKILL.md                   — Group facilitation: pre-work, 4-phase session, post-session output
└── okr-ai-product-teams/
    └── SKILL.md                   — AI-specific OKRs: trust metrics, probabilistic outputs, responsible AI
```

---

## How to Install

**Install a single skill:**
1. Clone this repository
2. In Claude, open your Project settings
3. Upload the skill folder (e.g. `okr-coach/`) — Claude reads the `SKILL.md` automatically

**Install the full suite:**
Upload each skill folder individually. Each skill activates based on what you are working on — they do not conflict.

**In Cowork (Claude desktop):**
Each folder can be added as a skill via the plugin or skills interface. The skill name matches the folder name.

---

## When Each Skill Triggers

**okr-coach** — writing OKRs, reviewing OKRs, "my goals feel too vague", "are these outcomes or outputs"

**okr-check-in-coach** — "let's do an OKR check-in", "our confidence has dropped", "should we change this key result mid-cycle"

**okr-retrospective-coach** — "let's score this quarter", "OKR retrospective", "what did we learn", "should we carry this forward"

**okr-workshop** — "I'm running an OKR planning session", "help me facilitate a workshop", "our last OKR session produced bad goals"

**okr-ai-product-teams** — "OKRs for our AI feature", "how do we measure trust", "our model output is non-deterministic", "responsible AI and OKRs"

---

## Example Prompts to Try

**okr-coach:**
- "Help me write OKRs for my product team this quarter"
- "Stress-test these OKRs before we lock them in"
- "Are my key results measuring outcomes or just outputs?"

**okr-check-in-coach:**
- "Run our bi-weekly OKR check-in"
- "KR2 confidence dropped to 4 — help me triage the blocker"
- "Should we change this key result or push through?"

**okr-retrospective-coach:**
- "Help us score and reflect on this quarter's OKRs"
- "What should carry forward to next cycle?"
- "Why do we keep hitting the same problems every quarter?"

**okr-workshop:**
- "I'm facilitating an OKR planning session tomorrow — help me prepare"
- "Run me through the 4-phase OKR workshop format"
- "Our last workshop produced OKRs nobody remembers — what went wrong?"

**okr-ai-product-teams:**
- "How do I write OKRs for a recommendation engine?"
- "Help me build a trust metric for our AI feature"
- "Our key results assume deterministic outputs but our model is probabilistic — how do we fix this?"

---

## Built On

The methodology in this suite draws from:
- *Measure What Matters* — John Doerr
- *Radical Focus* — Christina Wodtke
- OKR Mentors playbook on strategic OKR definition and execution
- Teresa Torres on continuous discovery and outcome-based thinking
- Jeff Gothelf on OKRs and lean product practice
- Felipe Castro on OKR implementation and common failure patterns
- IBM AI Product Management curriculum on lean product thinking and stakeholder management
- Real product leadership experience across MedTech, FinTech, EdTech, PropTech, and Agentic AI

---

## License

MIT — free to use, adapt, and share. Credit appreciated.

---

*Part of a growing library of product leadership skills for Claude.*
*Follow the journey on LinkedIn and Medium — search Keeya Wang-Jones.*

*Anthropic marketplace submission pending.*
