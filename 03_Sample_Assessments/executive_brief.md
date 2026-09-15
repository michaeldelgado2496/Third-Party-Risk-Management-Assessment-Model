# Executive Risk Summary: Cloud SaaS Vendor Assessment

## 1. Executive Summary
This brief summarizes the third-party risk assessment conducted for **CloudData Corp**, a prospective Tier 1 SaaS vendor requesting access to internal infrastructure and handling sensitive customer data. 

Based on our quantitative risk scoring methodology, CloudData Corp has received an **Overall Risk Score of 8 (Medium Risk)** due to a lack of recent penetration testing documentation. Conditional approval is recommended pending remediation.

---

## 2. Assessment Findings
* **Access Control & Encryption (Pass):** Vendor mandates MFA for all administrative accounts and utilizes AES-256 (at rest) and TLS 1.3 (in transit).
* **Compliance & Audit (Conditional Fail):** Vendor possesses an active SOC 2 Type II report, but failed to provide documentation of an independent third-party network penetration test conducted within the last 12 months.
* **Incident Response (Pass):** Vendor maintains an annual tested incident response plan with a guaranteed 48-hour breach notification SLA.

---

## 3. Recommendation & Remediation Plan
* **Status:** Conditional Approval (Medium Risk Threshold: 6–12).
* **Required Action:** CloudData Corp must provide an executive summary of a third-party penetration test or execute a binding security addendum committing to a formal test within 30 days of onboarding.
