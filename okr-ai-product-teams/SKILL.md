---
name: okr-ai-product-teams
description: Use this skill whenever someone is setting OKRs for an AI product team, an AI-enabled product, or any initiative where the output is non-deterministic — meaning the system learns, adapts, or produces results that cannot be fully predicted in advance. Triggers include any mention of AI product OKRs, machine learning metrics, model performance goals, trust metrics, responsible AI, AI feature adoption, or when someone is struggling to write Key Results for work where outcomes are probabilistic rather than guaranteed. Also use when a team is treating AI features like any other feature and missing the unique measurement challenges. This skill coaches AI-specific OKR writing and connects goal-setting to responsible AI practice.
---

# OKR Coach for AI Product Teams

A coaching skill for writing OKRs on AI product teams — where outputs are probabilistic, trust is a product metric, and responsible AI is not a compliance checkbox but an execution dependency.

## Core Philosophy

AI products break standard OKR patterns in two ways.

First, the output is non-deterministic. You cannot commit to "the model will achieve X accuracy" the same way you commit to "we will ship the login flow by March." The model learns. The environment shifts. The data changes. A Key Result that treats an AI output like a software feature will mislead the team.

Second, user trust is load-bearing. An AI feature that users do not trust does not get used — regardless of model performance. Trust is not a soft metric. It is a leading indicator of adoption, retention, and value delivery.

OKRs for AI teams have to account for both.

---

## How to Use This Skill

1. **Writing OKRs for an AI product team from scratch** → Start with the AI OKR Coaching Flow
2. **Existing OKRs feel wrong for AI work** → Run the AI OKR Audit
3. **Trying to measure trust** → Use the Trust Metrics Framework
4. **Responsible AI needs to be connected to OKRs** → Use the Responsible AI Gates Protocol
5. **Key Results are probabilistic and the team is uncomfortable with that** → Use the Probabilistic Output Protocol

---

## Step 1: AI OKR Coaching Flow

Ask these questions before writing anything.

### Clarify the Type of AI Work

"Is the AI feature generating recommendations, automating decisions, or assisting humans in making decisions?"

This matters because:
- Recommendations: user can accept or reject, trust is revealed through adoption rate
- Automated decisions: user may not see the decision, trust is revealed through override rate and error rate
- Human-in-the-loop: user and AI collaborate, trust is revealed through confidence calibration

### Clarify What Non-Deterministic Means Here

"What is the output of this AI system — and can you predict it with certainty in advance?"

If no: "Then your Key Result cannot be a commitment to a specific output. It needs to be a commitment to a specific behavior or signal from users that tells you the output is valuable."

### Clarify the Trust Baseline

"Do you have any data on whether users currently trust the AI outputs?"

If no: "Finding your trust baseline is a Key Result. You cannot set a target for something you have not measured."

Common trust signals:
- Feature adoption rate (are users actually using the AI feature?)
- Override rate (how often do users reject or override the AI recommendation?)
- User-reported confidence (survey: "How confident are you in the AI's suggestion?")
- Error escalations (how often do users flag the AI output as wrong?)

---

## Step 2: AI OKR Audit

Use this on existing OKRs to find where they break for AI work.

### The Four AI OKR Red Flags

**Red Flag 1: Committing to model performance as a Key Result**
Example: "Achieve 90% model accuracy"
Problem: Accuracy is an internal metric. It does not tell you if users are getting value. A 90% accurate model that users do not trust is not a business outcome.
Fix: Reframe around user behavior. "Increase user adoption of AI recommendations from 20% to 50% of eligible users."

**Red Flag 2: No trust metric in the OKR set**
Problem: If no Key Result measures whether users trust the AI output, the team is optimizing for model performance without a connection to user value.
Fix: Add at least one trust metric. See the Trust Metrics Framework below.

**Red Flag 3: Treating responsible AI review as a separate project**
Problem: If compliance or safety review is not in the OKRs, it will be deprioritized when the team is under pressure.
Fix: Add a responsible AI gate as a Key Result. "Complete responsible AI review for all model integrations before launch — 100% compliance rate."

**Red Flag 4: Key Results that assume deterministic outputs**
Example: "The AI will surface the correct recommendation in 95% of cases"
Problem: You do not know this in advance. The model will be evaluated on a distribution, not a single case.
Fix: Commit to the measurement, not the result. "Establish measurement pipeline for recommendation accuracy and publish baseline by end of Q1."

---

## Step 3: Trust Metrics Framework

Trust is the most important product metric for AI features and the least often measured.

