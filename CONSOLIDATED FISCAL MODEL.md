---
title: "New Crossroads — Consolidated Fiscal Model (2025 base)"
version: "2.0"
date: "2026-07-17"
author: "Thunderfish2"
description: "Single-page derived fiscal model. Rebuilt on the real $6T GDP base. Supersedes v1.2 entirely — the fictional $14.5T/$38.94T GDP, the FTT, the 3% resource surcharge, the SWF-as-capital-budget architecture, and the $497B unitary budget are all gone. Contains the five-pot architecture, the who-levies-what table, the rate-band structure, and what the SWF actually does."
supersedes: "v1.2 — every base assumption changed. GDP $14.5T → $6T. The FTT (~$150B) never existed. The '3% resource surcharge' had no derivation and was claimed by two acts. Five acts funded capital from the SWF that the SWF cannot fund. The 'national tier' was never a unitary budget."
---

# New Crossroads — Consolidated Fiscal Model (2025 Base) — v2.0

**Reading note.** A derived model, not asserted numbers. Sections C–J flow from the base assumptions (Section A). Figures are rounded; illustrative, not precise. **Where a figure awaits a decision it is marked [OPEN] rather than estimated.**

**What changed from v1.2, and it is nearly everything.** The 2025 column of v1.2 was fictional — it had been populated by copying 2075 end-state figures, and one error propagated roughly nine times. Real 2025 GDP is **$6T**, not $14.5T; 2075 is **$19T**, not $38.94T. Five independent checks confirm the $6T base (§A note). Everything GDP-derived moved with it. Everything physically anchored — 400 TWh, 50,000 Durahomes, $180,000 per home, 18M students, 112M patients, eight submarines — did not move at all, and is what caught the financial figures.

---

## A. Base Assumptions

| # | Assumption | 2025 | 2075 |
|---|---|---|---|
| A1 | Population | 112M | 130M |
| A2 | Adults (20+) | 94M | ~109M |
| A3 | Youth / students (5–20) | 18M | ~21M |
| A4 | **GDP** | **~$6T** | **~$19T** (2.33% avg, front-loaded reconstruction) |
| A5 | Labour share of GDP | ~55% (~$3.3T of wages) | ~55% |
| A6 | Co-op share of the economy | ~65% (~$3.9T value-added) | ~65% |
| A7 | **Co-op net profit** | **~$400B** (~10.3% margin on ~$3.9T value-added) | scales |
| A8 | Cash (physical BWC) in circulation | ~$720B (12% of GDP) | ~$2.28T |
| A9 | Broad money | ~$2.6T (43% of GDP) | ~$8.2T |
| A10 | Money multiplier | ~2.9× (cash drain binds, not the 10% reserve) | ~2.9× |
| A11 | **Reference rate** | **~3.5%** (~2% real + ~1.5% DLB inflation) | rule's output |

