# Problem Statement – SentinelAI

## 1. Background

Cloud environments generate security alerts from different services, workloads, identities, and infrastructure components. Security teams must review these alerts to identify suspicious activities, understand potential risks, and take appropriate remediation actions.

As cloud infrastructure grows, managing large volumes of security alerts becomes increasingly challenging.

## 2. Problem Definition

Cloud security teams often receive alerts from multiple cloud environments. These alerts differ in severity, accuracy, and business impact.

Security engineers may need to switch between different tools to investigate alerts, collect relevant information, identify affected resources, prioritize risks, and coordinate remediation.

Without a centralized and structured alert triage workflow:

- Critical security alerts may be overlooked among less important notifications.
- Investigation requires additional manual effort.
- Alert context and supporting evidence may be scattered across tools.
- Responsibility for remediation may be unclear.
- Investigation and resolution activities may not be documented consistently.

**Core Problem:** Cloud security teams need a centralized and structured way to prioritize, investigate, assign, and track security alerts from detection through resolution.

## 3. Target User Persona

**Persona:** Cloud Security Engineer

**Role:** Responsible for monitoring cloud security alerts, investigating suspicious activities, assessing risks, and coordinating remediation.

### Goals

- Identify critical security threats quickly.
- Understand affected cloud resources and potential impact.
- Prioritize alerts based on severity and risk.
- Assign remediation responsibilities.
- Track investigation progress and resolution.
- Maintain clear investigation records.

### Pain Points

- High volumes of security alerts.
- Difficulty identifying the most important alerts.
- Investigation context spread across multiple tools.
- Unclear ownership of remediation activities.
- Inconsistent tracking of investigation progress.

### User Needs

- A centralized alert dashboard.
- Clear severity and status indicators.
- Detailed alert investigation information.
- Recommended investigation and remediation steps.
- Assignment and resolution tracking.
- Investigation notes and activity history.

## 4. User Scenario

A Cloud Security Engineer receives a high-severity alert indicating suspicious activity involving a cloud resource.

The engineer opens the alert dashboard, reviews its severity and affected resource, and selects it for investigation.

The engineer examines the available evidence, assesses the potential impact, and identifies the necessary remediation steps.

The alert is assigned to the responsible engineer. After remediation, the engineer records the resolution details and updates the alert status to Resolved.

## 5. Expected Outcome

A centralized alert triage and resolution workflow can help security teams:

- Improve visibility into security alerts.
- Prioritize important alerts more effectively.
- Reduce unnecessary manual investigation effort.
- Establish clear remediation ownership.
- Improve tracking and documentation of security incidents.

## 6. Proposed Product

**SentinelAI – Cloud Security Alert Triage & Resolution Workflow**

SentinelAI proposes a centralized interface that supports the complete alert lifecycle:

**Detection → Triage → Investigation → Remediation → Resolution**

The proposed solution focuses on making alert investigation and resolution more organized, transparent, and trackable.