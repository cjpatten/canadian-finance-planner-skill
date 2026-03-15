# Cross-Border, Snowbird & Newcomer Planning — Deep-Dive for Canadians

Read this reference when the user has international connections: newcomer/immigrant to Canada,
snowbird (winters in the US or abroad), owns US property, leaving Canada, returning to Canada,
has foreign pension income, is a US citizen living in Canada, or has FBAR/FATCA questions.

All dollar amounts and thresholds should be verified via web search before presenting — treaty
interpretations change, thresholds are indexed, and provincial rules vary. Key sources: canada.ca
(CRA international), irs.gov, taxtips.ca, provincial health ministries. Full source URLs in
Section 12.

---

## Table of Contents

1. When to Use This Reference
2. Tax Residency — How Canada Determines It
3. Snowbird Tax Planning (US/Canada)
4. Canadians Owning US Real Estate
5. Newcomers to Canada
6. Departure from Canada (Emigration)
7. Foreign Pension Income
8. FBAR & FATCA (US Reporting Obligations)
9. Returning to Canada
10. Foreign Tax Credits — Avoiding Double Taxation
11. When to Refer to a Professional
12. Source URLs

---

## 1. When to Use This Reference

Load this file when the user mentions ANY of these:
- Moving to Canada, just arrived, immigrant, newcomer, refugee, PR, work permit
- Moving away from Canada, leaving, emigrating, departure tax
- Snowbird, wintering in US, spending time in Florida/Arizona, days counting
- Owning US property, vacation home in US, rental in US, buying in US
- Foreign income, foreign pension, US Social Security, UK pension
- US citizen in Canada, green card holder, dual citizen
- FBAR, FATCA, T1135, foreign assets, foreign bank accounts
- Returning to Canada after time abroad, re-establishing residency
- Non-resident tax status, tax residency determination, NR73

**Cross-references:**
- For US withholding tax on investments and US estate tax on portfolios → `references/portfolio-management.md` Section 6
- For provincial health coverage details → `references/provincial-rules.md`
- For RRSP/TFSA/RESP general rules → `references/canada-finance-rules.md`

---

## 2. Tax Residency — How Canada Determines It

### Significant Residential Ties (Primary Test)
Canada determines tax residency based on **ties**, not just days present:

**Primary ties (any one = likely resident):**
- Home in Canada (owned or leased, available for your use)
- Spouse or common-law partner in Canada
- Dependants in Canada

**Secondary ties (considered together):**
- Personal property in Canada (car, furniture, clothing)
- Social ties (memberships, clubs, professional associations)
- Economic ties (Canadian bank accounts, credit cards, RRSP, investments)
- Provincial health insurance
- Canadian driver's licence
- Canadian passport
- Landed immigrant status

### Factual vs Deemed Residency

| Type | How Determined | Tax Implications |
|------|---------------|-----------------|
| **Factual resident** | Based on ties analysis above | Taxed on worldwide income |
| **Deemed resident** | Present in Canada 183+ days in a year with no residential ties elsewhere | Taxed on worldwide income |
| **Non-resident** | Severed all significant ties AND established ties elsewhere | Taxed only on Canadian-source income |
| **Deemed non-resident** | Resident of another country under a tax treaty tie-breaker | Treated as non-resident for tax purposes |

### CRA Forms for Residency Determination
- **NR73 — Determination of Residency Status (Leaving Canada):** File when emigrating — CRA issues opinion
- **NR74 — Determination of Residency Status (Entering Canada):** File when immigrating — CRA issues opinion
- These are optional but recommended for borderline cases. CRA response takes 6-8 weeks.

(Source: canada.ca — Determining Your Residency Status, IT-221R3)

---

## 3. Snowbird Tax Planning (US/Canada)

### The US Substantial Presence Test

If you meet this test, the IRS considers you a **US resident for tax purposes** — meaning you'd
owe US tax on worldwide income. The test uses a **3-year weighted formula**:

```
Days in current year × 1.0
+ Days in prior year × 1/3
+ Days two years ago × 1/6
= Weighted total
```

**If the weighted total ≥ 183 → you meet the substantial presence test.**

