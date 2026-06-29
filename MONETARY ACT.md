---
title: "Crossroads Monetary Reform & Economic Stabilization Act of 2025"
draft: "9.6"
date: "2026-06-28"
author: "Thunderfish2"
repository: "crossroads-monetary-act"
description: "A monetary framework for New Crossroads: a fiat dual-currency system with an explicit issuance anchor, a rule-based Reference Rate Anchor, a two-tier crisis-management framework, an asset-owner sovereign wealth fund, the PPK/CED identity-economy split, informal economy protections, and structural corporate governance."
supersedes: "Draft 9.5. 9.6 syncs to Credit Union Act 5.5: adds §1.5A (Reference Rate Anchor — the flat-and-slow rule that defines the 'reference rate' the Credit Union Act consumes), adds §1.8 (Crisis Management & Automatic Stabilizers), adds a supply-shock override to the §1.5 price condition, replaces the fixed 250-per-region credit-union count with population/deposit chartering, adds place-of-residence to the PPK, and reconciles stale CLS distribution figures. (9.5 itself: national resource line re-split — royalties became regional own-source revenue; this act retains the national cut only.)"
---

# Crossroads Monetary Reform & Economic Stabilization Act of 2025: Draft 9.6

Posted to r/Bulwarkomics
Draft: 9.6 | Date: June 28, 2026
Author: Thunderfish2

**Note on figures.** All amounts are illustrative projections from a 2025 base. The design is in the structure and ratios, not the precise values. Magnitudes are rounded to honest precision and derive from a small set of base assumptions (see the companion Consolidated Fiscal Model).

**Author's note on the PPK/CED architecture.** This act treats the Professional Passport Key (PPK, identity) and Centralized Economic Database (CED, economy) as operational from inception — the founding data architecture of the state, not a later migration. In reality, issuing 112M hardware keys and standing up geo-replicated economic infrastructure would take years; the act assumes this build as complete for the sake of presenting the end-state design coherently. There is no Crossroads Workforce Database (CWD); the PPK/CED split is the system.

---

## Amendment note — Draft 9.6

Draft 9.6 keeps every element of 9.5 and changes only what the sync to Credit Union Act 5.5 requires. Explicit changelog (so nothing is silently dropped):

**New sections (these resolve forward-references in Credit Union Act 5.5).**
- **§1.5A — Reference Rate Anchor (new).** Defines the single, rule-based, flat-and-slow "reference rate" that the Credit Union Act consumes throughout (loan/deposit bands, special-share premium, RLP at reference + 1%, SWF at reference + 2%). Includes the decoupling clause: the interbank/peer-lending rate floats; the published reference rate does not track interbank stress.
- **§1.8 — Crisis Management & Automatic Stabilizers (new).** Tier-1 automatic stabilizers (no vote), Tier-2 time-boxed emergency mode (Wartime-Fee pattern), institutional-only detection telemetry, accelerated jubilee forbearance. Houses the trigger definitions the Credit Union Act §6.8 references.

**Edits to existing sections.**
- **§1.5** — added a standing **supply-shock override** to the price condition: the brake distinguishes demand-driven DLB movement from external/transient supply movement (fuel, imports) and looks through the latter. Always-on and rule-based; §1.8 references it for the crisis-scale case.
- **§1.2** — replaced "5,000 credit unions (250 per region)" with population/deposit chartering and field-of-membership coverage (≥3 catchments per residence; Credit Union Act §1.5); corrected the stale "CLS ~60,000 (3,000/region)" to demand-distributed; noted banking/loan rates are reference-rate-anchored and special shares are uninsured.
- **§1.6** — credit-union share compartment noted as residency-bound (Credit Union Act §1.5).
- **§1.7** — distinguished the low-frequency PMI dashboard from the high-frequency crisis telemetry in §1.8.
- **§5.1** — PPK now carries **place of residence** (for field-of-membership eligibility), since the Credit Union Act relies on the PPK to attest it.
- **§5.3** — Treasury now publishes the **reference rate**.
- **Key Stats** — credit-union count made variable; added reference-rate and crisis-framework rows.
- **Design Philosophy** — added one principle on rule-priced credit and pre-committed crisis response.

**Cleanup (no data changed).**
- Cleaned currency-encoding artifacts and reconstructed garbled tables (§2.3 SWF stabilizers, §3 commons split, §4 tax table, §5.2 oversight grid, Key Stats) — all legible figures preserved exactly.
- Reconciled the §1.1 $10,000 transparency-threshold wording with the layer description and oversight tables (sub-threshold private; above-threshold pseudonymously logged, never by identity).
- **Flagged, not invented:** the §2.1 per-line SWF contribution figures are garbled in the 9.5 source and conflict with the §2.2 seeding figure; left as a marked reconciliation item for the Consolidated Fiscal Model rather than silently re-derived.

---

## Table of Contents

1. Overview
2. Section 1: Monetary System
   - 1.1 Dual Currency System
   - Physical Cash — Layer 1
   - Bulwark Coin (BWC) — Layer 2
   - 1.2 Co-op Credit Union Network
   - 1.3 Transaction Fees & Liquidity Pool
   - 1.4 Daily Living Basket (DLB)
   - 1.5 Base Money Issuance & the BWC Anchor
   - **1.5A Reference Rate Anchor**
   - 1.6 Citizen Wallet Structure
   - 1.7 Personal Market Index (PMI) — Economic Health Dashboard
   - **1.8 Crisis Management & Automatic Stabilizers**
3. Section 1A: Informal Economy Guarantee
4. Section 2: Sovereign Wealth Fund (SWF)
5. Section 3: Co-op Ecosystem Integration
6. Section 4: Tax and Economic Reforms
   - 4.1 Corporate Governance Requirements
7. Section 5: Governance, Data & Oversight (PPK/CED)
8. Section 6: Foreign Investment — CGCI
9. Key Stats (2025–2075)
10. Design Philosophy

---

## Overview

This act creates:

