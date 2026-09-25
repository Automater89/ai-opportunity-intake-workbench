# AI Opportunity Scoring Model

## Overview

This lightweight scoring rubric assigns a priority band (High / Medium / Low) to each submitted AI idea. It balances four dimensions: business value, ease of implementation, governance risk, and adoption readiness.

The model is designed to be simple enough to maintain in Excel and explainable to a non-technical stakeholder in under 2 minutes.

## Scoring Dimensions

| Dimension | Weight | What We're Measuring |
|---|---|---|
| Business Value | 35% | Time saved, error reduction, experience improvement, strategic alignment |
| Ease of Implementation | 25% | Technical complexity, dependencies, data availability |
| Governance & Risk | 20% | Data sensitivity, compliance exposure, hallucination risk |
| Adoption Readiness | 20% | Stakeholder support, user readiness, change management burden |

## Scoring Scale (Per Dimension)

| Score | Meaning |
|---|---|
| 1 | Low / Risky / Complex |
| 2 | Moderate |
| 3 | High / Safe / Simple |

## Priority Band Thresholds

| Weighted Score | Priority Band |
|---|---|
| 2.5 – 3.0 | High — Action in current cycle |
| 1.8 – 2.4 | Medium — Queue for next cycle |
| < 1.8 | Low — Revisit or decline |

## Governance Risk Scoring Note

For the Governance & Risk dimension, scores are **inverted** before weighting:
- High data sensitivity = score of 1 (riskier)
- Low data sensitivity = score of 3 (safer)

This ensures that risky ideas are pulled down in priority until governance controls are defined, not fast-tracked.

## Excel Implementation

The scoring model lives in `exports/scoring-model.xlsx`. Each row is one submitted idea. Columns B through E are dimension scores (entered or calculated from intake fields). Column F is the weighted average. Column G auto-labels the priority band using an IF formula.

```excel
=IF(F2>=2.5,"High",IF(F2>=1.8,"Medium","Low"))
```
