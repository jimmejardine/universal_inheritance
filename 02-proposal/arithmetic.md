# The Balance Sheet: Is the Endowment Adequately Funded by the Receipts?

**Executive summary.** Not at launch, plausibly at maturity: on today's ~£104bn/yr transfer flow the tax nets an illustrative £10–25bn/yr (central ~£13–15bn, pessimistic tail below £10bn) against an endowment cost of £35–45bn/yr, while on the mid-2040s flow (>£230bn/yr) central scenarios reach ~£30–40bn — roughly covering the (smaller-cohort, wage-indexed) cost — and optimistic scenarios ~£60bn with clear surplus. This file is the single owner of the scheme's quantitative logic: every other file's revenue and cost figures reconcile to the tables below, and **every modelled number is illustrative pending the micro-simulation specified in §5**.

## Key findings

- The verified anchors: UK private wealth ~£13.6tn (stock) [3]; annual inheritance flow ≈£98bn (FYE 2020, 2021/22 prices) plus ≈£6bn/yr lifetime gifts ≈ **£104bn/yr** [1][2]; projected ~2.4× by the mid-2040s — **over £230bn/yr** [1]; ~890,000 residents aged 25 [5].
- Gross above-threshold flow (the 30–40% share inference, §1 note on softness): **~£31–42bn/yr today; ~£70–92bn/yr by the mid-2040s** (illustrative).
- Every above-threshold pound goes to exactly one destination — dispersal, charity, consumption, avoidance, or Treasury — so attrition channels are **composition shares that must sum to 100%**, not independent deductions. Earlier per-channel percentages elsewhere in the repo double-counted when read additively.
- Net receipts (illustrative): **launch decade ~£10–25bn/yr central-to-optimistic (pessimistic ~£3–8bn); mid-2040s maturity ~£25–60bn/yr (central ~£30–40bn, pessimistic ~£10–15bn)**. This supersedes the £40–70bn figure formerly carried in [endowment.md](endowment.md) §7, which mixed decades and omitted attrition.
- Verdict against the £35–45bn/yr cost: **the tax does not fully fund the endowment at launch under any scenario; central scenarios plausibly fund it at maturity (roughly at par to modest surplus), optimistic scenarios fund it with room; the crossover is ~15–20 years after Phase 3 launch** — which is exactly the length of the designed bridge ([`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md)).
- The single largest genuine uncertainty is **dispersal elasticity** — how aggressively estates split across recipients to stay under £500k each. It is also the intended behaviour: high dispersal means fiscal shortfall *and* structural success ([revenue-model.md](revenue-model.md) §8).
- Spousal transfers are untaxed between partners but an aggregate **deferral, not shrinkage** — now by construction: relieved corpus carries a deferred-charge tag ([carveouts.md](carveouts.md) §1) and re-enters the taxable flow at **exit from the marriage chain** (the survivor's death, or later if the survivor remarries — the tag rides along, so remarriage stretches timing without eroding the base). Likewise the 30-year business/farm instalments smooth receipts without reducing them (and add interest at gilts + 1%).

## 1. The stock and the flows: verified anchors

| Quantity | Value | Source / status |
|---|---|---|
| UK private household wealth (stock) | ~£13.6tn | ONS Wealth and Assets Survey, April 2020–March 2022 [3] — context only; the tax base is the flow, <1% of the stock per year |
| Annual inheritance flow (bequests) | ≈£98bn | Reported to HMRC, FYE 2020, in 2021/22 prices (Demos analysis) [1] |
| Annual lifetime gifts | ≈£6bn | Resolution Foundation estimate [2]; adopted here. The IFS puts gifts at ~20% of the inheritance flow (~£20bn) [7] — treated as upside to the base, not the planning figure |
| **Total transfer flow, today** | **≈£104bn/yr** | Sum of the two rows above |
| Projected flow, mid-2040s | **>£230bn/yr** (~2.4× the 2021 level, peaking ~2046) | Resolution Foundation projection via Demos [1] |
| Share of flow above £500k per recipient | **~30–40%** | Inference from IFS distributional work [4], as characterised in [thresholds.md](thresholds.md) §4/§6. **Soft:** no published series measures cumulative lifetime receipts per recipient; this is an order-of-magnitude reading of the shape of the wealth distribution, not a statistic. The micro-simulation (§5) exists to replace it |
| Residents aged 25 | 892,223 (mid-2024) | ONS mid-year estimates [5] |
| **Endowment cost, today** | **£35–45bn/yr** | ~890k × £50k ≈ £45bn; residence-eligibility rules ([endowment-delivery.md](endowment-delivery.md) §5) trim toward the ~700k UK-born cohort ≈ £35bn |
| Endowment cost, mid-2040s | ~£35–50bn/yr (illustrative) | The cohort turning 25 in the mid-2040s was born ~2020, when UK births were materially below today's cohort size (plausibly 15–20% smaller — **unverified here**, a §5 input); wage indexation pushes the per-head amount the other way |
| Current IHT take (comparator) | £7.5bn (2023–24), £8.25bn (2024–25) | HMRC receipts [6] |

## 2. The gross-to-net waterfall

### 2.1 Gross above-threshold flow

30–40% of £104bn ≈ **£31–42bn/yr today**; 30–40% of £230bn+ ≈ **£70–92bn/yr by the mid-2040s**. All downstream numbers inherit the §1 softness of the 30–40% share.

### 2.2 The waterfall, with named assumptions

| Step | Effect | Named assumption | Owner |
|---|---|---|---|
| Gross above-threshold flow | £31–42bn today; £70–92bn mid-2040s | 30–40% share (§1) | [thresholds.md](thresholds.md) §4, §6 |
| − Spousal transfers | **Timing shift only** — thins early-decade receipts by the average first-to-second-death gap (longer where the survivor remarries); no reduction of the mature base | Between partners the transfer is untaxed and consumes no threshold, but carries the deferred-charge tag of [carveouts.md](carveouts.md) §1; the wealth is taxed when it exits the marriage chain to a non-spouse, however many remarriages intervene. *Deferral of the generational base, not exemption from it — by construction* | [carveouts.md](carveouts.md) §1 |
| − Charitable redirection | −15% (opt) / −25% (central) / −30% (pess) of gross | Flow-weighted across the whole above-threshold base. Bequest price-elasticity estimates run from ≈−0.7 (Joulfaian) to ≈−2.1 (Bakija–Gale–Slemrod) [8][9]; at a 100% marginal rate the price of giving hits its floor, so the surge is near-certain in direction. [charitable-giving.md](../16-second-order/charitable-giving.md) §2's central 35–50% applies to the *largest* estates' above-threshold value; the flow-weighted average across all above-threshold receipts is taken lower | [`../16-second-order/charitable-giving.md`](../16-second-order/charitable-giving.md) |
| − Dispersal below threshold | −15% (opt) / −25% (central) / −40% (pess) of gross | **The intended behaviour and the biggest, least-evidenced number in the scheme.** A £2m estate split across four recipients pays nothing; at launch every ledger is empty, so dispersal headroom is at its maximum. No literature measures dispersal elasticity under a per-recipient lifetime threshold — Ireland's CAT is the nearest natural experiment (§5) | [thresholds.md](thresholds.md) §7 |
| − Extra lifetime consumption | −5–10% of gross | Late-life spend-down response | [`../16-second-order/savings-consumption.md`](../16-second-order/savings-consumption.md); [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) |
| − Avoidance / flight residual | −5–12% of gross (**tiered** — see the note below §2.3) | Bounded, not assumed away: migration elasticities are lowest at exactly the binding life-stage (late age, settled family, illiquid assets); the high-elasticity populations are young, internationally famous, thinly attached [10]. At the billionaire/£100m tiers elasticity reasoning is replaced by escape-completion scenarios | [avoidance.md](avoidance.md); [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md); [`../08-capital-flight/confiscatory-stakes.md`](../08-capital-flight/confiscatory-stakes.md) §3 |
| − Business/farm deferral | **No level effect** — smooths ~10–20% of receipts across 30 years and *adds* interest at gilts + 1% | Payment deferral, not relief ([carveouts.md](carveouts.md) §5–6); depresses early-decade cash receipts, raises later ones | [carveouts.md](carveouts.md) |
| **= Net receipts** | **See §3 scenario table** | Destination shares must sum to 100% (§2.3) | this file |

### 2.3 Destination shares — the composition constraint

Each above-threshold pound ends in exactly one place. The three scenarios (all illustrative):

| Destination of each above-threshold £1 | Optimistic | Central | Pessimistic |
|---|---|---|---|
| Dispersed to more recipients (below threshold) | 15% | 25% | 40% |
| Charitable redirection | 15% | 20% | 30% |
| Extra lifetime consumption | 5% | 10% | 10% |
| Avoidance / flight residual | 5% | 10% | 12% |
| **Treasury (net receipts)** | **60%** | **35%** | **8%** |

Two horizon adjustments, applied in §3: **at launch**, forestalling (pre-commencement transfers) and empty lifetime ledgers depress retention below these steady-state shares; **at maturity**, filled ledgers (each recipient's £500k headroom is consumed once per lifetime, so dispersal gets progressively less effective), the expired forestalling shadow, and deferral-interest income raise central retention by roughly +10 percentage points.

Note the asymmetry stressed in [revenue-model.md](revenue-model.md) §4: dispersal, charity, and consumption convert forgone revenue into policy-consistent outcomes; only the avoidance/flight residual is a genuine loss, and it is the channel attacked structurally rather than assumed away.

**The avoidance/flight residual is now tiered, not flat.** The undifferentiated 5–12% above conceals a composition claim that [`../08-capital-flight/confiscatory-stakes.md`](../08-capital-flight/confiscatory-stakes.md) §3 makes explicit: for the billionaire and £100m tiers, literature elasticities are rejected and the planning assumption is that most families *attempt* structured escape, with 30/50/70% full-completion scenarios; for the £500k–£10m mass of the base — most of the gross — flight is structurally unavailable and a 3–5%-of-gross avoidance residual applies. Tiered sensitivity (illustrative, from that file): 30% top-tier completion leaves this table's central case unchanged; 50% trims mature net receipts by ~£3–6bn/yr; 70% trims them by ~£5–9bn/yr, moving the mature verdict from "roughly at par" to "persistent gap of ~£5–15bn/yr against the mid-cost line". The flat 5–12% row above corresponds roughly to the 30–50% completion band and is retained as the planning range; the tier decomposition itself is a §5 micro-simulation output.

## 3. The verdict: three scenarios × two horizons

All figures illustrative, constant prices, pending §5 micro-simulation.

| Scenario | Net receipts, today's flow (£31–42bn gross) | Net receipts, mid-2040s flow (£70–92bn gross) | Against the cost (£35–45bn now; ~£35–50bn 2040s) |
|---|---|---|---|
| Pessimistic | ~£3–8bn | ~£10–15bn | Never fiscally self-funding; the policy still achieves its structural aim (dispersal *is* the point), but the endowment then needs a permanent co-funding decision |
| **Central** | **~£11–15bn** | **~£30–40bn** | **Not funded at launch (gap ~£20–30bn/yr); plausibly funded at maturity — roughly at par against the low-to-middle of the wage-indexed, smaller-cohort cost, with modest surplus in good years** |
| Optimistic | ~£20–25bn | ~£55–60bn | Not funded at launch (gap ~£10–20bn/yr); funded with clear surplus at maturity |

**Stated plainly: is the endowment adequately funded by the receipts?** *Not at launch on current flows — under any scenario. Plausibly yes at maturity: the central case roughly covers the mature cost and the optimistic case covers it with room. The crossover year — central estimate ~15–20 years after Phase 3 launch, i.e. the mid-2040s flow peak — is precisely the length of the designed bridge: the phased £35k-start escalator, Phase 2 reserve accumulation, and fund borrowing in* [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md) *are the engineered answer to exactly this gap, not a patch on it. The honest residual uncertainty is dispersal elasticity, which no existing dataset measures.*

Cross-check: [revenue-bridge.md](../15-transition/revenue-bridge.md)'s 20-year cashflow sketch (receipts £20–30bn in years 6–10 rising to £40–55bn in years 16–20) sits in the **central-to-optimistic** band of this table; on the pessimistic composition the bridge is longer and peak borrowing higher.

## 4. The National Endowment Fund balance sheet across the transition

The stock view of the same arithmetic — the fund architecture, borrowing logic, and year-by-year cashflow live in [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md) and are cross-referenced, not duplicated.

| | Item | Scale (illustrative) | Notes |
|---|---|---|---|
| **Assets** | Legislated receivable stream | PV of §3 receipts path | The fund's core collateral: hypothecated by statute, demographic (not cyclical) fundamentals |
| | Phase 2 accumulated reserve | £40–60bn at Phase 3 launch | Rising-schedule revenue banked for ~5 years before full endowment outlays begin |
| | State preferred-equity stakes (in-kind) | Grows with business/farm deferrals | Non-voting stakes taken in lieu of cash ([mechanism.md](mechanism.md) §4, [carveouts.md](carveouts.md) §5); held to maturity, plus deferral interest at gilts + 1% |
| **Liabilities** | Bridge borrowing | Peak ~£75–125bn cumulative (central; higher on the pessimistic path) | Secured on the receivable stream; serviced by future dynastic heirs, not future workers |
| | Annual endowment obligation | £43–45bn/yr full-rate (wage-indexed) | Or ~£31bn/yr at the £35k-start escalator variant |
| | Commencement taper (one-off) | ~£70–90bn spread over ~4 cohorts | [endowment-delivery.md](endowment-delivery.md) §6 |

The fund's solvency test is intertemporal, not annual: assets (reserve + receivable + stakes) against liabilities (borrowing + obligations) across the whole transition. On central assumptions the balance sheet closes — borrowing peaks and self-amortises as mature receipts arrive; on pessimistic assumptions it does not close without either the escalator staying at a lower amount or the sunset-dated supplements weighed in [revenue-bridge.md](../15-transition/revenue-bridge.md) (option F).

## 5. What would settle it: the micro-simulation

This is the single named research task that every quantitative flag in the repo resolves to — consolidating the "requires micro-simulation" markers in [thresholds.md](thresholds.md) §2–§4/§6, [revenue-model.md](revenue-model.md) §2, [revenue-bridge.md](../15-transition/revenue-bridge.md), [`../16-second-order/macro.md`](../16-second-order/macro.md) §7, and the [README](README.md) "what still needs doing" list.

**Data required:**

1. **HMRC estate data by estate size × beneficiary counts** — the joint distribution of estate value and number/relationship of recipients, to convert estate-level flow into per-recipient receipts.
2. **ONS Wealth and Assets Survey microdata** — the wealth distribution by age and household type, to project the composition of future estates.
3. **Mortality tables (ONS life tables) plus remarriage rates** — to time the flow: who dies when, and the gap between first death and exit from the marriage chain (the first-to-second-death interval, extended by widow(er) remarriage) that sizes the spousal deferral.
4. **Birth-cohort projections** — the denominator: cohort sizes turning 25 each year through the 2050s (sizes the cost line).
5. **Ireland CAT administrative data (if obtainable)** — the only operating per-recipient lifetime-threshold regime; the natural experiment for dispersal elasticity, the parameter nothing else measures.

**Outputs that replace this file's placeholders:** the share of flow above £500k per recipient (replacing the 30–40% inference); dispersal-elasticity bounds; the full receipts path with sensitivity bands; the crossover year; peak bridge borrowing; threshold-variant sensitivities (£250k/£750k/£1m, and the per-rung yields of the declined descending-ratchet variant in [thresholds.md](thresholds.md) §2); and the **tier decomposition of the above-threshold flow** — how much of the gross originates from >£700m, £100m–£700m, £10m–£100m, and sub-£10m estates, with situs-mobility composition per tier — the input that turns the tiered-flight scenarios of [`../08-capital-flight/confiscatory-stakes.md`](../08-capital-flight/confiscatory-stakes.md) §3 from illustration into estimate.

## 6. Honest limits

- **The 30–40% above-threshold share is the load-bearing soft number.** It is an inference from the shape of the wealth distribution, not a published statistic; everything downstream inherits its uncertainty.
- **Dispersal elasticity is unmeasured anywhere.** The pessimistic–optimistic spread (15–40% of gross) is judgement, not evidence.
- **Whether the £98bn flow nets out inter-spousal transfers is unverified.** If it does not, a slice of the gross base is timing-deferred rather than currently available, thinning early receipts further.
- **The gift base may be understated.** The RF £6bn figure is adopted; the IFS ~20%-of-flow estimate would raise the base ~£14bn/yr [7].
- **The 2040s cost line is doubly uncertain**: smaller cohorts cut it, wage indexation raises it, and residence-eligibility rules move it by ±£10bn/yr today.
- **All scenario compositions are illustrative pending §5.** They are constrained to sum to 100% and calibrated to be consistent with the per-channel evidence cited, but they are planning numbers, not forecasts.

## Sources

1. [Demos — Goss and Glover, *A New Age of Inheritance* (2023)](https://demos.co.uk/research/a-new-age-of-inheritance-what-does-it-mean-for-the-uk/) — inheritances £98bn in FYE 2020 (2021/22 prices); projected to peak around 2046 at ~2.4× the 2021 value, over £230bn/yr.
2. [Leslie, J. and Shah, K. (2022). *Intergenerational rapport fair?* — Resolution Foundation](https://www.resolutionfoundation.org/app/uploads/2022/02/Intergenerational-rapport-fair.pdf) — ≈£6bn/yr lifetime-gift estimate.
3. [ONS — Privately owned wealth in the UK (Wealth and Assets Survey, April 2020 to March 2022)](https://www.ons.gov.uk/aboutus/transparencyandgovernance/privatelyownedwealthintheuk) — household wealth ~£13.6tn.
4. [IFS — Bourquin, Joyce and Sturrock, *Inheritances and inequality over the life cycle* (2021)](https://ifs.org.uk/publications/inheritances-and-inequality-over-life-cycle-what-will-they-mean-younger-generations) — projected lifetime receipt distributions for the 1980s-born.
5. [ONS — Population estimates for the UK, mid-year](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates) — mid-2024: 892,223 residents aged 25.
6. [HMRC — Inheritance Tax liabilities statistics](https://www.gov.uk/government/statistics/inheritance-tax-liabilities-statistics) — receipts £7.50bn (2023–24), £8.25bn (2024–25).
7. [IFS Green Budget 2023 — Advani and Sturrock, "Reforming inheritance tax"](https://ifs.org.uk/publications/reforming-inheritance-tax) — annual gift flow ≈ 20% of the inheritance flow.
8. [Joulfaian, D. — "Estate Taxes and Charitable Bequests by the Wealthy," NBER Working Paper 7663 (2000)](https://www.nber.org/papers/w7663) — bequest price elasticity ≈ −0.7.
9. [Bakija, J., Gale, W. & Slemrod, J. — "Charitable Bequests and Taxes on Inheritance and Estates," NBER Working Paper 9661 (2003)](https://www.nber.org/papers/w9661) — elasticity ≈ −2.1.
10. [Kleven, H., Landais, C., Muñoz, M. & Stantcheva, S. — "Taxation and Migration: Evidence and Policy Implications," *JEP* 34(2), 2020](https://www.aeaweb.org/articles?id=10.1257/jep.34.2.119) — tax-driven mobility concentrated in specific highly mobile groups.
