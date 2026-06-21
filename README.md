# Vendor-Security-Assessment-Slack
Third-party vendor security assessment of Slack using SOC 2, ISO 27001, and GDPR documentation

# Third-Party Vendor Security Assessment — Slack

A self-directed GRC project designing a vendor security questionnaire and applying it to a real, major SaaS provider (Slack) using only publicly available security documentation — the core skill behind third-party/vendor risk management in real GRC programs.

## Project Summary

This project evaluates **Slack** (Slack Technologies, a Salesforce company) as a vendor under consideration for adoption as an organization's internal communication and collaboration platform. Unlike the fictional-company projects in this portfolio, this assessment is grounded entirely in real, citable evidence — Slack's public Trust Center, Security Practices page, Compliance page, and GDPR commitment page. The project walks through the full vendor assessment lifecycle:

1. **Questionnaire design** — building a 28-question security questionnaire across five domains (Governance, Access Control, Data Protection, Incident Response & Logging, Compliance), phrased in realistic procurement/security-review language rather than textbook control language
2. **Evidence-based scoring** — scoring each question Yes (2) / Partial (1) / No (0) strictly against what Slack's public documentation actually states, with every score backed by a specific cited source
3. **Vendor Scorecard** — synthesizing the 28 scored answers into a section-by-section breakdown, a visual chart, strengths/weaknesses, and an overall risk rating against a pre-defined risk scale
4. **Vendor Assessment Report** — a one-page executive summary including a before/after analysis of Slack's security posture across two real, publicly disclosed security incidents (2015 and 2022), plus a recommendation with specific follow-up items for procurement

## Deliverables

| File | Description |
|---|---|
| `Slack_Vendor_Assessment.xlsx` / `.pdf` | Full 28-question questionnaire with evidence notes, plus the Vendor Scorecard (section scores, chart, strengths/weaknesses, risk rating scale) |
| `Slack_Vendor_Assessment_Report.docx` / `.pdf` | One-page report with before/after incident analysis, assessment summary, and procurement recommendation |

## What I Did

- Designed a 28-question vendor questionnaire across five standard GRC domains, written in realistic, conversational procurement language rather than copied framework terminology
- Researched Slack's actual public security documentation (Trust Center, Security Practices, Compliance, and GDPR pages) rather than assuming or guessing at vendor capabilities
- Scored all 28 questions using a Yes=2/Partial=1/No=0 model, citing the specific public claim (or noting its absence) behind every single score
- Built a Vendor Scorecard with section-level scoring, a bar chart visualization, and a synthesized strengths/weaknesses summary
- Defined a risk rating scale (Low/Medium/High/Critical by score percentage) *before* finalizing the overall risk label, so the "Low Risk" conclusion follows a rule rather than a subjective call made after seeing the score
- Researched Slack's actual incident history (the 2015 password database compromise and the 2022 GitHub token theft) to build a real before/after comparison of the vendor's security maturity over time
- Wrote a one-page report synthesizing the score, the historical trend, and specific, actionable procurement recommendations

## What I Learned

- **A vendor questionnaire only has value if it's specific enough to fail.** Early drafts of these questions were generic enough that almost anything could count as a "Yes." Rewriting them in real procurement language ("is that on us to figure out?") forced sharper, more honest answers — and produced the project's only "No" score.
- **Public documentation has real, predictable gaps.** Vendors are consistently transparent about what they *do* (certifications, features) and consistently vague about specific operational commitments (breach notification timelines, plan-tier-specific enforcement). Knowing where that gap typically falls is itself a useful pattern for future vendor reviews.
- **A score without a documented evidence trail isn't defensible.** Citing the exact source claim behind each answer — and being honest when no public claim existed — is what separates a credible assessment from a vendor's own marketing page restated as a scorecard.
- **Vendor risk isn't static, and a single incident isn't the whole story.** Slack's 2015 and 2022 incidents look similar on the surface (unauthorized access via stolen credentials/tokens), but the *response* — speed of detection, transparency of disclosure, and confirmed blast radius — was meaningfully different. A vendor that has had an incident and demonstrably improved afterward can be a safer bet than a vendor with no incident history and no way to verify how they'd actually respond.
- **Risk thresholds should be set before scoring, not after.** Defining the Low/Medium/High/Critical bands in advance, rather than picking a label that felt right once the 89% appeared, is a small process discipline that meaningfully improves the credibility of the conclusion.

## Real-World Application

Third-party/vendor risk assessment is one of the highest-volume, most recurring tasks in real GRC roles, particularly as organizations adopt more SaaS tools:

- **Procurement security review** — most mid-size and large organizations require a documented vendor security assessment before any new SaaS tool is approved for company-wide use, and many GRC analysts review dozens of these per quarter
- **Vendor risk tiering** — the scoring/risk-rating approach used here mirrors how real organizations triage vendors (e.g., low-risk vendors get expedited approval, high-risk vendors require additional contractual protections or executive sign-off)
- **Ongoing vendor monitoring, not just onboarding** — the before/after incident analysis reflects a real and growing GRC practice: continuously monitoring existing vendors for new incidents or certification lapses, rather than treating the initial assessment as permanent
- **Standardized industry tools** — this project's structure (sectioned questionnaire, weighted scoring, evidence citation) mirrors real industry frameworks like the Shared Assessments SIG (Standardized Information Gathering) questionnaire used widely in enterprise vendor risk programs

## Conclusion

This project completes a third distinct pillar of GRC analyst work, alongside the compliance-matrix and risk-register projects in this portfolio: rather than assessing an organization's own controls or its internal risk landscape, this project assesses an *external* party using only the evidence that party chooses to make public — the same constraint a real analyst faces when a vendor hasn't yet agreed to a deeper audit or questionnaire response. Grounding the assessment in real evidence, including real incident history, rather than a fictional scenario, reflects how vendor risk decisions are actually made: imperfectly, with incomplete information, but as rigorously and transparently as the available evidence allows. Together, these three projects span the discipline a GRC analyst is expected to bring to almost any organization: conformance to an external standard, internal risk reasoning, and informed judgment about parties outside the organization's direct control.

---
*This assessment is based on Slack's publicly available security documentation as of mid-2026 and is intended as a self-directed portfolio exercise. It does not represent an official or contractual vendor risk determination.*
