# Mark Laird

**AI Solutions Engineer.** I take ambiguous problems and ship working AI products end to end, from the first customer conversation through to production.

Portfolio: [Portfolio Site](https://markslaird.com/) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/markslaird/) &nbsp;|&nbsp; Dallas-Fort Worth, open to relocation

---

### What I have built

**[amy-evals](https://github.com/mslaird/amy-evals)** &nbsp;·&nbsp; A deterministic eval harness for the production voice agent under CloudAurum, below. Six golden scenarios, string and state assertions instead of an LLM judge — because the published measurement on judges for agent task completion is poor, and a wrong metric you trust is worse than no metric. Runs from a clean clone with no API key. Auditing it, I found two of my own assertions were quietly broken; both are fixed with regression tests and written up in the README.

**CloudAurum** &nbsp;·&nbsp; Diagnostic-led AI and workflow consulting practice. Map where a business leaks revenue, quantify the cost, then architect and build only what closes it: AI voice and SMS agents (Retell, Twilio, Make, Claude), reactivation campaigns, workflow automation, and systems consolidation. The eval harness that keeps that voice agent honest is [amy-evals](https://github.com/mslaird/amy-evals), above.

**[Proffio](https://github.com/mslaird/proffio-case-study)** &nbsp;·&nbsp; An AI operating system for real estate brokerages, and the largest thing I have built. **Running:** 30 routed screens over a **118-table Postgres schema** behind **245 row-level security policies**, a three-tier permission model enforced in SQL rather than in the interface, and 24 Supabase edge functions. **Designed, not wired:** ~75 further screens and 20+ AI services. Source is private; the published case study is the RBAC pattern and the cross-tenant leak I shipped, found, and fixed.

**[GradeForAI](https://github.com/mslaird/gradeforai)** &nbsp;·&nbsp; Python scoring engine and data pipeline that graded **505,140 businesses** across **130+ industries** on whether AI agents can find, understand, and transact with them. Six engine versions, each calibrated against real results. Shipped a CLI, dashboard, automated refresh, and client-facing reports.

**[Ticker Buddy](https://github.com/mslaird/Ticker-Buddy-MVP)** &nbsp;·&nbsp; Multi-asset market intelligence platform. **Built:** a React/TypeScript MVP on Supabase with a 1,122-line Deno edge function wrapping two unreliable upstreams, a Manifest V3 browser extension sharing the app's auth session, and a D3 market-cap heat map. **Designed, not built:** the NLP sentiment and volatility layer the whitepaper specifies, which needed roughly $12K/month in licensed market data. Also a 47-page whitepaper, a full Figma design system, and a trademark that cleared USPTO examination with no conflicting marks found, then lapsed when no Statement of Use was filed because nothing sold. Paused pending capital.

**[OptionPulse](https://github.com/mslaird/optionpulse-insight-hub)** &nbsp;·&nbsp; Options analytics prototype (TypeScript, Supabase): a thirteen-screen product surface and an Alpha Vantage options-chain service behind a staleness-aware cache and a ticker allowlist. Put in front of early users, then stopped over data licensing and the regulatory exposure of publishing predictive signals on securities. The alerts and the auth were mock and the repo says so — there is no model in it.

### Stack

- **Voice and agents** &nbsp;·&nbsp; `Retell` `Twilio` `Make` `Claude` · agent and prompt design · deterministic evals
- **Backend and data** &nbsp;·&nbsp; `Python` `Supabase` (Postgres, RLS, edge functions) `SQLite` `Deno`
- **Frontend** &nbsp;·&nbsp; `TypeScript` `React` `Chrome MV3`
- **How I build** &nbsp;·&nbsp; I direct coding agents (`Claude Code`, `Codex`, `Cursor`) against a spec I write, then review and correct what comes back. The corrections are in the repos above.

### What I am looking for

Solutions Engineer, Sales Engineer, and AI implementation roles where building, AI, and the customer meet.

*SAG-AFTRA actor, most recently in a national Navy Federal Credit Union campaign, so I build the product and can also stand in front of a room and explain it.*