- **A fiat dual currency** — physical cash and digital Bulwark Coin (BWC), the same unit in two forms (1:1), with asymmetric oversight and an Informal Economy Guarantee.
- **BWC as honest fiat** — not redeemable for metal; its value held stable by an explicit issuance anchor (Section 1.5), backed in confidence by the mutual capital of the credit union network, the Deposit Insurance Pool, and the sovereign guarantee of the SWF.
- **A two-layer velocity architecture** — cash for high-frequency daily commerce; BWC for store-of-value, formal-economy, and institutional use.
- **An explicit money supply rule** — Treasury issues base cash to meet citizen cash demand within price stability and never to fund government spending; credit unions create broad BWC by lending, capped by a 10% reserve requirement.
- **A rule-based price of credit** — a flat-and-slow Reference Rate Anchor (Section 1.5A) sets the system reference rate by published rule, since New Crossroads has no bond market, no repo market, and no central-bank policy rate.
- **A two-tier crisis framework** — pre-committed automatic stabilizers plus a time-boxed emergency mode (Section 1.8), so a deliberate system is not a slow-reacting one.
- **The Citizens' Metals ETF** — a citizen-owned investment fund (held through wallets) that accumulates gold and silver. It backs its own shareholders, not the currency.
- **A self-limiting Sovereign Wealth Fund** — ~$2.0T, capped at 12% of GDP, with automatic citizen dividends and contribution cuts above the cap.
- **The PPK/CED architecture** — identity, credentials, voting, and residence in the citizen-held Professional Passport Key; pseudonymized economic data in the Centralized Economic Database; the two never joined except through a warranted Judicial Link Box.
- **Structural corporate governance** — short-term trade tax, quarterly-guidance ban, worker board seats, long-term voting multiplier, and buyback limits, in place of any GDP cap.

Credit unions and CLS manage loan allocation with reference to economic health indicators, not binding sector quotas.

---

## Section 1: Monetary System

### 1.1 Dual Currency System — Two-Layer Velocity Architecture

New Crossroads operates one currency in two complementary layers:

- **Layer 1 — Cash (Velocity Layer):** physical BWC. High-frequency, private, friction-free. Handles daily citizen commerce. No surveillance, no fees, no records. Cash is never entered into the CED.
- **Layer 2 — BWC (Store-of-Value / Formal Layer):** digital BWC. Pseudonymously transparent above $10,000, stable by design. Handles savings, large purchases, institutional transactions, and international trade.

Cash and digital BWC are the same unit at 1:1 parity — cash is simply BWC in physical form. The layers capture the full range of economic activity without forcing any citizen into the formal data layer to buy groceries.

---

### Physical Cash — Layer 1

*Rationale:* Cash is the velocity engine of the economy. It exists to be spent, passed hand to hand, and spent again. The state's goal is not to track it but to ensure there is always enough of it, that it is trusted and beautiful, and that no citizen is penalized for using it. The informal sector — commerce in cash below the Daily Living Basket threshold — is a protected constitutional economic zone.

- **Target per-capita cash balance:** 50 BWC per citizen aged 12+.
- **Automatic floor:** if average per-capita cash falls below 40 BWC for two consecutive quarters, Treasury automatically issues a cash distribution of 10 BWC to every citizen wallet (see Section 1.5).
- **Composition:** polymer substrate with embedded precious-metal flecks at ~5% of face value, standardized and uniform per denomination (so a note can be valued by its metal content if ever required).
- **Design:** holographic security features and regional artistic motifs; ranked among the world's most beautiful currencies.
- **Purpose of the metal flecks** — two functions, neither of them currency backing:
  - A. Security / anti-counterfeiting — real precious metal, polymer substrate, and holographic optics together place counterfeiting beyond non-state actors.
  - B. Catastrophe floor — in the event of a currency collapse, the standardized metal content lets cash continue to circulate as commodity money, re-priced to its metal value. The informal economy keeps a functioning medium of exchange even if digital BWC fails — buying the state time to restructure. Melt value sits far below face at any plausible metal price, so parity holds in normal times and notes are never melted absent a true collapse.
- The flecks are not redeemable on demand and do not back the currency. BWC is fiat (see below).
- **Denominations:** $1, $5, $10, $20, $50, $100 BWC — adjusted biennially to the DLB index (Section 1.4) by Central Council (6/11 vote).
- **Swap Fee (Cash → BWC):** Free. No fee to enter the formal layer.
- **Swap Fee (BWC → Cash):** 1% (~$14.5B/year in 2025, scaling to ~$47B by 2075). Friction is on exit from formal, not entry.
- **Legal Export:** prohibited. Cash may not cross national borders; customs enforcement at all ports and crossings. Violations: seizure and fines up to 10× face value.
- **Cost:** note production ~$500M/year. (The embedded metal is a one-time value carried in the note and recirculated, not an annual expense; only net new issuance consumes new metal.)

---

### Bulwark Coin (BWC) — Layer 2

*Rationale:* BWC is the national currency in digital form — the store of value and formal-economy medium. BWC is fiat. It is not redeemable for metal and is not backed by a metal reserve. Its value is held stable by the issuance anchor (Section 1.5) and supported in confidence by the mutual capital of the credit union network, the Deposit Insurance Pool, and the sovereign guarantee of the SWF.

- **Type:** blockchain-based digital currency; the same unit as cash, at 1:1.
- **Confidence backing (not redemption backing):** the collective mutual capital of the ~5,000 credit unions, the Deposit Insurance Pool, and the SWF guarantee. This is an honest acknowledgment that all money rests on trust; Crossroads puts that trust in plain sight rather than behind a redemption promise it could not universally honor.
- **How BWC is created — two taps, and only two:**
  - A. Treasury base issuance — Treasury prints cash (= base BWC), governed by the anchor in Section 1.5.
  - B. Credit-union lending — credit unions create broad digital BWC by lending (loans create deposits), capped by the 10% reserve requirement (Section 1.2). Broad money ≈ base × ~10.
  - No other channel creates BWC.
- **Transaction Fees:** smoothed tiers — 0% / 1% / 1.5% / 2% — across bands (0% under $100; 1% $100–$10,000; 1.5% $10,001–$100,000; 2% above $100,000); see §1.3.
- **Transparency Threshold:** $10,000. Digital BWC transactions below it carry no transaction-level detail; transactions above it are logged pseudonymously in the CED (transparent to the system, never tied to identity absent a warrant). Cash is never recorded.
- **Features:** real-time wallet status; CME-resilient via hardened grid and EMP-proof vaults.

---

### 1.2 Co-op Credit Union Network

*Rationale:* Credit unions are the backbone — member-owned, locally governed, audited by Regional Boards. Large loans face extreme scrutiny; micro-loans issue with minimal friction. The network is the formal handshake with the informal sector: it lends to citizens whose income is real but cash-based, without requiring them to prove or disclose it beyond self-attestation for micro-loans.

