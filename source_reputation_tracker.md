# Source Reputation Tracker v5 — Awake & Informed

## System Overview

**Credibility trend thresholds (≥3 appearances required for trend assignment):**
- ↑ Improving: Recent 3-run average exceeds overall average by >0.5
- ↓ Declining: Recent 3-run average falls >0.5 below overall average
- ⚠ Volatile: Standard deviation >1.5
- → Stable: Consistent performance
- 🆕 New: <3 appearances, no trend assigned

**Score scale:** 0–10 per run. Credibility scores reflect sourcing quality, accuracy, and primary source chain integrity.

**Relevance weight floor/ceiling:** ±1.5 per subscriber
**Decay rule:** ±0.2 toward 0 per run without confirming feedback; never overshoots 0

---

## Sources

| Source | Overall Avg | Appearances | Trend | Notes |
|---|---|---|---|---|
| Al Jazeera | 8.80 | 1 | 🆕 New | Single appearance |
| Anthropic | 7.50 | 1 | 🆕 New | Single appearance |
| AI2Work | 6.50 | 1 | 🆕 New | Single appearance |
| Bloomberg | 9.00 | 2 | 🆕 New | Strong sourcing |
| CNBC | 8.22 | 5 | → Stable | Consistent performance |
| Dark Reading | 7.50 | 1 | 🆕 New | Single appearance |
| Decrypt | 7.00 | 1 | 🆕 New | Single appearance |
| Engadget | 8.50 | 1 | 🆕 New | First appearance; strong multi-outlet corroboration on Terafab story |
| Fortune | 8.25 | 2 | 🆕 New | Two appearances |
| The Guardian | 7.50 | 1 | 🆕 New | First appearance; credible UK outlet, primary sourcing on FCA contract story solid |
| Import AI | 7.90 | 1 | 🆕 New | Single appearance |
| METR | 9.00 | 1 | 🆕 New | Single appearance |
| Microsoft Security Blog | 8.50 | 1 | 🆕 New | Single appearance |
| MIT Technology Review | 7.50 | 4 | → Stable | Preferred source; consistent |
| MIT News | 9.00 | 1 | 🆕 New | Single appearance |
| NVIDIA Newsroom | 9.10 | 1 | 🆕 New | Single appearance |
| Reuters | 8.50 | 1 | 🆕 New | First appearance; named journalists, clean source chain on Tencent/WeChat story |
| TechCrunch | 7.93 | 11 | → Stable | Stable; low score on podcast teaser reflected format, not source unreliability |
| The Decoder | 7.67 | 3 | → Stable | Stable |
| The New Stack | 6.90 | 4 | → Stable | Preferred source |
| Townhall | 8.80 | 1 | 🆕 New | Single appearance |
| Transparency Coalition | 7.60 | 2 | 🆕 New | Two appearances |
| VentureBeat | 8.23 | 10 | → Stable | Preferred source; stable |
| Wall Street Journal | 7.80 | 1 | 🆕 New | First appearance; strong outlet, anonymous sourcing standard for internal corporate tools reporting; credible |

---

## Publication History — AI-20260323-test (updated run)

### Article 1
**Source:** Wall Street Journal (corroborated: Reuters, Cointelegraph, Storyboard18, BusinessToday India, Implicator AI)
**Date:** 23 March 2026
**Run ID:** AI-20260323-test
**Title:** Mark Zuckerberg is building an AI agent to help him run Meta
**Topic area:** 🏢 AI in Business & Industry
**Sub-tags:** agentic AI, enterprise AI, AI governance
**Credibility score this run:** 7.80
**Sourcing note:** 2 primary sources cited — anonymous "person familiar with project" (standard corporate journalism practice, unverifiable by nature) and Zuckerberg's January 2026 earnings call (public record, verified). Key claims consistent across 8+ independent outlets. No contradictory reporting found. SEV1 security incident detail corroborated by Reuters. Solid WSJ reporting.
**Misrepresentation flags:** None

