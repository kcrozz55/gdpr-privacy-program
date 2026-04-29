# GDPR Personal Data Breach Notification Procedures

**Document ID:** GDPR-BRN-001
**Version:** 1.0
**Classification:** Confidential
**Owner:** Dr. Rachel Feinberg, Privacy Officer
**Effective Date:** May 25, 2025
**Regulatory Basis:** GDPR Articles 33 and 34

---

## 1. Overview

GDPR Article 33 requires Data Controllers to notify the competent supervisory authority of a personal data breach within 72 hours of becoming aware of it. GDPR Article 34 requires notification to affected data subjects without undue delay where the breach is likely to result in a high risk to their rights and freedoms.

These procedures define MedCore Health Systems' process for identifying, assessing, and notifying authorities and data subjects of GDPR-covered personal data breaches.

---

## 2. What Constitutes a GDPR Personal Data Breach

A personal data breach is a breach of security leading to the accidental or unlawful destruction, loss, alteration, unauthorized disclosure of, or access to, personal data transmitted, stored, or otherwise processed.

| Breach Type | Examples |
|------------|---------|
| Confidentiality breach | Unauthorized access to or disclosure of EU personal data |
| Availability breach | Accidental deletion or loss of EU personal data with no backup |
| Integrity breach | Unauthorized alteration of EU personal data |

**Note:** Not all security incidents constitute a reportable GDPR breach. Low-risk incidents (e.g., encrypted device lost with no compromise of key) may not require supervisory authority notification.

---

## 3. 72-Hour Breach Response Timeline

| Time | Action | Responsible Party |
|------|--------|------------------|
| Hour 0 | Incident detected and reported to IT Security / Privacy Officer | ISSO / Staff member |
| Hour 0-4 | Initial triage: Is EU personal data involved? What type of breach? | ISSO, Privacy Officer |
| Hour 4-12 | Assess scope: How many data subjects affected? What categories of data? | Privacy Officer, CISO |
| Hour 12-24 | Legal review: Is notification to supervisory authority required? | Privacy Officer, General Counsel |
| Hour 24-48 | If notification required: Draft notification to supervisory authority | Privacy Officer |
| Hour 48-72 | Submit notification to supervisory authority (BfDI for DE-linked subjects) | Privacy Officer |
| After Hour 72 | Assess whether data subject notification is required (high risk threshold) | Privacy Officer, CISO |
| Within 1 week | Provide full incident details to supervisory authority if initial notification was incomplete | Privacy Officer |

**Important:** MedCore must notify even if full investigation is not complete. The initial notification can be submitted in phases.

---

## 4. GDPR Supervisory Authority Notification — Required Content (Art. 33(3))

The notification to the supervisory authority must include, where possible:

| Required Item | Description |
|--------------|-------------|
| Nature of the breach | Confidentiality, availability, or integrity; approximate number of data subjects and records affected |
| Categories and approximate number of personal data records concerned | Health data, demographics, contact information, etc. |
| Name and contact details of DPO | Dr. Rachel Feinberg, privacy@medcorehealthsystems.com |
| Likely consequences of the breach | Risk assessment for affected data subjects |
| Measures taken or proposed | Containment, remediation, prevention measures |

**Notification Template:** GDPR-SA-NOTIFY-TEMPLATE (maintained by Privacy Officer)

---

## 5. Data Subject Notification (Art. 34)

Data subject notification is required when the breach is likely to result in **high risk** to the rights and freedoms of natural persons.

### High-Risk Factors (triggering data subject notification)

- Sensitive health data (special categories under Art. 9) disclosed to unauthorized parties
- Large scale: more than 100 EU data subjects affected
- Vulnerable data subjects (research participants, minors, elderly patients)
- Data disclosed to unknown parties with malicious intent
- Financial data combined with identifying information

### Data Subject Notification Content

| Required Item | Description |
|--------------|-------------|
| Description of the breach | Clear, plain-language description of what happened |
| DPO contact | Dr. Rachel Feinberg, privacy@medcorehealthsystems.com |
| Likely consequences | What risks the breach creates for data subjects |
| Measures taken | Steps MedCore has taken to address the breach |
| Recommendations for data subjects | Steps data subjects can take to protect themselves |
| Right to lodge complaint | Supervisory authority contact information |

### Notification Channels

1. **Direct notification preferred:** Email to last known EU address; written letter where email unavailable
2. **Public communication (if direct contact not possible):** Official website announcement for breaches affecting 250+ EU data subjects
3. **Research participants:** IRB notified; institution coordinating the study assists with participant notification

---

## 6. Relationship with HIPAA Breach Notification

For incidents involving EU data subjects who are also HIPAA-covered individuals (e.g., EU research participants enrolled in US-based studies), both HIPAA and GDPR breach notification requirements apply.

| Requirement | HIPAA | GDPR |
|------------|-------|------|
| Notification to authority | HHS/OCR within 60 days | Supervisory Authority within 72 hours |
| Notification to individuals | Within 60 days of breach discovery | Without undue delay (high-risk breaches only) |
| Notification to media | If 500+ residents in a state affected | Not required (but public communication may be appropriate) |

**Where both frameworks apply, the stricter GDPR 72-hour requirement governs supervisory authority notification.**

---

## 7. Documentation Requirements

All personal data breaches, whether or not notification is required, must be documented in the Breach Register (GDPR-BRG-001) to demonstrate compliance with Article 33(5). Documentation must include:

- Date and time breach discovered
- Date and time Privacy Officer notified
- Nature of the breach
- Assessment of notification obligation and reasoning
- Actions taken
- Final outcome

**Retention of breach documentation:** 3 years minimum.

---

## 8. Breach Register Summary — FY2025/2026

| Incident ID | Date | Type | EU Data Subjects Affected | SA Notified? | Data Subjects Notified? | Outcome |
|------------|------|------|--------------------------|-------------|------------------------|---------|
| BR-2025-001 | June 2025 | Confidentiality (DLP incident) | 0 (blocked by DLP; no data exfiltrated) | No — no breach occurred | No | Incident resolved; no notification required |
| BR-2026-001 | February 2026 | Confidentiality (departing employee access) | 0 confirmed (access terminated; no exfiltration evidence) | No — low risk | No | Investigation closed; access controls reinforced |

**0 reportable GDPR breaches in the observation period. Both incidents assessed as below the notification threshold.**
