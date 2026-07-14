# Canadian Finance Rules & Source Citations

Read this reference when you need tax rules, contribution limits, government program details,
or when a user asks "are you sure?" or "where did you get that number?"

**CURRENT NUMBERS LIVE ELSEWHERE:** All current-year dollar figures, rates, contribution limits,
tax brackets, and benefit amounts live in **`references/current-figures.md`** — that is the single
source of truth. Use those figures verbatim. This file holds the durable *rules*, structure, and
source-URL catalogue. For any figure not listed in `current-figures.md`, verify it against the
official source (canada.ca is always one) before using it in a calculation, and tell the user.

---

## Table of Contents

1. Tax Rules & Brackets
2. Registered Account Limits
3. CPP & OAS
4. Government Benefits & Credits
5. Investment Benchmarks
6. Estate Planning Rules
7. Self-Employed Rules
8. Source URLs

---

## 1. Tax Rules & Brackets

### Federal Tax Brackets
- Structure: five brackets (lowest rate, then 20.5% / 26% / 29% / 33% marginal tiers). The lowest
  federal rate dropped from 15% to 14% (phased in from July 1, 2025).
- Current bracket thresholds, exact rates, the basic personal amount (max/min), and the annual
  indexation factor: **see `references/current-figures.md`** (federal brackets + BPA lines). Use
  those verbatim.

### Provincial Brackets
Every province is different, and provincial thresholds are re-indexed annually. Always verify at
taxtips.ca/taxrates or the provincial government site before quoting. Note two recent structural
changes captured in `current-figures.md`: **Alberta is no longer effectively flat 10%** (new lower
bracket on the first ~$60K of income), and **Nova Scotia HST is 14%** (since Apr 1, 2025). Ontario
still has five brackets plus a surtax — verify the current thresholds; do not quote from memory.

### Capital Gains
- Inclusion rate: 50% (the proposed increase to 66.67% was cancelled in March 2025)
- Always verify current rate — this is politically volatile

### Key Tax Deductions & Credits
- Medical Expense Tax Credit: lesser of 3% of net income or a fixed threshold (current threshold in `references/current-figures.md`)
- Moving expenses: deductible if moving 40+ km closer to work/school
- Canada Workers Benefit: for low-income working individuals/families
- Canada Training Credit: $250/year accumulation for eligible training
- Charitable donations: lowest federal rate on first $200, 29% above (33% to the extent income sits in the top bracket — current top-bracket threshold in `references/current-figures.md`)

---

## 2. Registered Account Limits

### RRSP
- Annual limit = 18% of prior-year earned income, capped at the year's dollar maximum (current dollar limit in `references/current-figures.md`)
- Contribution deadline: 60 days after year-end (typically March 1 or 2)
- Must convert to RRIF by December 31 of the year you turn 71
- Spousal RRSP: contributor gets deduction, spouse owns the account
  - Attribution rule: funds must stay for remainder of contribution year + 2 full calendar years
- HBP: withdraw up to $60,000 for first home, repay over 15 years
- LLP: withdraw up to $20,000 for education, repay over 10 years

### TFSA
- Annual limit and cumulative room since 2009 (for someone 18+ since 2009): see `references/current-figures.md`
- Room accumulates from year you turn 18 AND become a Canadian resident
- Not subject to attribution rules — give money to spouse for their TFSA freely
- Withdrawals create new room the following January 1

### RESP
- Lifetime contribution limit: $50,000 per beneficiary
- No annual limit, but CESG is based on annual contributions
- CESG: 20% match on first $2,500/year per child = $500 max/year
  - Lifetime CESG cap: $7,200 per beneficiary
  - Additional CESG for lower income: 10-20% on first $500 contributed
  - Carry-forward: if room exists, contribute $5,000 to get $1,000 CESG (max $1,000/year with catch-up)
  - CESG stops at end of year child turns 17
  - Age 16-17 restriction: must have contributed $2,000+ before year child turned 16
- Canada Learning Bond (CLB): $500 initial + $100/year for low-income families, no contribution required

