# Portfolio Management — Advanced Strategies for Canadian Investors

Read this reference when the user has a substantial portfolio ($100K+), asks about tax
optimization beyond basic RRSP/TFSA sequencing, has US holdings, employee stock options,
wants to optimize their withdrawal strategy in retirement, or asks about rebalancing,
tax-loss harvesting, or asset location.

For entry-level investment education (all-in-one ETFs, GICs, HISAs, platform comparison),
read `references/investment-basics.md` instead.

All rates should be verified via web search — they change annually. Key sources: canada.ca
(CRA), taxtips.ca, FP Canada, Morningstar. Full URLs in Section 13.

---

## Table of Contents

1. When to Use This Reference
2. Asset Location Strategy
3. Portfolio Rebalancing
4. Tax-Loss Harvesting & Superficial Loss Rule
5. Adjusted Cost Base (ACB) Tracking
6. US Securities, Withholding Tax & Estate Tax
7. Employee Stock Options & RSUs
8. Dividend Taxation & REIT Income
9. Portfolio Withdrawal Strategy (Retirement)
10. Dollar-Cost Averaging vs Lump Sum
11. Behavioral Investing & Common Pitfalls
12. DIY vs Robo-Advisor vs Full-Service
13. Source URLs

---

## 1. When to Use This Reference

Load this file when the user:
- Has $100K+ in invested assets and wants to optimize
- Asks about which investments to hold in which account type
- Wants to do tax-loss harvesting
- Has US-listed investments (withholding tax, estate tax concerns)
- Has employee stock options or RSUs
- Is approaching or in retirement and needs a withdrawal strategy
- Asks about rebalancing their portfolio
- Has received a large inheritance and needs to invest it
- Asks "should I use a robo-advisor or do it myself?"
- Has concentration risk (too much in one stock/sector)

---

## 2. Asset Location Strategy

**Asset location** = which investments to hold in which account type. This is different from
**asset allocation** (how much in stocks vs bonds). Asset location can add 0.5-1.0% per year
in after-tax returns — significant over decades.

### The Principle
Put **tax-inefficient** investments in **tax-sheltered** accounts.
Put **tax-efficient** investments in **non-registered** accounts.

### Account Types Ranked by Tax Efficiency
1. **TFSA:** Tax-free growth AND withdrawals. Best for highest-growth investments.
2. **RRSP/RRIF:** Tax-deferred growth. Withdrawals taxed as income. Best for assets that
   would be taxed at the highest rates (interest, foreign dividends).
3. **Non-registered:** Taxed annually on income, gains taxed on sale. Best for tax-efficient
   Canadian investments.

### What Goes Where

| Investment Type | Best Account | Why |
|----------------|-------------|-----|
| Canadian equities (stocks/ETFs) | Non-registered | Eligible dividends get dividend tax credit (lower effective rate). Capital gains taxed at 50% inclusion. |
| US equities (directly held) | RRSP | US-Canada tax treaty exempts US dividend withholding tax in RRSP. 15% withholding tax applies in TFSA and non-registered. |
| International equities | RRSP or TFSA | Foreign withholding tax applies regardless, but growth is sheltered. |
| Bonds / fixed income | RRSP | Interest income is fully taxable (no preferential rate). RRSP shelters this entirely. |
| GICs | RRSP or TFSA | Same reasoning — interest is fully taxable. |
| High-growth / speculative | TFSA | Tax-free growth means the bigger the gain, the bigger the tax savings. |
| REITs (Canadian) | RRSP or TFSA | Distributions often include return of capital (complex tax treatment in non-registered). |

### Practical Example
User has $200K across accounts:
- RRSP: $80K → Hold bonds (XBB or ZAG) + US equity (VUN or XUS)
- TFSA: $60K → Hold high-growth equity (VEQT or XEQT)
- Non-registered: $60K → Hold Canadian dividend ETFs (XDV, VDY, or CDZ)

### When It Doesn't Matter
If you use an **all-in-one ETF** (VBAL, VGRO, VEQT) across all accounts, asset location is
already handled internally by the fund. The simplicity of one-fund portfolios outweighs the
small tax optimization of perfect asset location for most people.

**Asset location matters most for:** Portfolios over $500K with separate bond/equity holdings
across multiple account types.

(Source: taxtips.ca, canadianportfoliomanagerblog.com)

---

## 3. Portfolio Rebalancing

