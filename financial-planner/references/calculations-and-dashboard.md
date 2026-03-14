# Calculations Engine & Dashboard Specification

Read this reference when building the plan, running projections, or generating the dashboard.

---

## Pre-Calculation Validation

Before running any calculations, verify data completeness and consistency:

### Required Data Check
Confirm you have these from the interview (if any are missing, STOP and go back to ask):
- Province (for tax rates)
- All income sources with gross AND net amounts
- Complete expense list (fixed + variable + irregular)
- Every debt with: balance, interest rate, minimum payment
- All registered account balances and contribution room
- Insurance coverage details
- At least one financial goal

### Consistency Pre-Check
Before calculating, verify these relationships:
- Net income should be 65-80% of gross for typical employment income in their province
- Sum of listed debt minimum payments should approximately match debt payments in the expense list
- If they have investment accounts, any investment income mentioned should be plausible given
  balances and types
- RESP contributions in expenses should match what's described in the assets section
- Number of months of emergency fund = liquid savings / essential monthly expenses

If any check fails, note the discrepancy and use the corrected/verified number in calculations.
Flag the discrepancy in the plan under "Assumptions and Data Notes."

---

## Table of Contents

1. Calculations to Run
2. Plan File Structure
3. Dashboard Specification
4. Dashboard Template Notes

---

## 1. Calculations to Run

After the interview is complete, run ALL of these. The user doesn't need to understand the
math — just deliver the results.

### 1.1 Budget Analysis
- Categorize all spending (fixed, variable, irregular)
- Calculate surplus/deficit
- Compare to 50/30/20 benchmark (needs/wants/savings)
- Compare housing to CMHC GDS guideline (32%) and TDS (40%)
- Identify top 5 areas for realistic spending reduction
- Build suggested budget that funds goals while protecting joy spending
- Identify "habit spending" vs "joy spending" — redirect, don't cut joy

### 1.2 Tax Optimization
- Calculate marginal tax rate (federal + provincial)
- RRSP vs TFSA priority based on current bracket vs expected retirement bracket
  - Higher bracket now than expected in retirement → RRSP first
  - Lower bracket now → TFSA first
  - Close or uncertain → split or prioritize TFSA for flexibility
- If self-employed: flag quarterly installments, HST, business deductions
- If receiving CCB: model RRSP contribution impact on increasing CCB (lowers net income)
- If receiving GIS: flag clawback implications
- Spousal RRSP analysis if applicable
- All applicable credits and deductions they might be missing
- Capital gains planning for non-registered investments

### 1.3 Debt Strategy
- Rank all debts by interest rate (avalanche) and by balance (snowball)
- If payday loans exist → EMERGENCY, calculate effective rate, build exit plan
- Calculate both avalanche and snowball timelines + total interest
- Recommend based on debt stress score: high stress → snowball for quick wins, low stress → avalanche
- Check if consolidation helps (e.g., LOC at 8% to pay CCs at 22%)
- Flag student loan interest tax credit
- Build month-by-month payoff schedule
- Calculate debt-free date and monthly cash freed up after

### 1.4 Emergency Fund
- Essential monthly expenses = housing + food + utilities + insurance + min debt + transport
- Target: 3 months (stable dual income) to 12 months (self-employed/variable/single)
- Current coverage in months
- Monthly contribution plan and timeline to target
- Where to keep it: HISA or TFSA (if room available and not used for investing)

### 1.5 Free Money Capture
- Employer RRSP/DPSP match: capturing full match? If not, calculate what's left on the table
- CESG: contributing $2,500/year per child? If not, calculate missed grant money
- RDSP grants: if eligible, are they contributing? Model CDSG match
- FHSA: if first-time buyer, opened one? $8,000/year deduction opportunity
- Provincial grants they might be missing

