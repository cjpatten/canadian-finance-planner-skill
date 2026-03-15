# Canadian Personal Finance Manager

**Current version:** 1.3 | [View changelog](https://github.com/cjpatten/canadian-finance-planner-skill/releases)

A custom skill for [Claude](https://claude.ai) that turns it into your personal financial planner — built specifically for Canadians.

Claude conducts a thorough financial interview, builds a complete budget and action plan, generates an interactive dashboard with charts, and provides ongoing coaching. All tailored to Canadian tax rules, government benefits, and registered accounts.

---

## What You Get

- **Personalized financial profile** saved to your computer
- **Detailed monthly budget** with spending insights and optimization suggestions
- **Phased action plan** (Stabilize → Build → Accelerate) with timelines
- **Interactive HTML dashboard** with charts for net worth, debt payoff, retirement projections, RESP tracking, CPP comparison, investment growth comparison, and more
- **Investment education** — popular Canadian ETFs, GICs, and HISAs with risk-matched suggestions, Morningstar ratings, and growth projections
- **Life event action plans** — structured guidance for 10 major life changes (new baby, marriage, divorce, job loss, parental leave, death of spouse, aging parents, inheritance, moving provinces, buying a home) with Canadian programs, tax implications, and checklists
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

> Requires a paid Claude plan (Pro $20/mo, Max, Teams, or Enterprise). [See pricing](https://claude.ai/pricing)

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
git clone https://github.com/cjpatten/canadian-finance-planner-skill.git
cp -r canadian-finance-planner-skill/financial-planner ~/.claude/skills/
rm -rf canadian-finance-planner-skill

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
git clone https://github.com/cjpatten/canadian-finance-planner-skill.git
cp -r canadian-finance-planner-skill/financial-planner ~/.claude/skills/
rm -rf canadian-finance-planner-skill

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

---

## Demo

The [demo-sample-plan/](./demo-sample-plan/) folder contains a complete example for a fictional young Canadian family (Marcus & Sarah Chen, Barrie ON, combined income $157K, two kids). Open `4-my-dashboard.html` in any browser to see the interactive dashboard.

---

## Skill Structure

```
financial-planner/
├── SKILL.md                              # Core skill (always in context)
└── references/
    ├── interview-guide.md                # All 7 interview rounds
    ├── canada-finance-rules.md           # Tax rules, registered accounts, benefits
    ├── calculations-and-dashboard.md     # Budget math, projections, dashboard specs
    ├── scenarios-and-coaching.md         # Life scenarios, purchase decisions, coaching
    ├── investment-basics.md              # ETF education, GICs, HISAs, growth comparison
    └── life-events.md                    # 10 major life event action plans
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

## Disclaimer

This skill provides financial education and planning tools, not licensed financial advice. For complex situations (investments over $500K, estate planning, incorporation, cross-border tax), consult a fee-only financial advisor. The skill will recommend this when appropriate.

---

## Questions or Feedback?

[Open an issue](https://github.com/cjpatten/canadian-finance-planner-skill/issues) — happy to help with setup, bugs, or feature ideas.

---

## License

[MIT](./LICENSE)

---

*Built with Claude. Canada-focused (v1.3).*
