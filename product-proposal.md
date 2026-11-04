# Product Proposal – SentinelAI

## 1. Product Overview

**Product Name:** SentinelAI  
**Product Category:** Cloud Security Alert Triage and Resolution Workflow

SentinelAI is a proposed centralized workflow that helps cloud security engineers review, prioritize, investigate, assign, and resolve cloud security alerts.

The product focuses on improving alert visibility, reducing manual investigation effort, and providing structured remediation tracking.

## 2. Product Objectives

The primary objectives are:

- Help security engineers identify high-priority alerts.
- Provide relevant context for alert investigation.
- Establish clear ownership of remediation activities.
- Track alerts throughout their lifecycle.
- Maintain consistent investigation and resolution records.

## 3. Proposed Solution

SentinelAI provides three connected stages:

1. **Alert Dashboard:** Displays alerts with severity, affected resources, cloud provider, detection time, and current status.
2. **Investigation Workspace:** Provides alert details, supporting evidence, potential impact, and recommended investigation steps.
3. **Resolution Workflow:** Enables analyst assignment, remediation tracking, resolution notes, and alert closure.

## 4. Core User Journey

**Dashboard → Investigation → Resolution → Resolved**

### Screen 1: Alert Dashboard

**Purpose:** Help security engineers identify and prioritize alerts.

Key components:
- Total alert count.
- Critical and high-severity alert indicators.
- Investigation status summary.
- Alert table with affected resources and cloud providers.
- Search and filtering options.
- Alert investigation action.

**Product decision:** Severity and status are displayed prominently so engineers can identify important alerts without opening each record.

### Screen 2: Investigation Workspace

**Purpose:** Help engineers understand an alert before deciding how to respond.

Key components:
- Alert name and severity.
- Alert description and detection time.
- Affected cloud resource and provider.
- Supporting evidence and suspicious activity details.
- Potential impact.
- Recommended investigation steps.
- Assignment and investigation status.

**Product decision:** Relevant investigation context is brought together in one place to reduce unnecessary navigation between tools.

### Screen 3: Resolution Workflow

**Purpose:** Provide a structured process for tracking remediation and closing alerts.

Key components:
- Alert summary and severity.
- Assigned analyst.
- Remediation checklist.
- Resolution notes.
- Activity history.
- Status update and Mark as Resolved action.

**Product decision:** Resolution details and activity history create accountability and improve investigation documentation.

## 5. Feature Prioritization

Features are prioritized using a simple MoSCoW-inspired approach based on their importance to the core user journey.

| Priority | Features | Reason |
|---|---|---|
| P0 – Must Have | Alert dashboard, severity classification, investigation details, resolution workflow, status tracking | Essential to complete the alert lifecycle |
| P1 – Should Have | Search, filters, analyst assignment, investigation history | Improves usability and operational efficiency |
| P2 – Could Have | Automated remediation, advanced analytics | Adds capabilities after the core workflow is established |

## 6. Success Metrics

The following metrics can be used to evaluate the proposed product after implementation.

| Metric | What It Measures |
|---|---|
| Mean Time to Triage (MTTT) | Average time taken to review and prioritize an alert |
| Mean Time to Resolution (MTTR) | Average time taken to resolve an alert |
| Alert Resolution Rate | Percentage of alerts successfully resolved |
| Overdue Alert Rate | Percentage of alerts remaining unresolved beyond the defined target time |
| Investigation Completion Rate | Percentage of investigated alerts with documented outcomes |

These metrics provide a way to assess workflow efficiency, accountability, and resolution performance. Actual targets should be established using a baseline and operational requirements.

## 7. Assumptions and Scope

### Assumptions

- Security teams receive alerts from multiple cloud environments.
- Alert severity and affected-resource information are available for investigation.
- Security engineers are responsible for reviewing and coordinating remediation.
- A structured workflow can improve visibility and tracking.

### Initial Scope

The initial product concept focuses on alert review, investigation, assignment, and resolution tracking.

The prototype uses simulated alert data and demonstrates front-end workflow interactions only.

Live cloud integrations, automated threat detection, AI-driven analysis, and actual remediation execution are outside the current prototype scope.

## 8. Future Enhancements

Potential future improvements include:

- Integration with AWS, Azure, and Google Cloud security services.
- Automated alert enrichment and contextual risk scoring.
- Role-based access control.
- Notification and escalation workflows.
- AI-assisted investigation recommendations.
- Integration with incident management and ticketing platforms.

## 9. Expected Product Impact

SentinelAI aims to make cloud security alert management more organized and transparent by connecting alert prioritization, investigation, and resolution in one workflow.

The proposed approach can help security teams improve alert visibility, establish remediation ownership, and measure incident-handling efficiency.