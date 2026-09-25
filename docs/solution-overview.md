# Solution Overview: AI Opportunity Intake & Prioritization Workbench

## Purpose

Capture, score, route, and report on AI use case ideas across business functions. Ensure that AI investments are prioritized by value, feasibility, and governance risk — not by whoever speaks loudest.

## Users

| User Type | Role |
|---|---|
| Idea Submitter | Any employee or manager who identifies a potential AI use case |
| Function Lead | Reviews and validates submissions for their area |
| AI/Process Lead | Final prioritization and portfolio management |
| Executive Stakeholder | Reviews priority dashboard and approves investment decisions |

## Workflow Design

1. Submitter fills out Microsoft Lists intake form
2. Power Automate flow triggers on new submission
3. Flow calculates score band (High / Medium / Low) based on field inputs
4. Flow routes to appropriate reviewer by department
5. Reviewer receives Teams or email notification
6. Reviewer approves, declines, or flags for more information
7. Status updates in the list
8. Power BI dashboard reflects real-time pipeline state

## Key Design Decisions

- **Narrow scope on purpose:** Intake is for idea capture and routing, not full project management. Keeps friction low.
- **Scoring is lightweight:** Weighted rubric in Excel prevents over-engineering while giving consistent signal.
- **Privacy-aware:** Data sensitivity field ensures high-risk ideas are flagged before any build begins.
- **Governance built in from day one:** Not added later as an afterthought.

## Success Metrics

| KPI | Target |
|---|---|
| Ideas submitted per quarter | Baseline TBD in first 90 days |
| High-priority ideas actioned within 30 days | > 80% |
| Ideas abandoned without documentation | < 10% |
| Stakeholder satisfaction with pipeline visibility | > 4/5 |
