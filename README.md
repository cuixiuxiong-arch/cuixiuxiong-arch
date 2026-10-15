<div align="center">

# Edgar Cui

### Finance Professional · Self-taught Software Builder · Quant Research

Turning finance know-how into reliable software — automated reporting,
analytics, and risk-controlled trading research.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

[![Website](https://img.shields.io/badge/Website-auditablecode.com-0D2137?style=flat-square)](https://auditablecode.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Edgar_Cui-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/edgar-cui-882b58421)
[![Email](https://img.shields.io/badge/Email-cuixiuxiong%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cuixiuxiong@gmail.com)

</div>

---

## About

I work in finance and build the software I wish finance teams had. I started with
no programming background; today I design and ship end-to-end tools — data pipelines,
dashboards, reconciliation utilities and paper-first trading systems — using Python,
SQL and AI-assisted development.

My edge is the overlap: I understand how the ledger works *and* how the code works.
The numbers my tools produce are numbers an auditor can trace.

Now building **Auditable Code** — free finance calculators that show their working,
and small kits for finance teams who automate with AI: https://auditablecode.com

## Core Competencies

- **Finance & Control** — month-end close, reconciliations, indirect tax (GST/VAT),
  internal controls, audit-trail design, management reporting
- **Data & Analytics** — SQL, pandas, ETL pipelines, data-quality checks,
  semantic layers, BI dashboards (Metabase)
- **Engineering** — Python, automated testing (pytest), Git, Docker,
  scheduled jobs, AI-assisted development
- **Quant Research** — backtesting, position sizing, risk limits, kill switches,
  broker reconciliation — always paper-first

## Featured Work

<sub>Private repositories — demos available on request.</sub>

**US Market Command Centre** · `us-stock-platform`
> *Problem:* trading US markets from another time zone, with no time to watch screens.
> *Built:* a read-only dashboard with a market-regime light (SPY vs 200-day MA, VIX,
> breadth), a four-layer screening funnel, a sell-signal engine and session-aware
> scheduled alerts. No order placement by design; every alert states the rule behind it.

**A-share Next-day Order Planner** · `ashare-dapan-platform`
> *Problem:* delayed data, T+1 settlement, no intraday monitoring.
> *Built:* after-close screening that outputs a next-day limit-order sheet (entry, stop,
> target), 1%-risk position sizing, per-stock caps, daily new-position limits and a
> losing-streak pause.

**Event-driven Quant Engine** · `us-quant` / `ibkr-quant`
> Strategy registry, backtester, risk manager, kill switch, idempotent order router,
> broker reconciler and trade journal — with a test suite around every risk control.
> Live trading is gated behind configuration *and* human approval.

**Calendar-science Dashboard** · `bazi-dashboard`
> A deterministic calendar engine (solar terms, true solar time) with a timeline and
> web UI. 100+ automated tests; scoring uses no LLM, so every result is reproducible.

Also: `okx-quant-bot` (grid strategy + watchdog) · `lottery-analyzer`
(an expected-value reality check) · I Ching / Five Elements market dashboards.

## Engineering Principles

1. **Money is `Decimal`, never `float`.**
2. **Raw data is read-only.** Work on copies; keep the source intact.
3. **Every number is traceable** — source, formula, intermediate steps, result.
4. **Tests before trust.** Core logic is covered by automated tests.
5. **Human in the loop.** No automated system moves real money without explicit approval.
6. **Secrets never live in code.**
7. **AI drafts; I audit.**

## By the Numbers

| 10+ | 100+ | 2 | 0 |
|:---:|:---:|:---:|:---:|
| private projects shipped | automated tests in one project | markets covered end-to-end | bot orders without human approval |

## Currently

- Building an open-source starter kit for finance professionals adopting AI coding tools
- Self-service analytics for non-technical teams
- AI agents for repetitive finance workflows

## Open To

Finance systems, financial analysis and finance automation roles — and collaboration
on open-source tools for finance professionals.
Reach me on [LinkedIn](https://www.linkedin.com/in/edgar-cui-882b58421) or at
[cuixiuxiong@gmail.com](mailto:cuixiuxiong@gmail.com).

<sub>Built on open source. Thanks to the pandas, Metabase and Python communities.</sub>
