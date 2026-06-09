# Industrial Risk & Security Analytics Portfolio Roadmap

## Portfolio Theme

> Using data analytics to understand incidents, assess risk, and evaluate security controls in industrial and cyber-physical systems.

---

# Project 1: Industrial Risk Assessment Analytics

## Goal

Develop a data-driven platform that identifies, ranks, and visualizes operational risks in industrial environments.

---

## Objectives

- Analyze industrial/process datasets
- Identify operational risk indicators
- Develop risk scoring methodologies
- Visualize risk trends and priorities
- Support engineering decision-making

---

## Phase 1 — Risk Fundamentals

### Learn

- Risk Assessment Basics
- Risk Matrix Methodology
- Likelihood vs Consequence
- ALARP Principle
- Process Safety Fundamentals

### Deliverables

- Risk Framework Documentation
- Risk Categories
- Risk Scoring Criteria

### Timeline

1 Week

---

## Phase 2 — Excel Risk Register

### Learn

Excel Skills:

- IF()
- COUNTIF()
- COUNTIFS()
- SUMIF()
- SUMIFS()
- Conditional Formatting
- Pivot Tables

### Build

`industrial-risk-register.xlsx`

### Example Structure

| Equipment | Hazard | Likelihood | Consequence | Risk Score |
|------------|------------|------------|------------|------------|

### Example Formula

```excel
=Likelihood*Consequence
```

### Risk Classification

```excel
=IF(E2>=15,"High",
 IF(E2>=8,"Medium",
 "Low"))
```

### Timeline

1 Week

---

## Phase 3 — Dataset Exploration

### Tools

- Excel
- Python (Pandas)

### Tasks

- Missing Value Analysis
- Data Quality Assessment
- Trend Analysis
- Outlier Identification

### Deliverables

- EDA Workbook
- Exploratory Analysis Notebook

### Timeline

1 Week

---

## Phase 4 — Risk Indicator Development

### Examples

- Temperature Excursions
- Pressure Spikes
- Maintenance Delays
- Equipment Downtime

### Excel Functions

```excel
COUNTIFS()
SUMIFS()
AVERAGEIFS()
```

### Deliverables

- KPI Library
- KRI Library

### Timeline

1 Week

---

## Phase 5 — Python Automation

### Automate

- Risk Calculations
- KPI Generation
- Summary Reports

### Libraries

- Pandas
- NumPy
- OpenPyXL

### Timeline

1–2 Weeks

---

## Phase 6 — Dashboard Development

### Visualizations

- Risk Rankings
- Risk Heatmaps
- Trend Charts
- Summary Metrics

### Tools

- Streamlit
- Plotly

### Timeline

1–2 Weeks

---

## Final Deliverables

- Excel Risk Register
- Python Analytics Scripts
- Risk Dashboard
- Technical Documentation
- Portfolio Case Study

---

## Skills Gained

- Risk Assessment
- Process Safety
- Data Analytics
- Dashboard Development
- Engineering Decision Making

---

# Project 2: Security Control Effectiveness Dashboard

## Goal

Evaluate and visualize how effectively security controls reduce organizational risk.

---

## Objectives

- Measure control effectiveness
- Develop governance metrics
- Assess risk reduction
- Visualize compliance posture
- Support security decision-making

---

## Phase 1 — GRC Foundations

### Learn

- NIST Cybersecurity Framework
- CIS Controls
- ISO 27001 Fundamentals
- Risk Management Concepts

### Deliverables

- Security Control Catalog
- Framework Mapping Notes

### Timeline

1 Week

---

## Phase 2 — Excel Control Inventory

### Build

`security-control-inventory.xlsx`

### Example Structure

| Control | Coverage | Compliance | Status |
|----------|----------|----------|----------|

### Example Formula

```excel
=IF(B2>=90,"Effective",
 IF(B2>=70,"Moderate",
 "Weak"))
```

### Timeline

1 Week

---

## Phase 3 — Security Metrics Development

### Metrics

- Patch Compliance
- MFA Coverage
- Vulnerability Closure Rate
- Incident Frequency
- Asset Coverage

### Excel Functions

```excel
COUNTIF()
COUNTIFS()
AVERAGE()
SUMIFS()
```

### Deliverables

- KPI Library
- KRI Library

### Timeline

1 Week

---

## Phase 4 — Risk-Control Mapping

### Build

`risk-control-matrix.xlsx`

### Example

```text
Risk
 ↓
Control
 ↓
Mitigation Effectiveness
```

### Deliverables

- Risk-Control Matrix
- Control Coverage Assessment

### Timeline

1 Week

---

## Phase 5 — Python Analytics

### Automate

- Compliance Calculations
- Trend Reporting
- Control Scoring
- Risk Metrics

### Libraries

- Pandas
- NumPy
- OpenPyXL

### Timeline

1–2 Weeks

---

## Phase 6 — Dashboard Development

### Visualizations

- Compliance Trends
- Control Effectiveness
- Risk Scorecards
- Gap Analysis

### Tools

- Streamlit
- Plotly

### Timeline

1–2 Weeks

---

## Phase 7 — Recommendations