Credit unions operate under the Credit Union Act of 2025 (Draft 5.5), which establishes Regional Liquidity Pools (RLPs), the Deposit Insurance Pool (DIP), voting-linked deposit insurance, field-of-membership residency, professionalized boards, and the reference-rate-anchored rate bands. These are referenced here; full detail is in that act.

- **Money creation & reserve requirement:** credit unions create BWC by lending (loans create deposits). Each must hold 10% of deposits in reserve (in base BWC / cash). This reserve requirement is the cap on broad-money creation (≈10× multiplier on the Treasury base). (This 10% liquidity reserve is distinct from the Citizens' Metals ETF, which is investment, not currency backing.)
- **Structure:** ~5,000 credit unions, **chartered by population/deposits with field-of-membership coverage — catchments drawn so every residence falls within at least 3 credit unions' fields of membership; no fixed per-region count** (Credit Union Act §1.5). ~5,000 is a derived illustrative headline.
- **Loan Allocation:** by creditworthiness and productive use; reported by sector for monitoring; no binding quotas. The 2025 baseline (~65% co-op, 15% corporate, 20% informal) is descriptive, not prescriptive.
- **Micro-loans:** ~$500 each, 4% interest, self-attested income, no verification, 24-hour processing.

**Asymmetric Scrutiny:**

- Below $500,000: streamlined approval, minimal documentation, 48-hour issuance.
- $500,000–$1M: standard review, Regional Board notification.
- $1M–$10M: full audit, CED logging, Regional Board approval (6/11), public disclosure.
- Above $10M: Central Council review (6/11), SAP arbitration if disputed, published in the annual transparency report.

- **Banking Suite:** checking, savings (~5–6%), mutual funds, GICs, bonds, savings bonds, retirement (~6–8%), reachable through the wallet (Section 1.6). **All deposit and loan rates are set within system bands around the reference rate (§1.5A).**
- **Shares:** base shares (up to 1,000 per citizen, ~4–8% dividends); **special shares (uninsured member capital — see Credit Union Act §3.2).**
- **Crossroads Loan Service (CLS):** ~60,000 officers, **demand-distributed (not a flat per-region quota; ~12 per credit union on average, more where lending volume is high — Credit Union Act §5.1)**, administering loans, student ventures, bankruptcy recovery, and informal-sector engagement, with discretion tiered by loan size.

---

### 1.3 Transaction Fees & Liquidity Pool

*Rationale:* fees encourage cash for daily use and BWC for larger transactions, with progressive rates on large transfers to prevent elite avoidance. The smoothed tiers (0% / 1% / 1.5% / 2%) remove the old cliff at $10,000. Wartime fees raise emergency funds without burdening ordinary citizens (cash exempt).

- **BWC Fees:** as above (Central Council may adjust bands biennially, 6/11).
- **Cash Swap:** Cash→BWC free; BWC→Cash 1%.
- **Wartime Fee:** 10% on BWC transactions above $10,000 (5-year cap, 7/11 renewal); cash and cash-to-BWC swaps exempt entirely. (The Wartime-Fee pattern — high-quorum, hard sunset, forced re-authorization — is the model for the Tier-2 emergency mode, §1.8.)
- **National Liquidity Pool:** 0.5% fee (1% if liquidity tight); supports rural families and projects. Distinct from the Regional Liquidity Pools (Credit Union Act): RLPs are the first line of defense, the national pool handles systemic shocks.
- **Vaults:** EMP-proof BWC snapshot vaults for CME reboot.

---

### 1.4 Daily Living Basket (DLB) — Informal Threshold & Price Anchor

*Rationale:* the threshold below which cash transactions are protected informal commerce must track real purchasing power, not nominal values. The DLB also serves as the price-stability reference for base-money issuance (Section 1.5).

- **Definition:** a fixed basket representing one week of ordinary household commerce — groceries (2 persons, 7 days), one restaurant meal, one tank of fuel, one week of transit, one standard utility payment.
- **Base Value (2025):** $100 BWC.
- **Adjustment:** recalculated annually by Treasury statisticians; published the first week of January. Automatically updates the cash-transaction privacy threshold, the BWC 0% fee band, and the issuance price check (Section 1.5).
- **Governance:** methodology reviewed every 5 years (Central Council, 6/11); public methodology; basket changes require Regional Board majority (11/20).

> **Note (supply components):** the basket deliberately includes volatile externally-priced items (fuel, some groceries). Section 1.5's price brake reads through transient supply-driven movement in these so that an external price spike does not misfire the issuance brake — see the supply-shock override in §1.5.

---

### 1.5 Base Money Issuance & the BWC Anchor

*Rationale:* BWC is fiat, so nothing physical disciplines its value — the discipline must be an explicit, transparent rule. This section is the anchor that keeps BWC stable. Treasury does not decide how much to print; it follows two published figures.

**The issuance rule — both conditions bind:**

1. **Demand condition (the floor).** Treasury issues base cash to keep per-capita cash adequate: 50 BWC target, automatic 10 BWC top-up below the 40 BWC floor, indexed to population and the DLB. This keeps the velocity layer stocked.
2. **Price condition (the brake).** Issuance is capped by DLB price stability. If the DLB rises faster than a target band (1–2%/year), Treasury holds or reduces base issuance even when per-capita cash is at target. If the DLB is flat or falling, Treasury may issue freely to meet demand.

In plain terms: print to meet cash demand, but never so much that the basket inflates. The DLB is both the indexing mechanism and the speed limit; BWC's value is pinned to a steady basket.

**Supply-shock override (standing rule).** The price brake distinguishes **demand-driven** DLB movement (the basket genuinely inflating across components) from **supply-driven, external, transient** movement concentrated in volatile items (fuel, imported goods). It **looks through** the latter: a spike confined to externally-priced components does not trip the brake, so the anchor does not choke issuance into a supply shock or a recession. This discrimination is always on and rule-based — it does not require a declaration. For the crisis-scale case (a major external shock landing during a declared emergency), §1.8 references this same mechanism and may widen the look-through or pair it with the Tier-1 liquidity line. *(Division of labor: the everyday supply/demand discrimination lives here, in §1.5; the declared-emergency escalation lives in §1.8. Rule-based and continuous → §1.5; declared and time-boxed → §1.8.)*

**The deficit-financing bar (constitutional).** Base-money issuance may never fund government spending. Government is funded by taxes, fees, and the SWF — never by the printer. This single prohibition is what makes the anchor credible. Issuance that meets cash demand within price stability is permitted; issuance to cover a budget shortfall is prohibited.

**The two taps.** Total BWC = Treasury base issuance (this section) + credit-union lending (Section 1.2, capped by the 10% reserve). These are the only two channels that create BWC. No other body may issue it.

---

### 1.5A Reference Rate Anchor

*Rationale:* New Crossroads issues no sovereign bonds, runs no repo market, and has no central bank setting a policy rate. There is therefore no market to *discover* the price of credit — it must be **administered by an explicit, published rule**, in the same spirit as the §1.5 quantity anchor. Crucially, the interest rate here is relieved of its usual macro job: money-supply and inflation control are already done by the §1.5 quantity anchor, the 10% reserve, and CLS credit judgment. Freed from demand management, the reference rate can be set for **fairness, predictability, and solvency** rather than to clear a market. This section defines the single "reference rate" the Credit Union Act consumes throughout.

**Definition.** The **reference rate** is one published system rate set by rule off the DLB/PPI — illustratively, a target real return plus trailing DLB inflation, held within a narrow band. Treasury publishes it (quarterly) alongside the DLB and the PPI.

**Flat-and-slow mandate.** The reference rate changes only **gradually** and only in response to **sustained** DLB/PPI drift — never to short-term noise. Stability is chosen over responsiveness deliberately, matching the monthly-not-daily temperament of the PPI (Credit Union Act §1.4). A flat, slow rate keeps every downstream rate (savings, loans, special-share dividends, backstop pricing) steady.

**Decoupling clause (load-bearing).** The **intra-credit-union / interbank (peer-lending) rate floats freely** — it is the short-end liquidity price and the fastest crisis-detection signal (a spike *is* a freeze; see §1.8). The **published reference rate does not track interbank stress.** In a freeze, interbank rates may blow out, but the reference rate — and therefore the RLP backstop at reference + 1% and the SWF backstop at reference + 2% (Credit Union Act §6.4) — stays stable, keeping the lender of last resort cheap precisely when it is needed. The moving part detects the crisis; the stable part anchors the system through it.

**What "anchored to the reference rate" means.** A rate "anchored to the reference rate" is reset to its band around the reference rate when the reference rate is republished, and is fixed between republications. This is the precise meaning of the Credit Union Act's "reference-rate-anchored" loan and deposit rates.

**Band structure & federalism.**
- **National:** Treasury publishes the reference rate by rule (this section).
- **Regional:** the interbank/RLP reserves rate floats around it as the short-end liquidity price.
- **Local:** credit-union boards set their own savings and loan rates **within system bands** around the reference rate (Credit Union Act §6.1). Competition within the field-of-membership overlap does the fine-tuning.
- **Band widths** (not the rule, not the level) may be reviewed biennially by Central Council (6/11), like the fee bands. There is no discretionary level-setting — the level is the rule's output.

**Consumers of the reference rate (wiring).** Loan and deposit bands (Credit Union Act §4); the special-share dividend premium, reference + ~1.5–2% after the 7/6/5 step-down (Credit Union Act §3.2); RLP loans at reference + 1% and SWF backstop at reference + 2% (Credit Union Act §6.4); DIP short-term instruments (Credit Union Act §6.5).

**Relationship to §1.5.** §1.5 governs the **quantity** of base money — the macro lever. §1.5A sets the **price** of credit — administrative and distributive. They are separate jobs with separate instruments; neither substitutes for the other. Because demand management is handled by §1.5, the reference rate is explicitly **not** the crisis lever (see §1.8): a crisis flows through the automatic liquidity (quantity) channel, not through a rate move there is no bond market to transmit.

---

### 1.6 Citizen Wallet Structure

A citizen's wallet is one interface with separate, never-blended compartments:

1. **Spendable BWC** — fiat money for daily use, transfers, business, and government payment; 1:1 swappable with cash (free in, 1% out). Reports to the CED pseudonymously; identity authentication comes from the PPK, never from the money layer.
2. **Citizens' Metals ETF position** — an optional investment in the national gold/silver fund. Earns returns for the holder; grows the metals reserve as a byproduct. This is savings, not currency — the metal backs ETF shareholders, not BWC. National vehicle, not residency-bound.
3. **Credit-union shares** — membership/ownership stake and dividends; **held within the member's field of membership** (Credit Union Act §1.5; base and special shares are residency-locked, with grandfathering on relocation).
4. **Banking gateway** — access to savings, GICs, retirement, loans, and micro-loans at reference-rate-anchored rates (§1.5A).

The spendable-BWC compartment has nothing to do with metal; the ETF compartment is where metal lives. Identity and money are architecturally separate (Section 5).

---

### 1.7 Personal Market Index (PMI) — Economic Health Dashboard

*Rationale:* the PMI tracks economic health in real time, enabling early intervention if the co-op sector shows sustained weakness — as an early-warning system, not a binding target. The informal-sector component is estimated by statistical sampling, never by transaction surveillance. The dashboard is transparent and visible on every citizen's wallet.

**Dashboard metrics:**

- Co-op GDP share (annual tax/loan data) — informational only, not a trigger
- Corporate GDP share (annual tax data)
- Informal GDP share (estimated via quarterly household sampling, not CED tracking)
- BWC velocity (credit-union transaction data, pseudonymized)
- New FCL formation rate
- FCL maturation success (5-year cohorts)
- Informal → formal transition rate (micro-loan originations)
- Rent, fuel, and staple prices, jobs, and digital adoption — tracked against the BWC Purchasing Power Index (Credit Union Act §1.4), not a backing ratio

**Soft trigger:** if co-op GDP falls below 45% for three consecutive years, the Central Council commissions a Co-op Sector Review (findings within 180 days). The Review may recommend temporary incentives — micro-loan subsidies, formation grants, or CLS expansion — which the National Assembly may adopt, modify, or reject by simple majority.

No automatic policy response is triggered by GDP shares alone. There are no automatic fee hikes. The informal sector has no GDP cap — growth beyond any baseline is welcome and requires no response. The PMI informs judgment; it does not bind it.

> **Frequency note:** the PMI is a deliberately **low-frequency** early-warning dashboard (annual/quarterly), suited to slow structural drift. **High-frequency systemic-stress detection** — the signals that fire crisis triggers in hours — is separate and lives in §1.8. The two are not the same instrument.

*(Fiat note: prior drafts tied PMI price signals to a "BWC reserve ratio" and spoke of "BWC appreciation." Under the fiat conversion, price signals are read from the Purchasing Power Index and the DLB; there is no appreciation target and no backing ratio.)*

---

### 1.8 Crisis Management & Automatic Stabilizers

*Rationale:* a deliberate, stable system must not be a slow-**reacting** one. The way a stable system handles a fast crisis is to do its deliberating **in advance** — pre-committing the crisis response as automatic, threshold-triggered, sunset-bounded actions, authorized democratically in calm times — so execution is instant and still rule-bound. This is the same DNA as the SWF automatic stabilizers (§2.3), the automatic cash floor (§1.1/§1.5), and the Wartime Fee (§1.3). This section adds the framework; the credit-union-side mechanics live in Credit Union Act §6.8.

**Strategic posture.** The system trades fast-crisis agility for slow-crisis immunity, and the trade is deliberate:
- **Sovereign-debt crisis:** near-immune by construction. New Crossroads issues no sovereign debt (nothing to roll over), pegs BWC to nothing (no peg to defend, no reserves to burn), and free-floats its external value (the float is itself a shock absorber). Foreign capital is structurally illiquid (non-voting CGCI units, 50-year leases, cash-export ban), so it cannot stampede. Exposure is real-economy only (trade/commodity shocks).
- **GFC-2.0-style event:** this is the real exposure. The interbank market here is peer-credit-union lending plus the RLP, and it can freeze the way 2008 did (credit unions hoarding reserves); the asset leg hits the ETF/CGCI; the credit-crunch leg hits co-ops needing rollover. Crisis design concentrates here.

**Detection telemetry — institutional plumbing only.** Systemic-stress triggers are read entirely from the institutional-transparency layer, **never from citizen activity**: the inter-credit-union (peer-lending) rate, RLP draw velocity, reserve dispersion across credit unions, BWC→cash swap spikes, CUSM price pressure toward the 90% floor, DIP/RLP utilization, and ETF/CGCI drawdowns. These streams are inherently real-time and sit entirely on the elite/institutional side of the asymmetry. No citizen surveillance is used or permitted to detect a crisis.

**Trigger definitions (illustrative thresholds).** A *systemic-freeze trigger* is declared automatically when objective institutional signals breach pre-set bands — e.g., the interbank rate exceeds the reference rate by more than a set spread for several consecutive days; or RLP draws exceed a set share of the pool within a short window; or the aggregate reserve ratio breaches the 10% floor system-wide. (Precise bands set by rule and published; calibrated in the Consolidated Fiscal Model.)

**Tier 1 — automatic stabilizers (no vote, hours).** On a systemic-freeze trigger:
- The **RLP→SWF liquidity line opens automatically** — the 5/20 Regional Board + Central Council 6/11 certification of Credit Union Act §6.4 is **pre-cleared by the trigger itself**.
- **Penalty price held stable:** RLP at reference + 1%, SWF at reference + 2%. Per the §1.5A decoupling clause, these do **not** track the spiking interbank rate — the backstop stays cheap while the freeze rages. Quantity flows freely; price stays put. This is Bagehot done rules-style: lend freely, against good collateral, at a stable penalty rate.
- **Supply-shock escalation** references §1.5's standing override; in a declared crisis the look-through may widen or pair with the liquidity line.
- **Accelerated jubilee forbearance:** the surgical-jubilee logic (§2.2; Credit Union Act §5.4) may be fast-tracked by CLS for **solvent** co-ops facing a pure rollover crunch, preventing a liquidity event from manufacturing insolvencies. Eligibility standards are unchanged; only the timeline is accelerated.

**Tier 2 — emergency discretion (time-boxed).** For a genuinely novel systemic event no rule foresaw, a high-quorum **emergency mode** may be switched on (Central Council 8/11 + 5/20 Regional Boards), carrying **hard sunsets and forced re-authorization on the Wartime-Fee pattern** (§1.3). Discretion is bounded in time, not eliminated. Emergency mode may temporarily widen Tier-1 parameters, activate the Wartime Fee, or authorize extraordinary SWF deployment, each with its own sunset.

**What the reference rate does *not* do.** The reference rate is **not** the crisis lever. A crisis is met through the automatic **quantity** channel (liquidity provision), not a rate cut — there is no bond market to transmit a rate move, and the §1.5A decoupling deliberately keeps the reference rate stable through the panic. The moving interbank rate detects; the stable reference rate anchors; the automatic liquidity line responds.

---

## Section 1A: Informal Economy Guarantee

An affirmative constitutional protection for cash-based commerce — a binding prohibition on state surveillance of ordinary economic life.

### 1A.1 Declaration

1. All citizen-to-citizen commerce in physical cash at or below the current DLB threshold is protected informal economic activity.
2. Citizens have an absolute right to privacy in such commerce that no agency, credit union, or FCL may abridge or condition service upon.
3. The state has no legitimate interest in tracking informal transactions below the DLB threshold and prohibits the construction of any system designed to do so — including, explicitly, any system that would join PPK identity with CED economic data outside the warranted Judicial Link Box (Section 5).

### 1A.2 Specific Prohibitions

Unlawful for any government body, credit union, CLS officer, FCL, or corporation:

- Requiring disclosure of cash transaction history as a condition of any loan, membership, service, or benefit.
- Conditioning micro-loan approval on proof of formal income where cash income is self-attested.
- Using cash holdings or patterns as evidence of tax evasion absent independent corroboration.
- Constructing databases or surveillance infrastructure to track cash below the DLB threshold, or to merge identity with economic data outside the Link Box.
- Refusing service to citizens who decline to disclose cash income.

### 1A.3 Credit Union Non-Discrimination

Credit unions may not deny membership, downgrade tier, or withhold dividends based on a member's cash-to-BWC ratio; may not require BWC transaction history for micro-loans; and may not report cash withdrawal patterns absent a court order.

### 1A.4 Informal Sector Access

Cash-income citizens receive automatic access to micro-loans (self-attested, 24-hour), a base share on first repayment, and a basic wallet — on their terms, not as a pull into surveillance.

### 1A.5 Sampling-Only Measurement

Informal-sector GDP is measured only by anonymized voluntary surveys, DLB price extrapolation, and aggregate cash circulation data — never by surveillance. The figure is an estimate; the legislation accepts that uncertainty as the appropriate price of privacy.

---

## Section 2: Sovereign Wealth Fund (SWF)

### 2.1 Funding Mechanisms

*Rationale:* the SWF is the collective wealth of 112M citizens — sovereign savings, distinct from general revenue. It is self-limiting: it never exceeds 12% of GDP, and automatic stabilizers cut contributions as it approaches the cap.

- **Initial:** ~$1.5–2.0T (capped at 12% of GDP).
- **Contributions are carved out of general revenue (not additional),** to avoid double-counting:
  - Financial transactions tax (0.3% on BWC transactions above the $10,000 band)
  - Corporate SWF contribution (5% of profit over the threshold)
  - Resource surcharge (3% on minerals/energy): ~$50B/year
  - Other dedicated fees/tariffs: ~$103B/year
  - Plus the general budget surplus.

  > *Reconciliation flag:* the per-line contribution yields and the 2025 contribution total are garbled in the 9.5 source and do not reconcile against the §2.2 seeding figure of ~$362.5B/year. Preserved structurally and flagged for the Consolidated Fiscal Model — **not** silently re-derived here.

- **No co-op recharge — eliminated.** (The former "2% of GDP" co-op recharge does not exist; co-ops contribute to the commons through the FCL profit-sharing waterfall instead — see Section 3.)
- **Sub-funds (illustrative):** Charity, Rainy-Day, Emergency, Defense, Healthcare-subsidy, Education, Workforce, Pension, Research/Tech, Communications, Forced Savings, Housing, Special Mining. Scrutiny tiered by size; large allocations fully transparent.

**SWF as ultimate backstop:** the SWF reinsures Regional DIPs and acts as lender of last resort to exhausted RLPs only after 5 Regional Boards jointly certify an emergency (5/20) — except under an automatic systemic-freeze trigger, where certification is pre-cleared (§1.8) — preserving the anti-bailout ethos with systemic resilience.

### 2.2 Debt Jubilee, Freedom Shares & the Crossroads Loan Service

*Rationale:* unpayable, accumulating debt destroyed the previous system. The jubilee is the release valve that prevents debt from compounding into permanent servitude — but it is designed to relieve misfortune without rewarding mismanagement. It works through three connected instruments: the periodic jubilee itself, Freedom Shares, and the judgment of the Crossroads Loan Service.

**The Jubilee (the relief).**
- **2025 founding reset:** a one-time wipe of legacy debt and a 5-year bankruptcy reset, clearing the wreckage of the prior system.
- **The 25-year cycle:** every 25 years, up to 50% of qualifying co-op debt may be forgiven. This is not a blanket cancellation — it is surgical (see CLS below). Forgiveness is granted case by case, to co-ops whose distress arose from circumstances beyond their control. *(Under a declared crisis, forbearance may be accelerated for solvent co-ops in a rollover crunch — §1.8.)*

**Freedom Shares (turning forgiven debt into ownership).**

When a co-op's debt is forgiven, the forgiven amount is not simply written off as a loss. It is converted into Freedom Shares — equity in the recapitalized co-op. This is what makes the jubilee sustainable rather than merely charitable:

- **What they are:** Freedom Shares are patient equity stakes created when forgiven debt is converted into ownership. The debt disappears from the co-op's books; in its place stands equity.
- **Who holds them:** Freedom Shares are split between (a) the credit union that absorbed the forgiveness — compensating it with an equity claim instead of a defaulted loan, so the lender shares in the co-op's recovery rather than simply eating a loss — and (b) the co-op's worker-members, restoring their ownership stake in the enterprise they kept alive.
- **Why "Freedom":** they represent freedom from the debt that would have sunk the co-op, and the freedom to keep operating as a worker-owned enterprise rather than being liquidated.
- **How they resolve:** as the co-op stabilizes, the credit union exits its Freedom Shares by either selling them back to the co-op (member buyback, returning it to full member ownership) or selling them into the co-op index (CGCI / CCIF) — whichever the co-op's condition supports. The index path matters: a still-fragile co-op may not be able to afford a buyback, so selling into the index gives the credit union a liquid, always-available exit that recovers its capital on its own timeline without forcing a premature buyback. Worker-member Freedom Shares may remain as ownership. Because the credit union's shares are worth more at a clean exit, the lender gains a direct incentive to nurse the co-op back to health — its interest aligns with the co-op's recovery.
- **Where the equity ends up:** debt → Freedom Share equity → held by the credit union during recovery → sold back to the co-op or into the index once stabilized → residual ownership distributed broadly through the co-op index. The relief flows all the way through to distributed ownership, which is the system's ethos.
- **Democratic control:** Freedom Share issuance requires a Regional Board vote (11/20), ensuring the conversion is publicly authorized, not granted in the dark.

This is the difference between a jubilee and a bailout: a bailout writes off the loss; a Freedom Share converts the loss into shared, recoverable ownership.

**The Crossroads Loan Service (the judgment).**

The CLS — the corps of embedded credit-union loan officers established in detail in the Credit Union Act §5 — administers the surgical jubilee. Because CLS agents are embedded in the credit unions and know each co-op's actual history, they are the body positioned to judge why a co-op is in distress:

- **Eligible for forgiveness:** co-ops felled by circumstances beyond their control — bad timing, external shock, market or environmental disruption, misfortune despite sound management.
- **Not eligible:** co-ops felled by mismanagement, incompetence, or negligence. Bad management is not rewarded with relief.
- **Process & appeal:** CLS makes the determination case by case; a co-op denied may appeal to its Regional Board (11/20), and a grant made over objection may be reviewed by the same.

The CLS is also, by the same logic, a brake on the debt that makes jubilees necessary: because every loan its officers write creates money (Credit Union Act §1.1, §5.2), prudent CLS underwriting restrains both money creation and the build-up of unpayable debt in the first place. The corps that grants the jubilee is the same corps whose discipline limits how often one is needed.

**Funding & growth drivers.**
- **SWF seeding:** ~$362.5B/year from the tax and contribution structure (no co-op recharge — eliminated; co-ops contribute to the commons through the FCL profit-sharing waterfall instead, Section 3).
- **Growth drivers:** SWF investment returns and the housing program (see §2.5).

### 2.3 Automatic SWF Stabilizers

| SWF/GDP ratio | Automatic action |
|---|---|
| < 10% | Normal operations; full contributions |
| 10–12% | Warning zone; public notification |
| 12% (cap) | Automatic citizen dividend — 50% of annual excess above 12%, paid equally (50% cash, 50% BWC), tax-free |
| 12–14% | Cut all SWF contribution rates 25% |
| 14–16% | Cut 50% |
| > 16% | Suspend all contributions until ratio falls below 12% |

### 2.4 Contribution Phase-Out

The SWF weans off contributions over time — build (2025–2050), stabilize (2050–2075), mature (2075+, returns only). At maturity it acts solely as a buffer, growing in bad years and distributing in good. It never balloons.

### 2.5 Defense Fund (Separate Endowment)

The Defense Fund is a distinct sovereign endowment, not part of the SWF and not under the 12% cap, built over 50 years from citizen estate bequests plus investment returns, accumulating to ~$920B by 2075. At maturity its returns (~$37B/year) approximately cover the military's recurring operating budget (~$40B), so the Defense SWF allocation **declines from ~$40B (2025) toward ~$0 by ~2070** as the endowment matures. *(The military's recurring operating budget is ~$40B/year; one-time base buildout is funded separately and is not a recurring figure.)*