**Example:** A snowbird spending 150 days/year in the US:
- Current year: 150 × 1.0 = 150
- Prior year: 150 × 1/3 = 50
- Two years ago: 150 × 1/6 = 25
- **Total: 225 → EXCEEDS 183 → meets the test**

**Safe zone:** ~120 days/year passes safely (120 + 40 + 20 = 180 < 183)

### Closer Connection Exception (Form 8840)

Even if you meet the substantial presence test, you can claim an **exception** if:
1. You were present in the US **fewer than 183 actual days** that tax year
2. You maintained a **closer connection** to Canada (tax home in Canada)
3. You had a **tax home in Canada** for the entire year
4. You are **not applying for US permanent residency**

**Form 8840 (Closer Connection Exception Statement):**
- Must be filed by **June 15** of the following year
- **CRITICAL:** Failure to file = loss of the exception. File it every year you're near the limit.
- Document your closer connection: Canadian home, bank accounts, driver's licence, health card,
  memberships, family, voting registration, church, etc.

### Days That Don't Count
- Days in transit between two foreign countries (less than 24 hours in US)
- Days you intended to leave but couldn't due to a medical condition (with Form 8843 documentation)
- Commuting from Canada for work (regular cross-border commuters)

### Canadian Side — 183-Day Rule
- If you're away from Canada 183+ days AND have severed significant residential ties,
  you may be considered a **non-resident** of Canada
- But ties matter more than days — a snowbird who keeps their Canadian home, spouse in Canada,
  and bank accounts is almost always still a Canadian resident

### Practical Snowbird Strategy
1. **Track your days meticulously** — keep a log, passport stamps, flight records
2. **Stay under 150 US days/year** to build a safety margin
3. **File Form 8840 every year** if spending 100+ days in US
4. **Maintain strong Canadian ties** — keep your home, bank accounts, health card, memberships
5. **Get travel medical insurance** — provincial health insurance typically covers 0 days or very
   limited coverage outside Canada (varies by province: ON covers some, BC/AB/QC cover very little)
6. **Notify your province** of planned absence duration — some provinces cancel health coverage
   after 6-7 months away

### Health Insurance Gap
- Canadian provincial health care has **limited or zero coverage** outside Canada
- Snowbird medical insurance: $1,500-$8,000+/year depending on age, health, and duration
- Pre-existing condition clauses can void coverage if not disclosed
- **Always buy travel medical insurance before leaving Canada**

(Source: irs.gov — Substantial Presence Test, Publication 519, Form 8840 instructions)

---

## 4. Canadians Owning US Real Estate

### FIRPTA — Sale of US Property

**Foreign Investment in Real Property Tax Act (FIRPTA):**
- When a non-US person sells US real property, the **buyer must withhold 15% of the gross sale price**
  and remit it to the IRS
- This is a **withholding**, not the final tax — you may get some back when filing a US tax return
- **Personal residence exception:** If the buyer intends to use the property as a residence AND
  the sale price is ≤ $1,000,000 USD → **no FIRPTA withholding required**

**Example:** Canadian sells US vacation condo for $500,000 USD:
- FIRPTA withholding: $75,000 USD (15%)
- Actual capital gains tax may be less — file US return to claim refund of excess

### US Estate Tax Exposure

**For non-US citizens/non-residents:**
- US estate tax applies if **US-situs assets exceed $60,000 USD**
- US-situs assets include: US real estate, US stocks held directly, tangible property in US
- **Tax rate:** Up to 40% on amounts above the exemption

**Canada-US Tax Treaty protection:**
- If your **worldwide estate ≤ ~$1.2 million USD** (prorated unified credit), you likely owe no US estate tax
- Treaty provides a prorated share of the US unified credit based on (US assets / worldwide assets)
- **Form 706-NA** required if US-situs assets exceed $60,000 USD

**Planning strategies:**
- Hold US real estate in a Canadian corporation (can eliminate estate tax but creates other complications)
- Joint ownership with spouse (defers estate tax on first death)
- Life insurance to cover potential US estate tax liability
- For portfolios: use Canadian-listed ETFs instead of US-listed stocks for large holdings ($1M+)

### Rental Income Reporting (Dual)

If you rent out US property, you must report the income in **both countries**:

