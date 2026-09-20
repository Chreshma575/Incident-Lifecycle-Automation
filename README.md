# Incident Lifecycle Automation in ServiceNow

## Project Overview

**Incident Lifecycle Automation in ServiceNow** is a ServiceNow-based academic project focused on standardizing and automating the Incident Management lifecycle.

The project provides a structured process for creating, classifying, assigning, investigating, resolving, and documenting incidents while maintaining visibility of related records, Knowledge articles, changes, child incidents, and SLAs.

---

## Problem Statement

Incidents are often reported through different channels such as email, phone, or informal communication. This can result in:

- Inconsistent incident recording and classification
- Unclear ownership
- Delayed escalation and resolution
- Limited SLA visibility
- Manual coordination between support teams
- Difficulty tracking related records
- Difficulty managing change requests and child incidents

The project addresses these challenges through a structured Incident Management lifecycle in ServiceNow.

---

## Project Objectives

The project aims to:

- Standardize incident creation and classification.
- Capture appropriate incident information such as category, subcategory, urgency, service, and CI.
- Support Knowledge and Agent Assist for incident resolution.
- Assign and reassign incidents to appropriate support groups.
- Escalate incidents to Level 2 Support when required.
- Support Level 2 investigation and resolution.
- Create and link emergency change requests when required.
- Create and manage child incidents.
- Record incident cause and resolution information.
- Create Knowledge articles from resolved incidents.
- Track SLA information and incident activity.
- Validate related records and lifecycle activities.
- Improve visibility, consistency, ownership, and coordination in incident management.

---

## Incident Lifecycle

```text
Incident Creation
        ↓
Incident Classification
        ↓
Knowledge / Agent Assist
        ↓
Assignment / Reassignment
        ↓
Level 2 Investigation
        ↓
Resolution / Related Changes
        ↓
Child Incident Handling
        ↓
Incident Closure
        ↓
Knowledge Article Creation
        ↓
SLA and Final Validation
```

---

## Project Scope

The project covers the following areas:

1. Service and Service Offering setup
2. Incident creation
3. Incident classification
4. Knowledge and Agent Assist integration
5. Assignment and reassignment
6. Level 2 investigation and resolution
7. Emergency change creation
8. Child incident creation
9. Incident resolution and closure
10. Knowledge article creation
11. SLA and related-record validation
12. Testing and final validation

---

## Stakeholders

- **End Users** – Report IT issues and expect quick resolution and visibility.
- **Service Desk Agents** – Create, classify, assign, and manage incidents.
- **Level 2 Support** – Investigate and resolve incidents requiring advanced support.
- **Change Management Team** – Handle emergency changes related to incidents.
- **ServiceNow Administrator** – Maintain and manage the ServiceNow configuration.

---

## ServiceNow Components

The project uses the following ServiceNow capabilities:

- ServiceNow Incident Management
- Service Operations Workspace
- Knowledge Management
- Agent Assist
- Service Level Agreements (SLAs)
- Change Management
- Service
- Service Offering
- Configuration Items (CI)
- Incident Records
- Child Incidents
- Change Requests
- Knowledge Articles
- Activity and Work Notes
- Related Records

---

## Project Phases

### Phase 1 – Ideation Phase

This phase focuses on identifying the problem, understanding user needs, brainstorming ideas, and selecting the project concept.

**Documents:**

- Brainstorming and Idea Generation & Prioritization
- Problem Statement
- Empathy Map

---

### Phase 2 – Requirement Analysis

This phase defines the project requirements, user journey, data flow, user stories, and technology components.

**Documents:**

- Customer Journey Map
- Data Flow Diagrams and User Stories
- Solution Requirements
- Technology Stack

#### User Stories

The project contains **12 user stories (USN-1 to USN-12)** covering the Incident Management lifecycle.

| User Story | Description | Story Points |
|---|---|---:|
| USN-1 | Service and Service Offering Setup | 5 |
| USN-2 | Incident Creation | 5 |
| USN-3 | Incident Classification | 3 |
| USN-4 | Knowledge and Agent Assist | 5 |
| USN-5 | Assignment and Reassignment | 5 |
| USN-6 | Level 2 Incident Tracking | 3 |
| USN-7 | Emergency Change | 5 |
| USN-8 | Child Incident Management | 5 |
| USN-9 | Incident Resolution | 3 |
| USN-10 | Knowledge Creation | 5 |
| USN-11 | SLA and Related Record Validation | 5 |
| USN-12 | Testing and Final Validation | 2 |
| **Total** | | **51** |

---

### Phase 3 – Project Design

This phase defines the proposed solution and architecture for the Incident Lifecycle Automation project.

**Documents:**

- Problem–Solution Fit
- Proposed Solution
- Solution Architecture

---

### Phase 4 – Project Planning