---

## Section 3: Co-op Ecosystem Integration

*Rationale:* FCLs are the engine of the co-op economy. Their surplus funds the commons through a progressive profit-sharing waterfall — not a tax, but a structural contribution that flows partly back to the co-ops' own members.

- **Profit-sharing waterfall (progressive).** After expenses, the 5% profit tax, patronage, capital investment, and CCIF, the commons share of remaining profit scales by co-op size, bound by the Co-op Advantage Principle:

> **Co-op Advantage Principle:** a co-op's effective burden (tax + commons) shall never exceed an identical-size corporation's effective burden (tax + SWF) at any profit level.

| Profit tier | Commons share of remaining profit |
|---|---|
| $100k–$1M | 5% |
| $1M–$10M | 15% |
| > $10M | ~22% |

The commons share splits Healthcare : Education : Charity in a 2:1:2 ratio. **Total commons funding ≈ $125B** (Healthcare ~$50B : Education ~$25B : Charity ~$50B per the 2:1:2 split), concentrated in large co-ops while protecting small ones.

- **Capital Investment Fund (CCIF):** funds co-op startups and SWF projects; ~7.5% returns; allocated by the Alliance Network (FCL-led, Regional Board confirmation).
- **Asymmetric Scrutiny:** simplified reporting for small FCLs; full CED disclosure above $100M.