**US filing:**
- File US non-resident return (Form 1040-NR)
- Report rental income on Schedule E
- Claim US deductions (depreciation, maintenance, property tax, insurance, management fees)
- **Depreciation:** US allows 27.5-year straight-line depreciation on residential rental property
  (reduces US tax now but triggers "depreciation recapture" at up to 25% when you sell)

**Canadian filing:**
- Report net rental income (after expenses) on your Canadian return
- CCA (Capital Cost Allowance) rules differ from US depreciation — be careful of mismatches
- Claim **foreign tax credit** (Form T2209) for US taxes paid to avoid double taxation

### Form W-8BEN
- **Purpose:** Certifies your foreign (non-US) status to reduce withholding on US investment income
- Required when opening US bank/investment accounts
- Valid for 3 years, then must be renewed
- Reduces US withholding from 30% to 15% (treaty rate) on dividends and interest

(Source: irs.gov — FIRPTA, Publication 515, Publication 519; taxtips.ca — US Estate Tax)

---

## 5. Newcomers to Canada

### First Steps — Financial Onboarding Checklist

**Immediate (first month):**
- [ ] Apply for **Social Insurance Number (SIN)** — needed for employment, tax filing, and government benefits
  (Service Canada office with immigration documents)
- [ ] Open a **Canadian bank account** — major banks have newcomer packages with no-fee periods
  (TD, RBC, BMO, Scotiabank all offer newcomer accounts)
- [ ] Apply for provincial **health card** — most provinces have a 1-3 month waiting period
- [ ] Get a **Canadian phone number** — needed for credit building and SIN application
- [ ] Apply for a **secured credit card** — start building Canadian credit immediately

**Within 3 months:**
- [ ] File for **Canada Child Benefit (CCB)** if you have children under 18
- [ ] Register for **GST/HST credit** (automatic with first tax return)
- [ ] Open a **TFSA** (if 18+ and now a Canadian resident — room starts accumulating from arrival year)
- [ ] Look into **settlement services** — free government-funded services for newcomers
  (language training, employment help, community connections)

**Within first year:**
- [ ] File your **first Canadian tax return** (due April 30 of the year after arrival)
- [ ] Open an **RRSP** once you have Canadian earned income (room starts from first year of Canadian employment)
- [ ] Report foreign assets > $100,000 CAD on **Form T1135** with your tax return

### RRSP Room for Newcomers
- RRSP contribution room = 18% of **Canadian-source earned income** from prior year
- **First year:** No room (no prior-year Canadian income). Room begins accumulating the year after arrival.
- **Previous foreign employment:** Does NOT create Canadian RRSP room
- **Request your RRSP Deduction Limit** from CRA My Account once your first return is processed

### TFSA Room for Newcomers
- Accumulates from **January 1 of the year you became a Canadian resident** (if 18+)
- Or from January 1 of the year you turned 18, if you were already resident
- **Previous years as a non-resident:** No TFSA room accumulated
- Example: Arrive in Canada in March 2026, age 30 → TFSA room for 2026 = $7,000 (just the current year)
- **Do NOT contribute before becoming a resident** — non-resident contributions are penalized (1%/month tax)

### Deemed Acquisition at Fair Market Value
- When you become a Canadian resident, all your assets are treated as **acquired at their current
  fair market value (FMV)** on the date you establish residency
- Only **future appreciation** (above that FMV) is taxable in Canada
- **Keep records** of all asset values on your arrival date — you'll need them when you eventually sell

### Foreign Asset Reporting — Form T1135
- Required if total **cost** of specified foreign property exceeds **$100,000 CAD at any time** during the year
- Specified foreign property includes: foreign bank accounts, investment accounts, foreign rental
  property, shares of foreign corporations, foreign life insurance policies
- **Simplified reporting:** If cost between $100K-$250K, use the simplified tick-box method
- **Penalty for non-filing:** Up to $2,500/year (or more for gross negligence)
- **Note:** RRSPs, TFSAs, and employer pension plans are NOT specified foreign property

### Credit Building from Zero
Canadian credit history does **not** transfer from other countries. Start fresh:

