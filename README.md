# 31-weeks Comprehensive GRC-Training-Syllabus
Updated GRC Training Syllabus from beginner to professional
# GRC Mastery Program — 31-Weeks Expanded Syllabus

**Expanded from the original 45-Day / 7-Week GRC Mastery Program**
*Structured-only document — content for each week is developed separately.*

> **Coverage note:** This expansion is built directly from all 21 session decks supplied, covering the complete original program (Weeks 1–7, Days 1–45). Day 45 (Interview Prep & 90-Day Plan) has now been added as **Week 31**, appended after the original Week 30 without renumbering or altering any of Weeks 1–30.

---

## 1. Why 31 Weeks — Expansion Logic

The original program packed 21 sessions into 7 weeks (roughly 3 sessions/week, 1.5–2 hours each) — efficient for a bootcamp, but too dense for building real technical fluency in frameworks, regulations, and hands-on artifacts. The 31-week version keeps **every original topic, in its original order**, and gives each one room to breathe: most single sessions become 1–2 full weeks, with the extra time spent on technical depth (control catalog structure, protocol-level detail, worked numerical examples, current standard versions) rather than new subject matter.

| Original Week | Original Theme | Sessions | Expanded Into | New Weeks |
|---|---|---|---|---|
| Week 1 | GRC Foundations | 3 (A, B, C) | Phase I | Weeks 1–4 |
| Week 2 | Cybersecurity Risk Management | 3 (A, B, C) | Phase II | Weeks 5–9 |
| Week 3 | Compliance Frameworks & Regulatory Requirements | 3 (A, B, C) | Phase III | Weeks 10–14 |
| Week 4 | Audits, Assessments & Reporting | 3 (A, B, C) | Phase IV | Weeks 15–18 |
| Week 5 | Asset & Identity Management | 3 (A, B, C) | Phase V | Weeks 19–22 |
| Week 6 | Protect / Respond / Recover Operations | 3 (A, B, C) | Phase VI | Weeks 23–27 |
| Week 7 | Capstone & Career (Days 43–45) | 3 (Day 43, Day 44, Day 45) | Phase VII | Weeks 28–31 |

**Total: 31 weeks, 7 phases, zero new topic domains introduced** — only deeper technical treatment of what the original program already covers.

---

## 2. Roadmap at a Glance

```mermaid
flowchart LR
    subgraph P1["Phase I · Wks 1-4<br/>Foundations & Frameworks"]
        direction TB
        A1[Wk1 GRC Vocabulary & CIA Triad]
        A2[Wk2 Governance Structures]
        A3[Wk3 NIST CSF 2.0 & 800-53]
        A4[Wk4 ISO 27001 · CIS v8.1 · SOC 2 · COBIT]
    end
    subgraph P2["Phase II · Wks 5-9<br/>Risk Management"]
        direction TB
        B1[Wk5 Risk Fundamentals]
        B2[Wk6 Qualitative Assessment]
        B3[Wk7 Quantitative Assessment / FAIR]
        B4[Wk8 Treatment & Control Selection]
        B5[Wk9 Risk Register & Monitoring]
    end
    subgraph P3["Phase III · Wks 10-14<br/>Compliance & Regulation"]
        direction TB
        C1[Wk10 Control Frameworks Deep Dive]
        C2[Wk11 GDPR & CCPA/CPRA]
        C3[Wk12 HIPAA & GLBA]
        C4[Wk13 SOX & PCI DSS v4.0.1]
        C5[Wk14 Mapping & Gap Assessment]
    end
    subgraph P4["Phase IV · Wks 15-18<br/>Audits & Reporting"]
        direction TB
        D1[Wk15 Audit Fundamentals]
        D2[Wk16 Findings & Evidence]
        D3[Wk17 Remediation & Reporting]
        D4[Wk18 Mock Audit Practicum]
    end
    subgraph P5["Phase V · Wks 19-22<br/>Asset & Identity"]
        direction TB
        E1[Wk19 Asset Management]
        E2[Wk20 IAM Core Concepts]
        E3[Wk21 IAM Protocols & PAM]
        E4[Wk22 IAM Lifecycle & Governance]
    end
    subgraph P6["Phase VI · Wks 23-27<br/>Protect/Respond/Recover"]
        direction TB
        F1[Wk23 Security Awareness]
        F2[Wk24 DLP]
        F3[Wk25 Incident Response Foundations]
        F4[Wk26 IR Runbooks & Tabletop]
        F5[Wk27 Third-Party Risk]
    end
    subgraph P7["Phase VII · Wks 28-31<br/>Capstone & Career"]
        direction TB
        G1[Wk28 Capstone Build I]
        G2[Wk29 Capstone Build II]
        G3[Wk30 Career Launch]
        G4[Wk31 Interview Prep & 90-Day Plan]
    end
    P1 --> P2 --> P3 --> P4 --> P5 --> P6 --> P7
```