---

## Section 4: Tax and Economic Reforms

*Rationale:* progressive but simple. Informal earners under $100,000 pay no tax and have no filing obligation. Co-ops pay a low profit tax; corporations face higher tiered rates. All tax data is transparent to the individual (via PPK/CED) but not publicly disclosed.

- SWF contributions are carved out of these figures (Section 2.1), not added on top — no double-counting.

| Tax Type | Rate / Threshold | ~Yield/year | Scrutiny |
|---|---|---|---|
| Personal income (formal wages only) | 5% flat; 0% under $20k; informal exempt | ~$115B | Auto-withholding; no filing for most |
| Co-op profit tax | 5% over $100k; no SWF recharge | ~$45B | Full CED disclosure for co-ops >$1M |
| Corporate profit tax | 0% / 10% / 20% / 25% tiered | ~$25B | Full CED disclosure |
| Informal business tax | 0% under $100k; 5% $100k–$1M (self-attested) | ~$10B | Self-attested; no audits below $100k |
| Excise | 3% on fuel/goods | ~$15B | Point of sale; no individual tracking |
| Property | 0.75% on commercial/industrial | ~$19B | Public record |
| Tariffs | ~9.8% avg on imports | ~$49B | Collected at port |
| Resources (national cut) | 3% surcharge + profit tax on resource firms | ~$80–100B | Royalties/stumpage are regional own-source revenue (Municipal & Regional Funding Act §2.5); this line is the national portion only. Full CED tracking for extractive industries |