1. **Secured credit card** (deposit = credit limit): ~$500-$1,000 to start
2. **Prepaid phone plan** or postpaid with credit check — shows up on credit report
3. **Newcomer bank products** — some banks report account activity to credit bureaus
4. **After 6-12 months:** Apply for unsecured credit card
5. **After 12-18 months:** Credit score should be established enough for auto financing
6. **After 2-3 years:** Mortgage eligibility with good credit history

**Credit score target:** 680+ for competitive mortgage rates, 600+ for basic credit products

(Source: canada.ca — Newcomers to Canada, T1135, CRA My Account; Service Canada — SIN)

---

## 6. Departure from Canada (Emigration)

### Deemed Disposition — "Departure Tax"

When you leave Canada (sever residential ties), CRA treats you as having **sold all your
property at fair market value** immediately before departure. This triggers capital gains tax
on any appreciation.

**What's subject to deemed disposition:**
- Stocks, bonds, mutual funds, ETFs (in non-registered accounts)
- RRSP and RRIF — NOT deemed disposed, but become subject to withholding tax on future withdrawals
- Business interests, partnership units
- Real estate **outside** Canada (foreign property)
- Personal-use property with FMV > $1,000

**What's EXEMPT from deemed disposition:**
- **Canadian real estate** — NOT subject to departure tax (it remains Canadian-situs and taxable when actually sold)
- **Principal residence** — exempt under principal residence exemption (same as normal)
- RRSP/RRIF accounts (remain, but non-resident withholding applies to withdrawals: 25% or 15% treaty rate)
- Pension plan interests

### Forms Required

| Form | When Required | Purpose |
|------|--------------|---------|
| **T1161** — List of Properties | Total FMV of all properties > $25,000 | Comprehensive asset list for CRA |
| **T1243** — Deemed Disposition | Deemed disposition applies | Calculate and report capital gains |
| **T2062** — Certificate of Compliance | Disposing of Canadian taxable property | Get clearance before selling Canadian assets post-departure |

### Post-Departure Tax Obligations
- **Canadian-source income only:** After departure, Canada taxes you only on Canadian-source income
  (rental income, employment income, business income, capital gains on Canadian real property)
- **Withholding on Canadian income:**
  - Pension/RRSP/RRIF withdrawals: 25% (reduced to 15% under Canada-US treaty)
  - Rental income: 25% on gross (or elect under Section 216 to file a return and pay on net)
  - Investment income (dividends, interest): 25% (reduced to 15% under treaty)

### What You Lose on Departure
- **CCB** — stops when you become a non-resident
- **GST/HST credit** — stops
- **TFSA** — cannot contribute while non-resident (no penalty for keeping existing TFSA, but no new room)
- **Provincial health coverage** — coverage ends after departure (some provinces: immediately; others: up to 3 months)
- **OAS** — can still receive if qualified, but may be clawed back at higher rates for non-residents

### Section 220(4.5) — Security Instead of Paying

If the departure tax would be hardship, you can elect to **defer the tax** by posting security
(letter of credit or bond) with CRA. Interest accrues but no payment required until you
actually dispose of the property.

(Source: canada.ca — Leaving Canada (Emigrants), T1161, T1243, taxtips.ca — Leaving Canada)

---

## 7. Foreign Pension Income

### Canada-US Tax Treaty — Pension Provisions (Article XVIII)

| Pension Type | Canadian Withholding (to US resident) | US Treatment | Notes |
|-------------|--------------------------------------|-------------|-------|
| RRSP/RRIF withdrawal | 15% (treaty rate) | Taxable income | Claim foreign tax credit on US return |
| CPP/OAS to US resident | 25% default, 15% treaty | Taxable income | Section 217 election may reduce |
| US Social Security to Canadian resident | N/A | Generally taxable only in US | Include 85% on Canadian return per treaty |
| US 401(k)/IRA to Canadian resident | 15% US withholding (treaty) | Taxable in Canada | Claim foreign tax credit (T2209) |
| UK pension to Canadian resident | Treaty-dependent | Taxable in Canada | Complex — see professional |

### US Social Security for Canadians
- If you earned US Social Security credits (worked 10+ years in US or combined Canada-US credits):
  - Apply through Service Canada or US SSA
  - **Canada-US Social Security Agreement** allows combining work periods
  - When received by a Canadian resident: 85% is included in Canadian taxable income (treaty provision)
  - File **Form T2209** for any US tax withheld

