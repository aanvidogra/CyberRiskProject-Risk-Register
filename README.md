# CyberRiskProject-Risk-Register
Cyber risk register and executive summary for a local fitness studio, including threat scenarios, likelihood/impact scoring, and NIST/CIS-aligned mitigation recommendations.

# Local Fitness Studio – Cyber Risk Register (GRC Project)

This repository contains a cyber risk assessment for a local fitness studio that handles member personal data, payments, and day-to-day operations through SaaS platforms (e.g., scheduling/CRM, email, POS) and on-site networks (Wi-Fi, staff devices).

This project demonstrates entry-level cyber risk/GRC skills: identifying critical assets, documenting realistic threat scenarios, scoring risk using a likelihood × impact model, and recommending practical mitigations aligned to common frameworks.

## Scenario
**Organization:** Local fitness studio (single location)  
**Core services:** Membership management, class scheduling, payments, and staff operations  
**Key systems:** POS/payment terminals, scheduling/CRM app, email, Wi-Fi network, staff laptops/tablets, website/social media

## Deliverables
- **Risk Register**: `docs/risk-register.csv`
- **Executive Summary**: `docs/executive-summary.md`
- **Scope & Assumptions**: `docs/assumptions-scope.md` (recommended)

## Risk Method
- **Likelihood**: 1 (Rare) to 5 (Very Likely)
- **Impact**: 1 (Low) to 5 (Severe)
- **Risk Score**: Likelihood × Impact  
- **Risk Levels**:
  - Low: 1–7
  - Medium: 8–14
  - High: 15–25

## Framework Alignment
Recommendations are mapped at a high level to:
- **NIST Cybersecurity Framework (CSF)** categories (Identify, Protect, Detect, Respond, Recover)
- **CIS Controls** (e.g., access control, secure configuration, training)

## Highlights (Top Risks)
Examples of common high-priority risks for this environment include:
- Phishing and credential compromise affecting scheduling/CRM and email
- Payment/POS compromise and exposure of payment-related data
- Weak Wi-Fi segmentation leading to lateral movement from guest to staff systems
- Data exposure due to misconfiguration or poor access control in SaaS tools

## How to Use
- Open the risk register CSV and filter by **Risk Level = High**
- Review recommended controls and the suggested 30/90-day remediation roadmap

## Disclaimer
This is an educational/portfolio project using a realistic scenario. No real customer data, internal configurations, or sensitive operational details are included.