- **Asymmetric Scrutiny:** government allocations above $1M administered automatically with sampling audits.

### 4.1 Corporate Governance Requirements

*Rationale:* in place of a GDP cap, corporations are subject to structural limits aligning behavior with long-term stakeholder value.

1. **Short-Term Trade Tax:** 0.5% on sales of corporate shares held under 365 days; collected at point of sale regardless of trader location.
2. **Quarterly Guidance Ban:** annual guidance only. Violations: fines up to $10M, then trading suspension.
3. **Worker Board Representation:** worker-elected seats by headcount — 1 seat (50–500), 2 (501–2,000), 3 or 30% (2,001–10,000), 4 or 33% (10,000+); one worker, one vote; full voting rights including on compensation, buybacks, and capital allocation.
4. **Long-Term Voting Multiplier:** 2 votes/share at 5+ years, 3 at 10+ (cap); shares sold within 90 days of a vote forfeit voting rights for that meeting; no separate share classes.
5. **Stock Buyback Limits:** permitted only if the prior-year capex target was met, post-buyback equity ≥150% of long-term debt, annual buybacks ≤50% of net income, and worker board members approve by majority.

**Enforcement:** a Corporate Governance Enforcement Unit (~$150M/year) conducts random audits and may levy fines up to 5% of revenue for willful violations. Appeals to the Special Arbiter Panel (SAP).