This phase focuses on sprint planning, user stories, story point estimation, project scheduling, velocity, and progress tracking.

**Documents:**

- Planning Logic
- Project Planning

#### Sprint Planning

The project is planned across four sprints.

| Sprint | Story Points | Duration | Start Date | End Date |
|---|---:|---|---|---|
| Sprint-1 | 13 | 6 Days | 20 Aug 2026 | 25 Aug 2026 |
| Sprint-2 | 13 | 6 Days | 26 Aug 2026 | 31 Aug 2026 |
| Sprint-3 | 13 | 6 Days | 01 Sep 2026 | 06 Sep 2026 |
| Sprint-4 | 12 | 6 Days | 07 Sep 2026 | 12 Sep 2026 |

#### Planning Summary

- **Total Story Points:** 51
- **Number of Sprints:** 4
- **Velocity:** 12.75 Story Points/Sprint
- **Average Velocity per Day:** 2.125 Story Points/Day
- **Sprint Duration:** 6 Days

---

### Phase 5 – Project Development

This phase validates the ServiceNow Incident Management lifecycle through User Acceptance Testing.

**Document:**

- User Acceptance Testing

#### UAT Scope

The project includes User Acceptance Testing covering the complete Incident Management lifecycle.

- Service and Service Offering setup
- Incident creation
- Incident classification
- Knowledge and Agent Assist
- Assignment and reassignment
- Level 2 investigation and resolution
- Emergency change integration
- Child incident creation
- Cause and resolution documentation
- Knowledge article creation
- SLA and related-record validation
- End-to-end lifecycle validation

#### UAT Test Cases

The project contains **12 UAT test cases (TC-001 to TC-012)** covering the major project activities.

The UAT validates:

```text
Service Setup
      ↓
Incident Creation
      ↓
Classification
      ↓
Knowledge / Agent Assist
      ↓
Assignment / Reassignment
      ↓
Level 2 Investigation
      ↓
Emergency Change
      ↓
Child Incident
      ↓
Incident Resolution
      ↓
Knowledge Creation
      ↓
SLA / Related Records
      ↓
Final Validation

---

### Phase 6 – Project Documentation

This phase consolidates the complete project work into the final academic project report.

**Document:**

- Final Report

---

### Phase 7 – Project Demonstration

This phase demonstrates the completed Incident Lifecycle Automation in ServiceNow project.

**Document / File:**

- Project Demo Video

---

## Project Outcome

The project demonstrates a structured Incident Management lifecycle in ServiceNow.

The complete workflow supports:

- Standardized incident creation
- Incident classification
- Knowledge-assisted resolution
- Assignment and escalation
- Level 2 investigation
- Emergency change handling
- Child incident management
- Incident resolution
- Knowledge article creation
- SLA tracking
- Related-record validation
- Final lifecycle validation

---

## Conclusion

**Incident Lifecycle Automation in ServiceNow** provides a structured approach to managing IT incidents from creation to resolution.

By integrating Incident Management with Knowledge, Agent Assist, Change Management, child incidents, and SLA tracking, the project provides improved consistency, visibility, ownership, coordination, and documentation throughout the incident lifecycle.

---

## Repository Structure

```text
Incident-Lifecycle-Automation-in-ServiceNow/
│
├── Phase-1-Ideation-Phase/
│   ├── Brainstorming_Idea_Generation_and_Prioritization.docx
│   ├── Define_Problem_Statement.docx
│   ├── Empathy_Map.docx
│   └── README.md
│
├── Phase-2-Requirement-Analysis/
│   ├── Customer_Journey_Map.docx
│   ├── Data_Flow_Diagrams_and_User_Stories.docx
│   ├── Solution_Requirements.docx
│   ├── Technology_Stack.docx
│   └── README.md
│
├── Phase-3-Project-Design/
│   ├── Problem_Solution.docx
│   ├── Proposed_Solution.docx
│   ├── Solution_Architecture.docx
│   └── README.md
│
├── Phase-4-Project-Planning/
│   ├── Planning_Logic.docx
│   ├── Project_Planning.docx
│   └── README.md
│
├── Phase-5-Project-Development/
│   ├── User_Acceptance_Testing.docx
│   └── README.md
│
├── Phase-6-Project-Documentation/
│   ├── Final_Report.docx
│   └── README.md
│
├── Phase-7-Project-Demonstration/
│   ├── Project_Demo.mp4
│   └── README.md
│
└── README.md
```

---

## Project Information

**Project Name:** Incident Lifecycle Automation in ServiceNow

**Platform:** ServiceNow

**Total User Stories:** 12

**Total Story Points:** 51

**Number of Sprints:** 4

**Velocity:** 12.75 Story Points/Sprint

**UAT Test Cases:** 12

**Project Status:** Completed