---

## 3. Continuity Threads (carried through all 31 weeks)

| Thread | Detail |
|---|---|
| **Case-study companies** | MarketNest (E-commerce) · Quanta Labs (B2B SaaS) · PayFlow (Fintech) · NovaCare Health (Healthcare) · Helios Grid Utilities (Energy/OT) · NDSA (Government) |
| **Anchor framework** | NIST CSF 2.0's six Functions — GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, RECOVER — used throughout as the organizing spine, exactly as in the original program |
| **Capstone build-up** | Every phase now produces one artifact that feeds directly into the Week 28–29 "GRC Program in a Box" |

---

## 4. Phase I — GRC Foundations & the Framework Landscape (Weeks 1–4)
*Original lineage: Week 1, Sessions A–C*

### Week 1 — GRC Vocabulary, the CIA Triad & Policy Hierarchy
- Governance, Risk, and Compliance as one integrated discipline (not three silos)
- The CIA Triad — Confidentiality, Integrity, Availability — as the objective behind every control
- Policy hierarchy: Policy → Standard → Procedure → Guideline
- What a GRC analyst actually does day to day
- Program orientation: introduce all six case-study companies
- **Artifact:** GRC glossary + policy hierarchy map for one case-study company

### Week 2 — Governance Structures: Three Lines Model & Accountability
- The IIA Three Lines Model (2020 revision of the "Three Lines of Defense")
- Roles and RACI: Board/Audit Committee, CISO, GRC analyst, risk owner, control owner, internal/external auditor
- Security governance charters, escalation paths, reporting cadence
- **Artifact:** RACI matrix + governance charter draft

### Week 3 — Framework Landscape I: NIST CSF 2.0 & NIST SP 800-53
- NIST CSF 2.0 (finalized February 26, 2024): the six Functions, their Categories and Subcategories
- Why "Govern" was added as a standalone Function in 2.0 (previously implicit across the other five)
- NIST SP 800-53 Rev. 5 control catalog: control families, impact baselines (Low/Moderate/High), control enhancements
- Mapping CSF Functions to 800-53 control families
- **Artifact:** CSF 2.0 Function/Category primer sheet

### Week 4 — Framework Landscape II: ISO/IEC 27001:2022, CIS Controls v8.1, SOC 2 & COBIT 2019
- ISO/IEC 27001:2022 ISMS structure; Annex A's 93 controls across 4 themes (Organizational, People, Physical, Technological)
- CIS Controls v8.1 (June 2024 update): 18 Controls, 153 Safeguards, 3 Implementation Groups, mapped to CSF 2.0
- SOC 2 Trust Services Criteria: Security, Availability, Processing Integrity, Confidentiality, Privacy
- COBIT 2019 governance vs. management objectives
- **Artifact:** One-page framework comparison chart (seeds the Week 14 crosswalk)

---

## 5. Phase II — Cybersecurity Risk Management (Weeks 5–9)
*Original lineage: Week 2, Sessions A–C*

### Week 5 — Risk Fundamentals & Governing Standards
- Vocabulary: asset, threat, vulnerability, likelihood, impact
- The risk equation: Risk = f(Likelihood × Impact)
- Inherent vs. residual risk; risk appetite vs. risk tolerance
- The risk lifecycle: Frame → Assess → Respond → Monitor
- Governing standards: NIST SP 800-39, NIST SP 800-37 Rev. 2 (Risk Management Framework), ISO 31000:2018

### Week 6 — Qualitative Risk Assessment
- Qualitative vs. quantitative assessment — when to use each
- Building consistent 1–5 likelihood/impact rating scales
- Constructing and reading a risk matrix / heat map
- **Artifact:** Qualitative risk assessment for one case-study company

### Week 7 — Quantitative Risk Assessment
- SLE = Asset Value × Exposure Factor; ALE = SLE × Annualized Rate of Occurrence
- Full worked numerical example
- Introduction to Factor Analysis of Information Risk (FAIR — an Open Group risk-quantification standard) as a deeper model
- Scoring and prioritization: turning numbers into an action order
- **Artifact:** Quantitative loss-exposure worksheet