> **The five checks that confirm $6T.** Labour share (55% → $3.3T of wages against a plausible wage distribution); education as a share of GDP; healthcare as a share of GDP (7.5%, against OECD ~9%); the teacher-pay-to-median ratio; and per-capita healthcare ($4,280, against Canada's $6,300). A sixth — energy — was **withdrawn**: at 3.6 MWh/capita New Crossroads is UK-shaped (4.3), not US-shaped (12.7), so energy consumption cannot discriminate between GDP bases. The US is the outlier, not the yardstick.

---

## B. Architecture: five pots, not one budget

**There is no unitary budget, by design.** v1.2's "~$725–750B revenue vs ~$497B spending" described a consolidated national account for a state that deliberately has none. Five pots that do not touch:

| Pot | Source | Governed by |
|---|---|---|
| **1. Sovereign operations** | The federal tax base (§D) | Chambers; 4% operating cap; no debt |
| **2. The SWF** | Contributions + returns (§F) | Automatic rule; 12% cap; **may never fund sovereign operations** |
| **3. The commons waterfall** | Co-op profits (§C) | FCL Act; progressive by co-op size |
| **4. Premiums** | Citizens → healthcare | Healthcare Act; off-budget |
| **5. Municipal & regional** | Own-source (§G) | Own councils; no debt |

Money does not cross between pots except where an act says so, and each crossing is named.

---

## C. Derived Co-op Figures — and the one chain that never rescaled

**Co-op Advantage Principle:** a co-op's effective burden (profit tax + commons) never exceeds an identical corporation's (profit tax + SWF contribution) at any profit level. This is entrenched (Chamber Act §11) and is why **profit taxation is exclusively federal** (§G) — the comparison is between two rates and holds only where one body sets both.

| Profit tier | Commons share of remaining profit |
|---|---|
| < $1M | 5% |
| $1M–$10M | 15% |
| > $10M | ~22% |

### The co-op profit chain — settled

**v1.2 carried co-op net profit at ~$900B, and that figure was never rescaled.** It was derived as 9.5% of a $9.425T co-op revenue line, which was itself 65% of the fictional $14.5T GDP. At the real $6T base the same derivation gives **~$370B**. An independent cross-check from the labour share — co-op value-added $3.9T, capital share 45%, net profit ~25% of gross operating surplus — gives **~$440B**. **Two methods, one answer: ~$400B.**

**And $900B fails a sanity check the rescale makes visible.** It is **15% of GDP in co-op net profit alone**; add corporate profit and net profits approach 20% of GDP, against a real-world benchmark of ~10–12%. Co-ops also *distribute* patronage rather than retain earnings, so their profit share should sit **below** the corporate benchmark, not at double it.

**What it moves:**

| Line | v1.2 (at $900B) | Corrected (at ~$400B) |
|---|---:|---:|
| Co-op profit tax (5%) | | ~$20B |
| Total commons | | ~$48B |
| → Healthcare contribution | | ~$19B |
| → Education contribution | | ~$10B |
| → Charity contribution | | ~$19B |

**What it moved, and why the VAT went to 4%.** Revenue fell ~$25B (co-op tax $45B → $20B) and the education line rose ~$15B (the FCL offset shrank against an unchanged $180B gross voucher). Together those consumed the entire surplus a 3% VAT produced:

| VAT | Revenue | Spending | Surplus |
|---|---:|---:|---:|
| 3.0% | $394B | $395B | **–$1B** ← deficit, constitutionally barred |
| 3.5% | $411B | $395B | +$16B — no margin |
| **4.0%** | **$427B** | **$395B** | **+$32B** ← chosen |

**This is the last un-rescaled figure in the corpus, and it is the largest one left.** It is logged here rather than resolved because it is a decision, not arithmetic: either co-op profit really is ~$400B (and the VAT goes to ~3.5%), or the co-op sector's margin is materially higher than 9.5% (and A6 needs restating), or co-op "revenue" at 65% of GDP is conflating gross revenue with value-added and the ratio needs a different anchor. **The tables below carry the $45B/$125B figures pending that call, and every one of them moves when it lands.**

---

## D. NATIONAL TIER — Revenue (~$427B)

Set in full at Monetary Act §4; collected by Treasury; rates set by the chambers.

| Stream | Rate | ~Annual |
|---|---|---:|
| **Personal income above $100,000** | 20% ($100k–250k) · 30% ($250k–1M) · 40% (>$1M). **0% below $100,000, formal and informal alike** | ~$144B |
| **Federal VAT** | **3%**; the Daily Living Basket is zero-rated | ~$99B |
| **Tariffs** | ~9.8% average | ~$49B |
| **Co-op profit tax** | 5% over $100k on ~$400B of co-op net profit | **~$20B** |
| **Corporate profit tax** | 0 / 10 / 20 / 25% tiered | ~$25B |
| **Resource cut** | 40% of a 12% royalty on ~$306.4B gross (~$14.7B) + profit tax on resource firms (~$8B) | ~$22.7B |
| **National property layer** | 0.75% commercial/industrial | ~$19B |
| **Excise** | 3% fuel/goods | ~$15B |
| **Total** | | **~$427B** |

**What v1.2 counted that does not exist:**

| v1.2 line | v1.2 value | Status |
|---|---:|---|
| Financial transactions tax (0.3% on BWC >$10k) | ~$150B | **Abolished.** Replaced by the fee rail's SWF share. It was ~25% of the stated national revenue. |
| Resource national cut ("3% surcharge → SWF") | ~$85B | **Wrong rate, wrong destination.** The 3% had no derivation; the surcharge was claimed by both Monetary §2.1 (→SWF) and Sovereign §7 (→revenue). It is **sovereign revenue**, at 40% of a 12% royalty. |
| Personal income tax (formal wages only) | ~$115B | **Superseded.** The base is now formal *and* informal above $100,000 — the CED-visibility line. |
| Parks Index | ~$10B | **Not national revenue.** It funds parks directly (§H). |
| SWF investment returns | ~$27B | **Not revenue.** Returns stay in the fund (§F). |
| Infrastructure fee surplus | ~$5–15B | **Not national revenue.** The fee rails are boards' own income (§H). |

---

## E. NATIONAL TIER — Spending (~$400B)

| Line | ~Annual | Operation or transfer? |
|---|---:|---|
| Education vouchers (net of the FCL contribution) | ~$170B | **Transfer** — the family picks the school |
| Sustainability projects | ~$50B | Operation |
| Healthcare bottom-tier subsidy | ~$45B | **Transfer** — the citizen picks the provider |
| Military (sovereign share only; the endowment adds ~$4B) | ~$40B | Operation |
| R&D / Innovation Hubs | ~$30B | Operation |
| **National infrastructure buildout** | **~$20B** | Operation |
| Parks | ~$20B | Operation |
| The four functions — judiciary, auditors, four bureaus | ~$20B | Operation |
| **Total** | **~$400B** | **Operations ~$180B · Transfers ~$220B** |

### The 4% operating cap

**The cap binds operations, not transfers.** 4% of $6T is $240B; operations are **~$180B = 3.0% of GDP** — inside it. Transfers (~$220B) sit outside, and the test is **who chooses the recipient**: citizen → transfer, state → operation. Classification is justiciable and the presumption runs against the sovereign (Sovereign Functions Act §7.2).

> **This is not a hole cut to fit.** *"Operating"* is the word the cap always used; it had simply never been defined, and nothing turned on it while the plan was priced against $38.94T (4% of which was ~$1.6T). An education voucher is not the sovereign operating anything — the state runs no schools. A cap on what passes *through* the sovereign would count the voucher, the most anti-statist instrument in the corpus, as statism.

**Why the cap falls to ~2%.** Not because the Defense Fund matures — the military budget *rises* to $55–65B. **Because GDP triples.** Operations are physically anchored (a judiciary, eight submarines, a rail network), so a state roughly constant in real terms occupies a shrinking share of an economy growing around it. Operations at ~$180B against $19T is ~0.9%.

**What v1.2 got wrong here:** it labelled Education ($175B), Housing ($150B), Military ($40B), R&D ($30B), and "pensions/workforce/comms/other" ($50B) as **"SWF-funded programs"** — ~$445B/year against a $230B corpus. It also had the military *"declining"*, which is dead in four locations (Military Act §9.1: the endowment **supplements**; it does not replace).

---

## F. THE SOVEREIGN WEALTH FUND — what it actually does

**This is the section v1.2 did not have, and its absence is why five acts spent the fund.**

### F.1 What it is

| | 2025 | 2075 |
|---|---:|---:|
| Seed | **~$230B** (3.8% of GDP) | — |
| Cap (12% of GDP) | ~$720B | ~$2.28T |
| **Reaches the cap** | **~2029 (year 4)** | capped thereafter |

### F.2 What it does — three things, and only three

| Function | Mechanism | Scale |
|---|---|---|
| **1. Crisis liquidity** | The RLP→SWF line opens **automatically** at reference + 2% on a §1.8 systemic-freeze trigger. No vote — the trigger is the authorization; the sovereign may not close it while the trigger holds. | as needed |
| **2. Revolving lending** | **Industrial** (Industry Act §6) and **co-op housing construction** (Housing Act §3.4). **Loans revolve; the corpus survives.** | Housing ~$9B → ~$88B; Industry ~$205B cumulative over phase 1 |
| **3. The Defense Fund** | Estate bequests; **outside the SWF and outside the 12% cap**. Principal locked until total war; **returns drawable annually** (~$4B → ~$37B). | ~$100B → ~$920B |

### F.3 What it is NOT — and this is the load-bearing line

**The SWF is not the state's capital budget.** It lends and is repaid. Five acts had it funding one-way capital that would never return:

| Act | Claim | Now |
|---|---:|---|
| Infrastructure — freeway | $210B | General revenue |
| Infrastructure — rail | ~$185B | General revenue |
| Energy — grid hardening | $200B | General revenue |
| Communications — backbone | $15B | General revenue |
| Infrastructure — pipelines, ports, misc | ~$19B | General revenue |
| **Total one-way claims** | **~$629B** | **against a ~$230B corpus** |

**The fund would have been liquidated 2.7× before it ever reached its cap** — and since access fees recover only *maintenance* (§H), none of it would ever have come back. Plus Education's $175B, Sustainability's $50B, Parks' $20B, R&D's $30B, and the Military's $40B, all labelled "SWF" while Sovereign §7.3 already carried them as general revenue.

**Every act reached for the SWF because §7.3 had no infrastructure line to reach for.** A budget with no line for a thing the state is building does not stop the building; it moves the money somewhere nobody counts. The line exists now (~$20B/year), and the VAT went from 2% to 3% to carry it.

### F.4 Contributions — ~$121B/year

| Source | ~Annual |
|---|---:|
| Corporate SWF contribution (5% of profit over $10M) | ~$60B |
| **The 30% SWF share of every sector access-fee rail** — Infrastructure ~$22.4B, Energy ~$4.5B, Communications ~$0.06B | **~$27B** |
| The SWF's 20% share of the BWC network fee rail | ~$1.8B |
| General budget surplus | ~$32B |
| **Total** | **~$121B** |

> **The access-fee rails were missing from Monetary §2.1's total, and they are a quarter of the stream.** It said ~$63B. Infrastructure's ~$22.4B alone is the largest single SWF contributor in the corpus. Counting them, the fund caps in **year 4** rather than year 7.

### F.5 The stabilizers — destination, never rate

| SWF/GDP | Automatic action |
|---|---|
| < 10% | Full contributions |
| 10–12% | Warning zone; public notification |
| **12% (cap)** | **Automatic citizen dividend — 50% of annual excess** |
| 12–14% | **Redirect 25% of contributions to general revenue** |
| 14–16% | Redirect 50% |
| > 16% | Redirect all |

> **The stabilizer cuts where the money lands, never what anyone pays — and this is load-bearing.** The corporate SWF contribution sits on the **corporate side of the Co-op Advantage Principle**. Cut the *rate* and the corporate burden falls below the co-op's: the Principle inverts, automatically, by operation of a stabilizer nobody would think to check against it. So the rate never moves. Corporations pay 5% forever; once capped it flows to general revenue, and §7.4 sends the surplus onward to the citizens.
>
> **The stabilizer and the dividend are the same mechanism.** A capped fund cannot stop collecting without breaking the fairness rule that justified collecting — so it hands the money to the citizens instead.

### F.6 The citizen dividend — ~$135B/year

| Channel | ~Annual |
|---|---:|
| §2.3 — 50% of SWF excess above the cap | ~$14.4B |
| Sovereign §7.4 — surplus the sovereign may not accumulate, including redirected contributions | ~$121B |
| **Total** | **~$135B** |

**~$1,208 per citizen per year. ~$4,830 for a household of four.** Cash, tax-free, no filing, no threshold, no audit. **It is the largest single transfer in the system and the only one that reaches the informal majority**, which files nothing and is not asked to.

---

## G. SUBNATIONAL TIER — Who levies what

The taxing seam is where this corpus's errors kept surfacing — three acts each holding a third of the answer. It is one table now.

| | Federal | Region | Municipal |
|---|---|---|---|
| **Income above $100,000** | Yes — 20/30/40% (~$144B) | Yes — own rate, same base and threshold | **No** |
| **VAT** | Yes — 3%, DLB zero-rated (~$99B) | Yes — harmonized | Yes — harmonized: **one base, one form, collected once** |
| **Co-op profit tax** | Yes (~$20B) | **No** | **No** |
| **Corporate profit tax** | Yes (~$25B) | **No** | **No** |
| **Resource royalty** | 40% of 12% (~$14.7B) | **Owns it** — 60% (~$22.1B) | **No** |
| **Property — commercial/industrial** | 0.75% national layer (~$19B) | Assessment coordination | Cost-of-service |
| **Property — residential land or primary home** | **No** | **No** | **No** |
| **Tariffs, excise** | Yes | **No** | **No** |
| **Debt** | **No** | **No** | **No** |

Two rows carry weight out of proportion to their size:

- **Residential land is untaxable at every level.** Not capped — *untaxable*, by all three governments, entrenched as Chamber Act §11 Floor 2. No level of government holds the instrument.
- **Profit taxation is federal only.** The Co-op Advantage Principle compares two rates. Twenty regions setting their own would not make it unenforced — it would make it **unknowable**, because nobody could say what "an identical corporation's burden" was in any given place. One hand sets both, so the comparison is arithmetic rather than litigation.

**Equalization:** the MMF and RMF equalize within each tier; resource-rich regions are natural net contributors. Conditionality is formula-driven. No subnational debt.

**[OPEN — G1]** Line-by-line subnational budgets are not itemized. The tier is structurally self-funding (royalties + income tax + VAT + fees ≈ regional/municipal needs, with equalization smoothing disparities), but the per-region/per-municipality figures need pinning.

---

## H. Self-Funding Sectors (off-budget)

| Sector | Revenue | Verdict |
|---|---|---|
| **Healthcare** | Premiums ~$428B gross (94M adults at $200/$350/$600 by tier + 18M children at $50) + FCL commons ~$19B + partners ~$1.2B. **Total ~$448B = 7.5% of GDP, ~$4,000/capita.** | Balanced |
| **Parks** | Dark Corridor Fund surplus ~$10.1B + Parks Index ~$10B + general revenue ~$20B + stewardship levy ~$2B + CCIF ~$2.5B | Self-funding |
| **Infrastructure ops** | Access fees at **155% of annual maintenance** | Surplus by design |
| **Credit-union network** | Gross ~$115B, net ~$43B, NIM ~2.9% | Self-funding |

### The access-fee model — one phrase, one meaning

**Capital is general revenue. Fees recover 155% of *annual* maintenance, *annually*.** The 55% margin funds the SWF contribution, the sector's own fund, and the rural subsidy. Revenue splits **50% maintenance / 30% SWF / 10% sector fund / 10% rural**.

> **"155%" used to mean two things, and the ambiguity ran through five acts.** Under the *capital* reading the freeway recovered in **326 years** ($325.5B at a $1.0B/year toll) and the Communications backbone in **125**. The Utilities grid recovered in **21 years** — plausible-looking, which is why it survived while the freeway's did not. **Same wrong model, quieter failure.**
>
> Under the maintenance reading every rail clears, and the implied upkeep lands inside real-world bands: **~$64,500/km/year** for a hardened freeway with elevated sections, **~$81,000/km/year** for a buried EMP-hardened grid, **~$2,400/km/year** for buried fiber. **Freeways have never recovered construction from tolls anywhere.** Roads are a public good; tolls price maintenance and congestion.

---

## I. The Rate Structure — every rate is a band

**The reference rate is ~3.5%** (~2% real + ~1.5% DLB inflation). It is the *centre*, not the rate — and until v2.0 it had **no stated value anywhere**, while 83 cross-references hung off it.

| Instrument | Band | Illustrative |
|---|---|---|
| Savings | **reference − 1%** | ~2.5% |
| GICs, bonds, savings bonds | reference ± 0.5% | ~3–4% |
| Micro-loans | reference + 0.5% | ~4% |
| Service-sector (healthcare, education, parks, infrastructure) | reference + 0.5% to + 1.5% | ~4–5% |
| **Commercial loans (co-op, corporate, informal)** | **reference + 2%** | **~5.5%** |
| RLP backstop | reference + 1% | ~4.5% |
| SWF backstop · special-share dividend | reference + 2% | ~5.5% |
| CCIF lending | reference + 3% to + 3.5% | ~6.5–7% |
| Citizen revolving line | reference + 5% | ~8.5% |

**Net interest margin: ~3%.** Savings at reference − 1% against loans at reference + 2%. The margin comes from the **bands**, not the anchor — the anchor is the same number on both sides.

> **Every lender in the corpus used to be upside-down.** Credit unions paid 5–6% on savings against a 5.5% loan yield — a margin at or below **zero**, made up on fees, which is why fee income looked like 62% of gross and produced the false conclusion that the network was "a payments utility with a lending arm." The CCIF lent at 3.5–4% while paying depositors 5–7%: **negative carry on every advance.** And the Utilities rates *inverted with risk* — a $2B/30-year SMR at 3.5% against a $50k/10-year solar panel at 5%.
>
> **They are all monotonic now, and they all clear.** Micro +1.5% (a stated subsidy), commercial +3.0%, CCIF positive, revolving +6.0%.

---

## J. Endowments & Stocks

| Stock | 2025 | 2075 | Mechanism |
|---|---:|---:|---|
| **Sovereign Wealth Fund** | ~$230B | capped at 12% (~$2.28T) | Contributions + returns; caps ~2029 |
| **Defense Fund** | ~$100B | ~$920B | Estate bequests; **outside the SWF and its cap**; principal locked, returns drawable |
| **Citizens' Metals ETF** | **~$168–209B** | scaled | Citizen investment; **backs shareholders, not the currency** |
| **CCIF** | **~$991B** (~$811B FCL + ~$180B corporate) | scales | Co-op sector's own pool; **uninsured, no sovereign backstop**; prudential rules at FCL §3.8.6 |
| **Credit-union loan book** | **~$1.86T** (31% of GDP) | ~$5.89T | 10× leverage on ~$186B → ~$589B of special-share capital |
| **Deposit base** | **~$1.86T** | ~$5.89T | Equals the loan book — **loans create deposits** |

---

## K. Derive-Don't-Assert Rule

State the base assumptions (§A) once; derive the rest. **Round honestly. Where a figure awaits a decision, mark it [OPEN] rather than estimate it.** Carry the disclaimer: *"Illustrative projections from a 2025 base; the design is in the structure and ratios, not the precise values."*

**And the rule that this revision earned:** *a figure that holds its ratio across fifty years without being made to is a figure that was derived. A figure that produces a plausible-looking ratio against the wrong input is the hardest error there is to find.* The 60,000-agent CLS corps gave $20.1M per loan officer — a perfect-looking number — because it was measured against the equity instead of the book it supports. Every sanity check passed. Only two documents disagreeing found it.

---

## L. Open Items

| # | Item | Status |
|---|---|---|
| **C1** | **The co-op profit chain (A7).** Co-op net profit settled at ~$400B (~10.3% margin on ~$3.9T value-added). Profit tax $20B, commons $48B. **VAT went to 4%.** The Co-op Advantage Principle confirmed it as arithmetic: at $400B/$125B the co-op burden was 36.2% against corporate's 30% — a breach of the entrenched floor. At $400B/$48B it is 17.0%. | **RESOLVED** ✓ |
| **C2** | **Education's gross voucher.** The act states both **$180B** (18M × $10,000 — arithmetic) and **$200B** (Overview). $180B − $25B FCL = **$155B net**, not the $175B in Sovereign §7.3. Three figures, no two consistent. | **OPEN** |
| **G1** | Subnational budgets — itemize regional and municipal spending; confirm the tier self-funds at the line level. | OPEN |
| **H1** | CCIF participation is **2.5%** (1,832 members of ~72,700 eligible; Tier 1 exempt). The §3.8.7 vote tiers fix the *voice* of those in; they do not reach *who is in*. The shelter is why only large co-ops bother. | Logged, by design |
| **H2** | **Co-op resources ($274B) vs the Industry §3 headline ($213.28B)** — a part exceeding its whole. §3.1–3.5 sum to **$306.4B**; the headline was the error. | **RESOLVED** ✓ |
| J1 | SWF sub-fund routing (year-by-year flow). Aggregate solvency holds. | OPEN |
| — | FTT abolished; resource split settled at 60/40 on a 12% royalty → sovereign revenue; 155% means maintenance everywhere; capital is general revenue; all seven sector boards on the Chamber §7.1 template. | **RESOLVED** ✓ |

---

## Solvency Summary

**National tier:** ~$427B revenue against ~$395B spending = **~$32B surplus**, flowing to the SWF until it caps (~2029) and to the citizen dividend thereafter. Operations are ~$180B — **3.0% of GDP, inside the 4% cap**. No debt, no issuance, no SWF draw.

**The SWF** seeds at ~$230B, takes ~$121B/year, caps at 12% of GDP in ~2029, and thereafter pays **~$135B/year (~$1,208/citizen)** in cash to every citizen including the informal majority. It lends and backstops. **It does not spend.**

**Subnational tier** is self-funding — royalties, income tax, VAT, and fees — equalized by the MMF/RMF, with no debt at any level.

**Major services self-fund:** healthcare on premiums (~$448B, 7.5% of GDP), infrastructure on maintenance-recovery fees, the credit-union network on a ~3% net interest margin.

**Structurally solvent at both tiers.** C1 (the last un-rescaled figure) is resolved; the VAT absorbed it at 4%.
