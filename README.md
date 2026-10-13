# Project 01: Healthcare Cybersecurity Risk Assessment (Simulated)

**Author:** Khadijat Badmus  
**Focus areas:** Cybersecurity Risk Assessment | GRC | NIST SP 800-30 | HIPAA Security Rule | Risk Register

> **Portfolio disclosure:** CedarBridge Family Health is fictional. All system conditions, scores, treatment plans, and evidence requirements are hypothetical. This is an educational demonstration, **not** a real audit, penetration test, or certification of compliance. No real patient data or company records were used.

## Project overview

Developed a practice cybersecurity risk assessment for a fictional 150-person, two-clinic outpatient healthcare provider. The scenario covers an EHR SaaS platform, remote access, endpoints, backup/recovery, vendor billing integrations, and clinical network security.

The assessment uses the prepare / conduct / maintain approach from **NIST SP 800-30 Rev. 1** and considers HIPAA-related protection of ePHI. NIST CSF 2.0 and illustrative SP 800-53 control references support the remediation roadmap.

## Deliverables

- [`Risk_Assessment_Report.pdf`](Risk_Assessment_Report.pdf) — executive summary, methodology, prioritized risks, treatment plan and references.
- [`Risk_Assessment_Report.docx`](Risk_Assessment_Report.docx) — editable report.
- [`risk_register.csv`](risk_register.csv) — structured list of 10 simulated risks and target residual ratings.

## Highlights

| Measure | Simulated result |
| --- | --- |
| Scenarios identified | 10 |
| Critical (17–25) | 3 |
| High (10–16) | 6 |
| Moderate (5–9) | 1 |
| Low (1–4) | 0 |

**Main recommendations:** strengthen MFA and identity governance; remediate exposed remote-access vulnerabilities; validate ransomware-resistant backup recovery; centralize relevant monitoring; improve vendor due diligence and network separation.

## Approach

1. Define organizational context, in-scope assets, assumptions and boundaries.
2. Model potential threats and control exposure.
3. Rate inherent likelihood (1–5) and impact (1–5); calculate score = likelihood × impact.
4. Assign risk owners and select realistic preventative, detective and recovery measures.
5. Define evidence required to validate implementation and propose target residual scores.
6. Present a 30/60/90-day remediation roadmap and governance checkpoints.

**Important:** Target residual scores are illustrative, not verified post-treatment outcomes. This report intentionally distinguishes an assumed weakness from a factual finding.

## Tools and skills demonstrated

Risk register development · NIST risk assessment workflow · Risk scoring · Risk treatment planning · HIPAA-aware safeguards · Policy/governance communication · Evidence mapping · Executive reporting.

## References

- [NIST SP 800-30 Rev. 1, Guide for Conducting Risk Assessments](https://csrc.nist.gov/pubs/sp/800/30/r1/final)
- [NIST CSF 2.0](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
- [NIST SP 800-66 Rev. 2, HIPAA Security Rule Resource Guide](https://csrc.nist.gov/pubs/sp/800/66/r2/final)
- [HHS Guidance on Risk Analysis](https://www.hhs.gov/hipaa/for-professionals/security/guidance/guidance-risk-analysis/index.html)

## How to discuss this in an interview

“I designed a simulated risk assessment for a fictional healthcare provider using NIST SP 800-30. I documented ten plausible risks, scored and prioritized them, mapped treatment options to NIST controls, and developed a 90-day plan with evidence expectations. Because it is a practice scenario, I clearly distinguish assumptions from findings.”

## Future enhancements

- Add an approved, isolated home-lab control validation demonstration.
- Develop a separate Acceptable Use Policy and HIPAA security gap-analysis exercise.
- Link each project back to a top-level cybersecurity portfolio landing page.