### Week 8 — Risk Treatment & Control Selection
- Four treatment options: Avoid, Mitigate, Transfer, Accept
- Choosing a treatment that drives residual risk into appetite
- Control types — preventive, detective, corrective, compensating — with framework mapping
- **Artifact:** Treatment decision memo with control mapping

### Week 9 — The Risk Register & Continuous Monitoring
- Anatomy of a risk register; building a full 10-risk register
- Embedding a quantitative (SLE/ALE) entry inside the register
- Maintenance cadence, ownership, and Key Risk Indicators (KRIs)
- Scenario exercise and self-check
- **Artifact:** Completed 10-risk register for a case-study company

---

## 6. Phase III — Compliance Frameworks & Regulatory Requirements (Weeks 10–14)
*Original lineage: Week 3, Sessions A–C*

### Week 10 — Control Frameworks in Depth
- Revisiting NIST CSF 2.0, SP 800-53 Rev. 5, ISO/IEC 27001:2022, CIS Controls v8.1, SOC 2, COBIT 2019 side by side
- Comparing catalog structures: control families vs. Annex A domains vs. Trust Services Criteria vs. COBIT objectives
- Where each framework is actually used (federal, commercial, service-provider assurance)

### Week 11 — Data Privacy Regulations: GDPR & CCPA/CPRA
- EU General Data Protection Regulation (Regulation (EU) 2016/679): scope, data-subject rights, lawful bases, penalties (up to 4% of global annual turnover)
- California Consumer Privacy Act / California Privacy Rights Act (CCPA/CPRA): consumer rights, applicability thresholds
- **Artifact:** Applicability & obligations matrix

### Week 12 — Sector-Specific Regulations: HIPAA & GLBA
- HIPAA: covered entities, Privacy Rule, Security Rule (45 CFR §164.308), Protected Health Information, breach notification
- Gramm-Leach-Bliley Act (GLBA) Safeguards Rule for financial institutions
- **Artifact:** Sector-applicability memo across two case-study companies

### Week 13 — Financial & Payment Regulations: SOX & PCI DSS v4.0.1
- Sarbanes-Oxley Act Section 404: internal control over financial reporting, management assessment, external audit
- PCI DSS v4.0.1 — the current baseline standard: 12 requirements across 6 control objectives; the 51 previously future-dated requirements became fully mandatory March 31, 2025
- **Artifact:** Regulation-to-control crosswalk entry

### Week 14 — Mapping & Gap Assessment
- Control crosswalks: mapping one control to many frameworks
- Comparison matrix: NIST CSF 2.0 vs. ISO/IEC 27001:2022 vs. CIS Controls v8.1
- Hands-on gap assessment: current vs. required state, scored across 10 CSF 2.0 subcategories (fintech case)
- Gap scoring methodology and remediation roadmap
- **Artifact:** Full gap assessment + remediation roadmap for PayFlow

---

## 7. Phase IV — Audits, Assessments & Reporting (Weeks 15–18)
*Original lineage: Week 4, Sessions A–C (Days 22–28)*

### Week 15 — Audit Fundamentals
- Internal vs. external audits; 1st-, 2nd-, and 3rd-party audits
- Distinguishing a compliance audit, a risk assessment, and a penetration test
- The full audit lifecycle: scoping → fieldwork → reporting → follow-up
- Four evidence-gathering methods: inquiry, observation, inspection, re-performance
- **Artifact:** Realistic audit scope document

### Week 16 — Findings & Evidence
- Writing a defensible finding with the 5 C's: Condition, Criteria, Cause, Consequence, Recommendation
- Rating findings by severity and underlying risk
- Working papers and the audit trail
- **Artifact:** Three written findings from case-study evidence (MarketNest, Quanta Labs)

### Week 17 — Remediation Planning & Audit Reporting
- Designing a realistic, risk-based remediation timeline
- Structuring a professional audit report end to end
- Executive summary, scope/methodology, findings, recommendations sections
- Adapting the same findings for technical vs. executive audiences
- **Artifact:** Remediation plan + draft report sections

### Week 18 — Full Mock Audit Practicum
- End-to-end mock audit of NovaCare Health, scope through management response
- Peer review and quality-control pass on the final report
- **Artifact:** Complete audit report package

---

## 8. Phase V — Asset Management & Identity Governance (Weeks 19–22)
*Original lineage: Week 5, Sessions A–C*

