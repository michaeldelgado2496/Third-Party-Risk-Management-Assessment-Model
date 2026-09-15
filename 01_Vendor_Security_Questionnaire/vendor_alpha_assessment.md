# Vendor Risk Assessment: Vendor Denta (Dental Management Software)

## Assessment Overview
* **Vendor Name:** Vendor Denta
* **Date Evaluated:** September 14, 2026
* **Assessed By:** Michael Delgado (GRC Analyst)
* **Overall Risk Tier:** Low Risk

---

## Questionnaire Response Review

### Access Control
* **Multi-Factor Authentication:** MFA is enforced for administrative database access containing patient dental records.
* **Principle of Least Privilege:** Dental staff roles only have role-based database access restricted to required fields (e.g., daily charting)

### Data Protection
* **Data Encryption at Rest:** *Yes.* Patient electronic protected health information is encrypted in idle using AES-256.
* **Data Encryption in Transit:** *Yes.* TLS 1.3 is enforced for all patient portal web traffic.

### Compliance & Governance
* **Third-Party Audits:** *No.* Vendor Denta has not completed a HIPAA compliance assessment or SOC 2 audit. *(Action Item: Critical - Flagged for remediation)*
* **Incident Response Plan:** *Yes.* A documented data breach response plan exists for handling ePHI leaks.



---

## GRC Recommendation
Vendor Gamma presents a high risk due to the lack of MFA on critical developer accounts and the absence of a formal third-party audit (SOC 2 or ISO 27001). While data encryption standards are met, the access control and audit deficiencies are significant. 

**Decision:** **REJECTED for onboarding.** Recommend re-evaluation in 6 months pending implementation of mandatory MFA and completion of a SOC 2 Type I audit.