### Article 2
**Source:** Reuters (report by Liam Mo and Ryan Woo)
**Date:** 22 March 2026
**Run ID:** AI-20260323-test
**Title:** Tencent integrates WeChat with OpenClaw AI agent amid China tech battle
**Topic area:** 🛠️ AI Tools & Products · 🏢 AI in Business & Industry
**Sub-tags:** agentic AI, Chinese AI, AI tools
**Credibility score this run:** 8.50
**Sourcing note:** Reuters bylined report with named journalists. Sources Tencent product announcement and industry context. Multiple secondary outlets (Manila Times, Yahoo Finance, WHBL, ChinaTechNews, technology.org) accurately reproduce the Reuters report. Clean chain; no misrepresentation.
**Misrepresentation flags:** None

### Article 3
**Source:** The Guardian
**Date:** 23 March 2026
**Run ID:** AI-20260323-test
**Title:** Palantir wins UK FCA trial to access sensitive financial crime intelligence data
**Topic area:** ⚖️ AI Safety & Ethics · 🏢 AI in Business & Industry
**Sub-tags:** AI governance, AI security, enterprise AI
**Credibility score this run:** 7.50
**Sourcing note:** The Guardian reporting on public FCA procurement contract. FCA contract terms (data processor vs controller, UK storage, destruction on completion) are verifiable through public procurement records. Palantir's existing UK contracts (NHS £330M, MoD £240M) are public record and accurately cited. Privacy concern framing is editorially appropriate given factual context. No misrepresentation.
**Misrepresentation flags:** None

---

## Publication History — AI-20260323-test (previous test, superseded)

*(Articles from this earlier test — Terafab/Engadget, VentureBeat agentic AI, TechCrunch podcast teaser — are recorded in the AI-20260323-test entry from the prior session. Superseded by updated test above using March 23 articles.)*

---

## Publication History — AI-20260322-test

### Article 1
**Source:** TechCrunch
**Date:** 22 March 2026
**Run ID:** AI-20260322-test
**Title:** Cursor admits its new coding model was built on top of Moonshot AI's Kimi
**Topic area:** 🛠️ AI Tools & Products · ⚖️ AI Safety & Ethics
**Sub-tags:** model release, open-source AI, developer tools, AI governance, Chinese AI
**Credibility score this run:** 8.5
**Sourcing note:** 5 primary sources cited (company statements, API evidence, license text, partner confirmation). 4 verified. Accurate representation throughout.
**Misrepresentation flags:** None

### Article 2
**Source:** The Decoder
**Date:** 22 March 2026
**Run ID:** AI-20260322-test
**Title:** Xiaomi launches three MiMo AI models to power agents, robots, and voice
**Topic area:** 🔬 AI Research & Breakthroughs · 🛠️ AI Tools & Products
**Sub-tags:** model release, agentic AI, Chinese AI, AI research, AI tools
**Credibility score this run:** 8.0
**Sourcing note:** Official Xiaomi release plus independently verifiable public benchmarks.
**Misrepresentation flags:** None

### Article 3
**Source:** The Decoder
**Date:** 22 March 2026
**Run ID:** AI-20260322-test
**Title:** Andrej Karpathy says humans are now the bottleneck in AI research
**Topic area:** 🔬 AI Research & Breakthroughs
**Sub-tags:** AI research, agentic AI, AI engineering
**Credibility score this run:** 7.5
**Sourcing note:** Single primary source (No Priors Podcast, YouTube). Direct quote verified. Short-form news brief; limited citation depth appropriate to format.
**Misrepresentation flags:** None

---

## Subscriber Profiles

### Jason (jmc04g@gmail.com) — Active

**Topic weights (default, equal):** Research 25% · Business 25% · Tools 25% · Safety/Ethics 25%

**Sub-tag relevance weights:**