### Trust Signals by Feature Type

**Recommendation systems (search, content, product suggestions):**
- Click-through rate on AI recommendations vs. non-AI suggestions
- Adoption rate: percentage of users who act on the recommendation
- Repeat use: do users come back and use the feature again?

**Automated decisions (fraud detection, content moderation, eligibility):**
- Override rate: how often do users or reviewers reverse the AI decision?
- Appeal rate: how often do affected users contest the outcome?
- False positive / false negative rate and its downstream business impact

**Human-in-the-loop (writing assistants, AI copilots, diagnostics support):**
- Acceptance rate: percentage of AI suggestions accepted without editing
- Edit rate: how much do users modify the AI output before using it?
- Self-reported confidence: survey users on their confidence in AI-assisted outputs

### Writing a Trust Key Result

Structure: [Trust signal] from [baseline] to [target] by [end of cycle]

Examples:
- "Increase AI recommendation adoption rate from 15% to 40% of active users"
- "Reduce user override of automated moderation decisions from 18% to 8%"
- "Achieve AI-assisted output acceptance rate of 65% or above in user sessions"
- "Establish trust measurement baseline across all three signals by end of Q1"

If no baseline exists: your first Key Result is to find it.

---

## Step 4: Probabilistic Output Protocol

Use this when the team is uncomfortable writing Key Results for work where outcomes cannot be guaranteed.

### Reframe the Commitment

The commitment is not to the model's output. It is to:
1. The measurement being in place
2. The signal moving in the right direction
3. The team's ability to learn and adjust

Ask the team:
"What would tell you, at the end of this cycle, that you made the right bets on this AI feature — even if the model did not hit the target?"

That answer usually reveals what they actually care about: adoption, trust, learning velocity, or risk reduction.

### The Confidence Range Approach

For AI Key Results where the outcome is uncertain, use a confidence range rather than a single point target.

Example:
Instead of: "Achieve 80% recommendation adoption rate"
Write: "Achieve 50% to 70% recommendation adoption rate, with a learning review at week 6 to assess trajectory"

The range acknowledges uncertainty. The learning review keeps the team honest about whether they are on track.

### What to Do When the Model Fails

Build failure into the OKR:
"If the model does not meet the minimum threshold by mid-cycle, the team will [specific action — retrain, adjust scope, pivot to a rule-based fallback]."

This is not defeatism. It is professional risk management. Teams that plan for model failure respond faster than teams that assume it will not happen.

---

## Step 5: Responsible AI Gates Protocol

Responsible AI is not a legal formality. It is a product dependency. If you ship an AI feature without completing the required reviews, you are taking on hidden risk — for users and for the business.

### Connecting Responsible AI to OKRs

Add this as a standard Key Result on any OKR that includes a new AI feature or model integration:

"Complete responsible AI review for [feature/model] before launch — 100% compliance"

This Key Result has a binary score: done or not done. If it is not done, the OKR is not complete — regardless of what other Key Results achieved.

### Responsible AI Review Checklist (for OKR context)

Use these as the criteria for the review Key Result:

- Bias and fairness review: has the model been tested for performance across demographic groups?
- Data provenance: is the training data sourced, labeled, and documented appropriately?
- Explainability: can a user understand why the AI produced a specific output?
- User disclosure: do users know they are interacting with AI?
- Failure mode documentation: has the team documented what happens when the model is wrong, and built a response?
- Rollback plan: can the AI feature be disabled without breaking the product?

### When Responsible AI Blocks a Launch

If the review is not complete and launch pressure is high, name the tradeoff explicitly:

"Launching without completing this review is a risk decision, not a product decision. Who is authorizing it and what are the documented risks?"

This keeps the OKR honest and puts the right person in the room for the right conversation.

---

## Output Format

When presenting AI OKRs back to the team, use this structure:

```
OBJECTIVE: [Inspirational direction for the AI product work]

  KR1: [Trust or adoption metric — with baseline and target]
  KR2: [Model performance metric reframed around user behavior]
  KR3: [Responsible AI gate — binary completion]

Cycle: [Q_ YYYY]
Level: [Team / Product]
AI feature type: [Recommendation / Automated decision / Human-in-the-loop]
Trust baseline available: [Yes / No — if no, KR1 should establish it]
Confidence: [X out of 10]
Responsible AI review owner: [name]
Next check-in: [Date or cadence]
```

Always ask before finalizing: "Is there anything about how this AI system could harm a user that is not represented in these OKRs?" If yes, it belongs in the Key Results.
