# -1-few-ABM-scale-piple-line-framework-using-6Sense
This case study documents how I operationalized **1:few ABM** with **6sense** intent data to prioritize accounts, coordinate plays with Sales, and attribute impact—growing influenced pipeline to **$12M** across APAC and US and lifting **MQL→SQL** conversion from **8% → 24%**.

> **Stack:** 6sense • Salesforce • HubSpot/Marketo • LinkedIn Ads • Google Ads • Tableau/Power BI • Slack/Outreach  
> **Framework:** Identify → Prioritize → Engage → Enable → Convert → Attribute → Expand

---

## 🎯 Outcomes (TL;DR)

- **$12M influenced pipeline** (Tier-2 1:few cluster across APAC & US)
- **MQL→SQL** conversion **+16 pts** (8% → 24%) in two quarters  
  > Benchmarks: enterprise B2B typically sees **10–20%** MQL→SQL; >20% is strong for named-account programs
- **+34% win-rate** on opportunities flagged by ≥35% intent-surge cohorts
- **–27% CPL** by re-allocating spend to in-market accounts

---

## 1) Identify: Build the 1:Few Target Cluster

**Goal:** group 12–20 look-alike accounts per cluster (vertical + problem + tech).

**Inputs**
- 6sense **Fit** (ICP match), **Intent** (topic surges), **Buying Stage**
- Salesforce: ACV, open opps, last activity, whitespace
- Technographics (cloud: AWS/Azure/GCP), installed EHR/CRM, data stack
- Firmographics: region, employee bands, multi-site footprint

**Process**
1. In 6sense, query accounts with:
   - *Fit: A/B*, *Stage: Consideration/Decision*, *Surge ≥ 30%* on topics:
     - `"interoperability"`, `"data modernization"`, `"care coordination"`, `"HIPAA/PHI"`.
2. Cross-check with Salesforce to exclude saturated/no-whitespace accounts.
3. Split into **2× 1:few clusters** by region & problem theme (APAC “Interoperability”; US “Payer Data Modernization”).

**Output:** 32 accounts → trimmed to **18** (two pods of 9 each).

---

## 2) Prioritize: Persona & Buying Group Mapping

- Pull 6sense **Keywords** & **Web Pages Viewed** → infer pain narrative.
- Map buying groups in Salesforce:
  - **Economic:** CFO/VP Ops
  - **Technical:** CIO/CTO, Data/Platform Head
  - **Users/Champions:** Dir Analytics, Clinical Ops, Data Eng
- Create **Persona Cards** (1-page each): pains, proof, talk-tracks, do-donts.

> Tip: Push **daily intent digest** to a shared Slack channel: `#abm-6sense-pod-apac`, including top 10 accounts with an **“action”** suggestion.

---

## 3) Engage: Orchestrated Plays (Channel × Message × Moment)

| Cluster | Play | Asset | Channel | Trigger |
|---|---|---|---|---|
| APAC (Interoperability) | *Value Narrative* | 2-pager “Interoperability ROI in 90 Days” + 3 case tiles | LinkedIn Ads (Matched Audiences), Email, SDR sequences | Stage = Consideration & Surge ≥ 30% |
| APAC | *Problem-Solution* | 6-min product demo + ROI calc | 1:1 AE email, InMail to CIO/Dir Analytics | Persona viewed “integration” content |
| US (Payer Data) | *Benchmark* | Industry benchmark microsite + interactive charts | Retargeting + Nurture + AE follow-ups | ≥2 visits to benchmark/ROI pages |
| US | *Executive Invite* | 45-min virtual roundtable w/ customer speaker | AE/CSM invite + Calendly | ≥3 stakeholders active within 7 days |

**Creative rules**
- Reuse the same **core story**, swap **proof points** & **stats** per cluster.
- 3 ad variants per persona; rotate weekly based on 6sense **Topic** lift.

---

## 4) Enable: Tight Sales–Marketing Operating Rhythm

- **Weekly 30-min pod** (Marketing + AEs + SDRs + SE):
  - Top 10 surging accounts, last 7-day engagement, next plays
- **Shared dashboard** (Power BI/Tableau):
  - **Account score**, **Persona touches**, **Meeting set**, **Opp created**, **Stage velocity**, **Next action owner**
- **SLAs**:
  - SDR touch within **24h** after MQA flag (Marketing Qualified **Account**)
  - AE follow-up within **72h** after multi-persona engagement

---

## 5) Convert: From Signals to Opportunities

**Rules of motion**
- If **≥2 personas** at the same account interact within 7 days **or** 6sense surge ≥35% → **auto-route to SDR** with persona-specific sequence.
- If demo requested **and** MQA within 14 days → **AE + SE** joint call; send ROI calc template before the call.

**What moved the needle**
- **Pre-meeting ROI email** lifted meeting-to-opp conversion by **+21%**.
- **Executive follow-up** within 48h of roundtable: +14% opp creation.

---

## 6) Attribute: Prove Impact with Incrementality

**Why:** last-touch lies. We measured **incremental lift** of ABM vs. non-ABM twins.

**Method**
1. Build a **matched control** (similar fit/region/size but no ABM exposure).
2. Track over 8–12 weeks:
   - **Opp creation rate**, **$ pipeline**, **Stage velocity**, **Win-rate**
3. Model **incremental contribution** (ABM cohort – Control cohort).

**Results**
- **MQL→SQL**: **8% → 24%** (control ~11–13% baseline)
- **Opp creation**: +29% vs. control
- **Win-rate**: +7 pts on ABM-exposed opps
- **CPL**: –27% via spend reallocation to in-market accounts (6sense)

**Attribution stitching**
- **HubSpot/Marketo** UTMs → **Salesforce Campaigns** (Primary Campaign Source + Influence) → **BI model** for multi-touch view  
- Weighted model: 10% first, 40% primary inflection, 30% opp-creation touch, 20% late-stage enablement

---

## 7) Expand: Post-Sale & Reference Flywheel

- Launch **customer proof program**: joint webinar + 2-page story + quote tile
- **Advocacy**: add references to the pod’s microsite
- Feed **wins + learnings** back into 6sense **Keyword** tracking and content roadmap

---
Shivhoysala 2025, all rights reserved, do not duplicate.
hoysala.shiv@gmail.com
## Architecture (Simplified)