### Foreign Pension Transfer to RRSP
- **Very limited.** Generally, foreign pensions cannot be directly transferred to an RRSP.
- Some exceptions exist for **lump-sum payments** from foreign employer pension plans
  (must meet specific CRA criteria — consult a cross-border tax specialist)
- US IRA to RRSP: **Not a tax-free transfer.** Withdrawal from IRA is taxable in both countries
  (foreign tax credit applies to avoid double taxation)

### Totalization Agreements
Canada has **social security agreements** with 60+ countries. These allow:
- Combining work periods to meet minimum eligibility for pensions
- Avoiding double social security contributions
- Key countries: US, UK, France, Germany, Australia, Japan, India, Philippines

(Source: canada.ca — CPP International, irs.gov — Publication 597, canada.ca — Social Security Agreements)

---

## 8. FBAR & FATCA (US Reporting Obligations)

### Who Must File

**These obligations apply to US persons living in Canada:**
- US citizens (even if born in Canada to US parent, even if never lived in US)
- US permanent residents (green card holders)
- **NOT regular Canadian citizens** without US status

### FBAR — FinCEN Form 114 (Report of Foreign Bank and Financial Accounts)

| Item | Details |
|------|---------|
| **Threshold** | Aggregate value of ALL foreign accounts ≥ $10,000 USD at any time during the year |
| **What counts** | Bank accounts, investment accounts, mutual funds, RRSPs, TFSAs, RESPs — ALL foreign financial accounts |
| **Filing** | Electronically via FinCEN BSA E-Filing (NOT with IRS) |
| **Deadline** | April 15, automatic extension to October 15 |
| **Penalty (non-willful)** | Up to $10,000 USD per violation |
| **Penalty (willful)** | Greater of $100,000 USD or 50% of account balance |

**Key for US citizens in Canada:** Your Canadian bank accounts, RRSPs, TFSAs, and investment
accounts are ALL "foreign" accounts from the IRS perspective. Most US citizens in Canada must file FBAR.

### FATCA — Form 8938 (Statement of Specified Foreign Financial Assets)

| Filing Status | Threshold (Living Abroad) | Threshold (Living in US) |
|--------------|--------------------------|-------------------------|
| Single | >$200,000 USD year-end (or >$300K any time) | >$50,000 USD year-end (or >$75K any time) |
| Married filing jointly | >$400,000 USD year-end (or >$600K any time) | >$100,000 USD year-end (or >$150K any time) |

**Filed with:** IRS (attached to Form 1040)

### FBAR vs FATCA — Key Differences

| Feature | FBAR (FinCEN 114) | FATCA (Form 8938) |
|---------|-------------------|-------------------|
| Filed with | FinCEN | IRS |
| Threshold | $10,000 USD | $200,000+ USD (abroad) |
| What's reported | Financial accounts only | Financial accounts + other assets |
| Real estate | Excluded | Excluded (unless held through foreign entity) |
| Penalties | Severe ($10K-$100K+) | $10,000 per form + continuation penalties |

### Streamlined Filing Procedures
If a US citizen in Canada has **not been filing** US returns:
- **Streamlined Foreign Offshore Procedures** — file 3 years of returns + 6 years of FBARs with no penalties
  (if non-compliance was non-willful)
- Certify that failure was due to reasonable cause, not intentional tax evasion
- This is a one-time amnesty opportunity — do it before IRS contacts you

### Canadians WITHOUT US Status
- Generally **no FBAR or FATCA obligations** — these are US-person requirements
- Exception: If a Canadian institution classifies you as a "US person" (e.g., born in US, US address),
  they may report your accounts under FATCA's intergovernmental agreement (Canada-US IGA)
- **Renouncing US citizenship:** Requires filing 5 years of compliant returns, Form 8854,
  possible "exit tax" on worldwide assets

(Source: irs.gov — FBAR, Form 8938, Streamlined Procedures; FinCEN BSA E-Filing)

---

## 9. Returning to Canada

