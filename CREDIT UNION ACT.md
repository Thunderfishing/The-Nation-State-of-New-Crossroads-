---
title: "Crossroads Credit Union Act of 2025"
draft: "5.6"
date: "2026-06-29"
author: "Thunderfish2"
repository: "crossroads-monetary-act"
description: "Companion legislation to the Monetary Act 9.6. Fiat credit-union network, preserving all structural detail: a member-owned credit union network (~5,000, chartered by population/deposits with ≥3-catchment coverage), BWC money creation under a 10% reserve requirement, the Citizens' Metals ETF as citizen investment, demand-distributed CLS loan officers as a money-creation brake, a monthly BWC Purchasing Power Index, reference-rate-anchored loan and deposit rates, uninsured special shares (equity) on a 7/6/5-then-standardized-premium schedule with a 3-year lock-up and a national secondary market, local-priority primary issuance, professionalized boards with field-of-economy expertise and deposit-scaled compensation, residency-locked control (base shares and voting), mutual liquidity/solvency backstops with automatic crisis stabilizers, and a surgical CLS-administered debt jubilee."
supersedes: "Draft 5.5. 5.6 reworks the special-share market: the secondary market goes national (was local), primary issuance gains a 30-day local-priority window then a national remainder, a 3-year sale lock-up is added (redemption valve stays open), the steady-state premium is standardized to reference + 2%, the equity/balance-sheet treatment is stated explicitly (transfer vs redemption — the two doors), and outside ownership is governed by disclosure rather than a floor. Residency (§1.5) is re-scoped to govern base shares and voting only."
---

# Crossroads Credit Union Act of 2025: Draft 5.6

Posted to r/Bulwarkomics
Draft: 5.6 | Date: June 29, 2026
Author: Thunderfish2

**Cross-reference.** Companion to the Monetary Act 9.6. The DLB, the base-money issuance anchor (§1.5), the Reference Rate Anchor (§1.5A), the Crisis-Management & Automatic-Stabilizer section (§1.8), the Informal Economy Guarantee, the Two-Layer Velocity Architecture, and the PPK/CED data architecture are governed by that act. Loan and deposit rates here are plain nominal rates set within system bands around the reference rate defined in Monetary Act §1.5A — reset when the reference rate is republished. There is no BAR or DAI; those were removed in the fiat conversion.

**Note on figures.** Illustrative projections from a 2025 base; the design is in the structure and ratios, not the precise values.

---

## Amendment note — Draft 5.6

Draft 5.6 keeps every structural element of 5.5 and changes only the special-share market and the residency rule it depended on. Explicit changelog (so nothing is silently dropped):

