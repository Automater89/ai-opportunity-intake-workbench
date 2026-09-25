# GitHub Copilot Prompts — AI Opportunity Intake Workbench

Use these in VS Code Copilot Chat or GitHub Copilot to accelerate documentation, logic design, and artifact generation for this project.

---

## Project Planning

```
/plan Build an AI opportunity intake and prioritization system using Microsoft Lists, Power Automate, Power BI, and Excel. Break the project into phases: intake form design, scoring model, routing flow, reporting, and documentation artifacts.
```

---

## Field Dictionary

```
Create a markdown table for an AI use case intake field dictionary. Include columns for: field name, purpose, field type (text, choice, number, auto), required (yes/no/auto), and example value. Cover fields for idea title, business area, process pain, frequency, estimated time impact, stakeholder owner, systems involved, data sensitivity, desired outcome, status, and priority score band.
```

---

## Scoring Model Logic

```
Draft a lightweight AI use case prioritization scoring model suitable for Excel. Include four dimensions: business value (35%), ease of implementation (25%), governance and risk (20%), and adoption readiness (20%). Use a 1-3 scale per dimension. Output the weighted score and classify into High (2.5-3.0), Medium (1.8-2.4), and Low (<1.8) priority bands. Include a note that the governance risk dimension score is inverted before weighting.
```

---

## Power Automate Flow Description

```
Describe the logic for a Power Automate cloud flow that triggers when a new item is added to a Microsoft Lists intake form. The flow should: (1) calculate or look up a priority score band based on the submitted fields, (2) route the submission to the appropriate reviewer based on business area and sensitivity, (3) send a Teams or email notification to the reviewer with key details, and (4) update the item status from New to Under Review.
```

---

## Decision Brief Template

```
Create a one-page decision brief template for an AI use case review. Include sections for: problem statement, proposed AI use case, expected outcomes with a measurement table, risks and dependencies with a severity/mitigation table, governance considerations (data sensitivity, compliance, human-in-the-loop, error risk), and a recommended decision checklist (approve, queue, decline, request more info).
```

---

## Commit Message Helper

```
Based on the changes I just made to this project (list your changes here), write 3 clear Git commit messages in imperative style that describe what was added or updated.
```