| Sub-tag | Weight | Last confirmed | Decay applied |
|---|---|---|---|
| agentic AI | 0 | — | N/A |
| AI infrastructure | 0 | — | N/A |
| enterprise AI | 0 | — | N/A |
| AI chips | 0 | — | N/A |
| AI safety | 0 | — | N/A |
| AI governance | 0 | — | N/A |
| OpenAI | 0 | — | N/A |
| Anthropic | 0 | — | N/A |
| MCP | 0 | — | N/A |
| AI engineering | 0 | — | N/A |
| developer tools | 0 | — | N/A |
| inference | 0 | — | N/A |
| cloud AI | 0 | — | N/A |
| military AI | 0 | — | N/A |
| autonomous weapons | 0 | — | N/A |
| Nvidia GTC | 0 | — | N/A |
| model release | 0 | — | N/A |
| AI research | 0 | — | N/A |
| hallucinations | 0 | — | N/A |
| image generation | 0 | — | N/A |
| AI regulation | 0 | — | N/A |
| chatbot safety | 0 | — | N/A |
| deepfakes | 0 | — | N/A |
| AI security | 0 | — | N/A |
| prompt injection | 0 | — | N/A |
| Chinese AI | 0 | — | N/A |
| open-source AI | 0 | — | N/A |
| AI tools | 0 | — | N/A |
| export controls | 0 | — | N/A |
| federal preemption | 0 | — | N/A |
| world models | 0 | — | N/A |
| venture capital | 0 | — | N/A |

*Decay note: All weights at 0. Sub-tags agentic AI, enterprise AI, AI governance, Chinese AI, AI tools, AI security appeared today without confirming feedback. No decay applies (cannot decay below 0 in either direction from 0).*

**Source relevance weights:** All sources at 0. No confirmed feedback to date.

**Feedback log:** No feedback received.

**Processed run IDs:** AI-20260317, AI-20260320, AI-20260321, AI-20260322, AI-20260322-test, AI-20260323-test

---

### Jason Campbell (jcampbell2@lululemon.com) — Active

**Topic weights (default, equal):** Research 25% · Business 25% · Tools 25% · Safety/Ethics 25%

**Sub-tag relevance weights:** Identical to Jason — all 32 sub-tags at 0. No confirmed feedback to date.

*Decay note: Same as Jason — no decay applies from 0.*

**Source relevance weights:** All sources at 0. No confirmed feedback to date.

**Feedback log:** No feedback received.

**Processed run IDs:** AI-20260321, AI-20260322, AI-20260322-test, AI-20260323-test

---

## Run Log

| Run ID | Date | Subscribers | Featured | HM | Notes |
|---|---|---|---|---|---|
| AI-20260317 | 17 Mar 2026 | Jason | Multiple | Multiple | First multi-source run |
| AI-20260320 | 20 Mar 2026 | Jason | 6 | 6 | Full run; TechCrunch, Bloomberg, Townhall |
| AI-20260321 | 21 Mar 2026 | Jason, Jason Campbell | 7 | 1 | Saturday run; first dual-subscriber run |
| AI-20260322 | 22 Mar 2026 | Jason, Jason Campbell | 2 | 7 | Sunday run |
| AI-20260322-test | 22 Mar 2026 | Jason, Jason Campbell | 2 | 1 | Test run. Cursor/Kimi (8.98), Xiaomi MiMo (8.4), Karpathy bottleneck (7.65). |
| AI-20260323-test | 23 Mar 2026 | Jason, Jason Campbell | 1 | 2 | Test run (updated). Articles: Meta CEO Agent/WSJ (8.15 → Featured), Tencent ClawBot/Reuters (7.88 → HM), Palantir FCA/Guardian (7.78 → HM). Target 1F+2HM achieved. New sources added: WSJ, Reuters, The Guardian. |

---

## Tracker Stats

- **Total runs logged:** 6
- **Total sources tracked:** 24
- **Sources with ≥3 appearances (trend-eligible):** CNBC (5), MIT Technology Review (4), The New Stack (4), TechCrunch (11), The Decoder (3), VentureBeat (10)
- **Sources Improving (↑):** 0
- **Sources Declining (↓):** 0
- **Sources Volatile (⚠):** 0
- **Active subscribers:** 2
- **Total sub-tags tracked:** 32 (all weights at 0)
- **Feedback events processed:** 0