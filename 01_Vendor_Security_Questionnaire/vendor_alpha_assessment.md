# Vendor Risk Assessment: Vendor Gamma (AI Transcription Service)

## Assessment Overview
* **Vendor Name:** Vendor Gamma Ltd.
* **Date Evaluated:** September 14, 2026
* **Assessed By:** Michael Delgado (GRC Analyst)
* **Overall Risk Tier:** High Risk

---

## Questionnaire Response Review

* **1.1 Multi-Factor Authentication:** *No.* MFA is not enforced for developer console access, only for standard user accounts. *(Action Item: Flagged for remediation)*
* **1.2 Principle of Least Privilege:** *Partially Implemented.* Access reviews are ad-hoc and not documented formally.
* **2.1 Data Encryption at Rest:** *Yes.* All sensitive client data is encrypted at rest using AES-256.
* **2.2 Data Encryption in Transit:** *Yes.* TLS 1.3 is used for all API communications.
* **3.1 Third-Party Audits:** *No.* Vendor Gamma has not yet undergone a SOC 2 audit but states they are "working towards it." *(Action Item: Critical - Flagged for remediation)*
* **4.1 Incident Response Plan:** *Yes.* A documented IR plan exists and is reviewed annually.

---

## GRC Recommendation
Vendor Gamma presents a high risk due to the lack of MFA on critical developer accounts and the absence of a formal third-party audit (SOC 2 or ISO 27001). While data encryption standards are met, the access control and audit deficiencies are significant. 

**Decision:** **REJECTED for onboarding.** Recommend re-evaluation in 6 months pending implementation of mandatory MFA and completion of a SOC 2 Type I audit.