### 1.6 Retirement Projection
Model ALL income sources:
- CPP/QPP at 60, 65, and 70 (show the three scenarios)
- OAS (estimate from residency years, check clawback)
- GIS if low income
- Workplace pension (DB: projected annual; DC: projected balance)
- RRSP/RRIF drawdown (growth to retirement, then minimum withdrawals)
- TFSA drawdown (tax-free, no clawback impact)
- Non-registered investments, rental income

Use FP Canada 2025 Projection Assumption Guidelines:
- Conservative: ~2.7% real (~4.8% nominal)
- Moderate: ~3.4% real (~5.5% nominal)
- Aggressive: ~4.1% real (~6.2% nominal)
- Always label real vs nominal

Show: total projected income vs target (70-80% pre-retirement or stated goal), gap or surplus,
impact of changing contributions, RRSP→RRIF at 71, bridge years if early retirement.

### 1.7 RESP Projection (if children)
Per child:
- Current balance, annual contribution, CESG captured
- Project balance at 18 (contributions + grant + growth)
- Compare to estimated education costs (4-year Canadian university, inflated)
- If behind on CESG: calculate catch-up strategy
- Show gap or surplus

### 1.8 RDSP (if applicable)
- CDSG matching tier based on income
- Current balance and grants received
- Holdback rule implications
- Long-term projection

### 1.9 Net Worth Snapshot & Projection
- Current: assets minus liabilities
- Also show excluding primary residence (more conservative)
- Project at 1, 5, 10, 20 years
- Milestone markers ($100K, $500K, $1M)

### 1.10 Insurance Gap Analysis
- Life: need = mortgage payoff + 10yr income replacement + kids' education + final expenses - existing
- Disability: 60-70% income covered?
- If no will/POA → flag as urgent
- Estimate cost of term life to fill the gap

### 1.11 Benefits Check
Cross-reference profile against ALL federal and provincial programs. List every program they
likely qualify for, estimated value, whether currently receiving, and how to apply.

### 1.12 CRA Calendar
Personalized dates that matter to THIS user only:
- RRSP deadline, tax filing deadline, quarterly installments (if applicable)
- RESP contribution timing, TFSA room reset
- Benefit payment dates (CCB, GST/HST, OAS/CPP if applicable)
- Age milestones (60 early CPP, 65 OAS, 71 RRSP conversion)
- HSA reset dates, mortgage renewal

### 1.13 Post-Calculation Review (MANDATORY)

After running all 12 calculation modules above, perform these consistency checks before
writing any output files:

**Math Checks:**
1. **Budget equation:** Total net income - Total expenses = Surplus/deficit. Recalculate from
   the component numbers. If it doesn't match your earlier calculation, find the error.
2. **Savings rate:** Surplus / Net income. Must match what you put in the budget file.
3. **Net worth:** Sum every asset line item - Sum every liability line item. Recalculate from
   scratch, don't carry forward a running total.
4. **Debt payoff:** For each debt, verify: monthly interest = balance × (annual rate / 12).
   Minimum payment should exceed monthly interest (if not, flag as mathematically unpayable).
   Payoff timeline should use the EXTRA payment amount from the plan, not just minimums.
5. **Tax rates:** Verify marginal rate matches the bracket for their income and province.
6. **Retirement projection:** Total retirement income at target age should equal sum of all
   projected income sources. Verify CPP amounts are within the current maximum range.
7. **RESP projection:** Verify CESG calculated = 20% of contributions (max $500/child/year,
   $7,200 lifetime). Check that growth rate matches FP Canada assumptions.

**Cross-Reference Checks:**
8. **Expense categories in budget must sum to total expenses.** Add them up again.
9. **Percentage breakdowns must sum to 100%** (or within 1% due to rounding).
10. **Dashboard KPI values must match budget and plan files.** Specifically verify: net income,
    expenses, surplus, savings rate, net worth, total debt, emergency fund months.

