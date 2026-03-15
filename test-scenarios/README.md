# Test Scenarios — Skill vs No-Skill Comparison

This folder contains 12 test personas designed to evaluate the Canadian Personal Finance Manager skill against plain AI (no skill).

## How to Run the Tests

### With Skill
1. Open Claude desktop with the financial-planner skill installed
2. Copy the prompt from `prompt-template.md`
3. Replace `[PASTE PERSONA DATA HERE]` with the contents of a persona file from `personas/`
4. Let the skill run through its full process
5. Save all output to `results/XX-persona-name/with-skill/`

### Without Skill
1. Open a NEW Claude conversation (no skill installed) or ChatGPT
2. Copy the exact same prompt from `prompt-template.md`
3. Replace `[PASTE PERSONA DATA HERE]` with the same persona data
4. Save the response to `results/XX-persona-name/without-skill/`

### Tips
- Use the same AI model version for both tests when possible
- Don't give hints or follow-up prompts — judge the first response
- Save the full, unedited output

---

## The 12 Test Personas

| # | Persona | Province | Key Challenge | Features Tested |
|---|---------|----------|---------------|-----------------|
| 1 | Marcus & Sarah Chen | ON | Young couple, 2 kids, moderate debt | Core planning, RESP/CESG, insurance gaps, mortgage |
| 2 | Priya Sharma | BC | Newcomer from India, 6 months in Canada | Cross-border, credit building, TFSA/RRSP room, T1135 |
| 3 | Dave & Lisa Tremblay | QC | Incorporated consultant + employed spouse | Self-employed, salary vs dividends, QPP, Quebec tax |
| 4 | Robert & Marie Leblanc | NB | Near-retiree couple, DB pension | CPP/OAS timing, RRSP meltdown, pension splitting |
| 5 | Tanya Williams | AB | Single mom, debt crisis, payday loans | Consumer proposal, credit rebuilding, CCB, crisis planning |
| 6 | Jim & Carol Henderson | ON | Retired snowbirds, US condo | Substantial presence test, FIRPTA, US estate tax, Form 8840 |
| 7 | Dr. Aisha Patel | ON | High-income physician, incorporated | IPP, corp retention, OAS clawback, tax optimization |
| 8 | Tyler Nguyen | AB | Age 22, first job, zero savings | Starter plan, emergency fund, first TFSA, basic ETFs |
| 9 | Mark & Jennifer Foster | ON | Blended family, second marriage | Estate planning, beneficiary issues, wills, guardianship |
| 10 | Sam Rivera | BC | Freelance designer, variable income | HST, quarterly installments, irregular budgeting |
| 11 | Michael & Sarah Thompson | ON | US citizen in Canada + Canadian spouse | FBAR/FATCA, dual filing, Roth IRA, cross-border estate |
| 12 | Dorothy Walsh | NS | Age 72, widowed, inherited $350K | GIS optimization, RRIF strategy, estate simplification |

---

## Scoring Rubric

Score each output on the criteria below. Each criterion is scored:
- **0** = Missing or incorrect
- **1** = Partially correct or vague
- **2** = Fully correct with specific numbers

### A. Accuracy (score only criteria that apply to the persona)

| # | Criterion | With Skill | Without Skill |
|---|-----------|-----------|---------------|
| A1 | Correct marginal tax rate (federal + provincial) | | |
| A2 | Correct registered account contribution room | | |
| A3 | Correct government benefit amounts (CCB, GST credit, etc.) | | |
| A4 | Correct debt payoff order with math (interest saved) | | |
| A5 | Correct CPP/OAS timing analysis with break-even ages | | |
| A6 | Correct provincial rules applied (not generic) | | |
| A7 | Insurance gap correctly identified with DIME or similar | | |
| A8 | Net worth calculated correctly | | |

### B. Completeness

| # | Criterion | With Skill | Without Skill |
|---|-----------|-----------|---------------|
| B1 | All income sources captured (including benefits) | | |
| B2 | All expenses itemized (not lumped into "other") | | |
| B3 | All debts listed with payoff strategy | | |
| B4 | Registered accounts analyzed (RRSP, TFSA, RESP, FHSA) | | |
| B5 | Insurance gaps flagged with cost estimates | | |
| B6 | Estate planning addressed (wills, POA, beneficiaries) | | |
| B7 | Cross-border obligations identified (if applicable) | | |
| B8 | Self-employed deductions/structure addressed (if applicable) | | |

### C. Actionability

| # | Criterion | With Skill | Without Skill |
|---|-----------|-----------|---------------|
| C1 | Specific dollar amounts (not "save more") | | |
| C2 | Timeline with dates (not "eventually") | | |
| C3 | Prioritized action items (what first, second, third) | | |
| C4 | Phase-based plan (not just a flat list) | | |
| C5 | Spending insights (what to keep, cut, redirect) | | |
| C6 | "Money left on the table" identified (unused benefits, high fees) | | |

### D. Canadian-Specific Quality

| # | Criterion | With Skill | Without Skill |
|---|-----------|-----------|---------------|
| D1 | Uses correct Canadian terms (RRSP not 401k, TFSA not Roth) | | |
| D2 | References correct CRA forms (T1135, T2209, etc.) | | |
| D3 | Cites correct thresholds (OAS clawback, CCB phase-out) | | |
| D4 | Addresses provincial variations (not one-size-fits-all) | | |
| D5 | Mentions relevant government benefits the person qualifies for | | |
| D6 | Includes CRA deadlines and calendar items | | |

### Scoring Summary

| Category | Max Score | With Skill | Without Skill |
|----------|----------|-----------|---------------|
| A. Accuracy (16) | /16 | | |
| B. Completeness (16) | /16 | | |
| C. Actionability (12) | /12 | | |
| D. Canadian Quality (12) | /12 | | |
| **Total** | **/56** | | |

---

## Comparison Summary (fill in after testing)

| Persona | With Skill (/56) | Without Skill (/56) | Delta | Key Differences |
|---------|-----------------|--------------------|---------|--------------------|
| 1. Chen family | | | | |
| 2. Priya (newcomer) | | | | |
| 3. Tremblay (self-employed) | | | | |
| 4. Leblanc (retiree) | | | | |
| 5. Tanya (debt crisis) | | | | |
| 6. Henderson (snowbird) | | | | |
| 7. Dr. Patel (high income) | | | | |
| 8. Tyler (starter) | | | | |
| 9. Foster (blended family) | | | | |
| 10. Sam (gig worker) | | | | |
| 11. Thompson (US citizen) | | | | |
| 12. Dorothy (widow) | | | | |
| **Average** | | | | |
