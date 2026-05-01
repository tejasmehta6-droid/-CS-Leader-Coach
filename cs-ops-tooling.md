# CS Ops & Tooling Coaching Reference

## What CS Ops Actually Is

CS Ops is not just the admin who manages Gainsight. Done well, CS Ops is:
- The **data and systems layer** that makes CS scalable
- The **process designer** that defines playbooks and codifies what good looks like
- The **analytics function** that tells CS leaders where to focus
- The **enablement partner** that onboards and upskills CSMs

**The case for investing in CS Ops:**
CS teams without Ops spend 40–60% of CSM time on admin, reporting, and manual tasks. CS teams with mature Ops spend that time on customers. The ROI is not abstract — it's NRR.

---

## CS Tech Stack Design

### The Core Stack (What Every CS Team Needs)

| Layer | Purpose | Tools |
|-------|---------|-------|
| **CRM** | Account and contact data, renewal tracking | Salesforce, HubSpot |
| **CS Platform** | Health scoring, playbooks, automated tasks | Gainsight, ChurnZero, Totango |
| **Communication** | Customer touchpoints, email, video | Gmail/Outlook, Zoom, Loom |
| **Conversation Intelligence** | Call recording, coaching, account insights | Gong, Chorus |
| **Customer Portal / Hub** | Self-service, shared success plans | Gainsight PX, Zendesk, Notion |
| **Product Analytics** | Usage data, adoption signals | Mixpanel, Amplitude, Pendo |
| **Feedback** | NPS, CSAT, pulse surveys | Medallia, Delighted, Qualtrics |

### The AI-Enhanced Stack (2024+ Standard)

Add to core stack:
- **Predictive churn AI** — integrated in Gainsight, ChurnZero or via Clari/Mixpanel
- **Meeting AI** — Gong, Fireflies, or Otter for transcription + insights
- **Generative AI** — ChatGPT, Claude, or Copilot for CSM workflow augmentation
- **AI agents** — for low-touch account automation (increasingly available in Gainsight, ChurnZero)

### Tooling Decision Framework

Before buying any new CS tool, answer:
1. **What specific problem does this solve?** (Name the metric or behavior it will change)
2. **Do our CSMs have the time and willingness to adopt it?** (Tool graveyard risk)
3. **Does it integrate with our CRM?** (Data siloes kill adoption)
4. **What does success look like in 90 days?** (Define before buying)
5. **Is AI a core feature or a checkbox?** (Distinguish genuine AI from marketing)

**What NOT to do:**
- ❌ Buy a CS platform because a competitor uses it
- ❌ Implement a tool without a CSM champion who believes in it
- ❌ Add tools without retiring old ones (stack complexity kills teams)
- ❌ Let the vendor define success metrics — you define them

---

## Health Score Design

### The Most Common Health Score Mistakes

1. **Too many signals** — a health score with 15 inputs gives you mush. Aim for 5–7 max.
2. **Wrong weighting** — most teams over-weight product usage and under-weight relationship and commercial signals
3. **No leading indicators** — if your health score only tells you what already happened, it's a rearview mirror
4. **Not segmented** — a health score that works for enterprise won't work for PLG/SMB

### Health Score Design Framework

**Recommended signal categories and weights:**

| Signal Category | Weight | Why |
|----------------|--------|-----|
| Product engagement trend | 25% | Leading: trajectory matters more than current state |
| Executive relationship health | 20% | Lagging but high-impact: no exec = no renewal |
| Time-to-value achievement | 15% | Leading: did they get the outcome they bought for? |
| Support sentiment trend | 15% | Leading: rising frustration = churn signal |
| Commercial risk flags | 15% | Budget changes, champion departure, contract terms |
| NPS / CSAT trend | 10% | Lagging, but useful as a confirmation signal |

**Segment your health scores:**
- Enterprise (high-touch): weight executive relationship and commercial signals higher
- Mid-market (pooled): weight product engagement and support sentiment higher
- PLG/SMB: weight product engagement and self-service behavior almost exclusively

### Using AI to Enhance Health Scoring

Modern CS platforms can:
- Predict churn 60–90 days out based on behavioral patterns
- Surface accounts that look healthy but are statistically at risk
- Auto-trigger plays when risk thresholds are crossed

If you're still doing manual health score reviews, that's a Q1 priority.

---

## Playbook Design

### What a Playbook Is (and Isn't)

A playbook is a documented, repeatable process for a specific CS situation.
It is NOT a policy document. It's a field guide that a CSM can open and use immediately.

**Playbooks every CS team needs:**
- Onboarding (by segment)
- At-risk / churn save
- Expansion (CQL process)
- EBR / QBR execution
- Escalation handling
- Renewal (by segment and risk level)
- Champion departure response
- AI-assisted account monitoring

### Playbook Design Template

```
PLAYBOOK: [Name]
Trigger: When does this playbook activate?
Owner: Who runs it?
Timeline: How long does it take?
Steps:
  1. [Action] — [Owner] — [Timeline]
  2. ...
Templates: [Link to email/script templates]
Success metric: How do we know it worked?
Escalation: What triggers escalation to manager/VP?
```

### Measuring Playbook Effectiveness

Every playbook should be evaluated on:
- Adoption rate (are CSMs actually using it?)
- Outcome rate (is it working — save rate, NRR impact, TTV improvement?)
- Time cost (is it practical, or too burdensome?)

Review and update playbooks quarterly. A playbook that was written 18 months ago pre-AI is probably outdated.

---

## CS Metrics & Reporting Infrastructure

### The Metrics Every CS Leader Must Track

**Leading (predictive):**
- At-risk ARR by segment (updated weekly)
- Health score distribution and trend
- TTV by cohort (are customers reaching value faster?)
- CSM capacity utilization (accounts per CSM vs. target)

**Lagging (result):**
- NRR and GRR (monthly trend)
- Logo and revenue churn rate
- Expansion ARR (CS-sourced)
- Renewal close rate and on-time rate

**Operational:**
- Playbook adoption rate
- QBR/EBR completion rate
- Response time to at-risk flags
- CSM:ARR ratio vs. benchmark

### Building the CS Dashboard

For a VP CS, you need dashboards at three levels:
1. **Executive dashboard** — NRR, GRR, at-risk ARR, expansion. Updated weekly. Fits on one page.
2. **Manager dashboard** — Team capacity, account health distribution, playbook completion. Updated daily.
3. **CSM dashboard** — My accounts, my tasks, my at-risk flags. Real-time.

If your CS platform can't generate these automatically, that's a CS Ops gap to fix.
