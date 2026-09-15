# Overview
This document defines the risk scoring model used to evaluate third-party vendors based on their security questionnaire responses.

# 1. Vendor Criticality Tiers
* **Tier 1 (High Risk):** Vendors with access to PHI, PII, or internal infrastructure.
* **Tier 2 (Medium Risk):** Vendors handling internal non-sensitive operational data.
* **Tier 3 (Low Risk):** Public-facing services with zero internal system access.

# 2. Risk Scoring Rules
Instead of complex calculations, vendors are scored based on the total number of security controls they failed (answered "No"):
* **Low Risk (0 Failures):** Standard approval.
* **Medium Risk (1 - 2 Failures):** Conditional approval; requires remediation within 30 days.
* **High Risk (3+ Failures):** Automatic rejection due to critical data protection exposure.

# 3. Action Thresholds
* **Low Risk:** Onboard immediately.
* **Medium Risk:** Pending onboarding review.
* **High Risk:** Escalated to management for immediate rejection.