**If a check fails:**
- Fix the calculation silently. Do not present wrong numbers and correct later.
- If fixing requires a judgment call, pick the more conservative approach and note the assumption.
- If fixing requires data you don't have, flag it in the plan: "This projection assumes X
  because [reason]. Verify with [source] for a more precise number."

---

## 2. Plan File Structure

### 2-my-budget.md
- Monthly income table (all sources, net)
- Fixed expenses table
- Variable expenses table
- Annual/irregular expenses (monthly average)
- Budget summary: total income, expenses, surplus
- Key ratios: savings rate, GDS, TDS, needs/wants/savings
- Where money goes (% breakdown)
- Spending insights: joy spending (protect), habit spending (redirect), money left on table

### 3-my-plan.md
- Executive summary (2-3 sentences)
- Phase 1: Stabilize (immediate — kill high-interest debt, capture free money, get insurance)
  - Action items: this week, this month, this quarter
- Phase 2: Build (debt-free, emergency fund complete, investments optimized)
- Phase 3: Accelerate (wealth-building with freed-up cash flow)
- Debt payoff plan with table and timeline
- Investment optimization recommendations
- Retirement projection with income source table
- CPP timing recommendation with comparison
- RESP projection per child (if applicable)
- Benefits being missed (table with value and action)
- CRA calendar
- Verified reference data (date-stamped numbers used in calculations)
- Disclaimer and plan version history

---

## 3. Dashboard Specification

Generate `4-my-dashboard.html` as a single self-contained HTML file.

### Technical Requirements
- Chart.js 4.x loaded from CDN: `https://cdn.jsdelivr.net/npm/chart.js@4.5.1`
- All data embedded as JavaScript variables (no external fetches)
- Responsive design (CSS Grid/Flexbox), works on desktop and mobile
- Professional colour scheme: clean whites/grays, blue accent, green/yellow/red for status
- Print-friendly CSS
- System fonts for fast loading

