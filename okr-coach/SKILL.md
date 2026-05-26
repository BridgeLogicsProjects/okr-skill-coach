---
name: okr-coach
description: Use this skill whenever someone wants to write, build, review, stress-test, or improve OKRs (Objectives and Key Results). Triggers include any mention of OKRs, objectives, key results, goal setting, quarterly planning, strategy execution, or when someone says their goals feel too vague, too ambitious, or not connected to outcomes. Also use when someone wants to distinguish between outputs and outcomes, or when they feel their team is busy but not making progress. This skill coaches the user through writing doable OKRs, validates them for value delivery, and helps align strategy to measurable outcomes — not just activity. Use this skill proactively whenever planning, goal-setting, or strategy execution comes up, even if OKRs are not explicitly mentioned.
---

# OKR Coach Skill

A coaching skill that helps users write, validate, and stress-test OKRs — from scratch or from an existing draft. The goal is OKRs that are doable, outcome-driven, and connected to real business value.

## Core Philosophy

OKRs are not a template to fill out. They are a discipline — built the same way quality assurance is built into a product: from the start, not bolted on at the end.

The most common failure modes:
- Objectives that describe activity, not ambition
- Key Results that measure output (what was shipped) not outcome (what changed)
- Too many OKRs diluting focus
- OKRs written in isolation without stakeholder alignment
- No rhythm for checking in and updating confidence

**The golden rule: Less than 3 OKRs per cycle. Sharp focus. Built from evidence, not aspiration.**

---

## How to Use This Skill

Identify where the user is and jump in:

1. **Starting from zero** → Run the Coaching Flow below
2. **Has a draft** → Run the Stress-Test Protocol
3. **Wants strategy alignment** → Run the Outputs vs Outcomes Audit
4. **Wants to publish or share** → Help format and prepare for GitHub or team use

---

## Step 1: Coaching Flow (Writing OKRs from Scratch)

Ask the user these questions one at a time. Do not overwhelm them with all questions at once.

### Clarify the Level
"Are we setting OKRs at the company level, team level, or individual level?"

Coaching tip: Start with company or team level. Individual OKRs come later when the team is more practiced. If the goal is alignment, start at the top.

### Clarify the Cycle
"Are these quarterly OKRs or annual?"

Coaching tip: Quarterly for short-term focus and learning. Annual for long-term direction. Both can coexist — annual sets the north star, quarterly moves toward it.

### Clarify the Problem
"What is the biggest problem you are trying to solve this cycle?"

This is the anchor. Everything else flows from a clear problem statement.

### Draft the Objective
Help the user write an Objective that is:
- Inspirational and directional
- Qualitative, not numeric (numbers belong in Key Results)
- Answerable by: "If we achieve this, will we be proud?"

Bad example: "Improve the product"
Good example: "Make our onboarding experience so clear that new users succeed on their own"

### Draft Key Results
Help the user write 2 to 3 Key Results per Objective that are:
- Measurable and time-bound
- Outcome-based (what changed for the user or business) not output-based (what was built)
- Ambitious but achievable — a 70% confidence level is healthy

Bad example: "Launch the new dashboard feature" (output)
Good example: "Increase 30-day user retention from 40% to 60%" (outcome)

---

## Step 2: Stress-Test Protocol

Run this on any draft OKR set before finalizing.

### The 5 Stress-Test Questions

1. **The Pride Check**
"If you achieve these OKRs, will the team be proud of the cycle?"
If the answer is uncertain, the objective may be too small or too vague.

2. **The Output Trap Check**
"Do any Key Results describe something being shipped or delivered rather than something changing?"
If yes, rewrite them to reflect the change in user behavior, business metric, or outcome.

3. **The Essentials Check**
"Is there anything in this OKR set that is non-essential?"
If something would not meaningfully move the business forward, remove it.

4. **The Alignment Check**
"Do the stakeholders who need to execute these OKRs know about them and agree on them?"
OKRs written in a room without the people doing the work rarely survive contact with reality.

5. **The Confidence Check**
"On a scale of 1 to 10, how confident is the team that these are achievable?"
Target: 6 to 7. Below 5 means the objective is too ambitious without support. Above 8 means it is not ambitious enough.

---

## Step 3: Outputs vs Outcomes Audit

This is the most common gap in OKR writing. Use this when a user's Key Results feel flat or activity-based.

### The Distinction

| Output | Outcome |
|--------|---------|
| We launched the feature | Users adopted the feature |
| We ran 10 customer interviews | We identified 3 unmet needs that changed roadmap direction |
| We hired 2 engineers | Engineering velocity increased by 30% |
| We published the report | Leadership used the findings to make a budget decision |

### How to Reframe

Ask: "What is supposed to change because of this work?"
That change is the outcome. Write the Key Result around that.

Ask: "Who benefits, and how will we know they benefited?"
That answer gives you the metric.

---

## Step 4: Check-In Rhythm

OKRs without a check-in rhythm are wishes. Help the user set one up.

Recommended structure:
- Every two weeks: brief confidence update at the start of an existing team meeting
- Ask: "What is our current confidence level on each Key Result? What has changed?"
- Do not schedule a new separate OKR meeting. Embed it in what already exists.
- At end of cycle: run the Stress-Test questions as a retrospective

---

## Step 5: Strategy to Execution Bridge

When a user has a strategy but struggles to connect it to OKRs, use this bridge:

"What does success look like at the end of this cycle — not in terms of what you built, but in terms of what is different in the world?"

That answer becomes the Objective.

"How will you know that difference happened? What would you measure?"

Those answers become the Key Results.

If the user cannot answer these questions, the strategy is not clear enough yet. Help them clarify the strategy before writing OKRs.

---

## Reference Files

- `references/okr-examples.md` — Real-world OKR examples by function (Product, Marketing, Engineering, Sales)
- `references/common-mistakes.md` — The 10 most common OKR mistakes and how to fix them

Read these when the user needs examples or is making a mistake that is covered there.

---

## Output Format

When presenting OKRs back to the user, use this structure:

```
OBJECTIVE: [Inspirational, qualitative direction]

  KR1: [Measurable outcome with baseline and target]
  KR2: [Measurable outcome with baseline and target]
  KR3: [Measurable outcome with baseline and target — optional]

Cycle: [Q1 2026 / Annual 2026]
Level: [Company / Team / Individual]
Confidence: [X out of 10]
Next check-in: [Date or cadence]
```

Always ask the user: "If you achieve these, will you be proud of this cycle?" before finalizing.
