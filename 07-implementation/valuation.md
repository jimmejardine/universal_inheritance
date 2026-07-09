# Valuation

**Executive summary.** Every wealth-transfer tax in history has been litigated, gamed, and in two documented cases constitutionally struck down over *valuation*, not rates — the number on which a 100% marginal charge turns is worth fighting over precisely because the marginal rate is 100%. This file sets out an asset-class-by-asset-class valuation regime, confronts the appraisal-industry capture problem directly, and specifies an audit architecture ("the valuation lottery") designed so that aggressive undervaluation is negative expected-value even when most returns are never examined.

## Why valuation is the binding constraint

At a 40% rate, shaving 25% off a declared value saves the taxpayer 10p in the pound; at a 100% marginal rate it saves 25p. The incentive to undervalue scales with the rate, so the regime defined in [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §4 needs valuation machinery stronger than anything the UK or US currently operates. The historical warnings are specific: Austria's inheritance tax was struck down in 2007 largely because frozen cadastral values (*Einheitswerte*) made the effective rate arbitrary between asset classes [1], and US Tax Court dockets show decades of minority-discount stacking in family entities (see §5). The design principle throughout: **the taxpayer proposes, the state can verify, and the consequences of being caught proposing badly are severe and public.**

## Regime by asset class

| Asset class | Method | Verification | Known failure mode addressed |
|---|---|---|---|
| Listed securities | Mark-to-market, 5-day average around tax point | Automatic (market data) | None material |
| Cash, deposits | Face value | Bank reporting | None |
| Real estate | RICS Red Book (UK) / USPAP-certified (US) appraisal; rebuttable presumption | HMRC/IRS re-appraisal right, 24 months | Frozen or stale values (Austrian *Einheitswerte*) [1] |
| Private business | Statutory methodology (DCF + comparables); mandatory state review above £2m/$3m | District Valuer / IRS Engineering & Valuation programme | Discount stacking, sham "trading" recharacterisation |
| Art, collectibles | Registered-appraiser valuation cross-checked against insurance schedules and auction databases | Sampling audit of top decile of declared values | Insurance value ≫ declared probate value |
| Crypto and digital | Regulated-exchange reference price at tax point | Chain analysis, exchange reporting — see [digital-and-novel-assets.md](digital-and-novel-assets.md) | "Lost key" claims |
| IP / royalty streams | PV of projected cash flows at gilts + 3%; 5-year true-up | Re-assessment at each payment event | Systematic low-balling of projections |

## 1. Listed assets: the easy fifth

Mark-to-market with a short averaging window is mechanical and dispute-free. The design lesson is to *push as much of the base as possible toward this category*: the instalment and state-equity options below deliberately make it more attractive to hold inherited wealth in transparent, priced form than in opaque wrappers.

## 2. Private businesses: appraisal, instalments, and the state-equity backstop

Private operating companies are the hardest case and the historically decisive one (German business-relief valuation was central to the 2014 constitutional strike-down [2]). Three instruments work together:

1. **Statutory appraisal methodology.** A single prescribed framework — discounted cash flow cross-checked against transaction multiples — removes the current free choice among methods that lets appraisers span a 2–3x range for the same firm. Appraisals above £2m / $3m go to mandatory pre-assessment review.
2. **Earn-out / instalment settlement.** Where value is genuinely uncertain, the liability can be settled as a percentage of realised proceeds on eventual sale, or via the 30-year instalment route in [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §5. This converts a valuation dispute into a wait-and-see: the state gets paid on the *actual* value, not the argued one.
3. **State equity in lieu.** The heir may tender a non-voting preferred stake equal to the disputed liability. This is the elegant closure of the valuation game: if the heir claims the business is worth little, the state's stake is correspondingly cheap for the heir to give up; if the heir resists giving equity, that is itself evidence the declared value is low. Undervaluation stops being free. Sweden's brief experiment with accepting shares in payment, and France's *dation en paiement* for art, are partial precedents [3].

## 3. Real estate

Independent professional appraisal creating a rebuttable presumption, per [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md). Two additions for operational robustness: (a) **automatic comparison against transaction registers** — Land Registry price-paid data (UK) and county recorder data (US) allow algorithmic flagging of appraisals materially below hedonic-model predictions; (b) **post-sale true-up** — if the property sells within 3 years of receipt for more than 120% of declared value, the difference is reassessed as an additional receipt, with penalties where the gap is unexplained. The true-up removes the incentive to appraise low and flip quickly.

## 4. Art and collectibles: the insurance cross-check

Art valuation is famously soft, but owners betray their true beliefs in two documents: **insurance schedules** and **loan collateral valuations**, both of which owners want *high*. The regime requires disclosure of any insurance or collateral valuation obtained within the preceding 5 years; a declared receipt value materially below the owner-procured insurance value shifts the burden of proof to the taxpayer. Auction-house databases and the registries maintained for the conditional-exemption scheme ([`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §7) supply comparables. This is cheap enforcement: it uses numbers the wealthy generate for their own purposes.

## 5. The minority/marketability discount problem

US estate-tax practice built an industry around fragmenting assets into family limited partnerships so each heir receives a "minority interest" appraised at 30–50% below pro-rata net asset value (discount stacking litigated in cases such as *Estate of Elkins* [4]). Under a recipient-based tax the pressure is worse — donors can deliberately fragment to manufacture discounts for every recipient. The response, committed in [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §6, is statutory caps (10% minority, 15% marketability) plus an **anti-fragmentation rule**: where related recipients together receive interests that would carry control, each is valued at pro-rata value of the controlling block, mirroring the aggregation logic HMRC already applies to related-property under IHTA 1984 s.161 [5].

## 6. Appraisal-industry capture

Appraisers are hired by the taxpayer, want repeat business, and face asymmetric consequences — a documented dynamic in US valuation practice [6]. Countermeasures:

- **Licensing with skin in the game.** Statutory register of transfer-tax appraisers; an appraiser whose valuations are revised upward by more than 25% in more than a set fraction of audited cases loses the licence. (Precedent: IRC §6695A appraiser penalties, currently weak because rarely applied [6].)
- **Blind second appraisals.** For receipts above the mandatory-review threshold, the revenue authority commissions its own appraisal *before* seeing the taxpayer's; material divergence triggers a structured reconciliation, not a negotiation from the taxpayer's anchor.
- **Publication of anonymised outcomes.** Aggregate revision statistics by appraisal firm are published annually — reputational discipline that firm-level insurance markets will price.

## 7. Self-assessment vs pre-clearance

Pure self-assessment (the UK income-tax model) is cheap but invites gaming at a 100% rate; universal pre-clearance (every receipt valued by the state before title passes) would gum up probate. The regime splits the difference:

| Tier | Receipts | Treatment |
|---|---|---|
| 1 | Below threshold headroom, liquid assets | Self-assessed; automated plausibility checks only |
| 2 | Crossing the threshold, standard assets | Self-assessed with professional appraisal; audit lottery (§8) |
| 3 | Above £2m / $3m, or any private-business / art receipt above threshold | Mandatory pre-assessment review before probate closes |

An optional **binding pre-clearance ruling** is available at any tier for a fee — taxpayers who want certainty can buy it, and the ruling binds both sides. Ireland's Revenue opinion procedure for CAT is the working analogue [7].

## 8. The valuation lottery: audit design

No tax authority can audit every return; the goal is that undervaluation is negative-EV *ex ante*. Components:

- **Risk-scored selection** (opaque model: asset mix, appraiser history, gap vs algorithmic estimate) plus a **pure random component** so no return is safely below the radar — the random layer is what makes the lottery a lottery.
- **Penalty gradient tied to the size of the miss:** revisions under 10% are treated as good-faith; 10–25% attracts the tax plus 30%; over 25% attracts the tax plus 100% and appraiser referral; fraudulent valuation goes to the criminal track in [enforcement.md](enforcement.md).
- **No limitation period for concealed assets** (see [enforcement.md](enforcement.md)) — an undervaluation that depends on the state never noticing has no safe harbour date.

The arithmetic to communicate publicly: with even a 1-in-10 audit chance and a 100%-of-tax penalty, undervaluing by 25% has negative expected value for any risk-neutral taxpayer, and the wealthy are advised by professionals who cannot afford licence risk. Exact audit-rate and penalty calibration needs modelling (to verify against HMRC/IRS compliance-yield data).

## Research gaps

- Empirical distribution of appraisal error in UK probate valuations (District Valuer revision statistics — request via FOI).
- Whether the state-equity option needs a floor holding period to prevent immediate low-ball buy-backs.
- Cost of mandatory Tier-3 review at realistic caseloads (link [administration.md](administration.md)).

## Sources

1. [Verfassungsgerichtshof Österreich — G 54/06 (2007), inheritance tax struck down over *Einheitswerte*](https://www.vfgh.gv.at/)
2. [Bundesverfassungsgericht — 1 BvL 21/12 (17 Dec 2014)](https://www.bundesverfassungsgericht.de/SharedDocs/Entscheidungen/EN/2014/12/ls20141217_1bvl002112en.html)
3. [Henrekson & Waldenström (2014), *Inheritance Taxation in Sweden, 1885–2004*, IFN WP 1032](https://www.ifn.se/wfiles/wp/wp1032.pdf); French *dation en paiement* (Code général des impôts, art. 1716 bis).
4. [*Estate of Elkins v. Commissioner*, 767 F.3d 443 (5th Cir. 2014)](https://www.courtlistener.com/opinion/2680533/estate-of-elkins-v-commr/)
5. [HMRC — IHTM09731: related property (IHTA 1984 s.161)](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm09731)
6. [US IRC §6695A — appraiser penalties](https://www.law.cornell.edu/uscode/text/26/6695A); GAO and TIGTA reviews of IRS appraisal enforcement.
7. [Irish Revenue — opinions and confirmations procedure](https://www.revenue.ie/en/tax-professionals/tdm/income-tax-capital-gains-tax-corporation-tax/part-37/37-00-40.pdf)