### Re-Establishing Tax Residency
- You become a Canadian tax resident again when you establish **significant residential ties**
  (move back into a home, bring spouse/family back, etc.)
- CRA evaluates the same ties as initial residency (Section 2 above)
- File **NR74** if you want a CRA opinion on your return date

### TFSA on Return
- **No room accumulates** for years you were a non-resident
- **Withdrawal room:** Amounts withdrawn while non-resident are added back as contribution room
  on January 1 of the year **after** you re-establish residency
- **Contributions while non-resident are penalized** at 1% per month — do NOT contribute until
  you're officially a resident again
- Example: Left Canada in 2023 with $80K TFSA. Became resident again March 2026.
  Your TFSA room for 2026 = $7,000 (current year only, since no room accumulated 2024-2025)

### RRSP on Return
- RRSP deduction room **continues accumulating** based on Canadian-source earned income (if any) while away
- Any room from before departure is preserved
- Verify your current limit via CRA My Account or NOA after filing your return year

### Provincial Health Insurance
- **Waiting period:** Most provinces impose a waiting period before coverage resumes:
  - Ontario: 3 months
  - BC: up to 3 months
  - Alberta: first day of 3rd month
  - Quebec: up to 3 months
- **Get travel medical insurance** to cover the gap
- Re-apply with proof of residency (lease, utility bill, employment letter)

### Restarting Benefits
- **CCB:** Re-apply using Form RC66 once you're a resident with children under 18
- **GST/HST credit:** Automatic once you file your return as a resident
- **OAS/CPP:** If you were receiving these abroad, notify Service Canada of your return
- **Provincial benefits:** Re-apply for any province-specific benefits (Trillium, BC Climate Action, etc.)

### First Tax Return After Return
- Report worldwide income from your return date onward
- Report Canadian-source income (if any) from January 1 to return date
- File Form **T1135** if foreign assets >$100K (you may still hold foreign assets from time abroad)

(Source: canada.ca — Non-Residents Entering Canada, TFSA Non-Resident rules, provincial health ministries)

---

## 10. Foreign Tax Credits — Avoiding Double Taxation

### How Foreign Tax Credits Work
If you paid tax to another country on income that's also taxable in Canada, you can claim a
**foreign tax credit** to avoid being taxed twice.

**Federal:** Form T2209
**Provincial:** Form T2036

### Calculation (Simplified)
```
Foreign tax credit = Lesser of:
  (a) Foreign tax actually paid on the income
  (b) Canadian tax otherwise payable on that income
```

You always end up paying the **higher** of the two countries' tax rates on that income.

### Common Scenarios

| Situation | US Tax | Canadian Tax | Result |
|-----------|--------|-------------|--------|
| US rental income | File 1040-NR, pay US tax | Report on Canadian return | Claim T2209 for US tax paid |
| US dividend withholding (15%) | Withheld at source | Include in Canadian income | Claim T2209 for withholding |
| RRSP withdrawal by US resident | Taxable in US | 15% Canadian withholding | Claim on US return for Canadian withholding |
| US Social Security to Canadian | Potentially US-taxable | Include 85% in Canadian income | Claim T2209 for any US tax paid |

