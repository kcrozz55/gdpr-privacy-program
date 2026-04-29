# Record of Processing Activities (RoPA)

**Document ID:** GDPR-ROPA-001
**Version:** 2.0
**Classification:** Confidential
**Controller:** MedCore Health Systems, 1200 Peachtree Street NE, Atlanta, GA 30309
**DPO Contact:** Dr. Rachel Feinberg, privacy@medcorehealthsystems.com
**Last Updated:** March 31, 2026
**Next Review:** March 31, 2027
**Regulatory Basis:** GDPR Article 30

---

## Purpose

This Record of Processing Activities (RoPA) documents all processing activities carried out by MedCore Health Systems in its capacity as a Data Controller under GDPR Article 30. It covers only processing activities involving personal data of individuals in the European Union or European Economic Area.

---

## Processing Activity: PA-001 — Clinical Research Data Processing

| Field | Detail |
|-------|--------|
| Activity Name | Multi-center Clinical Research Study Data Management |
| Controller | MedCore Health Systems |
| Joint Controller (if any) | Munich Medical University (Germany); Rotterdam Clinical Institute (Netherlands) |
| DPO | Dr. Rachel Feinberg |
| Purpose of Processing | Collection, analysis, and reporting of de-identified clinical outcomes data for IRB-approved research studies |
| Categories of Data Subjects | EU/EEA patients enrolled in multi-center clinical research studies; EU-based clinical investigators |
| Categories of Personal Data | Patient demographics (age range, sex, diagnosis codes); clinical outcomes data; adverse event data; investigator contact information |
| Special Category Data | Yes — health data (Article 9); processed under explicit consent (Article 9(2)(a)) and for scientific research purposes (Article 9(2)(j)) |
| Legal Basis | Explicit consent (Article 6(1)(a)) for identifiable data; legitimate interest for anonymized research outcomes (Article 6(1)(f)) |
| Recipients | IRB; co-investigator institutions; FDA (if applicable); publication in peer-reviewed journals (anonymized only) |
| Third Country Transfers | Data transferred to US (MedCore) from EU institutions — SCCs (EU Standard Contractual Clauses 2021) in place with Munich Medical University and Rotterdam Clinical Institute |
| Retention Period | Study data retained for 15 years per FDA GCP requirements; identifiable data deleted at end of study or on withdrawal of consent |
| Security Measures | AES-256 encryption at rest; TLS 1.3 in transit; RBAC restricting access to research team only; research data stored in isolated AWS GovCloud environment |

---

## Processing Activity: PA-002 — EU Patient Referral Records

| Field | Detail |
|-------|--------|
| Activity Name | International Patient Referral and Care Coordination |
| Controller | MedCore Health Systems |
| Purpose of Processing | Processing referral information from EU-based physicians to coordinate patient care at MedCore facilities |
| Categories of Data Subjects | EU/EEA patients referred for treatment at MedCore |
| Categories of Personal Data | Name, date of birth, contact information, diagnosis, treatment history, referring physician details |
| Special Category Data | Yes — health data (Article 9); legal basis: vital interests (Article 9(2)(c)) and explicit consent (Article 9(2)(a)) |
| Legal Basis | Necessity for healthcare (Article 9(2)(h)); explicit consent for any secondary uses |
| Recipients | MedCore clinical staff; health insurance companies (with patient consent); referring physicians |
| Third Country Transfers | Data held in US (MedCore) — SCCs in place with EU referring physicians; HIPAA authorizations obtained where applicable |
| Retention Period | 7 years from last treatment date; consistent with HIPAA retention requirements |
| Security Measures | Same as PA-001; additionally, referral data encrypted in transit via HL7 FHIR over TLS 1.3 |

---

## Processing Activity: PA-003 — EU Vendor and Business Partner Data

| Field | Detail |
|-------|--------|
| Activity Name | EU Vendor Contact and Contract Management |
| Controller | MedCore Health Systems |
| Purpose of Processing | Managing business relationships with EU-based SaaS vendors and clinical partners; contract administration; invoicing |
| Categories of Data Subjects | EU-based vendor employees; clinical research partners; business contacts |
| Categories of Personal Data | Name, business email, telephone, job title, employer, contract correspondence |
| Special Category Data | None |
| Legal Basis | Legitimate interests in conducting business (Article 6(1)(f)); contract performance (Article 6(1)(b)) |
| Recipients | MedCore finance, legal, and IT departments; no further disclosure |
| Third Country Transfers | Data held in US (MedCore CRM and contract management systems) — SCCs in place |
| Retention Period | Active contacts: Duration of relationship + 3 years; contracts: 7 years per legal retention requirements |
| Security Measures | CRM access restricted to authorized staff; TLS encryption; standard corporate access controls |

---

## Subprocessor Register

The following subprocessors process EU personal data on behalf of MedCore Health Systems:

| Subprocessor | Country | Processing Activity | DPA Status | Security Certifications |
|-------------|---------|---------------------|------------|------------------------|
| Amazon Web Services (AWS GovCloud) | USA | Infrastructure hosting, storage | DPA executed | ISO 27001, SOC 2 Type II, FedRAMP High |
| Microsoft (Azure, Purview, Intune) | USA | DLP, endpoint management | DPA executed | ISO 27001, SOC 2 Type II |
| Okta | USA | Identity and access management | DPA executed | ISO 27001, SOC 2 Type II |
| CrowdStrike | USA | Endpoint detection and response | DPA executed | SOC 2 Type II |
| Splunk (SIEM) | USA | Security event logging | DPA executed | ISO 27001, SOC 2 Type II |
| Iron Mountain | USA | Physical records storage and destruction | DPA executed | ISO 27001 |

All DPAs include Standard Contractual Clauses (SCCs) per EU Commission Decision 2021/914.

---

## Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | March 2025 | R. Feinberg | Initial RoPA |
| 2.0 | March 2026 | R. Feinberg | Annual review; PA-003 added; subprocessor register updated |
