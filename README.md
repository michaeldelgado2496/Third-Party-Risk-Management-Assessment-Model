# Third-Party Risk Management (TPRM) Assessment Model

A practical, standardized Third-Party Risk Management framework and evaluation model designed for vendor due diligence, risk scoring, and executive reporting.

## Project Overview

This repository demonstrates core Governance, Risk, and Compliance (GRC) workflows by establishing a standardized vendor security questionnaire, a quantitative failure-count risk scoring methodology, and realistic vendor assessment artifacts.

## Repository Structure

* **`01_Vendor_Security_Questionnaire/`**
  * `questionnaire.md`: Standardized security baseline questionnaire used to evaluate prospective vendors.
* **`02_Risk_Scoring_Model/`**
  * `scoring_methodology.md`: Quantitative risk-tiering logic based on control failure counts (Low, Medium, High).
* **`03_Sample_Assessments/`**
  * `executive_brief.md`: High-level summary report for leadership and stakeholders.
  * `vendor_Denta_assessment.md`: Sample assessment resulting in conditional approval (Medium Risk).
  * `vendor_Oncolo_assessment.md`: Sample assessment resulting in rejection (High Risk).

## Risk Scoring Methodology

* **Low Risk (0 Failures):** Standard onboarding approval.
* **Medium Risk (1–2 Failures):** Conditional approval granted pending remediation within 30 days.
* **High Risk (3+ Failures):** Automatic onboarding rejection due to critical control gaps.
