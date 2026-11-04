# Cloud Security Alert Triage & Resolution

## Project Overview

SentinelAI is a proposed cloud security alert triage and resolution workflow designed to help cloud security teams identify, investigate, prioritize, and track security alerts through a centralized interface.

The product concept focuses on reducing manual investigation effort, improving alert prioritization, and providing a structured process for security incident resolution.

This project was developed as part of the AccuKnox Product Management Trainee assignment.

## Problem Statement

Cloud security teams receive numerous alerts from different cloud environments. These alerts vary in severity, accuracy, and potential business impact.

Security engineers often need to switch between tools to investigate alerts, understand affected resources, prioritize risks, and coordinate remediation.

Without a centralized and structured workflow, critical alerts may be overlooked, investigations may take longer, and remediation tracking may become inconsistent.

## Proposed Solution

SentinelAI proposes a centralized alert triage workflow that enables security engineers to:

- Review security alerts in one dashboard.
- Identify and prioritize critical and high-severity alerts.
- Investigate affected cloud resources and supporting evidence.
- Assign responsibility for remediation.
- Track investigation and resolution status.
- Maintain investigation notes and activity history.

## Key Features

### 1. Alert Dashboard
- Centralized alert overview.
- Severity-based classification.
- Search and filtering.
- Alert status tracking.
- Bulk actions and CSV export.

### 2. Alert Investigation
- Alert details and affected resource information.
- Investigation context and supporting evidence.
- Recommended investigation steps.
- Investigation status updates.

### 3. Resolution Workflow
- Assigned analyst information.
- Remediation checklist.
- Resolution notes.
- Activity history.
- Alert closure and status tracking.

## User Workflow

1. Security engineer reviews alerts on the dashboard.
2. Engineer selects an alert for investigation.
3. Engineer examines the available context and assesses its impact.
4. Engineer assigns and performs remediation activities.
5. Engineer records resolution details and updates the alert status.

**Workflow:** Dashboard → Investigation → Resolution → Resolved

## Target Persona

**Cloud Security Engineer**

Primary goals:
- Identify critical security threats.
- Understand affected cloud resources.
- Prioritize investigation activities.
- Coordinate remediation.
- Maintain investigation records.

## Feature Prioritization

| Priority | Features |
|---|---|
| P0 | Alert dashboard, severity classification, investigation details, resolution workflow, status tracking |
| P1 | Search, filters, analyst assignment, investigation history |
| P2 | Automated remediation, advanced analytics |

## Success Metrics

The proposed product can be evaluated using:

- Mean Time to Triage (MTTT).
- Mean Time to Resolution (MTTR).
- Alert Resolution Rate.
- Overdue Alert Rate.
- Investigation Completion Rate.

These are proposed success metrics, not measured product results.

## Technology Used

- HTML
- CSS
- JavaScript

## Running the Prototype

1. Clone or download this repository.
2. Open the `prototype` folder.
3. Open `index.html` in a web browser.
4. Explore the dashboard, alerts, investigation features, and available workflow interactions.

No backend setup is required for the demonstration prototype.

## Project Structure

```text
AccuKnox-Product-Management-Assignment/
├── README.md
├── problem-statement.md
├── product-proposal.md
├── prototype/
│   └── index.html
├── wireframes/
│   ├── screen-1-dashboard.png
│   ├── screen-2-investigation.png
│   └── screen-3-resolution.png
└── presentation/
    └── video-link.txt
```

## Prototype Disclaimer

This is a front-end demonstration prototype. Alert records, telemetry, investigation evidence, and workflow actions use simulated data. The prototype does not connect to live cloud environments, perform real security analysis, or execute actual remediation actions.

## Assignment

**Prepared for:** AccuKnox India Private Limited  
**Role:** Product Management Trainee  
**Project:** Cloud Security Alert Triage & Resolution Workflow