### Header
- Title: "[Name]'s Financial Plan"
- Subtitle: date, province, family size
- File navigation: show companion file names (1-my-profile.md, 2-my-budget.md, 3-my-plan.md) with brief descriptions. Use div elements with file names displayed (not hyperlinks, as they won't resolve in sandboxed browsers). Include a note: "These files are saved in your selected folder."

### Dashboard Sections (16-18 depending on situation)

**1. KPI Cards (6-8):**
Household net income, monthly expenses, surplus/deficit, savings rate, net worth, consumer debt, emergency fund coverage (months), debt-free target date

**2. Financial Health Check:**
Colour-coded table (green/yellow/red badges): savings rate, emergency fund, TDS, GDS, RRSP progress, TFSA usage, RESP on track (if kids), life insurance adequacy, will/POA status

**3. Where Your Money Goes:**
Doughnut chart of expense categories with dollar amounts and percentages in tooltips

**4. Income vs Expenses:**
Bar chart showing net income, total expenses, and surplus side by side

**5. Suggested Budget:**
Table: category, current, suggested, change (with colour-coded savings). Note at bottom about protected joy spending.

**6. Debt Payoff Timeline:**
Line chart showing each debt's balance declining month by month. Mark debt-free date. Label each line with debt name and rate.

**7. Net Worth Projection:**
Bar chart projecting 10 years. Negative bars in red, positive in green. Note assumptions.

**8. Emergency Fund Progress:**
Progress bar with current amount, target, percentage, and estimated completion date.

**9. Retirement Projection:**
Stacked bar chart by age showing income layers (personal savings, pension, CPP, OAS). Dashed line for target income. Include tab buttons to switch between scenarios (e.g., retire at 60 vs 62).

**10. RESP Tracker (if kids):**
Per-child card with progress bar, current balance, projected balance at 18, CESG status.

**11. Recommended Monthly Allocation:**
Table organized by phase (stabilize/build/accelerate) showing where, amount, and why.

**12. Benefits Being Missed:**
Table: opportunity, estimated annual value, action required. Bold total at bottom.

**13. CPP Timing Comparison:**
Line chart showing cumulative CPP received for age 60, 65, and 70 start. Lines cross at break-even ages.

**14. Key CRA Dates:**
List of personalized dates with descriptions.

**15. Action Items:**
Prioritized list with colour-coded tags (this week / this month / this quarter / this year).

**16. Investment Growth Comparison:**
Line chart showing how the user's monthly investment amount grows over time across different
vehicles. Uses data from `references/investment-basics.md` (section 6). Before generating,
verify current rates via web search.

- **Chart type:** Line chart, multiple datasets
- **X-axis:** Years (1 to 30, or until retirement age)
- **Y-axis:** Portfolio value ($)
- **Lines:**
  - Big 5 Savings Account (0.75%) — grey, dashed
  - Online HISA (2.75%) — light blue, dashed
  - GIC Ladder (3.50%) — blue, dashed
  - Balanced ETF — VBAL/XBAL (6.5%) — green, solid
  - Growth ETF — VGRO/XGRO (8.5%) — orange, solid
  - All-Equity ETF — VEQT/XEQT (10.5%) — red, solid
- **Formula:** FV = PMT × [((1 + r/12)^(n×12) - 1) / (r/12)]
- **Highlight** the line matching the user's risk profile with a thicker stroke
- **Annotation:** Show the dollar difference between Big 5 savings and the recommended ETF
  at the user's time horizon (e.g., "Investing instead of saving = $220K more over 25 years")
- **Below chart:** Brief educational note about all-in-one ETFs — one purchase, instant
  diversification, ~0.20% MER, Morningstar rated. Link to the plan file for full details.
- **Disclaimer:** "ETF returns shown are long-term historical averages. Actual returns vary
  year to year. Past performance does not guarantee future results."
- Include only if the plan has a monthly investment allocation > $0

**17. Key Insights:**
Styled cards: biggest strength (green), biggest risk (red), #1 trajectory changer (blue), free money being missed (yellow), goal assessment (green).

**18. Footer:**
Disclaimer, creation date, review recommendation.

### Sections to Include/Exclude Based on Situation
- RESP Tracker: only if they have children
- RDSP Tracker: only if DTC eligible
- CPP Timing: only for users approaching or past age 50
- Retirement Projection: include for everyone (even young users — it motivates saving)
- Investment Growth Comparison: include if plan has monthly investment allocation > $0

---

## 4. Dashboard Template Notes

### Colour Palette (CSS variables)
```
--accent: #2563eb (blue)
--green: #059669
--yellow: #d97706
--red: #dc2626
--bg: #f8f9fa
--card: #ffffff
--border: #e5e7eb
--text: #1a1a2e
--text-secondary: #6b7280
```

### Chart.js Tips
- Use `tension: 0.3` for smooth lines
- Use `pointRadius: 0` for clean line charts (show data on hover)
- Use `borderRadius: 6` for rounded bars
- Use `stack: 'income'` for stacked retirement bars
- Format tooltips with dollar amounts: `callback: ctx => '$' + ctx.raw.toLocaleString()`
- For scenario switching (retirement tabs): destroy and rebuild chart on tab click

### Responsive
- KPI cards: `grid-template-columns: repeat(auto-fit, minmax(180px, 1fr))`
- Two-column layouts: `@media (max-width: 800px) { grid-template-columns: 1fr; }`

### Numbers Integrity (MANDATORY CHECK)
All financial numbers in the dashboard must match the plan and budget files exactly. Before
generating the dashboard HTML, verify each of these values against the budget and plan files:
- Net income (monthly and annual)
- Total expenses
- Surplus/deficit
- Savings rate percentage
- Net worth
- Total consumer debt
- Emergency fund coverage (months)
- Each KPI card value
- Each chart's data points

If ANY number in the dashboard differs from the plan or budget file, fix it before generating
the HTML. The user sees the dashboard FIRST — if a number contradicts their plan file, trust
evaporates immediately.