---

## Section 5: Governance, Data & Oversight (PPK/CED)

*Rationale:* oversight is layered and redundant — large actors face full transparency, ordinary citizens almost none. The founding principle is architectural: the state surveils the economy, not the citizen. This is enforced by physically separating identity from economic data.

### 5.1 The PPK/CED Split (Foundational)

- **Professional Passport Key (PPK):** a citizen-held, air-gapped hardware key holding identity, credentials, professional licensing, voting eligibility, education, and **place of residence (for field-of-membership eligibility, Credit Union Act §1.5)** — and no economic data. Verification is by zero-knowledge proof (prove eligibility without revealing identity). Residence is self-attested and surfaced only as a qualified/not-qualified check, never as tracked location.
- **Centralized Economic Database (CED):** a pseudonymized economic ledger holding BWC balances, tax, supply-chain value flows, and SWF calculations — and no identity, credentials, or voting data. Every record carries only a salted, quarterly-rotated hash of the citizen's PPK public key.
- **Judicial Link Box:** the only bridge between the two — a hardware module that maps a CED hash to a real identity solely under warrant (probable cause; signed by a Regional Board judge; two-region approval; publicly logged; citizen notified within 90 days). Annual abuse audit by the Citizen Oversight Board.
- Cash is never entered into the CED. The informal cash layer sits entirely outside both systems.

### 5.2 Asymmetric Oversight Architecture