### What Is Rebalancing?
Over time, your portfolio drifts from its target allocation because different asset classes
grow at different rates. A 60/40 stock/bond portfolio might drift to 70/30 after a strong
stock market year. Rebalancing brings it back to target.

### When to Rebalance
Three approaches:

**1. Calendar-based:** Rebalance on a set schedule (annually or semi-annually).
- Pros: Simple, disciplined, removes emotion.
- Cons: May rebalance when drift is small (unnecessary trading).
- **Recommended for most people.** Once per year is sufficient.

**2. Threshold-based:** Rebalance when any asset class drifts more than 5% from target.
- Example: Target 60% equity. Rebalance if equity hits 65% or drops to 55%.
- Pros: Only trades when needed. Captures larger moves.
- Cons: Requires monitoring.

**3. Contribution-based:** Direct new contributions to the underweight asset class.
- Example: Stocks are overweight → direct next RRSP contribution entirely to bonds.
- Pros: No selling required (avoids triggering capital gains in non-registered).
- **This is the most tax-efficient method.** Use it whenever possible.

### Tax-Efficient Rebalancing Order
1. **First:** Rebalance within registered accounts (RRSP, TFSA) — no tax consequences.
2. **Second:** Direct new contributions to underweight classes (no selling).
3. **Last resort:** Sell overweight holdings in non-registered (triggers capital gains).
   If selling, sell losers first (harvest the tax loss — see Section 4).

### How Often Is Enough?
Academic research shows **annual rebalancing** captures most of the benefit. More frequent
rebalancing (monthly, quarterly) adds trading costs and complexity with minimal improvement.

(Source: FP Canada, Vanguard research)

---

## 4. Tax-Loss Harvesting & Superficial Loss Rule

### What Is Tax-Loss Harvesting (TLH)?
Selling an investment at a loss in a **non-registered account** to realize a capital loss,
which offsets capital gains and reduces your tax bill.

- Capital losses offset capital gains dollar-for-dollar
- Net capital losses can be **carried back 3 years** or **carried forward indefinitely**
- Only applies to **non-registered accounts** (RRSP/TFSA gains and losses have no tax impact)

### When to Harvest
- You have unrealized losses in non-registered holdings AND
- You have realized capital gains in the current year (or expect to), OR
- You have gains from the past 3 years to carry back against

**Best time:** Late November/December (year-end planning). But can be done anytime.

### The Superficial Loss Rule (Canada's "Wash Sale" Rule)

**CRA will DENY your capital loss** if you (or an affiliated person) repurchase the **same
or identical property** within **30 calendar days before or after** the sale.

**The 61-day window:**
- 30 days before the sale
- The day of the sale
- 30 days after the sale

If the identical property is acquired by you, your spouse, or your RRSP/TFSA during this
window, the loss is deemed "superficial" and added to the ACB of the replacement property
instead of being claimed as a loss.

### "Identical Property" — What Counts?
- Same stock (selling and rebuying Apple shares = superficial loss)
- Same ETF (selling and rebuying VGRO = superficial loss)
- Different class of same fund is generally considered identical
- **NOT identical:** Different ETFs tracking the same index from different providers
  (selling VGRO and buying XGRO is generally NOT a superficial loss — different funds,
  different managers, different holdings. But CRA has not formally ruled on this.)

### Tax-Loss Harvesting Strategy
1. **Sell the losing position** in your non-registered account.
2. **Immediately buy a similar (but not identical) investment** to maintain your portfolio
   allocation. Example: sell VGRO (Vanguard balanced), buy XGRO (iShares balanced).
3. **Wait 31 days.** After 31 days, you can switch back to the original if you prefer.
4. **Claim the capital loss** on your tax return (Schedule 3).
5. **Apply the loss** against current-year gains, carry back 3 years, or carry forward.