**Special-share market (the focus of this revision — §3.2, §3.3).**
- **Secondary market goes national.** Existing special shares (past lock-up) trade nationwide; any citizen may buy or sell. The 5.5 "local CUSM" is retired — a small-town buyer pool was the binding constraint, and a national pool dissolves it.
- **Primary issuance becomes a waterfall.** On a new series, the issuing credit union's field of membership gets a **30-day local-priority window at par**; whatever the community does not subscribe then lists on the **national market, also at par**. Priority, not exclusion — the window is a minimum a board may not shorten, with advance notice and in-branch/in-wallet posting so residents get the full window.
- **Three-year sale lock-up.** A share may not be sold on the secondary market for its first 3 years — exactly its 7/6/5 step-down period (locked as long as it pays above the steady rate). The **redemption valve** (the $500/BWC/yr withdrawal cap) stays open throughout as the hardship exit.
- **Standardized premium.** The steady-state dividend is fixed at **reference + 2%** (replacing 5.5's "reference + ~1.5–2%, board-set" band). Because it floats and resets uniformly, every post-lock-up share pays one identical coupon, so the market prices only **credit risk**, not yield.
- **Two doors, made explicit.** A **transfer** (sale to another holder) leaves the credit union's balance sheet untouched — only the share register changes. A **redemption** (sale back to the credit union) reduces capital and is the capped door.
- **Equity treatment, stated on its face.** Special shares are equity (capital), subordinate to all depositors, loss-absorbing; dividends are payable only from available earnings and skipping one is **not a default**; capital is distinct from the 10% liquidity reserve. Member-held and investor-held shares are shown as separate balance-sheet sub-lines.
- **Disclosure, not a floor.** Each credit union publishes its local-vs-national special-share equity split; there is **no cap** on outside ownership.

**Residency re-scoped (§1.5).**
- The residency lock now governs **base shares and voting only**. Special shares are **local-priority on issue, then freely held and traded nationally** — the 5.5 hard lock on special-share investment is replaced. The relocation/grandfather rule now applies to base shares only.

**Companion/version.** Companion updated to Monetary Act 9.6.

**Cleanup.** Re-cleaned currency artifacts and reconstructed tables flattened in the source round-trip; all figures preserved.

---

## Abstract

Establishes a network of member-owned credit unions — roughly 5,000 nationally, distributed by population and deposits rather than a fixed 250 per region — as New Crossroads' decentralized financial backbone. Credit unions issue and manage Bulwark Coin (BWC) as fiat money — created by lending under a 10% reserve requirement — deliver wallets and a citizen investment path through the Citizens' Metals ETF, provide reference-rate-anchored loans (~$1.2084T by 2075) and banking suites, and let every citizen-member build wealth through low-barrier entry and tiered incentives.

Sector loan allocation is by creditworthiness and productive use, not binding quotas. The 2025 baseline (~65% co-op, 15% corporate, 20% informal) is descriptive, not prescriptive. The system is built for asymmetric scrutiny: extreme transparency for large transactions and elite actors, complete privacy for ordinary daily life. Credit unions are the formal economy's open door to the informal sector — serving cash-based citizens on those citizens' terms, not pulling them into surveillance.

---

## Section 1: Core Features & Currency

### 1.1 Dual Currency Role & Money Creation

Credit unions issue and manage BWC, the national fiat currency (the same unit as physical cash, at 1:1).

- Cash (Layer 1): velocity medium for informal-sector and daily private transactions at or below the DLB threshold.
- BWC digital (Layer 2): store of value and formal-economy medium.

BWC is fiat. Not redeemable for metal, not backed by a metal reserve. Its value is held stable by the Monetary Act's issuance anchor and supported in confidence by the mutual capital of the credit union network, the Deposit Insurance Pool (DIP), and the sovereign guarantee of the SWF.

**Money creation (Model A — loans create deposits).** A loan credits the borrower's wallet with new BWC, matched on the books by the borrower's promissory obligation. Money is created at the moment of lending.

**The reserve requirement (quantitative cap).** Each credit union holds 10% of deposits in reserve (base BWC and cash) — the cap on broad-money creation (~10× the Treasury base). This 10% liquidity reserve is the money constraint, entirely distinct from the Citizens' Metals ETF (investment, not currency backing). There is no per-coin metal backing of any kind.

**CLS credit judgment (qualitative brake).** Because lending creates money, the professional credit judgment of embedded CLS loan officers is itself a brake on money creation (Section 5). Reserve = the ceiling; CLS = the judgment beneath it.

- **Features:** real-time wallet status; the monthly BWC Purchasing Power Index (Section 1.4) on every wallet; CME-resilient via hardened grid and EMP-proof vaults.

*Rationale:* a fiat BWC disciplined by an explicit issuance anchor (Monetary Act §1.5), a 10% reserve, and CLS credit judgment can fund a growing co-op economy without the credit scarcity a metal standard imposes. Trust comes from a transparent purchasing-power index and sound institutions, not from a redemption promise the system could not universally honor.

### 1.2 Self-Recapitalization & Capital Growth

Credit unions self-recapitalize through:

- **Special Shares (primary mechanism):** 1–2 series per year, each raising ~$12.5B system-wide (illustrative), scaled per region by population/deposits rather than a flat $2.5B × 250 (see §1.5, §3.2). Tiered pricing ($1,000–$25,000/BWC per citizen). Uninsured equity, raised locally-first then nationally (§3.2). This is the engine of loan growth toward ~$1.2084T by 2075.
- **Fees:** transaction, swap (BWC→Cash only), checking, liquidity, and micro-loan fees. (No special-shares insurance fee — special shares are uninsured.)
- **Loan interest:** anchored to the reference rate (Monetary Act §1.5A); micro and service-sector rates set deliberately below it (§4.2).
- **SMSWF profits:** ~$1.736B/year to credit unions.
- **Citizens' Metals ETF & SWF investment returns:** grow credit-union capital and member savings (not currency backing).

**Recapitalization cycle:** each series raises ~$12.5B → at 2 series/year, ~$25B/year of new capital → deployed as reference-rate-anchored co-op, corporate, and informal loans → loan interest and fees fund special-share dividends → strong performance attracts the next series.

**Metal allocation for physical cash:** ~40% of the SMSWF gold/silver stream is allocated to minting the ~5% standardized metal flecks in polymer notes (Monetary Act), so the cash supply and its catastrophe floor grow organically with mining as GDP rises.

*(The former "ETF returns to base backing until the $300/BWC target" mechanism is removed — ETF returns now flow to member savings and credit-union capital. The ETF backs its shareholders, not BWC.)*

### 1.3 Informal Sector Mandate

*Rationale:* the informal economy is a protected economic zone, not a gap to be closed. Credit unions are the formal system's handshake with it — accessible on informal terms. Binding on all credit unions and all CLS officers.

Credit unions and CLS **must**:

- Accept self-attested cash income as sufficient for micro-loan approval ($500, 4% nominal). No documentation, no income verification, no cash-history review.
- Process micro-loan applications within 24 hours.
- Post the current DLB threshold, the monthly BWC Purchasing Power Index, the reference rate, the loan rate table, and any open special-share series and its local-priority window (§3.2) in all branches (physical and digital), updated as published.

Credit unions and CLS **may not**:

- Deny, downgrade, or penalize membership tier based on a member's cash-to-BWC ratio.
- Require BWC transaction history or cash-history disclosure for micro-loans.
- Report cash withdrawal patterns to any body absent a court order.

Violations: Regional Board sanction, CED audit, and fines up to $5M per incident.

### 1.4 BWC Purchasing Power Index (PPI) — replaces the daily backing ratio

*Rationale:* under fiat there is no metal backing ratio to display, and a daily readout would imply a volatility the anchor is designed to remove. Citizens need to see not "how much metal backs my coin" but "is my money holding its value."

- **Definition:** the BWC Purchasing Power Index (PPI) measures the purchasing power of one BWC against the DLB basket, set to 100 at the 2025 base. A falling PPI signals erosion; a rising PPI signals strengthening.
- **Publication:** Treasury publishes the PPI monthly. Every credit union displays it on every wallet dashboard and in every branch.
- **Function:** the PPI is the public-facing expression of the issuance anchor (Monetary Act §1.5). If it drifts outside the stability band (DLB movement beyond ~1–2%/year), the anchor's price condition tightens or loosens base issuance accordingly.
- **Why monthly, not daily:** stable money does not need a daily readout; a monthly index communicates steadiness without manufacturing the appearance of volatility. The daily backing ratio of prior drafts is retired entirely.

### 1.5 Field of Membership, Catchment Coverage & Residency

*Rationale:* discipline comes from two places, and they govern two different things. **Local competition** keeps each credit union honest on service and rates — through community membership, the ≥3-catchment overlap, and the local-priority share window. The **national special-share market** prices each credit union's credit risk. Residency therefore governs **control** (votes and membership), not the holding of non-voting capital: locking *who governs* a credit union to the community it serves, while letting *who funds* it extend nationally.

**Field of membership (the local common bond).** Each credit union serves a defined field of membership — the municipality and surrounding area assigned to it. This is the cooperative common bond at community level and is distinct from the 20-region governance tier (which retains the word "region" throughout this act and the Monetary Act). "Field of membership" is the operative term for the local catchment.

**Chartering by rule, not fixed count.** Credit unions are chartered roughly one per N residents (or per deposit base), so a highly populated area may host many (e.g., ~1,000) and a sparsely populated one only a few (e.g., ~200). The flat 250/region is retired. ~5,000 nationally is a derived illustrative headline, not a target.

**Coverage guarantee (≥3 catchments).** Catchments are deliberately drawn to overlap so that every residence falls within the field of membership of no fewer than 3 credit unions, guaranteeing every citizen at least three to choose among for membership, shares, and loans. Dense areas naturally exceed this; the rule fixes the minimum. To meet the floor where density is low, rural catchments may be geographically larger so remote districts are still reached by at least three credit unions (whose catchments may extend from neighboring towns).

**Residency-locked control (base shares and voting).** To hold **base shares** and to **vote**, a member must reside within that credit union's field of membership. Base shares carry membership and the vote; locking them keeps each credit union governed by the community it serves. **Special shares are non-voting capital and are *not* residency-locked to hold** — they are local-priority on issue (the 30-day window, §3.2) and freely held and traded nationally thereafter (§3.3). Widening who holds non-voting capital never touches who controls the credit union.

**Portable deposits, ETF, and special-share holding.** Deposits, withdrawals, cash transactions, checking, savings, GICs, retirement, loans, the national Citizens' Metals ETF, and **special-share holding** are all portable/national. A traveler or visitor may deposit, withdraw cash, and transact at any credit union. Only **base shares and the vote** are residency-bound.

**Overlap eligibility.** Where two or more catchments cover a residence, the resident is eligible to join (take base shares and vote) in any of them. The mild local rate-shopping this permits is the intended competition, not a defect; the flat-and-slow reference band keeps the spread to chase small.

**Residency via PPK.** Field-of-membership residence is an identity-layer attribute, self-attested through the PPK as a qualified/not-qualified check. It is never established by transaction tracking and never merged with CED economic data outside the warranted Judicial Link Box.

**Relocation / grandfather rule (base shares).** On moving out of a credit union's field of membership, a member **keeps existing base shares** (grandfathered, estate-transferrable) but may not acquire new base shares there or vote there; they establish membership in the new field. **Special shares are unaffected** — they are nationally holdable regardless of residence, so relocation never threatens them.

---

## Section 2: Membership & Tiers

### 2.1 Membership Categories

- **Citizen-members:** full membership, 1+ base shares, wallet, banking suite, ETF access, loans, voting rights.
- **Ages 12–19:** voluntary student/minor account (1 base share), checking/savings/ETF/$500 venture loans, parental oversight for full features.
- **Non-voting members:** basic banking with reduced deposit-insurance coverage (Section 6.3).
- **Non-member capital holders:** any citizen may hold special shares in a credit union outside their field of membership (§3.2, §3.3). They are non-voting, receive dividends, and have no membership or tier benefits.

### 2.2 Membership Tiers

| Tier | Requirements | Wallet ETF Investment Cap | Key Benefits & Bonuses |
|---|---|---|---|
| **Base** | 1–1,000 base shares ($1,000/BWC) | ~$300/BWC | 75% patronage to shares, full banking, voting rights |
| **Silver** | + special shares | ~$15,000/BWC | +$50/BWC bonus, 80% patronage, +5% activity bonus, silver card |
| **Gold** | $25,000/BWC special shares + 1,000 base | ~$20,000/BWC | +$200/BWC bonus, 0% savings fees, 0.5 advisory vote on non-SWF loans, 85% patronage, gold card |

*(Tier benefits require membership — a residency-locked base share in that credit union. ETF cap is an investment ceiling per tier — member protection — not a backing figure.)*

- **Patronage Bonuses:** +5% for on-time line-of-credit payments, +10% for 12-month consistency (max $50/BWC/year).
- **System-wide:** ~$862.5M/year activity bonuses + ~$4.7B/year payment bonuses.
- **Tier Non-Discrimination:** tier status is determined solely by share holdings and payment history. Cash income, cash transaction volume, and informal-sector participation are not factors in tier assignment, maintenance, or demotion.

---

## Section 3: Shares & Wealth Building

### 3.1 Base Shares

- **Cost:** $1/BWC, max 1,000 ($1,000/BWC lifetime; ~$94B system-wide).
- **Acquisition:** buy ~$100 BWC/year, earn 75% patronage to shares / 25% cash, reinvest 4–8% dividends.
- **Informal Sector Welcome Share:** 1 free base share granted automatically on successful repayment of first micro-loan. No purchase required. Grants full membership and voting rights.
- **Minor incentives (12–19):** 1 share for voting in board elections, 1 for town-hall attendance.
- **Residency:** base shares are held only in a credit union within the member's field of membership (§1.5); they carry the vote and are the seat of membership. Grandfathered on relocation (§1.5).
- **Mechanics:** lifetime, non-sellable, estate-transferrable; grants membership, banking, and voting rights.

### 3.2 Special Shares — Uninsured Member & Investor Capital

*Rationale:* special shares are patient risk-capital that lets sound lending exceed the Treasury base while staying solvent. Modeled on the cooperative practice of issuing uninsured investment shares at a premium over insured deposits: because they carry no deposit insurance, they pay more — and that extra return is honest compensation for the risk, not a subsidy. Because they are **non-voting**, capital formation can be local-first while capital *holding* extends nationally without ever touching who controls the credit union.

**Issuance.**
- **Schedule:** 1–2 series/year, at board discretion with Regional Board approval (6/11).
- **Series structure:** each raises ~$12.5B system-wide (illustrative), scaled per region by population/deposits rather than a flat $2.5B across 250 credit unions/region (re-derived off the actual catchment distribution — see §1.5, Appendix B). Offered sequentially (not simultaneously) to avoid saturation; between series, credit unions deploy prior-series capital into reference-rate-anchored loans.
- **Pricing (subscription):** $1,000–$25,000/BWC per citizen (tiered), at **par**.
- **Primary issuance waterfall (new):**
  - *Local-priority window* — on a new series, the issuing credit union's field of membership has **first refusal for 30 days, at par**. The series, terms, and window must be posted in advance, in-branch and in-wallet (§1.3), so residents get the full window. The window is a **minimum**; a board may not shorten it to push shares to outside investors.
  - *National remainder* — whatever the field of membership does not subscribe within the window lists on the **national market, also at par**. This is how a small credit union that cannot self-fund a full series still capitalizes: the community buys what it can, the nation funds the rest.

**Dividend.**
- **Year 1: 7% · Year 2: 6% · Year 3: 5%** — the step-down, paid for committing through the lock-up.
- **Year 4 onward: reference rate + 2%** — the **standardized national premium**, floating and reset when the reference rate is republished (Monetary §1.5A). Every post-lock-up share therefore pays one identical current coupon. The premium is a **system constant, not a board choice**: boards decide whether to issue, not what to pay.

**Three-year sale lock-up (new).** A share may not be sold on the secondary market for **3 years from issue** — exactly its step-down period, so a holder is locked precisely as long as the share pays above the steady rate. This is the honest quid pro quo for the 7/6/5 teaser, like a term deposit. The **redemption valve stays open** throughout the lock-up as the hardship exit (see Withdrawals).

**Withdrawals (the redemption door).** $500/BWC/year (1-year cooldown for a $1,000/BWC withdrawal). A withdrawal is a **redemption** — selling the share back to the credit union, which pays cash and cancels it, reducing the credit union's capital and liquidity. This is the **capped** door, open during and after lock-up. For liquidity beyond the cap (after lock-up), holders use the national secondary market (§3.3), which does not de-capitalize the credit union.

**Two doors (new — transfer vs redemption).**
- **Transfer (secondary sale to another holder):** the credit union pays nothing; the share stays on its books at the same value; only the **share register** changes — who the dividend is owed to. Cash moves wallet-to-wallet, off the credit union's balance sheet. National and open after lock-up (§3.3). The credit union keeps every dollar of its capital; only the dividend recipient changes.
- **Redemption (sale back to the credit union):** capital and liquidity shrink; this is the capped door above.

**Equity treatment (new — what a special share is on the books).**
- **Equity, not a liability.** Special shares sit in the **capital** section of the balance sheet — members'/investor capital, not money the credit union owes back on demand.
- **Subordinate and loss-absorbing.** In a wind-up, special-share holders rank **below all depositors and the DIP** (§6.5) — they absorb losses before insured depositors are touched. That subordination is what the premium pays for.
- **Discretionary, earnings-funded dividend.** Dividends are payable only from available earnings, at board declaration. A skipped or reduced dividend in a bad year is **not a default** — which is exactly what lets this instrument absorb stress without triggering insolvency.
- **Capital, not reserve.** Special shares count toward the credit union's **capital** (the solvency cushion); they are distinct from the **10% liquidity reserve** (base BWC/cash held against deposits, §1.1). A subscription arrives as a cash asset, is recorded as special-share equity, and is then deployed into loans.
- **Member vs investor equity.** A share held by a resident member and one held by a non-member national holder are the same instrument at the same rank, shown as separate balance-sheet sub-lines — *member special-share equity* and *investor special-share equity* — for the §3.3 disclosure.

**Holding & voting.**
- After issue, special shares are freely held and traded **nationally** and are **not residency-locked**. A holder outside the issuing credit union's field of membership is a **non-voting, non-member capital holder** — no vote, no membership, no tier benefits. Membership still requires a residency-locked base share (§3.1).
- **Non-voting** (capital never buys board control — §6.1), except Gold-tier members' 0.5 advisory vote on ~$50B non-SWF loans.

**Carry / solvency note (reframed).** Special-share capital is leveraged ~10× into the loan book under the 10% requirement, so the capital earns the loan spread on a multiple of itself (plus fee, SMSWF, and ETF income) — a modest net interest margin covers the reference + 2% dividend comfortably. The standardized premium is set at the system level so this holds. If the network's net interest margin ever compresses to where leveraged spreads plus other income cannot cover the dividend, that is a **system-level signal** addressed through the reference-rate review (Monetary §1.5A) and the Central Council — not a per-board adjustment.

**Recapitalization impact:** each series adds ~$25B/year of capacity; over 50 years (2025–2075), ~$1.2084T.

*(Special shares recapitalize credit-union capital that satisfies the reserve/capital requirement; they do not add metal to any reserve. This is the instrument that lets sound lending exceed the base while staying solvent — genuinely at-risk, premium-paying equity.)*

### 3.3 Credit Union Secondary Market (CUSM) — national

*Rationale:* the withdrawal cap and the 3-year lock-up keep capital deployed; the CUSM gives an individual holder liquidity **without de-capitalizing the credit union** — because a secondary sale *transfers* ownership, it does not *redeem* capital. National scope solves the small-credit-union liquidity problem: a small town's buyer pool was the binding constraint, and a national pool of 130M dissolves it.

- **National transfer market.** Special shares past their 3-year lock-up trade nationwide; any citizen may buy or sell, through the Regional-Board-overseen CUSM exchange.
- **Transfer, not redemption.** A sale changes only the **share register** — the credit union's balance sheet, capital, and equity are untouched (§3.2, Two doors). The wobbly small-town credit union keeps every dollar of its capital; only the dividend recipient changes.
- **Homogeneous coupon → risk-priced, not yield-chased.** Because the standardized premium (reference + 2%) floats and resets uniformly, every tradable share pays the same current coupon. The market therefore prices only the **credit risk** of the issuing credit union (these are uninsured) — risk discipline, not yield arbitrage. Capital does not flood the highest-paying credit union, because none pays more.
- **Trading band:** 90%–110% of par. A sound credit union's shares hold near par; a weak or very small one's may trade at a discount within the band — the market pricing real risk. National scope guarantees a **buyer**, not par; the 90% floor caps the downside.
- **Share register (the mechanism).** The exchange maintains the current holder of each share so dividends and ownership route correctly. A transfer is a registry update — trivial beside moving capital.
- **Accrued-dividend rule.** On transfer, the seller's accrued portion of the current dividend period is settled in the sale price (or paid to holder-of-record on a set date), so the buyer does not collect dividends the seller earned.
- **Trades above 105% of par** require CLS notification (notification only, no approval).
- **Disclosure, not a floor.** Each credit union publishes its special-share equity split — **member (local) vs investor (national)** — quarterly. There is **no cap** on outside ownership; the discipline is transparency, so "how much of our capital is member-owned" stays legible without re-stranding a small credit union that needs outside capital.
- **Liquidity waterfall.** National CUSM trading is the default venue; the co-op index (CGCI / CCIF) and member-buyback paths remain the **last-resort backstop** for genuinely thin or distressed cases, so no holder is ever stuck.
- **Governance:** CED logs aggregate CUSM volume (quarterly, system-wide) and the per-credit-union member/investor equity split; individual trades are private.

### 3.4 Citizens' Metals ETF — citizen investment (NOT currency backing)

*Rationale:* citizens should have a sound, inflation-resistant savings vehicle. The Citizens' Metals ETF provides one — and grows a national metals reserve as a byproduct — without that reserve backing the currency.

- **Mechanism:** members invest part of their wallet into the BWC-administered metals ETF (gold/silver, plus SMSWF ETF). The ETF holds physical metal; returns accrue to the member's savings.
- **What it backs:** the ETF's metal backs the ETF's shareholders — an investment position, like any commodity fund. It does not back BWC, sets no oz-per-BWC ratio, and creates no redemption claim on the currency.
- **National benefit:** the aggregate metal strengthens the state's balance sheet and external position and stands as a sovereign reserve — but it is investment-owned, not currency-backing.
- **National, not residency-locked:** the ETF is a national investment vehicle and is not subject to the field-of-membership lock (§1.5); any citizen may hold it from any wallet.
- **Caps:** investment capped per tier (Section 2.2); returns flow to personal savings.

### 3.5 Privacy and Scrutiny Tiers

- **Wallet balances below $10,000 BWC:** private. No CED detail beyond pseudonymized aggregate. No reporting.
- **$10,000–$100,000:** pseudonymized aggregates only; annual summary.
- **Above $1M assets:** full pseudonymized detail; quarterly audits; holdings above $10M publicly disclosed.
- **Cash:** never recorded (Informal Economy Guarantee).

---

## Section 4: Banking Suite & Loans

All banking-suite and loan rates below are set within system bands around the reference rate (Monetary Act §1.5A) and reset when the reference rate is republished. Because deposit and loan rates share one anchor, they move together; the levels shown are illustrative 2025 figures, not fixed-forever values.

### 4.1 Banking Suite

| Product | Volume | Rate / Fee | Notes |
|---|---|---|---|
| Checking | $94B | 1% fee | Waived for earners under $10,000/year BWC |
| Savings | $94B | 5–6% | Anchored to reference rate |
| Mutual Funds | $10B | 4.6% | |
| GICs | $5B | 3–5% | |
| Bonds / FCL Equity | $5B | 3–4% | |
| Savings Bonds | $47B | 3–4% | |
| Crypto | $23.5B | 5–10% | |
| Retirement | $94B | 6–8% | |

*(Component figures preserved from prior drafts. Note: components sum higher than the previously stated "208B" headline — a pre-existing inconsistency to reconcile in a future pass; Appendix A lists ~$260.2B.)*

### 4.2 Loans (~$1.2084 trillion) — reference-rate-anchored

All loan rates are plain nominal rates set within system bands around the reference rate (Monetary Act §1.5A). There is no DAI adjustment and no BAR. Loans are written against creditworthiness and productive use; reported by sector for monitoring; no binding quotas.

**Historical baseline (2025, descriptive only):**
- Co-op loans: ~$294.125B
- Corporate loans: ~$67.875B
- Informal-sector loans: ~$90.5B

These are not binding targets; the system fosters a co-op-dominant productive economy through incentives, not mandatory allocation.

| Loan Type | Nominal Rate | Notes |
|---|---|---|
| Co-op loans | 5–6% | At/around the reference rate |
| Corporate loans | 5–6% | At/around the reference rate |
| Informal-sector loans | 5–6% | At/around the reference rate |
| Non-SWF loans | 5–6% | ~$50B; small co-ops/informal |
| Micro-loans | 4% | ~$500 each; self-attested income; set below reference by design |
| Student venture loans | ~5% | $500; ages 12–15; lenient criteria |
| Service-sector loans (healthcare, education, infrastructure) | 4–5% | Recognizes labor subsidy; set below reference by design |

*(Prior drafts applied a DAI adjustment and a 0.5%/1.0% effective-rate floor to these. Under fiat there is no DAI: the low rates for micro/service/informal loans are the actual nominal rates, set deliberately below the reference rate to recognize their social value.)*

**Asymmetric Scrutiny for Loans:**

- Below $500,000: streamlined, minimal documentation, CLS-issued within 48 hours.
- $500,000–$1M: standard review, Regional Board notification.
- $1M–$10M: full audit, CED logging, Regional Board approval (6/11), public disclosure.
- Above $10M: Central Council review (6/11), SAP arbitration if disputed, published.

**Micro-Loan Special Rules:**

- Self-attested income accepted; no documentation. Cash income explicitly valid; CLS may not request bank statements, BWC history, or employment records.
- Processed within 24 hours. First successful repayment triggers the Informal Sector Welcome Share (3.1).
- Default recovery is supportive, not punitive: the CLS bankruptcy-recovery program applies before any collection.

---

## Section 5: Crossroads Loan Service (CLS) — embedded loan officers & money-creation brake

*Rationale:* CLS agents are not a separate bureaucracy — they are the credit unions' own loan officers, embedded in the credit unions they serve. Because lending creates money, CLS credit judgment is the human brake on money creation, working beneath the 10% reserve cap.

### 5.1 Structure & Demand-Based Distribution

- **Total corps:** ~60,000 CLS agents nationally — an average of ~12 per credit union, but distributed by loan demand, not a flat per-region quota.
- A small rural farm-country credit union may need only 2–4 agents; a high-volume urban credit union may have many more. Allocation follows where lending activity actually is.
- **Scalable:** a credit union may request additional agents as demand grows; the corps expands to meet genuine lending volume. Agent count is a function of demand, not a fixed cap.
- **Composition (illustrative):** field agents (~48,000), supervisors (~11,800), seniors (~200), re-weighted by demand rather than fixed per region; field-agent compensation ~$12,000 stipend + 3% shares, seniors ~$200,000/year.
- Agents are embedded as the credit union's loan officers while belonging to the national CLS corps (shared standards, training, discipline).

### 5.2 CLS as a Money-Creation Brake

- Since every loan creates BWC, CLS lending standards govern the pace of money creation beneath the reserve ceiling. Prudent underwriting restrains broad-money growth; lax underwriting would expand it. The corps is a distributed, professional check on monetary expansion.
- The corps structure — independent professional standards, an academy, citations and disciplinary actions — keeps this brake credible: money creation is disciplined by trained credit judgment, not by mechanical limits alone.
- This complements the 10% reserve requirement: reserve = the ceiling; CLS = the judgment beneath it.

### 5.3 Academy & Functions

- **Academy:** ~$1.5375B/year (Crossroads City + New Tech City). Curriculum: loan management, student-venture mentorship, bankruptcy recovery, informal-sector engagement, reference-rate-anchored rate application (including the lower service/micro/informal rates), DLB threshold tracking, Purchasing Power Index literacy, and Informal Economy Guarantee compliance. (Backing-ratio and DAI education retired.)
- **Functions:** administer ~500 student-venture loans (ages 12–15, lenient, mentorship), support bankruptcy recovery, monitor economic-health indicators (Monetary Act Economic Health Dashboard), serve as primary contact between the formal credit system and informal-sector participants.
- **Cost & funding:** ~$93.75M/region equivalent (now demand-weighted), funded by credit-union revenue + ~$337.5M SWF, plus the academy.

**Sector Health Monitoring:** CLS compiles aggregate loan data by sector for the Dashboard. If co-op GDP falls below 45% for three consecutive years, the Monetary Act's soft trigger initiates a Co-op Sector Review; CLS provides data but takes no independent action. No loan approval/denial is conditioned on sector GDP shares.

**Informal Sector Engagement:** agents are evaluated on informal-access metrics (24-hour micro-loan processing, self-attested approval rate, Base-tier satisfaction). Exceeding targets earns citations and 5–10% salary bumps; requiring documentation beyond self-attestation, or conditioning access on cash-history disclosure, triggers disciplinary review (5–15% fines/suspension/expulsion). Agents may not require cash-history disclosure for any loan under $500,000.

**Discretion:** full discretion below $1M; $1M–$10M with public disclosure.

**Oversight:** CED tracks performance metrics; informal-access metrics weighted equally with loan-performance metrics in annual reviews.

### 5.4 Surgical Jubilee Administration (CLS-judged)

The Monetary Act's 25-year debt jubilee forgives up to 50% of qualifying co-op debt — but this is not blanket forgiveness. It is surgical, administered by CLS on the basis of why a co-op is in distress:

- **Eligible:** co-ops in distress through circumstances beyond their control — bad timing, external shock, market or environmental disruption, or misfortune despite sound management.
- **Not eligible:** co-ops whose distress is the result of mismanagement, incompetence, or negligence. Bad management is not rewarded with forgiveness.
- **Process:** CLS, drawing on its ongoing relationship with and data on each co-op, makes the determination case by case — not automatically.
- **Freedom Shares** are issued to forgiven co-ops (per Monetary Act §2.2). Forgiven debt is converted into Freedom Share equity rather than written off: stakes are split between the credit union (compensated with ownership instead of a defaulted loan) and the co-op's worker-members (restored stake). After the co-op stabilizes, the credit union exits by selling its Freedom Shares back to the co-op (member buyback) or into the co-op index (CGCI / CCIF) — whichever the co-op's condition supports — recovering its capital on its own timeline and aligning its incentive with the co-op's recovery. Residual ownership distributes broadly through the index.
- **Appeal:** a co-op denied may appeal to the Regional Board (11/20); a grant made over objection may be reviewed by the same.

*Rationale:* a surgical jubilee preserves the relief function (resilient co-ops felled by bad luck get a fresh start) without the moral hazard of a blanket bailout (incompetence is not subsidized). CLS — closest to each co-op's actual history — is the right body to judge which is which.

---

## Section 6: Governance, Oversight & Sustainability

### 6.1 Credit Union Boards

*Rationale:* boards must be both democratic (members govern, not capital) and competent (directors who understand banking and the local economy). The design gets both by keeping one-member-one-vote elections while gating candidacy by field of expertise — and by paying the credentialed working directors enough to attract that expertise.

**Election & equality.**
- The **full membership elects all board seats**. **One member, one vote** — each member casts a single vote regardless of how many shares they hold. Special shares are **non-voting**; capital carries economic weight (dividends) but never board control, whether held by a resident member or a national investor.
- Elections held every 3 years, regionally staggered.

**Board size scales with credit-union size.**
- **5 seats** at small credit unions; **7 seats** at large ones (by deposits). This holds governance cost down at small credit unions and matches board capacity to institutional complexity.

**Expertise requirement (credentialed seats).**
- Credentialed seats must be filled by members drawn from **relevant economic fields** — a published list including economics, finance, accounting, banking/credit-union management, law, and cooperative governance.
- The **Regional Board verifies candidate eligibility against the published list as a yes/no candidacy gate** — it screens the field, it does not judge the person. Members then elect freely from the eligible candidates.

**Informal Sector Seat (credential-exempt).**
- Each board includes at least one seat reserved for a member whose **primary income is cash-based or informal**, qualifying by **lived experience** and **exempt from the credential bar**. Elected by the same one-member-one-vote membership. This seat may not be eliminated by board vote. Its role is to represent the informal economy, not to audit a loan book.

**Compensation.**
- **Credentialed directors:** a **$60k floor** per seat, **scaled by the credit union's total deposits** up to a cap of roughly **$150–180k** at the largest credit unions (illustrative tiering: <$50M deposits → ~$60k; $50M–$250M → ~$90k; $250M–$1B → ~$120k; >$1B → ~$150–180k).
- **Informal/lived-experience seat:** sits on a **stipend** (illustratively ~$25–40k), not the full professional salary, reflecting its governance-representation rather than working-director role.
- System-wide, with ~30,000 seats and an average post-scaling seat near ~$100–110k, board compensation lands near ~$3–3.3B/year, ~3% of the network's ~$107.6B revenue.

**Responsibilities:** loan policy; CLS oversight; setting **local deposit and loan rates within the reference-rate-anchored system bands** (§4); proposing special-share series and running the local-priority window (§3.2); Informal Sector Mandate compliance.

### 6.2 Special Shares Oversight

- Each series requires Regional Board approval (6/11). Series tracked via CED at aggregate level; individual purchases private below $10,000.
- **Local-priority window** compliance (the full 30 days, advance posting) is verified by the Regional Board; a board may not shorten the window or steer the local tranche to outside investors.
- **National secondary market** activity is reported to Regional Boards quarterly in aggregate volume, together with each credit union's **member-vs-investor special-share equity split** (the §3.3 disclosure). No cap on outside ownership; transparency is the discipline.

### 6.3 Deposit Insurance & Voting Requirement

*Rationale:* deposit insurance is a mutual benefit; full coverage requires governance participation — tying rights to responsibilities without excluding anyone from basic banking. Insurance covers deposits and wallets only — never special shares, which are uninsured equity (§3.2).

- **Scope:** deposit insurance covers deposits and wallets. Special shares are not insured (the former special-shares insurance pool is removed).
- **Standard coverage:** up to $250,000 BWC per member, per credit union.
- **Reduced (non-voting):** up to $50,000 BWC.
- **Qualification:** voted in at least one of the last three board elections. Missing two consecutive elections (without exemption) reverts to reduced coverage until voting resumes.
- **Grace/exemptions:** 12 months standard coverage for new members; exemptions (no loss of coverage) for documented serious illness (self-attested, no verification under 12 months), military deployment outside region, or residence outside region >6 months — by simple declaration, no proof required for absences under 12 months.
- **Reinstatement:** voting in any election after a lapse regains standard coverage within 30 days.
- **Verification via PPK:** eligibility is confirmed through the PPK as a zero-knowledge "qualified/not qualified" proof — never by disclosing individual votes. Voting is identity-layer data and lives only in the PPK, never the CED.
- **Appeal:** members may appeal a coverage determination to the Regional Board.

### 6.4 Regional Liquidity Pools (RLPs) — Lender of Last Resort

*Rationale:* credit unions need a lender of last resort, not a central bank. RLPs are mutual liquidity backstops owned collectively by each region's credit unions.

- **Establishment:** one RLP per region, administered by the Regional Board with daily operations by an elected, annually-rotating committee of credit-union managers.
- **Funding:** each credit union contributes 2% of total deposits annually + 20% of patronage dividends (e.g., $100M patronage → $20M to RLP, $80M to members). Returns stay in the pool.
- **Assets:** held in BWC and short-term inter-credit-union loans, with a liquidity-appropriate metal allocation. (Metal here is a liquid reserve asset, not currency backing.)
- **Target:** 5–10% of regional deposits.
- **Access:** a credit union may draw on a liquidity shortfall (reserves <10% of deposits; peer lending failed). Failure to repay forfeits its stake and forces board re-election within 90 days.
- **Loan terms from RLP:** **reference rate + 1%** (Monetary Act §1.5A), 12-month term.
- **If exhausted (normal path):** the credit union may petition the SWF, which activates on 5 Regional Boards jointly certifying an emergency (5/20) and Central Council approval (6/11). SWF loans carry **reference rate + 2%** (no BAR).
- **Crisis path:** under a declared systemic-freeze trigger, the petition step is pre-cleared and the SWF line opens automatically — see §6.8.

### 6.5 Deposit Insurance Pool (DIP) — Solvency Backstop

*Rationale:* the RLP handles liquidity; the DIP handles solvency (pays depositors if a credit union fails entirely).

- **Nesting:** each region's DIP is a sub-fund of its RLP.
- **Funding:** half of the 20% patronage diversion (i.e., 10% of patronage) + 0.1% of BWC transactions above $10,000 (absorbed within the existing 1.5%/2% fee tiers, no net fee increase).
- **Payout:** on insolvency (assets <80% of liabilities for 90 days), pays insured depositors up to $250,000 (or $50,000 non-voting) within 30 days, into a wallet at another credit union of their choice. Failed-CU assets are liquidated by the Regional Board, proceeds returning to the DIP. **Special-share holders are not covered** (uninsured equity) — they rank below depositors and absorb losses first (§3.2).
- **Reinsurance:** if a regional DIP falls below 2% of insured deposits, it may draw from the SWF to restore to 4% (Regional Board unanimous for that region + Central Council 6/11).
- **Investment:** 50% BWC, 30% reference-rate-anchored short-term government instruments, 20% metal. No loans or illiquid assets.

### 6.6 System-Wide Oversight Architecture (PPK/CED)

The data architecture is the PPK/CED split, operational from inception (Monetary Act §5). There is no CWD. Identity, credentials, voting, and residence live in the citizen-held PPK; pseudonymized economic data lives in the CED; the two join only through the warranted Judicial Link Box.

| Level | Income / Assets | CED treatment | Reporting |
|---|---|---|---|
| Informal | At/below DLB (cash) | Never collected | None. Constitutionally protected. |
| Citizen | Under $10k/year BWC | Pseudonymized; no detail | None |
| Middle | $10k–$100k/year | Pseudonymized aggregates | Annual summary |
| Elite | Above $1M assets | Full pseudonymized detail | Quarterly audits; public above $10M |
| Institutional | Credit unions >$10M revenue | Full transparency | Public annual reports; Regional Board audit |

- **Treasury:** administers BWC issuance under the Monetary Act §1.5 anchor, the reference rate (§1.5A), and the Citizens' Metals ETF. Publishes the monthly BWC Purchasing Power Index, the annual DLB (by January 15), the reference rate, and the loan rate table. Treasury does not publish a backing ratio, BAR, or DAI table — BWC is fiat.
- **CED:** tracks CLS performance, FCL metrics, aggregate loan/sector data, RLP/DIP aggregate health, CUSM volume, and the member/investor special-share equity split — all pseudonymized. Cash data is never collected. Identity is reachable only via the Link Box (2-region warrant). Audited by 50–75 auditors + AI systems; fraud cap ~$2.5B; appeals to judiciary.
- **Regional Boards:** 20 boards (11 members each) approve special-share series, verify the local-priority window, oversee the national CUSM, approve major loans and FCL opt-ins, run RLP/DIP operations; verify board-candidate field eligibility (§6.1); investigate Informal Sector Mandate violations; report annually on informal-access and RLP/DIP solvency.
- **Auditors:** 50–75 system auditors; may not request, subpoena, or receive individual cash transaction records.

### 6.7 Sustainability

- ~$50B/year SWF projects (greenhouses, CO₂ pipelines, parkweb).
- SMSWF mining FCLs feed profits to credit unions (~$1.736B/year) and the Citizens' Metals ETF; ~40% of the SMSWF metal stream is allocated to the ~5% standardized cash flecks, keeping the velocity layer supplied and the catastrophe floor intact as GDP grows.
- Loan affordability is maintained by the issuance anchor holding the PPI stable and by the flat-and-slow reference rate — not by any appreciation-adjustment mechanism.
- RLPs and DIPs provide self-insurance without a central bank, preserving the decentralized, anti-concentration character of the system while enabling sound lending growth.

### 6.8 Crisis Liquidity & Automatic Stabilizers

*Rationale:* a deliberate, stable system must not be a slow-reacting one. The defense against a GFC-speed event is to do the deliberating in advance — pre-committing the crisis response as automatic, threshold-triggered, sunset-bounded actions, authorized democratically in calm times — so execution is instant and still rule-bound. This subsection houses the credit-union-side mechanics; trigger definitions and the Tier-2 emergency mode live in Monetary Act §1.8.

**Detection — institutional plumbing only.** Systemic-stress triggers are read entirely from the institutional-transparency layer, never from citizen activity: the inter-credit-union (peer-lending) rate, RLP draw velocity, reserve dispersion across credit unions, BWC→cash swap spikes, **CUSM price pressure toward the 90% floor (now a deeper, more informative national signal)**, and DIP/RLP utilization. No citizen surveillance is used or permitted to detect a crisis.

**Tier 1 — automatic stabilizers (no vote, hours).** On an objective systemic-freeze trigger (Monetary Act §1.8), the RLP→SWF liquidity line opens automatically — the 5/20 + Central Council certification gates of §6.4 are pre-cleared by the trigger itself. The penalty price stays stable (reference rate + 1% to the RLP, + 2% to the SWF — it does not track the spiking interbank rate), while the quantity of liquidity flows freely. This is Bagehot done rules-style: lend freely, against good collateral, at a stable penalty rate.

**Accelerated forbearance.** Under a declared trigger, the surgical-jubilee logic (§5.4) may be fast-tracked by CLS for solvent co-ops facing a pure rollover crunch, preventing a liquidity event from converting sound co-ops into insolvencies. Eligibility standards are unchanged; only the timeline is accelerated.

**Tier 2 — emergency discretion (time-boxed).** For a genuinely novel systemic event no rule foresaw, a high-quorum emergency mode (Monetary Act §1.8) may be switched on, with hard sunsets and forced re-authorization on the Wartime-Fee pattern. Discretion is bounded in time, not eliminated.

---

## Appendix A: Key Stats (2025–2075)

| Metric | 2025 | 2075 |
|---|---|---|
| Credit Unions | ~5,000 (chartered by population/deposits; ≥3-catchment coverage; no fixed per-region count) | ~5,000 |
| Loans (total) | ~$452.5B | ~$1.2084T |
| Money-creation cap | 10% reserve (~10× multiplier) | same |
| Money-creation brake | CLS credit judgment | same |
| Reference rate | Flat-and-slow, rule-based (Monetary Act §1.5A) | same |
| BWC Purchasing Power Index | 100 (base) | published monthly |
| Banking Suite | ~$260.2B (see §4.1 note) | scaled |
| Wallets | ~$16.25B+ | scaled |
| Base Shares (residency-locked; carry the vote) | ~$94B | — |
| Special Shares (cumulative capital; uninsured equity) | ~$1.25T over 50 years | |
| Special-share market | National secondary market; 3-yr lock-up; standardized reference + 2% premium; 90–110% band; risk-priced | same |
| Special-share issuance | 30-day local-priority window at par → national remainder at par | same |
| Citizens' Metals ETF (investment, not backing) | $407–504B | |
| Physical Cash in Circulation | ~$4.67T (12% of GDP) | |
| Cash Metal Content (~5%, security + catastrophe floor) | ~$233B | |
| DLB Threshold (base) | $100 BWC | adjusted annually |
| CLS Officers | ~60,000 (avg ~12/CU, demand-distributed) | scales with demand |
| Micro-loans | $500 each | — |
| Board compensation (network) | ~$3–3.3B/year (~3% of revenue) | scaled |
| Revenue (credit union network) | ~$107.6B/year (see note) | — |
| FCLs (reference, per Monetary Act) | 195,100 | — |
| Deposit Insurance (voting) | $250,000 BWC | DLB-indexed |
| Deposit Insurance (non-voting) | $50,000 BWC | DLB-indexed |
| RLP target | 5–10% of regional deposits | same |
| Crisis stabilizer | Automatic RLP→SWF line on §1.8 trigger | same |
| Jubilee | Surgical, CLS-judged, up to 50% co-op debt | same |
| Data architecture | PPK + CED (no CWD) | PPK + CED |
| Backing ratio / BAR / DAI | Removed (fiat) | — |

*(Revenue line carried from prior drafts; the largest component, "reserve/ETF returns," should be re-derived under the fiat model — flagged for the consolidated fiscal pass.)*

---

## Appendix B: Recapitalization Summary

Loan growth from ~$452.5B to ~$1.2084T by 2075 rests on three streams:

| Stream | Annual Amount | Cumulative by 2075 | Purpose |
|---|---|---|---|
| Special Shares (1–2 series/year; uninsured equity; local-first then national) | $12.5–25B/year | $625B–$1.25T | Primary capital for loan expansion |
| SMSWF profits to credit unions | ~$1.736B/year | ~$87B | Secondary capital, dividend support |
| Citizens' Metals ETF & SWF returns | (reinvested) | (member savings + capital) | Member wealth & capital growth — not currency backing |

Special shares are the engine: each ~$12.5B series adds new lending capacity. At 2 series/year, the loan portfolio grows toward ~$1.2084T by 2075. (Per-region series sizing is re-derived off the actual catchment distribution — §1.5 — not a flat $2.5B × 250.)

---

## Appendix C: RLP & DIP Quick Reference (for CLS Agents & Credit Union Managers)

| Pool | Purpose | Funded by | Used when |
|---|---|---|---|
| RLP (Regional Liquidity Pool) | Short-term liquidity (cash flow) | 2% of deposits annually + 20% of patronage (half to RLP) | Reserves <10% of deposits; peer lending failed |
| DIP (Deposit Insurance Pool) | Solvency (pays depositors if a CU fails) | 10% of patronage (the other half) + 0.1% on BWC txns >$10k | Credit union insolvent (assets <80% of liabilities) |

**If a credit union needs help (normal path):** (1) borrow from peer credit unions first; (2) borrow from RLP (reference rate + 1%, 12 months); (3) if RLP exhausted → SWF backstop (5 Regional Boards certify + Central Council 6/11).

**If a systemic-freeze trigger is declared (crisis path, §6.8):** the SWF backstop opens automatically — certification pre-cleared by the trigger; penalty pricing (reference + 1% / + 2%) held stable while liquidity flows.

**If a credit union fails:** (1) DIP pays insured depositors within 30 days (up to $250k voting / $50k non-voting); (2) Regional Board liquidates assets; (3) proceeds return to DIP. **Special-share holders are uninsured equity and are not paid out by the DIP — they rank below depositors and absorb losses first.**

---

## Appendix D: Special Shares Quick Reference (member & investor capital)

| Item | Detail |
|---|---|
| What it is | Uninsured equity (capital), subordinate to all depositors; loss-absorbing |
| Dividend (yrs 1–3) | 7% / 6% / 5% step-down (paid for committing through the lock-up) |
| Dividend (yr 4+) | Reference rate + 2%, standardized & floating — every tradable share pays the same coupon |
| Lock-up | No secondary sale for 3 years from issue; redemption valve stays open |
| Primary issuance | 30-day local-priority window at par → national remainder at par |
| Secondary market | National (§3.3); transfer = register change, CU balance sheet untouched; 90–110% band, risk-priced |
| Redemption | Sell back to CU; $500/BWC/yr cap; reduces CU capital (the capped door) |
| Voting | Non-voting (member or investor); membership requires a residency-locked base share |
| Insurance | None — the premium is the compensation for being uninsured |
| Ownership disclosure | Member vs investor equity split published quarterly; no cap on outside ownership |

---

## Appendix E: BWC Purchasing Power Index (PPI) Quick Reference

*(Replaces the former DAI Quick Reference — DAI is retired under the fiat conversion.)*

| Item | Detail |
|---|---|
| What it is | Purchasing power of 1 BWC vs the DLB basket, base 100 (2025) |
| Published | Monthly, by Treasury; displayed on every wallet |
| Stable band | DLB movement within ~1–2%/year |
| If PPI falls (erosion) | Anchor price-condition tightens base issuance (Monetary §1.5) |
| If PPI rises (strengthening) | Anchor permits freer issuance to meet cash demand |
| Loan/deposit rates | Plain nominal, anchored to the reference rate (Monetary §1.5A); micro/service/informal set deliberately below it |

---

End of Draft 5.6
