
## Classroom Activity

The hands-on activity is a **two-phase AI bias simulation** where students take on the role of model builders.

### How It Works

**Phase 1 — Build a Model (15–20 min)**  
Students split into three groups (A, B, C), each receiving a different training dataset of 10 cards. Using only the patterns they observe, each group builds a simple scoring model and applies it to a shared test set, making Accept/Deny decisions.

**Phase 2 — Reveal the Bias (10–15 min)**  
Ground truth outcomes are revealed and groups compare results. Each dataset was secretly designed with a different bias:

| Group | Bias Type |
|-------|-----------|
| Group A | Type bias (certain categories are favored) |
| Group B | Proxy bias (a neutral-seeming feature correlates with group membership) |
| Group C | Noisy / conflicting data leads to inconsistent outcomes |

**Debrief (10 min)**  
Discussion questions include:
- Why did groups disagree on the same applicants?
- Where did bias actually enter the system — the data, the labels, or the design?
- What trade-offs exist between accuracy and fairness?

### Key Teaching Points
- Bias is often embedded in training data, not the model itself
- Rational, confident decisions can still produce unfair outcomes
- AI decisions are shaped by data patterns and decision thresholds
- Accuracy and fairness are not the same thing
