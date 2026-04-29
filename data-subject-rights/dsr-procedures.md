# GDPR Data Subject Rights (DSR) Procedures

**Document ID:** GDPR-DSR-001
**Version:** 1.1
**Classification:** Internal
**Owner:** Dr. Rachel Feinberg, Privacy Officer
**Effective Date:** May 25, 2025
**Review Date:** May 25, 2026
**Regulatory Basis:** GDPR Articles 12-23

---

## 1. Overview

This document defines MedCore Health Systems' procedures for receiving, verifying, and responding to Data Subject Rights (DSR) requests from EU/EEA data subjects in accordance with the General Data Protection Regulation (GDPR). MedCore is committed to honoring all applicable data subject rights within the statutory timeframes.

---

## 2. Applicable Data Subject Rights

| Right | GDPR Article | Description | MedCore Applicability |
|-------|-------------|-------------|----------------------|
| Right to be Informed | Art. 13-14 | Transparent information about processing | YES — Privacy Notice published |
| Right of Access | Art. 15 | Copy of personal data being processed | YES |
| Right to Rectification | Art. 16 | Correct inaccurate personal data | YES |
| Right to Erasure (Right to be Forgotten) | Art. 17 | Delete personal data in certain circumstances | YES — with limitations for research/legal obligations |
| Right to Restrict Processing | Art. 18 | Limit how data is used while disputes are resolved | YES |
| Right to Data Portability | Art. 20 | Receive data in machine-readable format | YES — HL7 FHIR export |
| Right to Object | Art. 21 | Object to processing based on legitimate interests | YES — for non-healthcare processing |
| Rights re: Automated Decision Making | Art. 22 | Challenge automated decisions with legal/significant effect | YES — no fully automated decisions; human review in clinical contexts |

---

## 3. DSR Intake Process

### 3.1 Submission Channels

EU/EEA data subjects may submit DSR requests through the following channels:

| Channel | Contact |
|---------|---------|
| Email | privacy@medcorehealthsystems.com |
| Online DSR Portal | medcorehealthsystems.com/privacy/dsr-request |
| Written Request | Dr. Rachel Feinberg, Privacy Officer, 1200 Peachtree Street NE, Atlanta, GA 30309 |
| Phone (EU contacts forwarded to Privacy Office) | +1 (404) 555-0188 |

### 3.2 Identity Verification

Before processing any DSR, MedCore must verify the identity of the requestor to prevent unauthorized disclosure:

1. **Standard verification:** Government-issued ID + verification of contact information on file
2. **For healthcare data:** Additional clinical record verification (date of service, treating provider name)
3. **For research participants:** IRB study ID + confirmation of enrollment
4. **Third-party requests:** Power of attorney or guardian documentation required

**Note:** MedCore must not request disproportionate information for verification. If in doubt, use the least invasive verification method sufficient to confirm identity.

---

## 4. Response Timeframes

| Scenario | Deadline |
|---------|----------|
| Standard DSR response | Within 1 month of receipt |
| Complex or numerous requests | Up to 3 months total; notify data subject of extension within 1 month |
| Refusal to act | Inform data subject within 1 month; provide reason and right to lodge complaint |

---

## 5. DSR Procedures by Right

### 5.1 Right of Access (Art. 15)

**Process:**
1. Privacy Officer receives and logs request in DSR tracker (ServiceNow)
2. IT Security retrieves personal data from EHRP, CRM, and relevant systems
3. Privacy Officer reviews data for third-party information that must be redacted
4. Response package compiled: confirmation of processing, categories of data, purposes, recipients, retention periods, data subject rights information
5. Delivered securely via encrypted email or secure portal within 30 days
6. Fee: No fee for first request; reasonable fee for manifestly unfounded or excessive subsequent requests

### 5.2 Right to Erasure (Art. 17)

**Process:**
1. Privacy Officer assesses whether erasure grounds apply:
   - Data no longer necessary for original purpose
   - Consent withdrawn and no other legal basis
   - Data subject objects and no overriding legitimate interest
   - Unlawful processing
2. Assess exceptions that override erasure:
   - Legal obligation to retain (HIPAA 6-year minimum; FDA GCP 15-year for research)
   - Vital interests of data subject or third party
   - Scientific research purposes (Article 9(2)(j))
3. If erasure is required: Delete from primary system, backup systems (at next scheduled backup purge), and notify subprocessors
4. Document decision and response in DSR tracker

**Important:** For clinical research data subject to FDA regulations, erasure may not be possible. Data subjects will be informed of applicable restrictions.

### 5.3 Right to Data Portability (Art. 20)

**Process:**
1. Confirm portability applies: data provided by subject + consent or contract basis + automated processing
2. IT Security exports data in HL7 FHIR R4 format (structured, machine-readable, interoperable)
3. Deliver via secure encrypted download link (valid 72 hours)
4. For transfer to another controller: implement secure API transfer upon written request specifying destination

### 5.4 Right to Rectification (Art. 16)

**Process:**
1. Identify inaccurate data; obtain correct data from data subject
2. Clinical data corrections: physician review required; corrections appended as amendments (original record preserved for audit trail)
3. Non-clinical data corrections: Privacy Officer updates directly with IT Security support
4. Notify relevant third parties of corrections where feasible

---

## 6. DSR Logging and Tracking

All DSR requests are logged in ServiceNow with:
- Request date
- Request type
- Data subject identity verification status
- Action taken
- Response date
- Outcome
- Any extensions or refusals with documented reasons

**Retention of DSR records:** 3 years to demonstrate GDPR compliance.

---

## 7. DSR Activity Summary — FY2025/2026

| Request Type | Received | Completed On Time | Extended | Refused | Pending |
|-------------|----------|------------------|---------|---------|---------|
| Right of Access | 4 | 4 | 0 | 0 | 0 |
| Right to Erasure | 1 | 1 | 0 | 0 | 0 |
| Right to Rectification | 2 | 2 | 0 | 0 | 0 |
| Right to Portability | 1 | 1 | 0 | 0 | 0 |
| Right to Object | 0 | — | — | — | — |
| **Total** | **8** | **8 (100%)** | **0** | **0** | **0** |

**All 8 DSR requests in the reporting period were completed on time and within GDPR statutory timeframes.**

---

## 8. Complaints and Supervisory Authority

EU data subjects who are unsatisfied with MedCore's response have the right to lodge a complaint with the competent supervisory authority in their EU member state. MedCore's lead supervisory authority is the BfDI (Germany) given the primary research partnership.

MedCore provides supervisory authority contact information in all DSR response communications.

---

## 9. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | May 25, 2025 | R. Feinberg | Initial procedures |
| 1.1 | November 2025 | R. Feinberg | Added portability via FHIR; updated verification procedures |
