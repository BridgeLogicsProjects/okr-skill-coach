---
name: okr-check-in-coach
description: Use this skill whenever someone wants to run a mid-cycle OKR check-in, update confidence levels on active OKRs, triage blockers, or adjust key results that are off track. Triggers include any mention of checking in on OKRs, updating progress, weekly or bi-weekly OKR reviews, team confidence updates, or when someone feels their OKRs are going stale or no one is looking at them anymore. Also use when a team is debating whether to change a key result mid-cycle. This skill runs the check-in, surfaces what matters, and keeps the cycle alive without adding overhead.
---

# OKR Check-In Coach

A coaching skill for running effective bi-weekly OKR check-ins. The goal is to keep OKRs alive through the cycle — not just reviewed at the start and scored at the end.

## Core Philosophy

Most OKRs fail between the writing and the retrospective. The cycle loses momentum because there is no consistent signal about what is working, what is blocked, and what needs to adjust.

A check-in is not a status report. It is a short, honest conversation about confidence — and what the team is going to do about it.

The rule: no new meetings. Embed the check-in in a team sync that already exists. Ten minutes. Three questions. Done.

---

## How to Use This Skill

Identify where the user is and jump in:

1. **Running a check-in now** → Go to the Check-In Protocol below
2. **Confidence has dropped and they don't know why** → Run the Blocker Triage
3. **Debating whether to change a Key Result mid-cycle** → Run the Mid-Cycle Adjustment Protocol
4. **Setting up a check-in rhythm for the first time** → Run the Rhythm Setup

---

## Step 1: Check-In Protocol

Run this every two weeks. Do not wait for a month to pass.

### The Three Check-In Questions

Ask these in order. One at a time.

**Question 1: Confidence**
"For each Key Result, what is your current confidence level on a scale of 1 to 10?"

- 7 or above: on track, no action needed
- 5 to 6: watch this, ask what would move it to a 7
- 4 or below: this is blocked or at risk, go to Blocker Triage

**Question 2: What changed?**
"Since the last check-in, what has moved — in either direction?"

This surfaces new information. Something that was blocked may now be clear. Something that looked easy may have new obstacles.

**Question 3: What is the next action?**
"What is one thing we will do before the next check-in to move the lowest-confidence Key Result forward?"

This closes the loop. A check-in without a next action is just a conversation.

---

## Step 2: Blocker Triage

Use this when confidence drops to 4 or below on any Key Result.

### Triage Questions

Ask these one at a time:

"What specifically is blocking this Key Result?"

Common blockers to probe for:
- Dependency on another team or system
- Data or baseline not yet available
- Scope was larger than estimated
- Priority conflict — the team is working on something else
- The Key Result was measuring an output, not an outcome (the root issue)

"Is this blocker within the team's control?"

If yes: "What would it take to unblock it before end of cycle?"
If no: "Who owns the blocker, and what is the ask?"

"Is this Key Result still the right thing to measure?"

Sometimes a drop in confidence reveals a problem with the Key Result itself — not the work. If the Key Result was output-based or the baseline was wrong, it may need adjustment. Use the Mid-Cycle Adjustment Protocol below.

---

## Step 3: Mid-Cycle Adjustment Protocol

Changing a Key Result mid-cycle is appropriate in two cases:
1. New information has made the original target irrelevant
2. The Key Result was measuring the wrong thing from the start

It is not appropriate when the team simply fell behind and wants to lower the bar.

### The Adjustment Test

Before changing anything, ask:

"Are we changing this because we learned something, or because we are behind?"

If the answer is "we learned something" — adjust. Document what changed and why.
If the answer is "we are behind" — do not change the Key Result. Instead, triage the blocker and reset the plan for the remaining weeks.

### If Adjustment Is Warranted

Help the user rewrite the Key Result with:
- The original target preserved for the record
- The new target with a reason
- A note on what changed

Format:
```
KR [original]: [original text]
Updated: [new text]
Reason: [what new information justified this change]
Date adjusted: [date]
```

---

## Step 4: Rhythm Setup

Use this when a team is starting check-ins for the first time or their check-ins have broken down.

### Setting Up the Rhythm

Ask:
"What team meeting already exists on your calendar every two weeks?"

Find an existing meeting — do not create a new one. Typical candidates: sprint retrospective, team sync, product review.

"Can we add 10 minutes at the start of that meeting for OKR confidence updates?"

That is the entire ask. 10 minutes. The three questions. A written update in the OKR tracker.

### What a Good Check-In Looks Like

Walk the user through a sample check-in:

```
OKR Check-In — [Date]

Objective: [Objective text]

KR1: [Key Result text]
  Confidence: 7/10
  What changed: Baseline data now confirmed at 38%.
  Next action: Begin A/B test by Thursday.

KR2: [Key Result text]
  Confidence: 4/10
  What changed: Engineering capacity reduced due to incident response.
  Blocker: Dependency on platform team deploy.
  Next action: Escalate to platform team lead by EOD Monday.

KR3: [Key Result text]
  Confidence: 8/10
  What changed: Partnership signed, ahead of schedule.
  Next action: None needed this cycle.
```

---

## Output Format

When producing a check-in summary, use this structure:

```
OKR CHECK-IN — [Date]
Facilitator: [Name or team]

OBJECTIVE: [text]

  KR1: [text] | Confidence: X/10 | Status: [On track / Watch / Blocked]
  KR2: [text] | Confidence: X/10 | Status: [On track / Watch / Blocked]
  KR3: [text] | Confidence: X/10 | Status: [On track / Watch / Blocked]

Key blockers: [summary]
Actions before next check-in: [list]
Next check-in: [date]
```

Always end by asking: "Is there anything this check-in revealed that we need to bring to leadership or another team?"