### Week 19 — Asset Management
- NIST CSF 2.0 IDENTIFY function, Asset Management category (ID.AM)
- Inventory, classification, and lifecycle management
- Shadow IT, unmanaged endpoints, and forgotten cloud services as real attacker entry points
- **Artifact:** Asset inventory + classification scheme

### Week 20 — IAM Core Concepts
- AAA: Authentication, Authorization, Accounting
- Principle of least privilege
- Access control models: DAC, MAC, RBAC, ABAC
- MFA and Privileged Access Management (PAM) fundamentals
- **Artifact:** Access-model recommendation memo

### Week 21 — IAM Technical Protocols & Privileged Access
*(Technical deepening of Week 5-Session B — same topic, protocol-level detail)*
- Single sign-on (SSO) concepts; SAML 2.0, OAuth 2.0, and OpenID Connect (OIDC) at a working level
- Privileged Access Management mechanics: credential vaulting, session recording, just-in-time access
- **Artifact:** IAM technical control diagram

### Week 22 — IAM Lifecycle & Governance
- Joiner-Mover-Leaver (JML); privilege creep at the "Mover" stage
- Access reviews and recertification cadence
- Identity governance and common IAM audit findings
- **Artifact:** JML workflow + access-review checklist

---

## 9. Phase VI — Protect, Respond & Recover Operations (Weeks 23–27)
*Original lineage: Week 6, Sessions A–C*

### Week 23 — Security Awareness & Human Risk
- The human element as the leading factor in breaches
- PayFlow case: scaling headcount from 8 to 45 staff with no security policy or training, leading to an exposed API key on public GitHub
- Awareness program design: onboarding, phishing simulation, metrics

### Week 24 — Data Loss Prevention (DLP)
*(Splits the original combined Awareness + DLP session into two full weeks)*
- DLP architecture across endpoint, network, email, and cloud channels
- Classification-driven policy design
- **Artifact:** DLP policy outline mapped to data classification

### Week 25 — Incident Response Foundations
- The legacy NIST SP 800-61 Rev. 2 four-phase model (Preparation; Detection & Analysis; Containment, Eradication & Recovery; Post-Incident Activity) — still the reference point for the SANS PICERL model widely used in practice
- NIST SP 800-61 Rev. 3 (finalized April 2025): incident response reframed as a NIST CSF 2.0 Community Profile spanning all six Functions, replacing the earlier fixed-lifecycle diagram — an important update for anyone certifying against current NIST guidance
- NovaCare Health & MarketNest incident cases

### Week 26 — IR Runbooks, Communication & Tabletop Exercises
- Building practical, repeatable runbooks
- Regulatory breach-notification timing (ties back to GDPR/HIPAA from Phase III)
- Tabletop exercise simulation
- **Artifact:** One completed IR runbook + tabletop exercise write-up

### Week 27 — Third-Party / Vendor Risk Management
- Vendor risk lifecycle: onboarding, due-diligence questionnaires, contractual controls
- Reviewing a SOC 2 report as vendor assurance evidence
- Ongoing monitoring; Helios Grid Utilities OT/vendor case (public-safety dimension of vendor risk)
- **Artifact:** Vendor risk assessment for one case-study vendor relationship

---

## 10. Phase VII — Capstone, Portfolio & Career Launch (Weeks 28–31)
*Original lineage: Week 7, Days 43–45*

### Week 28 — Capstone Program Build I: GOVERN & IDENTIFY
- Assembling Phase I–II artifacts (governance charter, framework crosswalk, risk register) into one program
- Initial maturity scoring against the GOVERN and IDENTIFY functions

### Week 29 — Capstone Program Build II: PROTECT, DETECT, RESPOND, RECOVER
- Assembling remaining artifacts (controls, audit findings, IAM program, IR runbook, vendor risk assessment)
- Full six-Function maturity assessment and executive summary
- Completed "GRC Program in a Box," mapped end-to-end to all six NIST CSF 2.0 Functions

### Week 30 — GRC Career Launch
- Five common entry routes into GRC; matching capstone evidence to a route
- Selecting one target certification aligned to route and budget
- Translating each weekly deliverable into a résumé bullet (verb + object + result)
- LinkedIn profile optimization and public portfolio publishing

### Week 31 — Interview Prep & the 90-Day Post-Course Plan
*(New — incorporates Day 45, the final session of the original program)*
- The four-stage structure of a real GRC interview: recruiter screen → hiring manager → technical/scenario round → stakeholder/panel round → candidate questions
- The artifact-backed answer framework: Situation → Task → Action → Result → **Evidence close** (naming the actual deliverable you can share)
- Rehearsing the "core four" GRC interview questions against named case-study evidence:
  - Walking through a full risk assessment (NDSA scenario)
  - Handling a failing audit control with the 5 C's (MarketNest scenario)
  - Explaining least privilege with implementation proof (NovaCare Health, Quanta Labs, NDSA scenarios)
  - Vetting a SaaS vendor end to end (MarketNest scenario)
