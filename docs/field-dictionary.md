# Intake Field Dictionary

This document defines every field in the AI Opportunity intake form, its purpose, type, whether it is required, and a sample value.

| Field Name | Purpose | Type | Required | Example Value |
|---|---|---|---|---|
| Idea Title | Short name for the opportunity | Single line text | Yes | Automate vendor invoice exception routing |
| Business Area | Department or function submitting | Choice (HR, IT, Legal, Finance, Ops, Other) | Yes | Finance |
| Process Pain | What currently goes wrong or takes too long | Multi-line text | Yes | Invoice exceptions are emailed manually, no tracking, delays up to 5 days |
| Frequency | How often the pain occurs | Choice (Daily / Weekly / Monthly / Ad hoc) | Yes | Daily |
| Estimated Time Impact | Rough hours saved per week if solved | Number | No | 6 |
| Stakeholder Owner | Who owns the process today | Single line text | Yes | Controller, Finance |
| Systems Involved | Tools or platforms touched by this process | Multi-line text | No | SAP, Outlook, SharePoint |
| Data Sensitivity | Does the process involve PII, financial, or legal data? | Choice (Low / Medium / High) | Yes | High |
| Desired Outcome | What does success look like? | Multi-line text | Yes | Exceptions auto-routed to correct approver within 1 hour, full audit trail |
| Status | Current state in the pipeline | Choice (New / Under Review / Approved / Declined / In Progress / Complete) | Auto | New |
| Priority Score Band | Auto-calculated from scoring model | Choice (High / Medium / Low) | Auto | High |
| Reviewer Assigned | Set by routing flow | Person | Auto | |
| Submission Date | Auto-stamped | Date | Auto | |
