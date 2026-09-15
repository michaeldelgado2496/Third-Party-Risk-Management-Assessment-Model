# Vendor Risk Scoring Methodology

## Overview
This document defines the quantitative risk scoring model used to evaluate third-party vendors based on their questionnaire responses and data access levels.

---

## 1. Vendor Criticality Tiers
* **Tier 1 (High Risk):** Vendors with access to Personally Identifiable Information (PII), PHI, financial data, or direct infrastructure integration.
* **Tier 2 (Medium Risk):** Vendors handling internal non-sensitive operational data.
* **Tier 3 (Low Risk):** Public-facing services with zero internal system access.

---

## 2. Risk Calculation Formula
$$\text{Risk Score} = (\text{Likelihood} \times \text{Impact}) - \text{Mitigating Controls}$$

* **Likelihood (1–5):** Probability of a security failure occurring based on current vendor posture.
* **Impact (1–5):** Severity of business disruption or data loss if a failure occurs.
* **Mitigating Controls (0–3):** Points deducted for robust compensating controls like valid SOC 2 Type II reports or strict MFA enforcement.

---

## 3. Action Thresholds
* **Low Risk (1–5):** Standard approval.
* **Medium Risk (6–12):** Approval granted conditionally upon remediating specified gaps within 30 days.
* **High Risk (13–25):** Executive escalation required; CISO sign-off needed before onboarding.