### Key Rules
- **Excess credit:** If foreign tax exceeds Canadian tax on that income, the excess is **not refunded**
  (it's wasted — you can carry it back 1 year or forward 7 years in limited cases)
- **Must be income tax:** Only foreign income taxes qualify (not property taxes, sales taxes, etc.)
- **Must be on the same income:** The foreign tax must be on income that Canada also taxes
- **Timing:** Claim in the year the foreign tax is paid or accrued

### Competent Authority Assistance
If both countries tax the same income and foreign tax credits don't fully resolve the double
taxation, you can request **competent authority assistance** under the Canada-US Tax Treaty.
Contact CRA's Treaty and International Relations Division.

(Source: canada.ca — T2209, Income Tax Folio S5-F2-C1, taxtips.ca — Foreign Tax Credit)

---

## 11. When to Refer to a Professional

### Complexity Thresholds — Recommend Professional Help When:

**Always recommend a cross-border tax specialist if:**
- US citizen or green card holder living in Canada (dual filing obligations)
- Owning real estate in both countries
- Receiving income from both countries simultaneously
- Business with cross-border operations
- Leaving or entering Canada with assets >$500K
- Renouncing US citizenship
- Estate planning with cross-border assets

**Recommend an immigration lawyer if:**
- Residency status is unclear (NR73/NR74 pending)
- Permanent residency application in progress
- Work permit issues affecting tax status

**Recommend a fee-only financial planner if:**
- Cross-border retirement planning (CPP + US Social Security)
- Complex asset location decisions (which account in which country)
- Snowbird with total assets >$1M

### Finding Cross-Border Specialists
- **CPA Canada:** Look for CPAs with US CPA or EA (Enrolled Agent) designation
- **Canadian Tax Foundation:** Directory of international tax professionals
- **US-based:** H&R Block Expat Tax Services, Greenback Expat Tax, or a US CPA

**Typical costs:**
- Cross-border tax return preparation: $800-$3,000+ CAD (both countries)
- FBAR/FATCA compliance: $500-$1,500 CAD
- Streamlined filing (catch-up): $3,000-$8,000 CAD
- Cross-border financial plan: $2,000-$5,000 CAD

---

## 12. Source URLs

### CRA — International & Non-Residents
- Determining Residency Status: https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/information-been-moved/determining-your-residency-status.html
- Newcomers to Canada: https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/individuals-leaving-entering-canada-non-residents/newcomers-canada-immigrants.html
- Leaving Canada (Emigrants): https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/individuals-leaving-entering-canada-non-residents/leaving-canada-emigrants.html
- Non-Resident TFSA Rules: https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/tax-free-savings-account/non-resident.html
- T1135 Foreign Income Verification: https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/t1135.html
- Form T2209 (Foreign Tax Credit): https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/t2209.html
- CPP International: https://www.canada.ca/en/services/benefits/publicpensions/cpp/cpp-international.html
- Social Security Agreements: https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/payroll-deductions-contributions/canada-pension-plan-cpp/international-social-security-agreements.html

### IRS — US Tax for Non-Residents & Expats
- Substantial Presence Test: https://www.irs.gov/individuals/international-taxpayers/substantial-presence-test
- Closer Connection Exception: https://www.irs.gov/individuals/international-taxpayers/closer-connection-exception-to-the-substantial-presence-test
- Form 8840: https://www.irs.gov/pub/irs-pdf/f8840.pdf
- FIRPTA: https://www.irs.gov/individuals/international-taxpayers/firpta-withholding
- FBAR (FinCEN 114): https://www.irs.gov/businesses/small-businesses-self-employed/report-of-foreign-bank-and-financial-accounts-fbar
- Form 8938 (FATCA): https://www.irs.gov/businesses/comparison-of-form-8938-and-fbar-requirements
- Streamlined Filing Procedures: https://www.irs.gov/individuals/international-taxpayers/streamlined-filing-compliance-procedures
- Publication 519 (US Tax Guide for Aliens): https://www.irs.gov/publications/p519
- Publication 597 (Canada-US Tax Treaty): https://www.irs.gov/publications/p597

### Canada-US Tax Treaty
- Full text: https://www.canada.ca/en/department-finance/programs/tax-policy/tax-treaties/country/united-states-america-convention-consolidated-1980-1983-1984-1995-1997-2007.html

### TaxTips.ca
- US Estate Tax for Canadians: https://www.taxtips.ca/personaltax/us-estate-tax-for-canadians.htm
- Leaving Canada: https://www.taxtips.ca/personaltax/leavingcanada.htm
- Foreign Tax Credit: https://www.taxtips.ca/filing/foreign-tax-credit-non-business-income.htm
- T1135 Foreign Asset Reporting: https://www.taxtips.ca/filing/foreign-asset-reporting.htm

### Provincial Health Insurance (Re-Entry Waiting Periods)
- Ontario (OHIP): https://www.ontario.ca/page/apply-ohip-and-get-health-card
- BC (MSP): https://www2.gov.bc.ca/gov/content/health/health-drug-coverage/msp
- Alberta (AHCIP): https://www.alberta.ca/ahcip-coverage
- Quebec (RAMQ): https://www.ramq.gouv.qc.ca/en/citizens/health-insurance/registration
