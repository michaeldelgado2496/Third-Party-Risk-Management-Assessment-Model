# Vendor Risk Assessment: Vendor Denta (Dental Management Software)

## Assessment Overview
* **Vendor Name:** Vendor Denta
* **Date Evaluated:** September 14, 2026
* **Assessed By:** Michael Delgado (GRC Analyst)
* **Overall Risk Tier:** Medium

---

## Questionnaire Response Review

### Access Control
* **Multi-Factor Authentication:** *(Yes)* MFA is enforced for administrative database access containing patient dental records.
* **Principle of Least Privilege:** *(Yes)* Dental staff roles only have role-based database access restricted to required fields (e.g., daily charting)

### Data Protection
* **Data Encryption at Rest:** *(Yes)* Patient electronic protected health information is encrypted at rest using AES-256.
* **Data Encryption in Transit:** *(Yes)* HTTPS is enforced across all patient portal web traffic.

### Compliance & Governance
* **Third-Party Audits:** *(Yes)* Vendor Denta has completed a HIPAA compliance assessment.
* **Incident Response Plan:** *(No)* A documented data breach response plan currently does not exist for handling ePHI leaks.



---

## GRC Recommendation
Vendor Denta presents a medium risk simply due to the lack of a response plan in case of an incident. Otherwise, all internal controls are very well protected.

**Decision:** **Pending for onboarding.** Recommend setting up a data breach response plan before we continue.
