# AI Opportunity Intake & Prioritization Workbench

**Owner:** Wes Shelton | [LinkedIn](https://www.linkedin.com/in/wallace-shelton-559b0364) | [Agent Showcase](https://automater89.github.io/Agent-Showcase/)

## What This Demonstrates

This project simulates how I would approach capturing, scoring, routing, and reporting on AI use case ideas in a real enterprise environment. It mirrors the kind of process-first, governance-aware work described in an AI Process Innovation role.

Instead of starting with a tool, I started with the process: Who submits ideas? What makes an idea worth pursuing? How do you route it? How does leadership see the pipeline?

## Problem

Organizations generate AI ideas informally — in meetings, emails, and hallway conversations. Without a structured intake, high-value ideas get lost and low-value ones consume engineering time. This workbench creates a repeatable, measurable intake process.

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Lists / SharePoint | Intake form and underlying data store |
| Power Automate | Routing, notifications, and approval logic |
| Power BI Desktop | Priority dashboard and reporting |
| Excel | Weighted scoring model and rubric |
| VS Code + GitHub Copilot | Documentation, scoring logic, and commit scaffolding |
| GitHub | Version control and portfolio documentation |

## Solution Overview

See [`docs/solution-overview.md`](docs/solution-overview.md) for full design.

## Folder Structure

```
ai-opportunity-intake-workbench/
├── README.md
├── docs/
│   ├── solution-overview.md
│   ├── field-dictionary.md
│   ├── scoring-model.md
│   ├── governance-notes.md
│   └── decision-brief-template.md
├── prompts/
│   └── copilot-prompts.md
├── screenshots/
│   └── (add SharePoint list, flow, and dashboard screenshots here)
└── exports/
    └── (add Excel scoring model and Power BI export here)
```

## What This Demonstrates for AI Process Innovation

- Structured requirements and intake design
- Governance and risk awareness before building
- KPI framing (value, risk, effort, readiness)
- Power Platform fluency (Lists, Power Automate, Power BI)
- Stakeholder-ready documentation and decision artifacts
- Measurable outcomes tied to business value, not just tool output