| Level | CED treatment |
|---|---|
| Informal (DLB and below, cash) | Never recorded. Constitutionally protected. Sampling only. |
| Citizen (under $10k/year BWC) | Pseudonymized; no transaction-level detail. |
| Middle ($10k–$100k/year) | Pseudonymized aggregates; annual summary. |
| Elite (above $1M assets) | Full pseudonymized detail; quarterly audits; holdings above $10M publicly disclosed. |
| Institutional (FCLs, corporations, credit unions >$10M revenue) | Full transparency; public annual reports. |

### 5.3 Bodies & Treasury

- **Bodies:** 11-member Central Council, 20 Regional Boards, National Assembly, judiciary.
- **Treasury:** administers BWC issuance under the Section 1.5 anchor, the **reference rate (Section 1.5A)**, the SWF, and the Citizens' Metals ETF. Publishes the annual DLB, cash-adequacy figures, base-issuance reports, and **the reference rate**. Treasury does not publish a backing ratio — BWC is fiat; there is no per-coin metal backing.
- **Data cost:** CED + PPK ≈ ~$450M/year (CED ~$250M/year), a net saving versus prior centralized data systems.

---

## Section 6: Foreign Investment — Crossroads Global Co-op Index (CGCI)

*Rationale:* foreign capital is welcome but strictly non-voting and tracked at the highest scrutiny. Foreign nationals may not hold physical cash (which cannot leave the country in any case) and must use BWC or CGCI units.

- **Structure:** Treasury-managed, SWF-seeded. FCLs pool a share of profits into the index.
- **Units:** non-voting, ~5% return; profits allocated to CCIF, the Rainy-Day Fund, and the SWF.
- **Parks foreign access (cross-reference Parks Act):** cottages (hard-capped, 50-year leases) and timeshares (scaling with parkweb carrying capacity) are auctioned, not fixed-fee — capturing the scarcity value of residence in a dark-sky reserve, funding the commons entirely from foreign capital.
- **Scrutiny:** foreign investment above $100,000 logged in the CED and Regional-Board reviewed (11/20).
- **Structural illiquidity (crisis note):** non-voting units, 50-year leases, and the cash-export ban make foreign capital structurally illiquid — it cannot stampede for the exits in a panic. This is a deliberate part of the §1.8 crisis posture.

---

## Key Stats (2025–2075)

| Metric | 2025 | 2075 |
|---|---|---|
| Population | 112M | 130M |
| GDP | $38.94T | scaled |
| BWC | Fiat; stable by anchor (Section 1.5) | Fiat; stable by anchor |
| Cash : BWC | 1:1, same unit | 1:1 |
| Cash metal flecks | ~5%, security + catastrophe floor (not backing) | ~5% |
| Money creation | Treasury base + CU lending (10% reserve, ~10×) | same |
| Reference rate | Flat-and-slow, rule-based (Section 1.5A) | same |
| Crisis framework | Two-tier: auto stabilizers + time-boxed emergency mode (Section 1.8) | same |
| SWF (total) | ~$1.5–2.0T (cap 12% GDP) | |
| Defense Fund (separate endowment) | ~$920B (bequests + returns) | |
| Citizens' Metals ETF (investment, not backing) | $407–504B | |
| Loans | ~$1.21T | |
| Credit Unions | ~5,000 (chartered by population/deposits; ≥3-catchment coverage — Credit Union Act §1.5; no fixed per-region count) | ~5,000 |
| Total state revenue | ~$725–750B | scaled |
| Total state spending | ~$497B | scaled |
| Aggregate surplus (grows SWF) | ~$230–255B | — |
| Education (net of FCL) | ~$175B | scaled |
| Military (operating, declining) | ~$40B → ~$0 as endowment matures | |
| Commons via FCL waterfall | ~$125B | scaled |
| Data architecture | PPK + CED (no CWD) | PPK + CED |
| Corporate GDP cap | None (replaced by §4.1) | None |

---

## Design Philosophy (Informative)

The Crossroads monetary system rests on one principle: trust through asymmetry.

The informal economy is not a gap to be closed, a tax base to be captured, or a population to be graduated into formal finance. It is the living core of daily economic life. New Crossroads leaves it alone — actively, legislatively. The prohibition on cash surveillance is not a privacy policy; it is a declaration of what the state is for.

- **Ordinary citizens face almost no scrutiny.** Their cash is private, their small transactions unrecorded, their wallets their own. The beautiful metal-flecked notes are a daily token that the state trusts them — and that even if everything digital fails, the money in their pocket is still worth something.

- **The formal system serves the informal, not the reverse.** Micro-loans without income verification, 24-hour processing, free entry to BWC. The door is always open; citizens choose when to walk through it.

- **Elites and institutions face extreme transparency.** Every large transaction is logged (pseudonymously in the CED), every major loan audited, every large FCL surplus disclosed — preventing the concentration of wealth and power that destroyed the previous system.

- **BWC is honest fiat.** It is not pegged to metal and makes no redemption promise it could not keep. Its value is held by an explicit, published rule — print to meet cash demand, never to inflate the basket, never to fund the budget — and supported in confidence by mutual capital and the sovereign guarantee. All money rests on trust; Crossroads puts the trust in plain sight.

- **Credit is priced by rule, and crises are met by pre-commitment.** With no bond market and no central bank, a flat-and-slow reference rate sets the cost of money transparently rather than leaving it to a market the system chose not to build. And because a deliberate system must not be a slow-reacting one, the crisis response is pre-committed and automatic — the deliberation done in advance, in calm times, so the response is instant and still rule-bound.

- **Identity and money are architecturally separate.** The PPK knows who you are and nothing about what you own; the CED knows what value moved and nothing about who you are. No system may join them except a judge, under warrant, on the record. The state surveils the economy; it does not surveil the citizen.

- **The SWF is self-limiting.** It never exceeds 12% of GDP; above the cap, excess returns to citizens as dividends — in cash, untracked, constitutionally protected.

- **The state is lean.** It owns infrastructure and rents it at a surplus; it funds services and lets co-ops deliver them; it employs few. It front-loads its society — funding education generously — because productive, debt-free citizens are the engine of everything downstream. Even its defense is funded, in time, by the dead, through bequest.

- **Corporations are disciplined** — by a speculation tax, a guidance ban, worker board seats, a patient-ownership voting multiplier, and buyback limits. A corporation may grow as large as the market allows, but it will act more like a co-op along the way.

Cash is beautiful and resilient. BWC is honest. Identity is sovereign. The system is legible. The informal economy is free. The SWF is capped. Corporations are disciplined. And the elite have nowhere to hide.

---

End of Draft 9.6
