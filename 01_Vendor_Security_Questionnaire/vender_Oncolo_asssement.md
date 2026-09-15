# Vendor Risk Assessment: Vendor Oncolo (Oncology Electronic Health Record Software)

## Assessment Overview

* **Vendor Name:** Vendor Oncolo
* **Date Evaluated:** September 7, 2026
* **Assessed By:** Michael Delgado (GRC Analyst)
* **Overall Risk Tier:** High

---

## Questionnaire Response Review

### Access Control

* **Multi-Factor Authentication:** *(No)* MFA is not enforced to gain access to the administrative database containing patient health records.
* **Principle of Least Privilege:** *(No)* Oncologist staff have full access beyond what is necessary for their role.

### Data Protection

* **Data Encryption at Rest:** *(Yes)* Patient electronic protected health information is encrypted at rest using AES-256.
* **Data Encryption in Transit:** *(No)* HTTPS is not enforced across all portal web traffic.

### Compliance & Governance

* **Third-Party Audits:** *(Last audit was in 2021.)* Vendor Oncolo has yet to complete a HIPAA compliance assessment.
* **Incident Response Plan:** *(Yes)* There is a documented data breach response plan in place.

---

## GRC Recommendation

**Decision:** **Rejected** There are multiple risks that were flagged: lack of MFA; oncologist staff having access to parts of the database they shouldn't (such as payroll); lack of encryption in transit; and no recent third-party audit, as it has been 5 years since the last assessment.
