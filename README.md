# Canadian Personal Finance Manager
### Your AI Financial Coach — Built for Canadians

**Current version:** 2.4 | [View changelog](https://github.com/cjpatten/canadian-finance-planner-skill/releases)

A custom skill for [Claude](https://claude.ai) that turns it into your personal AI financial coach — built specifically for Canadians.

Claude conducts a thorough financial interview, builds a complete budget and action plan, generates an interactive dashboard with charts, and provides ongoing coaching. All tailored to Canadian tax rules, government benefits, and registered accounts.

---

## What You Get

You don't need to use all of the below features — most people start with a simple budget and go from there. Claude meets you where you are, whether that's "I just need help tracking my spending" or "I'm incorporating my business and need to optimize salary vs dividends." The list below shows everything the skill *can* do, not what you *have* to do. Think of it as having your own AI financial coach on call who happens to know every corner of Canadian finance.

- **Personalized financial profile** saved to your computer
- **Detailed monthly budget** with spending insights and optimization suggestions
- **Phased action plan** (Stabilize → Build → Accelerate) with timelines
- **Interactive HTML dashboard** with charts for net worth, debt payoff, retirement projections, RESP tracking, CPP comparison, investment growth comparison, and more
- **Investment education** — popular Canadian ETFs, GICs, and HISAs with risk-matched suggestions, Morningstar ratings, and growth projections
- **Life event action plans** — structured guidance for 10 major life changes (new baby, marriage, divorce, job loss, parental leave, death of spouse, aging parents, inheritance, moving provinces, buying a home) with Canadian programs, tax implications, and checklists
- **Estate planning** — wills (types, costs, intestacy rules by province), Powers of Attorney (property + personal care), executor duties and compensation, probate process and fees by province, probate avoidance strategies, trusts (Henson, family, alter ego, testamentary), deemed disposition tax and mitigation, blended family planning, cottage succession, digital estate, charitable giving, guardianship, and incapacity planning
- **Retirement income optimization** — CPP timing (60/65/70 with break-even math), OAS deferral decision tree, GIS optimization (TFSA strategy), RRSP meltdown, RRIF conversion strategy, income layering by age, pension decisions (DB commuted value vs monthly), pension income splitting, bridge income for early retirement, annuities, and couples coordination
- **Tax filing season guide** — complete checklist of credits and deductions people miss, couples optimization (who claims what), investment income reporting, tax software comparison, CRA My Account, penalties and disputes, voluntary disclosure, student/senior/new immigrant guidance
- **Portfolio management** — asset location optimization, rebalancing strategies, tax-loss harvesting (superficial loss rule), ACB tracking, US securities (withholding tax, estate tax, RRSP treaty), employee stock options/RSUs, dividend tax credit, REIT taxation, retirement withdrawal strategy (RRIF minimums, OAS clawback, 4% rule), and behavioral investing
- **Self-employed & incorporated** — incorporation decision tree with tax math, salary vs dividends optimization, SBD rates by province, business expense deductions (home office, vehicle, CCA), HST/GST registration, quarterly installments, startup planning, business succession (LCGE $1.25M), SRED tax credits, IPP for 40+, shareholder loans, and gig economy guidance
- **All provinces & territories** — province-specific tax brackets, child benefits, disability programs, pharmacare, and health coverage for all 13 jurisdictions. Full Quebec support (QPP, QST, QPIP, Revenu Québec, RAMQ). No longer Ontario-centric.
- **Insurance deep-dive** — DIME needs analysis, term vs permanent life insurance with cost benchmarks, disability insurance (own-occ vs any-occ, elimination periods), critical illness insurance, group vs individual coverage, conversion rights, employer benefits optimization, and insurance estate planning
- **Real estate & housing** — rent vs buy analysis, mortgage strategy (fixed vs variable, prepayment, renewal negotiation), home equity (HELOC, refinancing, reverse mortgage), investment property with tax treatment, condo vs freehold, principal residence exemption, downsizing, and provincial land transfer tax
- **Debt strategy deep-dive** — consumer proposals, bankruptcy guidance, collections rights, CRA tax debt, payday loan exit plans, credit rebuilding, and behavioral coaching for debt stress
- **Cross-border planning** — snowbird tax residency (substantial presence test, Form 8840, days counting), Canadians owning US property (FIRPTA, US estate tax), newcomer financial onboarding (SIN, credit building, RRSP/TFSA room), departure tax (deemed disposition), foreign pensions, FBAR/FATCA for US citizens in Canada, returning to Canada, and foreign tax credits
- **Ongoing coaching** — monthly check-ins, purchase decisions ("should I buy this?"), and life change updates
- **Multiple output formats** — shareable PDFs, editable Excel budget, plus interactive HTML dashboard
- **Built-in validation** — every number is double-checked for accuracy and cross-file consistency

## Canadian-Specific Features

- Federal and provincial tax bracket optimization
- RRSP, TFSA, RESP, FHSA, and RDSP strategies
- CPP/OAS deferral analysis
- Canada Child Benefit (CCB) and other government benefits
- CESG and CDSG capture (free government money)
- Provincial variations (probate, health premiums, benefits)
- CRA calendar and deadline tracking
- Self-employed and incorporated planning
- Spousal strategies and attribution rules

---

## Quick Install (Cowork Mode — Recommended)

The easiest way to use this skill. Works on **Mac and Windows**.

1. Download the **[financial-planner.skill](./financial-planner.skill)** file from this repo
2. Open the **Claude desktop app** ([download here](https://claude.ai/download))
3. Enter **Cowork mode** (bottom-left of the Claude window)
4. Click **Customize** → **Skills** → **Upload**
5. Select the `financial-planner.skill` file
6. Start a conversation and say: **"Help me with my finances"**

That's it! Claude will walk you through everything from there.

> Requires a paid Claude plan with Cowork mode: Pro (C$24/mo billed annually), Max (from C$140/mo), Team (C$27.42/seat/mo), or Enterprise. The free tier does not support skills or Cowork mode. Prices exclude tax. [See pricing](https://claude.com/pricing)

## Install via Claude Code (Command Line)

For users comfortable with a terminal. Works on **Mac, Windows (WSL), and Linux**.

### Mac

```bash
# Install Claude Code (requires Node.js 18+)
npm install -g @anthropic-ai/claude-code

# Sign in
claude

# Create skills folder and install the skill
mkdir -p ~/.claude/skills
unzip financial-planner.skill -d ~/.claude/skills/

# Or install directly from GitHub
mkdir -p ~/.claude/skills
git clone https://github.com/cjpatten/canadian-finance-planner-skill.git ~/.claude/skills/financial-planner

# Navigate to where you want your plan saved and launch
mkdir -p ~/Documents/MyFinances && cd ~/Documents/MyFinances
claude
```

### Windows (via WSL)

```bash
# First, install WSL if you haven't (run in PowerShell as Admin):
# wsl --install
# Then restart and open your Ubuntu/WSL terminal

# Install Node.js
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs

# Install Claude Code
npm install -g @anthropic-ai/claude-code

# Sign in
claude

# Create skills folder and install the skill
mkdir -p ~/.claude/skills
unzip /mnt/c/Users/YOUR_USERNAME/Downloads/financial-planner.skill -d ~/.claude/skills/

# Or install directly from GitHub
mkdir -p ~/.claude/skills
git clone https://github.com/cjpatten/canadian-finance-planner-skill.git ~/.claude/skills/financial-planner

# Navigate to your Windows Documents folder and launch
mkdir -p /mnt/c/Users/YOUR_USERNAME/Documents/MyFinances
cd /mnt/c/Users/YOUR_USERNAME/Documents/MyFinances
claude
```

> Replace `YOUR_USERNAME` with your Windows username. Run `ls /mnt/c/Users/` to see available usernames.

## Install via Plugin Marketplace

```
/plugin marketplace add cjpatten/canadian-finance-planner-skill
```

---

## How It Works

### The Interview
Claude walks you through 7 rounds of questions (2–3 at a time, never overwhelming):

| Round | Topic | What Claude Asks About |
|-------|-------|----------------------|
| 1 | Life Context | Age, province, family, housing, employment |
| 2 | Income | Salary, side hustles, government benefits |
| 3 | Expenses | Fixed, variable, and annual spending |
| 4 | Debts | Credit cards, loans, mortgage details |
| 5 | Assets & Savings | RRSP, TFSA, RESP, FHSA, real estate |
| 6 | Insurance | Life, disability, employer benefits, will/POA |
| 7 | Goals | Short-term, medium-term, long-term priorities |

The interview takes 30–60 minutes across 1–3 sessions. You can stop and come back anytime — Claude saves your progress.

### Your Plan Files
Claude saves files to your selected folder, organized for easy use:

| File / Folder | Contents |
|------|----------|
| `1-my-profile.md` | Your complete financial snapshot |
| `2-my-budget.md` | Detailed budget with insights |
| `3-my-plan.md` | Phased action plan with projections |
| `4-my-dashboard.html` | Interactive visual dashboard (open in any browser) |
| `shareable/` | PDF + Excel versions ready to email, print, or share with an advisor |
| `README.txt` | Quick guide explaining what each file is for |

### Ongoing Use
After your initial plan, come back anytime and say:

- **"Let's do a monthly check-in"** — compare actual vs. planned spending
- **"Should I buy a $900 TV?"** — purchase decision analysis using your real budget
- **"I got a raise"** / **"We're having a baby"** — life change recalculation
- **"Is my RRSP on track?"** — quick questions answered with your data

### What Can I Ask? (Example Prompts)

This skill covers far more than basic budgeting. Here are examples of what you can ask, from simple to advanced:

**Getting Started**
- "Help me with my finances"
- "I need a budget"
- "Can you build me a complete financial plan?"

**Budgeting & Spending**
- "Should I buy a $900 TV?"
- "Where is all my money going every month?"
- "My partner and I keep fighting about money — how should we split expenses?"

**Debt**
- "How do I pay off my credit card debt fastest?"
- "Should I consolidate my debts into a line of credit?"
- "I can't make my minimum payments — what are my options?"
- "Should I do a consumer proposal or file bankruptcy?"
- "I'm being contacted by a collection agency — what are my rights?"

**Investing**
- "How do I start investing? What's a good first ETF?"
- "Should I put my money in a TFSA or RRSP?"
- "I have $200K to invest — how should I split it across my accounts?"
- "What's the difference between VGRO, VBAL, and VEQT?"
- "I have US investments — what's this withholding tax I'm paying?"

**Retirement**
- "When can I retire? Will I have enough?"
- "Should I take CPP at 60, 65, or 70?"
- "How do I avoid the OAS clawback?"
- "Should I do an RRSP meltdown before I turn 65?"
- "I have a pension — should I take the lump sum or monthly payments?"

**Real Estate**
- "Should I rent or buy?"
- "My mortgage is up for renewal — how do I negotiate a better rate?"
- "Should I pay down my mortgage faster or invest instead?"
- "I want to buy a rental property — what's the tax treatment?"
- "We're thinking about downsizing — what's the financial impact?"

**Insurance**
- "How much life insurance do I actually need?"
- "Do I need disability insurance? My employer has some coverage."
- "My bank is pushing whole life insurance — is that a good idea?"
- "I'm leaving my job — can I keep my group insurance?"

**Taxes**
- "What deductions am I missing on my tax return?"
- "Should my spouse or I claim the medical expenses?"
- "I'm self-employed — what can I deduct?"
- "I got a Notice of Assessment from CRA — what does it mean?"

**Life Events**
- "We're having a baby — what do we need to do financially?"
- "I just lost my job — what's my emergency plan?"
- "We're getting divorced — how do we split everything?"
- "I inherited $150,000 — what should I do with it?"
- "I'm caring for my aging parents — what financial help is available?"

**Self-Employment**
- "Should I incorporate my business?"
- "Salary vs dividends — which is better for me?"
- "What's the lifetime capital gains exemption and do I qualify?"

**Estate Planning**
- "I don't have a will — what happens if I die?"
- "What's the difference between a will and a Power of Attorney?"
- "How do I pass my cottage to my kids without a huge tax bill?"
- "I've been named executor — what do I actually have to do?"
- "My child has a disability — what's a Henson trust?"

**Cross-Border & International**
- "I spend winters in Florida — do I have US tax obligations?"
- "I just moved to Canada — where do I start financially?"
- "We own a condo in Arizona — what are the tax implications?"
- "I'm leaving Canada — what happens to my investments?"
- "I'm a US citizen living in Canada — what do I need to file?"
- "I have a US pension — how does that work in Canada?"

---

## Demo

The [demo-sample-plan/](./demo-sample-plan/) folder contains a complete example for a fictional young Canadian family (Marcus & Sarah Chen, Barrie ON, combined income $157K, two kids). Open `4-my-dashboard.html` in any browser to see the interactive dashboard.

## Test Scenarios

The [test-scenarios/](./test-scenarios/) folder contains 12 pre-built sample personas representing diverse Canadian financial situations — from newcomers and snowbirds to debt crises and blended families. Use these to test the skill with realistic data or to compare output quality with and without the skill. Each persona includes complete interview data ready to paste into a conversation. See the folder's README for instructions and a scoring rubric.

---

## Skill Structure

```
SKILL.md                                  # Core skill (always in context)
references/
├── interview-guide.md                    # All 7 interview rounds
├── canada-finance-rules.md               # Tax rules, registered accounts, benefits
├── calculations-and-dashboard.md         # Budget math, projections, dashboard specs
├── scenarios-and-coaching.md             # Life scenarios, purchase decisions, coaching
├── investment-basics.md                  # ETF education, GICs, HISAs, growth comparison
├── life-events.md                        # 10 major life event action plans
├── debt-strategy.md                      # Consumer proposals, bankruptcy, collections, credit rebuilding
├── real-estate.md                        # Rent vs buy, mortgages, home equity, investment property
├── insurance.md                          # Life, disability, critical illness, group vs individual, estate planning
├── provincial-rules.md                   # Tax brackets, benefits, health, pharmacare for all 13 jurisdictions
├── self-employed.md                      # Incorporation, salary vs dividends, deductions, SRED, IPP, succession
├── portfolio-management.md               # Asset location, rebalancing, tax-loss harvesting, withdrawal strategy
├── tax-filing.md                         # Credits, deductions, couples optimization, CRA disputes, filing guide
├── retirement-income.md                  # CPP/OAS timing, GIS optimization, RRIF strategy, pensions, annuities
├── estate-planning.md                    # Wills, probate, trusts, executor duties, guardianship, incapacity
└── cross-border.md                       # Snowbirds, newcomers, US property, departure/return, FBAR/FATCA
```

The `SKILL.md` file is always loaded and controls the conversation flow. Reference files are loaded on demand when the relevant phase is active, keeping things fast and focused.

---

## Documentation

- **[Getting-Started-Guide.docx](./Getting-Started-Guide.docx)** — Step-by-step instructions for non-technical users (Mac & Windows)

---

## Privacy

- All plan files are saved **on your computer**, not in the cloud
- Claude processes data through Anthropic's servers (encrypted in transit and at rest)
- To prevent training on your data: Claude Settings → Privacy → turn off "Help improve Claude"
- The skill never asks for or stores your SIN, bank account numbers, or credit card numbers

---

## Sources & Citations

Every number in this skill is double-source verified against authoritative Canadian and international sources. The skill also verifies current data via web search before presenting it to users, so even if a reference file becomes slightly stale, the user always gets up-to-date figures.

**150+ source URLs** are embedded across 16 reference files. Here are the key sources by category:

| Category | # Sources | Key References |
|----------|-----------|----------------|
| **CRA / Canada.ca** | 50+ | [Tax brackets & rates](https://www.canada.ca/en/revenue-agency/services/tax/individuals/frequently-asked-questions-individuals/canadian-income-tax-rates-individuals-current-previous-years.html), [RRSP/TFSA/RESP limits](https://www.canada.ca/en/revenue-agency/services/tax/registered-plans-administrators/pspa/mp-rrsp-dpsp-tfsa-limits-ympe.html), [CPP amounts](https://www.canada.ca/en/services/benefits/publicpensions/cpp/amount.html), [OAS payments](https://www.canada.ca/en/services/benefits/publicpensions/old-age-security/payments.html), [CCB](https://www.canada.ca/en/revenue-agency/services/child-family-benefits/canada-child-benefit.html), [CRA My Account](https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals.html) |
| **Provincial Governments** | 40+ | Tax brackets, disability programs (ODSP, AISH, PWD), pharmacare, health coverage for all 13 provinces and territories. Full Quebec support (Revenu Québec, RAMQ, QPIP). |
| **IRS / US Government** | 10+ | [Substantial presence test](https://www.irs.gov/individuals/international-taxpayers/substantial-presence-test), [FIRPTA](https://www.irs.gov/individuals/international-taxpayers/firpta-withholding), [FBAR](https://www.irs.gov/businesses/small-businesses-self-employed/report-of-foreign-bank-and-financial-accounts-fbar), [Canada-US Tax Treaty](https://www.canada.ca/en/department-finance/programs/tax-policy/tax-treaties/country/united-states-america-convention-consolidated-1980-1983-1984-1995-1997-2007.html), [IRS Publication 597](https://www.irs.gov/publications/p597) |
| **Financial Institutions** | 15+ | [Vanguard Canada](https://www.vanguard.ca), [iShares/BlackRock](https://www.blackrock.com/ca), [Morningstar Canada](https://www.morningstar.ca), [RateHub.ca](https://www.ratehub.ca), [WOWA.ca](https://www.wowa.ca), [EQ Bank](https://www.eqbank.ca) |
| **Professional Bodies** | 5+ | [FP Canada](https://www.fpcanada.ca) (projection assumptions, planner directory), [CLHIA](https://www.clhia.ca), [Insurance Bureau of Canada](https://www.ibc.ca), [Credit Counselling Canada](https://www.creditcounsellingcanada.ca) |
| **Tax & Planning** | 15+ | [TaxTips.ca](https://www.taxtips.ca) (comprehensive tax reference), [Adjusted Cost Base](https://www.adjustedcostbase.ca), [Canadian Couch Potato](https://canadiancouchpotato.com), [FCAC](https://www.canada.ca/en/financial-consumer-agency.html) |
| **Housing & Mortgage** | 10+ | [CMHC](https://www.cmhc-schl.gc.ca), [FCAC Mortgage Tools](https://www.canada.ca/en/financial-consumer-agency/services/mortgages.html), provincial land transfer tax calculators |
| **Legal & Estate** | 5+ | [Office of the Superintendent of Bankruptcy](https://www.ic.gc.ca/eic/site/bsf-osb.nsf/eng/home), provincial probate rules, Henson Trust resources |

All source URLs are organized by topic within each reference file, with verification dates noted. The skill's reference files cite 50+ government URLs (canada.ca), ensuring guidance is grounded in official rules rather than opinion.

---

## Disclaimer

This skill provides financial education and planning tools, not licensed financial advice. For complex situations (investments over $500K, estate planning, incorporation, cross-border tax), consult a fee-only financial advisor. The skill will recommend this when appropriate.

---

## Questions or Feedback?

[Open an issue](https://github.com/cjpatten/canadian-finance-planner-skill/issues) — happy to help with setup, bugs, or feature ideas.

---

## License

[MIT](./LICENSE)

---

*Built with Claude. Canada-focused (v2.4).*
