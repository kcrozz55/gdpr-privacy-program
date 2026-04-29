# GDPR Privacy Program

**Organization:** MedCore Health Systems
**Regulation:** EU General Data Protection Regulation (GDPR) — Regulation (EU) 2016/679
**Applicability:** MedCore receives referral data and engages clinical research partners in the EU/EEA
**Role under GDPR:** Data Controller (for EU/EEA patient and research partner data)
**DPO:** Dr. Rachel Feinberg, Privacy Officer (serving as de facto DPO)
**Status:** Program Implemented | Annual DPIA Complete | RoPA Current
**Last Updated:** April 2026

---

## Overview

MedCore Health Systems maintains a GDPR compliance program to address its obligations when processing personal data of individuals located in the European Union and European Economic Area. MedCore's GDPR exposure arises from:

1. **International clinical research partnerships** — MedCore participates in multi-center clinical studies with EU-based research institutions
2. **EU patient referrals** — Occasional international patients referred from EU-based physicians and clinics
3. **EU-based vendor relationships** — SaaS vendors and subprocessors processing MedCore data from EU infrastructure

While HIPAA remains MedCore's primary privacy framework, GDPR obligations are maintained in parallel for in-scope data subjects.

---

## GDPR Compliance Program Structure

| Component | Description | Status |
|-----------|-------------|--------|
| Lawful Basis Determination | Documented legal basis for each processing activity | Complete |
| Record of Processing Activities (RoPA) | Comprehensive register of all processing activities | Complete and Current |
| Data Protection Impact Assessments (DPIAs) | Risk assessments for high-risk processing | Annual DPIA Complete |
| Data Subject Rights Procedures | Processes for handling DSR requests | Implemented |
| Privacy Notices | GDPR-compliant notices for EU data subjects | Published |
| Data Breach Notification | 72-hour notification procedures to supervisory authority | Documented |
| International Data Transfers | SCCs and adequacy decisions documented | Current |
| Subprocessor Management | Register of all subprocessors handling EU personal data | Maintained |

---

## Repository Structure

```
gdpr-privacy-program/
├── README.md                              # This file
├── ropa/
│   └── record-of-processing-activities.md  # RoPA — all processing activities
├── dpia/
│   └── dpia-ehrp-clinical-research.md     # DPIA for clinical research data processing
├── data-subject-rights/
│   └── dsr-procedures.md                  # Data Subject Rights request procedures
└── breach-notification/
    └── gdpr-breach-notification.md        # 72-hour breach notification procedures
```

---

## Key Personnel

| Role | Name |
|------|------|
| Data Controller Representative | Marcus T. Hargrove, CEO |
| Data Protection Officer (de facto) | Dr. Rachel Feinberg, Privacy Officer |
| GDPR Program Lead | Dr. Rachel Feinberg |
| Legal Counsel | Sarah T. Worthington, General Counsel |
| CISO (Technical Controls) | Jonathan E. Steele |

---

## GDPR Articles Coverage

| GDPR Article | Title | Coverage |
|-------------|-------|---------|
| Art. 5 | Principles relating to processing | Data minimization, accuracy, storage limitation policies |
| Art. 6 | Lawful basis for processing | Documented basis per processing activity in RoPA |
| Art. 9 | Special category data | PHI classified as special category; explicit consent or vital interest basis |
| Art. 13-14 | Transparency / Privacy Notice | GDPR Privacy Notice for EU data subjects published |
| Art. 17 | Right to erasure | DSR erasure procedures documented and implemented |
| Art. 20 | Data portability | DSR portability procedures; HL7 FHIR export capability |
| Art. 25 | Privacy by design and default | Privacy requirements in SDLC; data minimization enforced |
| Art. 28 | Processor agreements | DPAs signed with all EU subprocessors |
| Art. 32 | Security of processing | EHRP technical and organizational security measures documented |
| Art. 33 | Breach notification to supervisory authority | 72-hour notification procedures to EU supervisory authority |
| Art. 35 | Data Protection Impact Assessment | Annual DPIA conducted for high-risk processing activities |
| Art. 46 | Transfers to third countries | SCCs (Standard Contractual Clauses) in place for US-EU transfers |

---

## Supervisory Authority Contact

Given MedCore's primary EU research partnerships are with German institutions, the competent supervisory authority for GDPR purposes is:

**Bundesbeauftragte fur den Datenschutz und die Informationsfreiheit (BfDI)**
Graurheindorfer Str. 153, 53117 Bonn, Germany
Tel: +49 (0)228 99 7799-0

MedCore maintains contact information for BfDI and all relevant EU supervisory authorities in its Incident Response Plan for GDPR breach notification purposes.