### Affiliated Persons (Careful!)
The superficial loss rule applies if the property is acquired by:
- You
- Your spouse/common-law partner
- A corporation controlled by you or your spouse
- Your RRSP or TFSA (or your spouse's)
- A trust in which you or your spouse are a majority interest beneficiary

**Common trap:** Selling a stock at a loss in your non-registered account and buying the same
stock in your TFSA within 30 days = superficial loss. The loss is denied AND doesn't increase
the ACB of the TFSA holding (the loss is effectively destroyed).

### Settlement Date Matters
With Canada's **T+1 settlement** (since May 2024), trades settle the next business day.
The superficial loss period is based on **settlement dates**, not trade dates. In practice,
this means you need to count from the settlement date of your sale.

(Source: canada.ca/superficial-loss, taxtips.ca, Questrade TLH guide)

---

## 5. Adjusted Cost Base (ACB) Tracking

### What Is ACB?
The Adjusted Cost Base is your total cost of an investment, including purchase price +
commissions + reinvested distributions. You need ACB to calculate capital gains/losses when
you sell in a **non-registered account**.

**Capital gain = sale proceeds - ACB - selling costs**

### Why It Matters
- CRA requires you to report capital gains/losses accurately
- Your brokerage may NOT track ACB correctly (especially for ETFs with return of capital)
- If you don't track ACB, you may overpay tax (or underpay and face penalties)

### How ACB Changes
| Event | Effect on ACB |
|-------|--------------|
| Buy more shares | ACB increases (add purchase price + commissions) |
| Reinvested distributions (DRIP) | ACB increases (each reinvested distribution is a "purchase") |
| Return of capital distributions | ACB **decreases** (you got some of your own money back) |
| Superficial loss | ACB of replacement shares increases by the denied loss |
| Transfer between accounts | Deemed disposition at FMV — triggers gain/loss |

### ACB Calculation (Average Cost Method)
Canada uses the **average cost method** for mutual funds and ETFs (not FIFO/LIFO):

```
Total ACB of all shares / Total number of shares = ACB per share
```

**Example:**
- Buy 100 shares at $25 = $2,500 ACB
- Buy 50 shares at $30 = $1,500 ACB
- Total ACB: $4,000 / 150 shares = $26.67 per share
- Sell 75 shares at $35: gain = (75 × $35) - (75 × $26.67) = $2,625 - $2,000 = $625 capital gain

### Tools for Tracking
- **AdjustedCostBase.ca:** Free Canadian ACB tracking tool
- **Your brokerage statements:** May show ACB but often incorrect for complex situations
- **Spreadsheet:** Simple for a few holdings, complex for many
- **Tax software:** TurboTax, Wealthsimple Tax, StudioTax can help calculate

### Return of Capital (ROC) — The ACB Trap
Some ETFs and REITs distribute "return of capital" — money returned to you from the fund
that is NOT income or gains. ROC is tax-free when received BUT reduces your ACB.

**Impact:** If your ACB drops to $0 from ROC, any further ROC distributions are taxed as
capital gains immediately. And when you eventually sell, your capital gain is larger because
your ACB is lower.

**Track ROC carefully.** ETF providers publish the tax breakdown of their distributions
annually (usually by March). Use this to adjust your ACB.

(Source: adjustedcostbase.ca, taxtips.ca/acb)

---

## 6. US Securities, Withholding Tax & Estate Tax

> For comprehensive cross-border planning (snowbirds, US property ownership, departure tax,
> newcomers, FBAR/FATCA), read `references/cross-border.md`. This section covers portfolio-specific
> US tax implications only.

### US Dividend Withholding Tax
When a Canadian holds US stocks or US-listed ETFs, the US withholds **15% of dividends**
under the Canada-US tax treaty (default rate is 30%, treaty reduces to 15%).

**Impact by account type:**

| Account | US Withholding Tax | Can You Recover It? |
|---------|-------------------|-------------------|
| RRSP/RRIF/LIRA | **0% (exempt)** | Treaty exemption — no withholding |
| TFSA | 15% withheld | **Cannot recover** — lost forever |
| RESP | 15% withheld | Cannot recover |
| FHSA | 15% withheld | Cannot recover |
| Non-registered | 15% withheld | Claim as Foreign Tax Credit on T1 |

**Strategy:** Hold US dividend-paying stocks/ETFs in your **RRSP** to avoid the 15% drag.
Hold Canadian stocks in your TFSA or non-registered (dividend tax credit applies).

### Canadian-Listed vs US-Listed ETFs
- **Canadian-listed ETF holding US stocks** (e.g., VFV, XUS): US withholding tax is embedded
  inside the fund. You can't claim a Foreign Tax Credit. The drag is ~0.3-0.5% per year on
  US dividend yield.
- **US-listed ETF** (e.g., VOO, VTI): US withholding tax is visible on your statement.
  In RRSP: exempt. In non-registered: claim Foreign Tax Credit. In TFSA: lost.
- **For RRSP:** US-listed ETFs are more tax-efficient (treaty exemption works directly).
- **For TFSA/non-registered:** Canadian-listed ETFs are simpler (no US dollar conversion,
  no US tax forms). The withholding tax drag is small enough that simplicity wins for most.

### US Estate Tax for Canadians
If a Canadian resident dies holding **US-situs assets** (US stocks, US real estate, US ETFs)
above **~$85,000 CAD** ($60,000 USD), their estate may be subject to US estate tax.

- **Rate:** Up to 40% on US-situs assets above the exemption
- **Unified credit:** Under the Canada-US treaty, Canadians get a prorated share of the US
  unified credit based on the proportion of worldwide assets that are US-situs.
- **Treaty relief:** Effectively, most Canadians with worldwide estates under ~$19M CAD (~$13.6M USD)
  (2025 — verify, this threshold may drop in 2026) won't owe US estate tax. But you still
  need to FILE a US estate tax return (Form 706-NA) if US-situs assets exceed $60K.
- **US-situs assets include:** US stocks (even in Canadian brokerage accounts), US real estate,
  US-domiciled ETFs. Canadian-listed ETFs that hold US stocks are generally NOT US-situs.

**Strategy for large portfolios:** Use Canadian-listed ETFs for US exposure to avoid US estate
tax filing and potential liability. Especially important for portfolios over $1M with
significant US allocation.

(Source: canada-us-tax-treaty, rbcwealthmanagement.com, scotiawealth)

---

## 7. Employee Stock Options & RSUs

### Stock Options (Basics)
Your employer grants you options to buy company shares at a fixed price (exercise price).
You exercise when the market price is above the exercise price — the difference is your profit.

**Taxation in Canada:**
- **At grant:** No tax (just a right, not income yet)
- **At exercise:** The "benefit" (market price - exercise price) is taxed as **employment income**
  (reported on your T4). This is NOT a capital gain — it's taxed at your full marginal rate.
- **50% deduction available** if: the exercise price was at least FMV at grant date, shares are
  common shares (not preferred), you're dealing at arm's length with the employer, AND for
  non-CCPC shares, there's a $250,000 annual vesting limit on the deduction (2025 — verify).
- **CCPC special rule:** Taxable benefit deferred until you sell the shares (not at exercise).
  Must hold shares 2+ years after exercise for the 50% deduction.
- **At sale:** Any gain above the exercise price + benefit already taxed = capital gain (50% inclusion)

### RSUs (Restricted Stock Units)
Your employer promises you shares that vest over time (e.g., 25% per year over 4 years).

**Taxation in Canada:**
- **At grant:** No tax
- **At vesting:** The FMV of shares received is taxed as **employment income** (on your T4).
  No 50% deduction available for RSUs (unlike stock options).
- **At sale:** Any gain above FMV at vesting = capital gain (50% inclusion)

**Example:** 100 RSUs vest when stock = $50/share. Employment income = $5,000 (fully taxed).
You sell at $60. Capital gain = $10/share × 100 = $1,000 (50% inclusion = $500 taxable).

### Concentration Risk
Employee stock options and RSUs create **concentration risk** — too much of your net worth
tied to one company. If the company struggles, you lose both your job AND your investment.

**Guidelines:**
- Once shares vest, consider selling and diversifying into a broad ETF portfolio
- Don't hold more than **10-15%** of your investable assets in a single stock (including employer)
- Some companies allow cashless exercise (sell immediately, receive the profit as cash)
- **Tax planning:** Time exercises/sales to manage taxable income across years. Exercising
  $200K in options in one year vs $50K over 4 years can save significant tax.

### ESPPs (Employee Stock Purchase Plans)
Some employers offer shares at a discount (typically 10-15% below market).
- The discount is a **taxable employment benefit** (on your T4)
- Subsequent gain on sale = capital gain
- Almost always worth participating — the discount is immediate guaranteed return

(Source: canada.ca/stock-options, nicolawealth.com, taxtips.ca)

---

## 8. Dividend Taxation & REIT Income

### Canadian Dividend Tax Credit System
When a Canadian corporation pays dividends, they've already paid corporate tax on the income.
The dividend tax credit system prevents double-taxation by giving you a credit.

**Eligible dividends** (from large public corporations, CCPCs paying out income taxed at
the general rate):
- Gross-up: 38% (include 138% of actual dividend in income)
- Federal dividend tax credit: 15.02% of grossed-up amount
- **Effective tax rate: ~20-30%** for most brackets (significantly lower than salary)

**Non-eligible dividends** (from CCPCs paying out SBD income):
- Gross-up: 15% (include 115% of actual dividend in income)
- Federal dividend tax credit: 9.03% of grossed-up amount
- **Effective tax rate: ~30-45%** (closer to salary rates)

### Why This Matters for Asset Location
Canadian eligible dividends are taxed very favorably. In lower tax brackets (under ~$50K),
the effective rate can be close to **0%**. This makes Canadian dividend-paying stocks ideal
for **non-registered accounts** — you're barely taxed on the income.

In contrast, interest income (from bonds, GICs) is taxed at your **full marginal rate** — the
worst tax treatment. Keep these in registered accounts.

### REIT Distributions
Canadian REITs (Real Estate Investment Trusts) distribute income that can include:
- **Return of capital (ROC):** Tax-free when received, but reduces ACB (see Section 5)
- **Capital gains:** 50% inclusion
- **Other income:** Fully taxable (like interest)
- **Foreign income:** May include foreign withholding tax

**Complexity:** REIT distributions are messy from a tax perspective. Each year, the REIT
publishes a breakdown of its distributions by type. You need this to adjust your ACB and
report taxes correctly.

**Strategy:** Hold REITs in registered accounts (RRSP, TFSA) to avoid the complexity. If in
non-registered, track ACB carefully using the annual tax breakdown.

(Source: taxtips.ca/dividends, canada.ca)

---

## 9. Portfolio Withdrawal Strategy (Retirement)

### The Question
In retirement, you have multiple income sources and account types. The ORDER in which you
draw from them significantly impacts how much tax you pay over your lifetime.

### General Tax-Efficient Withdrawal Order
1. **First: Non-registered accounts** — These are already being taxed annually (dividends,
   interest, capital gains). Draw these down first to stop the ongoing tax drag.
2. **Second: RRSP/RRIF** — Mandatory minimum withdrawals start at 72 (when RRSP converts to
   RRIF). Draw more than the minimum in low-income years to avoid a tax spike later.
3. **Last: TFSA** — Tax-free growth. Let this grow as long as possible. Use it to top up
   income in years when you need more without increasing your tax bracket.

### RRIF Minimum Withdrawals
At age 72, you MUST convert your RRSP to a RRIF and begin minimum annual withdrawals:

| Age | Minimum % of Balance |
|-----|---------------------|
| 72 | 5.28% |
| 75 | 5.82% |
| 80 | 6.82% |
| 85 | 8.51% |
| 90 | 11.92% |
| 94+ | 20.00% |

**Risk:** If your RRIF balance is large, minimum withdrawals in your 80s-90s can push you
into high tax brackets and trigger OAS clawback ($93,454 threshold, 2025 — verify).

**Strategy:** Withdraw MORE than the minimum in your 60s-70s (while in a lower bracket) to
reduce the RRIF balance before the minimums force large withdrawals later.

### OAS Clawback Management
OAS clawback (recovery tax) starts when net income exceeds ~$93,454 (2025 — verify). OAS
is fully clawed back at ~$151,668.

**Strategies to minimize clawback:**
- Draw from TFSA instead of RRIF when near the threshold (TFSA withdrawals don't count as income)
- Split pension income with spouse (Form T1032 — up to 50% of eligible pension income)
- Time RRSP/RRIF withdrawals to stay below the clawback threshold
- Use non-registered capital gains strategically (only 50% is included in income)

### CPP/OAS Integration
- **CPP at 60 vs 65 vs 70:** See `canada-finance-rules.md` for break-even analysis
- **OAS deferral:** Can defer OAS up to age 70 for a 36% increase (0.6%/month × 60 months).
  Worth it if you can fund the gap years from other sources and expect to live past ~83.
- **GIS optimization:** If eligible for GIS, minimize RRIF withdrawals (GIS is income-tested).
  TFSA withdrawals don't affect GIS eligibility.

### The 4% Rule (Sustainable Withdrawal Rate)
A guideline: withdraw 4% of your portfolio in the first year of retirement, then adjust for
inflation annually. Research suggests this provides a ~95% chance of your portfolio lasting
30 years.

**Canadian considerations:**
- FP Canada 2025 guidelines suggest lower sustainable rates for conservative portfolios
  (~2.5-3.5% real withdrawal rate)
- CPP/OAS/pension income reduces the amount you need from your portfolio
- Healthcare costs in Canada are lower than the US (less withdrawal pressure)
- The 4% rule assumes a 50/50 to 75/25 stock/bond portfolio

**Sequence-of-returns risk:** If you retire into a bear market and withdraw at 4%, you're
selling low and the portfolio may never recover. Mitigations:
- Keep 2-3 years of cash/GICs as a buffer (don't sell equities in a downturn)
- Reduce withdrawals in down years
- Use TFSA as an emergency buffer during market downturns

(Source: FP Canada, taxtips.ca, Vanguard retirement research)

---

## 10. Dollar-Cost Averaging vs Lump Sum

### The Question
"I have $100K to invest. Should I invest it all at once or spread it out?"

### The Evidence
Research consistently shows **lump sum investing beats dollar-cost averaging (DCA) about
2/3 of the time.** (Source: Vanguard 2012 study, updated 2023) This makes sense — markets
go up more often than they go down, so being invested earlier captures more upside.

### When Lump Sum Wins
- Long time horizon (10+ years)
- Diversified portfolio (not a single stock)
- Comfortable with short-term volatility
- Money is already available (inheritance, windfall, account transfer)

### When DCA Wins
- The investor is anxious about investing a large sum at once
- The market has recently hit all-time highs and they're worried about a correction
- They need the **psychological comfort** of gradual entry
- They're investing from ongoing income (salary, business income) — this is natural DCA

### Practical Compromise
If the user is nervous about lump sum:
- Invest 50% immediately, DCA the remaining 50% over 6 months
- This captures most of the lump sum advantage while reducing anxiety
- Set up automatic weekly/bi-weekly investments to remove emotion from the process

### What NOT to Do
- Leave the money in cash "waiting for a dip" — this is market timing and consistently
  underperforms both lump sum and DCA
- Invest a large sum in a single stock (that's speculation, not investing)

---

## 11. Behavioral Investing & Common Pitfalls

### The Biggest Risk Is You
Investment returns are less about which fund you pick and more about whether you can
**stay invested during downturns.** The average investor significantly underperforms the
average fund because of behavioral mistakes.

### Common Pitfalls

**1. Panic selling (loss aversion):**
The market drops 20%. You sell "to protect what's left." The market recovers. You've locked
in losses and missed the recovery. **The fix:** Automate contributions, don't check your
portfolio daily, remember that every major crash in history has been followed by recovery.

**2. Recency bias:**
"Tech stocks went up 30% last year, I should move everything to tech." Past performance
is the worst predictor of future performance. **The fix:** Stick to your target allocation
regardless of recent performance.

**3. FOMO (Fear of Missing Out):**
"Everyone is making money on [crypto/meme stocks/AI stocks], I should get in." By the time
it's on the news, you're usually late. **The fix:** If it's not in your plan, it's not for
your portfolio.

**4. Overtrading:**
Checking your portfolio daily and making frequent trades based on headlines. Each trade has
a cost (commissions, spreads, taxes on gains). **The fix:** Check quarterly at most. Rebalance
annually. Otherwise, leave it alone.

**5. Home bias:**
Canadians tend to over-invest in Canadian stocks (which are ~3% of global markets). This
concentrates risk in energy, financials, and real estate. **The fix:** All-in-one ETFs
(VBAL, VGRO, VEQT) are globally diversified by design.

**6. Anchoring:**
"I bought it at $50, I'll sell when it gets back to $50." The price you paid is irrelevant
to the investment's future value. **The fix:** Evaluate holdings on current fundamentals,
not your purchase price.

### What Actually Works
1. **Automate everything.** Automatic contributions to RRSP/TFSA on payday.
2. **Use a simple, diversified portfolio.** One all-in-one ETF is enough for most people.
3. **Don't check your portfolio more than quarterly.**
4. **Rebalance once a year, no more.**
5. **Ignore financial news.** It's entertainment, not investment advice.
6. **Stay invested through downturns.** The biggest gains happen in the recovery.

---

## 12. DIY vs Robo-Advisor vs Full-Service

### Comparison (Canadian Context, 2026 — verify fees)

| Feature | DIY (Discount Brokerage) | Robo-Advisor | Full-Service Advisor |
|---------|------------------------|-------------|---------------------|
| Annual fee | $0 (commission-free trades) | 0.25-0.50% of assets | 1.0-1.5% of assets |
| + Fund MER | ~0.20% (all-in-one ETF) | ~0.20% (ETF-based) | 1.5-2.5% (mutual funds) |
| **Total cost** | **~0.20%/year** | **~0.45-0.70%/year** | **~2.5-4.0%/year** |
| On $500K portfolio | ~$1,000/year | ~$2,250-$3,500/year | ~$12,500-$20,000/year |
| You do | Everything (buy, sell, rebalance, tax planning) | Nothing — fully automated | Nothing — advisor manages |
| Tax optimization | You handle | Basic (some do TLH) | Should handle (often don't) |
| Financial plan | Not included | Basic goals-based | Comprehensive (if good advisor) |
| Best for | Confident, engaged investors | Busy people who want hands-off | Complex situations, need advice |

### Canadian Platforms (2026 — verify)

**DIY Discount Brokerages:**
- Wealthsimple Trade: $0 commissions, no account minimums, RRSP/TFSA/non-reg
- Questrade: $0 ETF purchases (sell commissions apply), powerful platform
- National Bank Direct Brokerage: $0 commissions
- BMO InvestorLine, TD Direct Investing, RBC Direct Investing: traditional bank brokerages

**Robo-Advisors:**
- Wealthsimple Invest: 0.40-0.50% fee + ~0.20% MER, automatic rebalancing, tax-loss harvesting
  on higher tiers, socially responsible investing option
- Questwealth: 0.20-0.25% fee + ~0.20% MER, lower cost
- BMO SmartFolio: 0.40-0.70% fee, bank-backed
- CI Direct Investing (formerly WealthBar): 0.35-0.60%

**Full-Service (Fee-Only Advisors):**
- Fee-only planners charge a flat fee ($2,000-$5,000 for a financial plan) or hourly ($200-$400)
- They do NOT earn commissions on products they recommend
- **This is what we recommend for complex situations** (investments $500K+, business owners,
  cross-border, estate planning)
- Find one: FP Canada (fpcanada.ca), Fee-Only Financial Planners (moneysense.ca directory)

### When to Switch
- **DIY → Robo:** If you're not rebalancing regularly or find investing stressful
- **Robo → DIY:** When you're confident enough to manage a simple portfolio and want to
  save on fees
- **Full-service → DIY or Robo:** If you're paying 2%+ in fees and your advisor hasn't
  added that much value. The fee difference on $500K over 20 years = $100K+.
- **DIY/Robo → Fee-only advisor:** For one-time complex decisions (retirement income planning,
  business succession, estate planning). Get a plan, then implement yourself.

(Source: Wealthsimple, Questrade, MoneySense, FP Canada)

---

## 13. Source URLs

### CRA Tax Rules
- Capital Gains: https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/personal-income/line-12700-capital-gains.html
- Superficial Loss Rule: https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/personal-income/line-12700-capital-gains/completing-schedule-3/superficial-losses.html
- Stock Options: https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/benefits-allowances/security-options.html
- Dividend Tax Credit: https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/deductions-credits-expenses/line-40425-federal-dividend-tax-credit.html
- RRIF Minimum Withdrawals: https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/completing-slips-summaries/t4rsp-t4rif-information-returns/payments/chart-prescribed-factors.html

### Investment Research
- ACB Tracking: https://www.adjustedcostbase.ca/
- FP Canada Projection Guidelines: https://www.fpcanada.ca/planners/projection-assumption-guidelines
- TaxTips.ca Investment Income: https://www.taxtips.ca/personaltax/investing.htm
- Canadian Portfolio Manager Blog: https://www.canadianportfoliomanagerblog.com/

### US-Canada Tax Treaty
- Treaty Text: https://www.canada.ca/en/department-finance/programs/tax-policy/tax-treaties/country/united-states-america-convention-consolidated-1980-1983-1984-1995-1997.html
- US Withholding Tax Guide: https://www.taxtips.ca/personaltax/investing/foreigntaxcredit.htm

### Platform Comparisons
- Wealthsimple: https://www.wealthsimple.com/
- Questrade: https://www.questrade.com/
- MoneySense Best Robo-Advisors: https://www.moneysense.ca/save/investing/best-robo-advisors-in-canada/
- FP Canada Find a Planner: https://www.fpcanada.ca/findaplanner

### Behavioral Finance
- Vanguard Behavioral Finance Research: https://investor.vanguard.com/investor-resources-education
