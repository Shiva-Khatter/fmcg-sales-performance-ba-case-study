# FMCG Sales Performance & Distributor Analytics Platform

## Business Analysis Case Study

A self-directed Business Analysis case study focused on analysing a proposed FMCG sales performance and distributor analytics solution.

The case study demonstrates how a business problem can be translated into structured requirements, Agile user stories, process improvements, traceability, UAT scenarios, and dashboard design.

> **Note:** This is a self-directed portfolio project. All business scenarios, requirements, and data are synthetic/illustrative and do not represent a production implementation or actual client data.

---

## Business Problem

FMCG sales information may be maintained across multiple sources, making it difficult for managers to obtain a consistent and timely view of performance.

The proposed scenario focuses on challenges such as:

- Sales information distributed across multiple sources
- Manual consolidation and reporting
- Limited visibility into product and distributor performance
- Delayed identification of declining or underperforming entities
- Different stakeholders requiring different views of sales information

---

## Proposed Solution

The proposed **Sales Performance & Distributor Analytics Platform** is designed to centralize sales performance information and provide management with an interactive view of key performance indicators.

The solution includes:

- Centralized sales performance information
- KPI monitoring
- Region, product, distributor, and date filtering
- Sales trend analysis
- Product performance analysis
- Distributor performance analysis
- Regional-to-distributor drill-down
- Predefined sales exception detection
- Exception alerts
- Empty-state handling

---

## Business Analysis Approach

The project follows an end-to-end BA workflow:

**Business Problem → Business Requirements → Functional Requirements → User Stories → Acceptance Criteria → Process Analysis → Solution Design → UAT**

Requirements were organized and traced across the different stages to maintain consistency between business needs and proposed functionality.

---

## Key BA Deliverables

| Area | Deliverable |
|---|---|
| Requirements Analysis | Business & Functional Requirements |
| Agile Requirements | Epics, User Stories & Acceptance Criteria |
| Process Analysis | AS-IS / TO-BE Process |
| Solution Design | Solution Flow & Dashboard Wireframe |
| Traceability | Requirements Traceability Matrix |
| UAT | UAT Test Case Matrix |
| Analytics | Synthetic Sales Dataset & Power BI Dashboard |

---

## Agile & Jira

The proposed solution was organized into three functional epics:

### Sales Performance Dashboard
US-01 to US-05

### Performance Analysis
US-06 to US-07

### Exception Management
US-08 to US-10

Jira was used to structure the proposed backlog and organize the relationship between functional areas and user requirements.

---

## Process Analysis

The case study compares the current-state and proposed future-state processes.

### AS-IS

**Sales Data Sources → Multiple Files / Systems → Manual Consolidation → Manual Report Preparation → Manager Review → Issues Identified Late**

### TO-BE

**Sales Data Sources → Centralized Data Ingestion → Data Validation → KPI Calculation → Dashboard → Exception Detection → Alert Generated → Manager Action**

---

## Key KPIs

The proposed dashboard focuses on:

- **Total Sales**
- **Units Sold**
- **Target Achievement %**
- **Sales Growth %**

Example definitions:

**Target Achievement %**

`Actual Sales ÷ Assigned Target × 100`

**Sales Growth %**

`(Current Period Sales − Previous Comparable Period Sales) ÷ Previous Comparable Period Sales × 100`

---

## UAT

10 UAT scenarios were defined based on the documented user stories and acceptance criteria.

Coverage includes:

- KPI display
- Region filtering
- Product filtering
- Date filtering
- Sales trend analysis
- Distributor analysis
- Product analysis
- Exception detection
- Exception alerts
- No matching data / empty-state handling

The test matrix represents **planned UAT coverage**. Test execution has not been completed because this is a self-directed portfolio case study.

---

## Tools

- **Jira** — Agile backlog, epics, user stories and acceptance criteria
- **Microsoft Excel** — Requirements, traceability and UAT documentation
- **Microsoft Word** — BA documentation
- **Canva** — Process and solution visuals
- **Power BI** — Planned interactive analytics implementation

---

## Repository Structure

```text
01-Requirements/
02-Process-Analysis/
03-Agile-Jira/
04-Solution-Design/
05-UAT/
docs/