### Generate

- Weakest Controls
- Missing Controls
- Improvement Priorities

### Deliverables

- Security Posture Report
- Governance Dashboard
- Portfolio Documentation

### Timeline

1 Week

---

## Final Deliverables

- Excel Control Inventory
- Risk-Control Matrix
- Governance Dashboard
- Security Analytics Report
- Portfolio Case Study

---

## Skills Gained

- Governance
- Risk Management
- Compliance Analytics
- Dashboard Design
- Security Metrics

---

# Project 3: Cyber-Physical Incident Analysis Repository

## Goal

Build a searchable repository of industrial and cybersecurity incidents and extract lessons learned through analytics.

---

## Objectives

- Document cyber-physical incidents
- Identify recurring causes
- Analyze failed controls
- Discover risk patterns
- Build a lessons-learned knowledge base

---

## Phase 1 — Incident Collection

### Engineering Incidents

- Bhopal
- Texas City Refinery
- Deepwater Horizon

### Cyber Incidents

- Stuxnet
- Triton
- Colonial Pipeline
- Ukraine Power Grid Attack

### Deliverable

`incident_repository.xlsx`

### Timeline

1–2 Weeks

---

## Phase 2 — Incident Classification

### Example Structure

| Incident | Industry | Cause | Severity | Control Failure |
|------------|------------|------------|------------|------------|

### Fields

- Date
- Industry
- Location
- Incident Type
- Root Cause
- Impact
- Controls Failed
- Lessons Learned

### Timeline

1 Week

---

## Phase 3 — Excel Analytics

### Questions

- Most common causes?
- Most affected industries?
- Most frequent control failures?
- Most severe incident types?

### Excel Tools

```excel
COUNTIF()
COUNTIFS()
SUMIFS()
Pivot Tables
Conditional Formatting
```

### Timeline

1 Week

---

## Phase 4 — Root Cause Analysis

### Categories

- Human Error
- Technical Failure
- Cyber Attack
- Management Failure
- Procedural Failure

### Deliverables

- Root Cause Taxonomy
- Incident Categorization Framework

### Timeline

1 Week

---

## Phase 5 — Python Enhancement

### Automate

- Incident Statistics
- Trend Analysis
- Summary Reports
- Visualization

### Libraries

- Pandas
- Matplotlib
- Plotly

### Timeline

1–2 Weeks

---

## Phase 6 — Searchable Repository

### Features

- Search
- Filtering
- Timelines
- Analytics Dashboard

### Tools

- SQLite
- Streamlit

### Timeline

1–2 Weeks

---

## Phase 7 — Lessons Learned Engine

### Generate

- Common Failure Patterns
- Repeated Control Failures
- Preventive Recommendations

### Deliverables

- Knowledge Base
- Lessons Learned Database

### Timeline

1 Week

---

## Final Deliverables

- Incident Repository
- Analytics Dashboard
- Searchable Database
- Lessons Learned Knowledge Base
- Portfolio Case Study

---

## Skills Gained

- Root Cause Analysis
- Incident Investigation
- Process Safety
- Cybersecurity
- Risk Management
- Research Methodology

---

# Common Tool Stack

## Excel

### Core Functions

```excel
IF()
COUNTIF()
COUNTIFS()
SUMIF()
SUMIFS()
AVERAGE()
AVERAGEIFS()
```

### Intermediate

```excel
XLOOKUP()
INDEX()
MATCH()
```

### Analytics

- Pivot Tables
- Conditional Formatting
- Charts
- Data Validation

### Advanced (Optional)

- Power Query
- Power Pivot

---

## Python

### Core Libraries

```text
Pandas
NumPy
OpenPyXL
```

### Visualization

```text
Matplotlib
Plotly
```

### Dashboarding

```text
Streamlit
```

---

## Documentation

### Obsidian

For:

- Research Notes
- Risk Notes
- Incident Notes
- Project Planning

### Zotero

For:

- References
- Papers
- Citations

---

# Recommended Build Order

## Phase 1 (Fastest Start)

Cyber-Physical Incident Analysis Repository

Reason:
- Research-heavy
- Low technical barrier
- Builds domain knowledge

Timeline:
1–2 Months

---

## Phase 2

Industrial Risk Assessment Analytics

Reason:
- Builds on lessons learned from incidents
- Strong ChE + Analytics alignment

Timeline:
1–2 Months

---

## Phase 3

Security Control Effectiveness Dashboard

Reason:
- Most GRC-focused
- Benefits from previous risk and incident knowledge

Timeline:
2–3 Months

---

# Career Alignment

These projects align strongly with:

- Chemical Engineering
- Data Analytics Engineering
- Risk Analysis
- Governance, Risk & Compliance (GRC)
- Industrial Cybersecurity
- Process Safety
- Security Fundamentals

and intentionally minimize reliance on:

- Deep Learning
- Advanced Machine Learning
- Complex Process Modeling
- SOC-centric workflows

while emphasizing:

```text
Data Collection
        ↓
Data Cleaning
        ↓
Excel Analysis
        ↓
Python Automation
        ↓
Interpretation
        ↓
Risk-Based Decisions
```