- Rapid-fire question bank and the interview-question-to-portfolio-artifact map
- Mock-interview and scenario-simulation practice across all six case-study companies, plus handling pressure and unanswerable follow-ups honestly
- Building the dated **90-day post-course plan**: one certification (booked), one real project, a sustainable weekly study/application cadence, and a weekly review discipline
- Final program self-check across all six NIST CSF 2.0 Functions (Govern, Identify, Protect, Detect, Respond, Recover)
- **Artifact:** Final submission package — published portfolio (all capstone artifacts, versioned and dated), updated résumé and LinkedIn profile, and a one-page dated 90-day plan with a named accountability partner

---

## 11. Standards & Facts Referenced (verification notes)

| Standard / Regulation | Key fact used in this syllabus | Source basis |
|---|---|---|
| NIST CSF 2.0 | Released February 26, 2024; added "Govern" as a sixth Function | NIST / multiple legal & industry trackers |
| NIST SP 800-61 | Rev. 2 (four-phase model) formally withdrawn; Rev. 3 finalized April 2025, reframing IR as a CSF 2.0 Community Profile | NIST CSRC publication record |
| CIS Controls | v8.1 released June 2024: 18 Controls, 153 Safeguards, added Govern-aligned mapping to CSF 2.0 | Center for Internet Security |
| PCI DSS | v4.0.1 (June 2024 clarification release of v4.0, March 2022); all future-dated requirements became mandatory March 31, 2025 | PCI Security Standards Council |
| ISO/IEC 27001:2022 | Annex A restructured into 93 controls across 4 themes | ISO/IEC |

*(This table intentionally stays high-level — full source citations belong in each week's developed content, not in the syllabus skeleton.)*

---

## 12. Summary Table — All 31 Weeks

| Wk | Phase | Title | Original Lineage |
|---|---|---|---|
| 1 | I | GRC Vocabulary, CIA Triad & Policy Hierarchy | W1-A |
| 2 | I | Governance Structures: Three Lines Model | W1-B |
| 3 | I | Framework Landscape I: CSF 2.0 & SP 800-53 | W1-C |
| 4 | I | Framework Landscape II: ISO 27001, CIS v8.1, SOC 2, COBIT | W1-C |
| 5 | II | Risk Fundamentals & Governing Standards | W2-A |
| 6 | II | Qualitative Risk Assessment | W2-B |
| 7 | II | Quantitative Risk Assessment / FAIR | W2-B |
| 8 | II | Risk Treatment & Control Selection | W2-C |
| 9 | II | Risk Register & Continuous Monitoring | W2-C |
| 10 | III | Control Frameworks in Depth | W3-A |
| 11 | III | GDPR & CCPA/CPRA | W3-B |
| 12 | III | HIPAA & GLBA | W3-B |
| 13 | III | SOX & PCI DSS v4.0.1 | W3-B |
| 14 | III | Mapping & Gap Assessment | W3-C |
| 15 | IV | Audit Fundamentals | W4-A |
| 16 | IV | Findings & Evidence | W4-B |
| 17 | IV | Remediation Planning & Audit Reporting | W4-C |
| 18 | IV | Full Mock Audit Practicum | W4-C |
| 19 | V | Asset Management | W5-A |
| 20 | V | IAM Core Concepts | W5-B |
| 21 | V | IAM Technical Protocols & PAM | W5-B (extension) |
| 22 | V | IAM Lifecycle & Governance | W5-C |
| 23 | VI | Security Awareness & Human Risk | W6-A |
| 24 | VI | Data Loss Prevention | W6-A |
| 25 | VI | Incident Response Foundations | W6-B |
| 26 | VI | IR Runbooks & Tabletop Exercises | W6-B |
| 27 | VI | Third-Party / Vendor Risk Management | W6-C |
| 28 | VII | Capstone Build I: GOVERN & IDENTIFY | W7-Day43 |
| 29 | VII | Capstone Build II: PROTECT–RECOVER | W7-Day43 |
| 30 | VII | GRC Career Launch | W7-Day44 |
| 31 | VII | Interview Prep & 90-Day Post-Course Plan | W7-Day45 |
