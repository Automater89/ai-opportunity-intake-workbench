# Governance Notes

## Why Governance Is Built In From the Start

AI intake systems fail when governance is treated as a final-step review. By the time a project has momentum, it is hard to slow down for risk assessment. This workbench embeds governance signals into the intake form itself so that high-risk ideas are visible early.

## Governance Checkpoints in This Workbench

| Checkpoint | Where It Lives | What It Catches |
|---|---|---|
| Data Sensitivity field | Intake form | Flags PII, financial, legal, or regulated data before scope is set |
| Governance & Risk dimension | Scoring model | Weights risk into priority so high-sensitivity ideas require stronger justification |
| Reviewer routing | Power Automate flow | High-sensitivity submissions route to a governance or compliance reviewer, not just a function lead |
| Decision Brief template | docs/ | Requires documenter to name risks, dependencies, and mitigations before approval |

## What This Workbench Does NOT Replace

- A formal AI governance policy
- Legal or compliance review for regulated use cases
- Data privacy impact assessments (DPIA)
- Security architecture review

This intake system surfaces ideas and flags risk. It does not approve production deployment.

## Responsible AI Reminder

Before any AI idea moves to implementation, the following questions should be answered:

1. What data does this use? Is it sensitive?
2. Who sees the output? Can the AI be wrong in a harmful way?
3. Is there a human in the loop at critical decision points?
4. How will we know if the AI is underperforming or drifting?
5. What is the rollback or escalation path?