### FHSA (First Home Savings Account)
- Annual limit: $8,000 (can carry forward $8,000 unused room, max $16,000 in a year)
- Lifetime limit: $40,000
- Must be first-time home buyer (haven't owned in current or prior 4 years)
- Tax deduction on contributions (like RRSP) + tax-free growth and withdrawal (like TFSA)
- Must use within 15 years of opening or by age 71

### RDSP (Registered Disability Savings Plan)
- Requires Disability Tax Credit (DTC) eligibility
- Lifetime contribution limit: $200,000 (no annual cap)
- CDSG (Canada Disability Savings Grant): matching depends on family income (the income cutoff is indexed annually — verify current threshold):
  - At or below the cutoff: 300% on first $500 + 200% on next $1,000 = up to $3,500/year
  - Above the cutoff: 100% on first $1,000 = up to $1,000/year
  - Lifetime CDSG cap: $70,000. Paid until year beneficiary turns 49.
- CDSB (Canada Disability Savings Bond): up to $1,000/year for low-income, no contribution needed, $20,000 lifetime
- 10-year holdback rule: $3 of grants/bonds repaid per $1 withdrawn if received in prior 10 years
- After age 60: holdback drops to zero, funds fully vested
- RDSP is exempt from asset tests for provincial social assistance in most provinces

---

## 3. CPP & OAS

### CPP (Canada Pension Plan)
- YMPE (max pensionable earnings), YAMPE (second/CPP2 ceiling), max monthly benefit at 65, and the average new-beneficiary benefit: see `references/current-figures.md`
- Early (age 60): reduced 0.6%/month × 60 months = 36% reduction
- Deferral (to age 70): increased 0.7%/month × 60 months = 42% increase
- Break-even ages: 60 vs 65 ≈ age 74 | 65 vs 70 ≈ age 82 | 60 vs 70 ≈ age 77
- CPP2: additional contributions on earnings between YMPE and YAMPE, 4% employee + 4% employer
- Survivor's pension: NOT enhanced by contributor's deferral
- CPP pension sharing: both spouses must be 60+, split based on years cohabiting during contributory period

**Professional consensus:** Defer to 70 if financially feasible — 8.4%/year guaranteed, inflation-indexed. Exceptions: health concerns, financial hardship, strong lifestyle preference, or need for bridge income.

### OAS (Old Age Security)
- Eligible at 65 with 10+ years of Canadian residency (partial) or 40+ years (full)
- Maximum monthly amounts (age 65-74 and 75+, indexed quarterly), the clawback start and full-clawback thresholds, and the GIS maximum: see `references/current-figures.md`
- Deferral: 0.6%/month increase, max 36% at age 70 (no early OAS; deferral also delays GIS)

---

## 4. Government Benefits & Credits

### Federal
- Canada Child Benefit (CCB): per-child maximums (under 6 / ages 6-17) and the AFNI phase-out start point for the current benefit year — see `references/current-figures.md`. Paid monthly, income-tested.
- Canada Groceries and Essentials Benefit (CGEB): **replaces the GST/HST credit from July 2026** (~25% higher; paid quarterly, income-tested). Current base amounts in `references/current-figures.md`. (Do NOT tell users to expect a separate GST/HST credit or a one-time top-up — the final top-up was already paid June 2026.)
- Canada Workers Benefit: for low-income workers (current amounts in `references/current-figures.md`)
- Canada Dental Care Plan (CDCP): income-based eligibility
- Canada Disability Benefit: for working-age DTC holders
- EI special benefits: maternity (15 weeks), parental (35-61 weeks), sickness (26 weeks), caregiver (35 weeks)

### Provincial (the skill must check the user's province)
Every province has unique programs. Common ones:
- **Ontario:** Trillium Benefit (energy + property tax + sales tax credits), Ontario Child Benefit, ODSP, Ontario Works, OESP, Drug Benefit, CARE tax credit
- **BC:** BC Family Benefit (formerly Child Opportunity Benefit), Fair PharmaCare, CleanBC (note: the BC Climate Action Tax Credit ended alongside the federal carbon rebate — do not list it as active)
- **Alberta:** AISH, Alberta Child and Family Benefit, Alberta Seniors Benefit
- **Quebec:** Solidarity Tax Credit, reduced-contribution ("$X/day") subsidized childcare (the daily rate is indexed annually — verify), QPP (not CPP), unique tax system

Always web-search for the user's specific province to confirm current programs.

---

## 5. Investment Benchmarks

### FP Canada 2025 Projection Assumption Guidelines
- Conservative (40/60 portfolio): ~2.7% real return (~4.8% nominal, 2.1% inflation)
- Moderate (60/40 portfolio): ~3.4% real return (~5.5% nominal)
- Aggressive (80/20 portfolio): ~4.1% real return (~6.2% nominal)
- Always label whether showing real or nominal returns

### All-in-One ETF MERs (verify — these change)
- VGRO (Vanguard Growth, 80/20): 0.17%
- XGRO (iShares Growth, 80/20): 0.20%
- ZGRO (BMO Growth, 80/20): 0.20%
- VBAL/XBAL/ZBAL (Balanced, 60/40): similar MERs
- VEQT/XEQT/ZEQT (All-equity, 100/0): similar MERs

### Fee Impact Math
On $100,000 over 25 years at 6% nominal growth:
- At 0.20% MER: grows to ~$386,000
- At 2.30% MER: grows to ~$246,000
- Difference: ~$140,000 lost to fees

### Managed Investing Platforms (verify fees — they change)
- Wealthsimple Managed: 0.40-0.50% management + ~0.20% fund fees
- Questrade QuestWealth: 0.20-0.25% management
- BMO SmartFolio: 0.40-0.70%
- RBC InvestEase: 0.50% + fund fees

### GIC Rates
Never hardcode GIC rates. Always direct users to ratehub.ca or similar comparison sites.
Online banks (EQ Bank, Oaken, Achieva) consistently offer better rates than big banks.

### Housing Guidelines
- CMHC GDS (Gross Debt Service): housing costs ≤32% of gross income
- CMHC TDS (Total Debt Service): all debt payments ≤40% of gross income
- 50/30/20 rule: 50% needs, 30% wants, 20% savings

### CDIC Coverage
- $100,000 per deposit category per member institution
- Categories: deposits in one name, joint deposits, RRSPs, TFSAs, RRIFs, FHSAs

---

## 6. Estate Planning Rules

### Deemed Disposition at Death
- CRA treats all assets as sold at fair market value on date of death
- RRSPs/RRIFs: fully taxable (100%, not 50%) unless rolled to surviving spouse
- Capital gains: 50% inclusion rate on non-registered investments
- Principal residence exemption: no tax on primary home gain

### Probate Fees by Province
See `references/current-figures.md` (Probate section) for exact rates and sources. Key points:
- **Manitoba: $0 — probate fees were eliminated (Nov 6, 2020).** Not "essentially zero."
- **Ontario: first $50,000 is EXEMPT, then $15 per $1,000 (1.5%) on the amount above $50,000** (e.g. a $500K estate → $6,750). The pre-2020 two-tier rate is dead.
- **Quebec: notarial wills need NO probate;** holograph/witnessed wills need court or notary validation (fee varies — do not quote a dollar amount).
- Alberta: flat brackets, maximum $525 (estates over $250K), $35 minimum.
- BC: $0 to $25K; $6/$1,000 on $25K–$50K (0.6%); $14/$1,000 above (1.4%).
- Saskatchewan: $200 flat + $7/$1,000 of estate assets.

### Beneficiary Designations
Bypass probate when named: RRSP, RRIF, TFSA, FHSA, life insurance
Go through probate: RESP, RDSP, non-registered investments, bank accounts (unless joint), real estate

### Quebec Terminology
Powers of Attorney are called "protection mandates" (mandat de protection) in Quebec.

---

## 7. Self-Employed Rules

### Salary vs Dividends (Incorporated)
- Salary: creates RRSP room, builds CPP, qualifies for mortgage, eligible for EI/parental leave
- Dividends: avoids CPP contributions, simpler admin, sometimes more tax-efficient
- Most advisors recommend a blend

### Small Business Deduction
- Federal: 9% on first $500,000 of active business income (CCPC)
- Combined federal+provincial: 9-12% depending on province
- Above $500K: jumps to 23-31%

### IPP (Individual Pension Plan)
- For incorporated owners age 40+
- Contribution limits exceed the RRSP dollar maximum, and the gap widens with age (compare against the current RRSP limit in `references/current-figures.md`)
- Setup: ~$3,000, actuarial valuations ~$2,000 every 3 years
- Requires T4 salary of $100K+

### HSA (Health Spending Account)
- Corporation pays medical/dental as tax-deductible expense, received tax-free
- Sole proprietors need at least one arm's-length employee to qualify
- Eligible expenses: prescriptions, dental, vision, paramedical, mental health

### Quarterly Tax Installments
- Required if net tax owing >$3,000 in current and either of prior two years
- Due: March 15, June 15, September 15, December 15
- CRA charges compound daily interest on late/deficient payments

---

## 8. Source URLs

For the authoritative `[Source: URL]` behind any current figure (brackets, limits, CPP/OAS/GIS,
benefits, probate), see the matching line in `references/current-figures.md` — quote those URLs
exactly; never construct a URL.

### Tax Rules & Limits
- RRSP/TFSA/FHSA limits: canada.ca/en/revenue-agency/services/tax/registered-plans-administrators/pspa/mp-rrsp-dpsp-tfsa-limits-ympe.html
- Federal tax brackets: canada.ca — Canadian income tax rates for individuals
- Provincial brackets: taxtips.ca/taxrates.htm
- Medical Expense Tax Credit: canada.ca/en/revenue-agency/services/forms-publications/publications/rc4065/medical-expenses.html
- Capital gains: canada.ca — line 12700 taxable capital gains

### CPP, OAS & Benefits
- CPP payment amounts: canada.ca/en/services/benefits/publicpensions/cpp/payment-amounts.html
- When to start CPP: canada.ca/en/services/benefits/publicpensions/cpp/when-start.html
- OAS payments & clawback: canada.ca/en/services/benefits/publicpensions/old-age-security/payments.html
- CCB: canada.ca/en/revenue-agency/services/child-family-benefits/canada-child-benefit-overview.html
- GIS: canada.ca/en/services/benefits/publicpensions/old-age-security/guaranteed-income-supplement.html
- Canada Groceries and Essentials Benefit (CGEB, replaces GST/HST credit July 2026): canada.ca/en/department-finance/news/2026/01/the-new-canada-groceries-and-essentials-benefit.html

### Registered Accounts
- CESG: canada.ca — canada-education-savings-grant-cesg.html
- RDSP/CDSG/CDSB: canada.ca — canada-disability-savings-grant-canada-disability-savings-bond.html
- FHSA: canada.ca — first-home-savings-account.html

### Investing
- FP Canada Projection Assumptions: fpcanada.ca/projection-assumption-guidelines
- ETF MERs: verify at vanguard.ca, blackrock.com/ca (iShares), bmogam.com
- CDIC: cdic.ca
- GIC rate comparisons: ratehub.ca/gics

### Estate
- Deemed disposition: canada.ca — what-when-someone-died.html
- Probate fees: taxtips.ca/willsandestates/probate-fees-by-province-territory.htm (per-province official sources in `references/current-figures.md` — e.g. Ontario ontario.ca/laws/statute/98e34; Manitoba elimination notice manitobacourts.mb.ca)

### Self-Employed
- HSA eligibility: canada.ca — warning-buyer-beware-health-spending-accounts
- IPP: nbc.ca — understanding-the-individual-pension-plan

### Crypto
- CRA crypto treatment: canada.ca — cryptocurrency-guide/income-crypto-transactions.html
- Mining & staking: canada.ca — cryptocurrency-guide/income-crypto-mining-staking-activities.html

### Statistics
- 52% without wills: Angus Reid Institute (2024)
- 51% would end relationship over finances: Simplii Financial / Ipsos
- 12% of 85+ in LTC: Statistics Canada
