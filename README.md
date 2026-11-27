# NSE Trader AI — 11 Educational Skills

A Claude-compatible skill-pack structure for learning about Indian listed stocks
and reviewing **simulated paper trades only**.

## Skills
- `nse-scanner/SKILL.md` — NSE Stock Scanner
- `nse-analyst/SKILL.md` — NSE Company Analyst
- `nse-news/SKILL.md` — NSE News Context
- `nse-risk/SKILL.md` — Paper Trading Risk Checker
- `nse-entry/SKILL.md` — Simulated Entry Planner
- `nse-exit/SKILL.md` — Simulated Exit Reviewer
- `nse-budget/SKILL.md` — Virtual Portfolio Budget
- `nse-backtest/SKILL.md` — Historical Strategy Tester
- `nse-portfolio/SKILL.md` — Virtual Portfolio Monitor
- `nse-data-check/SKILL.md` — Market Data Quality Checker
- `nse-daily-report/SKILL.md` — Daily Paper Trading Report

## Suggested daily workflow
1. `nse-data-check` — validate supplied daily data.
2. `nse-scanner` — screen a chosen NSE watchlist.
3. `nse-news` — summarize supplied news.
4. `nse-analyst` — explain shortlisted companies.
5. `nse-entry` — apply the paper-entry checklist.
6. `nse-risk` — check virtual exposure and limits.
7. `nse-budget` — update virtual cash and estimated costs.
8. `nse-portfolio` — summarize virtual positions.
9. `nse-exit` — review virtual exit conditions.
10. `nse-backtest` — evaluate historical rules separately.
11. `nse-daily-report` — create the daily report.

## Data format
A daily CSV can use: `date,symbol,open,high,low,close,volume`.
State its source, date range, timezone, and whether prices are adjusted.

## Mobile use
Keep this repository in GitHub and read/edit its Markdown files from your phone.
Uploading it to GitHub does not automatically activate the skills in Claude.
Use the AI product's current skill-import instructions if available.

## Safety
This project is educational only. It has no broker integration, no order placement,
and no real-money execution. Market data may be delayed or incomplete. It is not
financial, legal, or tax advice. Historical tests do not predict future results.
