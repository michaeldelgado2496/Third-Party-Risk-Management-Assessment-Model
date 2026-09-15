# Vendor Risk Assessment: Vendor Oncolo (Oncology Electronic Health Record Software)
## Assessment Overview

* **Vendor Name:** Vendor Oncolo
* **Date Evaluated:** September 7, 2026
* **Assessed By:** Michael Delgado (GRC Analyst)
* **Overall Risk Tier:** High

---

## Questionnaire Response Review

### Access Control

* **Multi-Factor Authentication:** *(No)* MFA is not enforced to gain access to the administrative database containing the patients health records
* **Principle of Least Privilege:** *(No)* Oncologist staff have full access to beyond what is necessary for their role

### Data Protection

* **Data Encryption at Rest:** *(Yes)* Patient electronic protect health information is encrypted in idle using AES-256. 
* **Data Encryption in Transit:** *(No)* HTTPS is not enforced across all portal web traffic.

### Compliance & Governance

* **Third-Party Audits:** *Last audit was in 2021* Vendor Oncolo has yet to complete a HIPPA compliance asssessment.
* **Incident Response Plan:** *(Yes)* There is a documented data breach response plan set in place.  

---

## GRC Recommendation



**Decision:** **Rejected** There is multiple risks that were flagged; no MFA, Oncologist Staff have access to parts the database they shouldn't such as payroll, Lack of encrpytion in Transit, No recent third-party audit its been half a decade since the last audit 
