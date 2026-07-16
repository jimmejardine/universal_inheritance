# Revenue Model

**Executive summary.** The fiscal arithmetic of the proposal is presented here without varnish: at current UK inheritance-and-gift flows of roughly £104bn a year [10], a £500k-per-recipient lifetime threshold yields a pre-behavioural gross base of perhaps £31–42bn a year, which behavioural attrition — dispersal, charitable diversion, consumption, avoidance, and payment deferral — plausibly cuts to £10–25bn in early steady state, against an endowment cost of ~£35–45bn a year (consolidated waterfall, scenarios, and funding verdict: [arithmetic.md](arithmetic.md)). The gap is real, it is bridgeable ([`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md)), and — crucially — it is not the test of the policy's success: the dynastic break occurs whether the money arrives as revenue or dissolves as dispersal.

## Key findings

- UK aggregate annual inheritance flow is ~£100bn — inheritances reported to HMRC reached £98bn in 2019–20 (in 2021–22 prices), having doubled in real terms roughly every twenty years since 1979 — and is projected to double again by the 2040s (Resolution Foundation projection, via Demos) [10]. Gift flows on top of bequests are poorly measured — HMRC observes only gifts made within seven years of death — and add roughly a further 20% on the IFS's estimate [2].
- IFS distributional work implies ~30–40% of the aggregate flow sits above £500k per recipient — an illustrative order-of-magnitude inference from the shape of the wealth distribution, not a published statistic (see §2 and [`thresholds.md`](thresholds.md) §4) [1].
- Behavioural attrition is large by design: every pound the tax "loses" to wider dispersal or charitable giving is the policy working, not failing (§4).
- The universal endowment costs ~£35–45bn/year in the UK (illustrative: ~890,000 residents aged 25 at the ONS mid-2024 count [3] × £50,000 = ~£45bn; residence-eligibility rules would trim the cohort toward the ~700,000 UK-born) and ~$270bn/year in the US (illustrative: ~4.5m aged 25 in July 2024 [4] × $60,000).
- Existing UK IHT raised £7.5bn in 2023–24 and £8.2bn in 2024–25 (HMRC receipts) [5]; the central £10–25bn net range is roughly 1.5–3× that, though the pessimistic tail in [arithmetic.md](arithmetic.md) §3 falls back toward parity.
- Early years run a funding deficit; mature years (2040s flows) plausibly run a surplus. The bridge options are set out in [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md).
- Politically, the number that matters is "is my endowment funded?"; structurally, the number that matters is the share of dynastic wealth that fails to reach a single concentrated heir — which rises even as measured revenue falls (§8; [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md)).

## 1. The flow: what passes each year

The tax base is the annual flow of gratuitous transfers — bequests plus inter-vivos gifts — not the stock of wealth. UK anchors:

| Quantity | Estimate | Status |
|---|---|---|
| Annual UK inheritance flow (bequests) | ~£100bn | £98bn reported to HMRC in 2019–20, in 2021–22 prices (Demos analysis of HMRC data) [10] |
| Projected flow, mid-2040s | >£230bn (real) | The flow has doubled every ~20 years since 1979 and is projected to reach ~2.4× its 2021 level, peaking around 2046 (Resolution Foundation, via Demos) [10]; driven by baby-boomer housing and pension wealth |
| Annual inter-vivos gift flow | ~20% of the inheritance flow | HMRC only observes gifts that fail the 7-year rule; the IFS estimates the annual gift flow at around 20% of the inheritance flow [2] |
| Existing IHT take | £7.5bn (2023–24); £8.2bn (2024–25) | HMRC receipts [5] |
| Effective rate of current IHT on the flow | ~7–8% | Illustrative division of the two rows above |

The last row is the headline indictment of the status quo: a nominally 40% tax collects an effective single-digit share of the flow, because reliefs, exemptions, and planning hollow it out — the incidence pattern that [`avoidance.md`](avoidance.md) is designed to invert.

## 2. Share above the threshold — order-of-magnitude reasoning

No published series measures cumulative lifetime receipts per recipient, so this is inference, clearly labelled **illustrative** throughout. The reasoning: inheritance flows inherit the shape of the wealth distribution they drain, and UK wealth is heavily top-concentrated (the top 10% of households held ~43% of wealth in April 2018–March 2020 — ONS WAS [6]). IFS projections of lifetime receipts imply a quarter of those born in the 1980s will inherit more than £280k, while a fifth will inherit less than £10k [1], and estates above £1m — a small percent of deaths — account for a disproportionate share of the aggregate flow. Chaining these:

- If the top ~5% of recipients receive ~40–50% of the flow (consistent with the US finding that the top 1% of heirs receive over 40% [7]), and
- the £500k threshold exempts the first £500k *of each of them*,

then the taxable slice is plausibly **30–40% of the aggregate flow**, i.e. **£31–42bn/year gross at current flows, £70–92bn at mid-2040s flows** (illustrative). [`thresholds.md`](thresholds.md) §6 tabulates the sensitivity to other thresholds. Proper micro-simulation on cumulative lifetime receipts remains the top item in the [README's](README.md) "what still needs doing" list; the consolidated spec is [arithmetic.md](arithmetic.md) §5.

## 3. Gross-to-net waterfall

| Step | Effect on base (illustrative) | Note |
|---|---|---|
| Pre-behavioural gross base | £31–42bn/yr | §2 |
| Spousal relief timing | defers a large minority of the base ~10 yrs | Tax arrives when wealth exits the marriage chain — at second death, or later where the survivor remarries and the deferred-charge tag rides along; a delay, not a loss ([`carveouts.md`](carveouts.md) §1) |
| Distributive estate planning | −15–40% of gross | Splitting estates across more recipients is the *intended* response ([`thresholds.md`](thresholds.md) §7) |
| Charitable diversion | −15–30% of gross | Flow-weighted from the [`../16-second-order/charitable-giving.md`](../16-second-order/charitable-giving.md) §2 scenarios; see sensitivity §4 |
| Lifetime consumption response | −5–10% of gross | [`../16-second-order/savings-consumption.md`](../16-second-order/savings-consumption.md); [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) |
| Avoidance and flight residual | −5–12% of gross | After the [`avoidance.md`](avoidance.md) spine; evidence base in [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md) |
| Business/farm deferral | smooths ~10–20% of receipts over 30 yrs | Cash-flow timing, plus interest income ([`carveouts.md`](carveouts.md) §5–6) |
| **Net near-term steady state** | **~£10–25bn/yr** | Central planning range; pessimistic tail ~£3–8bn |
| **Net at mid-2040s flows** | **~£25–60bn/yr** | Central ~£30–40bn; pessimistic ~£10–15bn |

The channels above compete for the same above-threshold pound, so the percentages are not additive: [arithmetic.md](arithmetic.md) §2.3 states them as destination shares constrained to sum to 100%, and is the single owner of the scenario compositions and net ranges.

**Reconciling the repo's own spread.** The consolidated waterfall, scenario table, and funding verdict now live in [arithmetic.md](arithmetic.md), to which this file's ranges are aligned. The earlier spread — [`thresholds.md`](thresholds.md) §4's £10–25bn against a £40–70bn figure formerly in [`endowment.md`](endowment.md) §7 — arose almost entirely from (a) which decade's flow was assumed and (b) how much behavioural attrition was loaded in; both files now state both horizons explicitly. Planning should be done on the conservative number; that discipline is itself a defence against the over-promising that invites later sabotage ([`constitutional-design.md`](constitutional-design.md)).

## 4. Behavioural attrition — sensitivity lines

Each channel, with its sensitivity to being wrong (all illustrative, on a £35bn gross base at current flows):

| Channel | Assumption ([arithmetic.md](arithmetic.md) §2.3 scenario spans) | Sensitivity |
|---|---|---|
| Dispersal to more recipients | 15–40% of gross | Each additional 10pp of dispersal removes ~£3.5bn/yr — and disperses ~£3.5bn of dynastic wealth, the policy goal |
| Charitable diversion | 15–30% | Each 10pp diverted removes ~£3.5bn/yr from revenue and adds it to the charitable sector; anti-cycling rules in [`carveouts.md`](carveouts.md) §4 keep it genuinely public-benefit |
| Consumption ("spend it all") | 5–10% | Each 10pp removes ~£3.5bn/yr and returns it to the economy as demand, partly recouped via VAT/income tax (recoupment share unverified); see [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) |
| Avoidance/flight residual | 5–12% | Most damaging channel per pound because it is regressive; the entire [`avoidance.md`](avoidance.md) spine and [`../08-capital-flight/`](../08-capital-flight/) section exist to hold this down |

Note the asymmetry: three of the four channels convert forgone revenue into policy-consistent outcomes. Only the fourth is a genuine loss, and it is the one attacked structurally rather than assumed away.

## 5. What the endowment costs

- **UK:** ~890,000 residents aged 25 (ONS mid-2024 estimate: 892,000) [3] × £50,000 = **~£45bn/year** (illustrative; the residence-eligible cohort under the rules in [`endowment-delivery.md`](endowment-delivery.md) §5 would be smaller — late-1990s UK birth cohorts were ~700,000 — so **£35–45bn** brackets the cost).
- **US:** ~4.5m residents aged 25 (Census, July 2024: 4.47m) [4] × $60,000 = **~$270bn/year** (illustrative).

Against the §3 ranges: the UK endowment is *not fully funded* by the tax in the early years (£10–25bn vs £35–45bn) and *plausibly funded* at mature flows (£25–60bn vs a wage-indexed, smaller-cohort cost — the full verdict table is [arithmetic.md](arithmetic.md) §3). The honest formulation: **the tax funds the endowment across the transition on average, not in every year.** Bridge instruments — phased grant ramp-up, pre-funding the National Endowment Fund before first payout, general-revenue top-up, borrowing against the rising flow — are specified in [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md), and the fund architecture that smooths across years is in [`constitutional-design.md`](constitutional-design.md) §3.

## 6. US parallel sketch

All figures illustrative except the cited anchors. The US "great wealth transfer" literature projected $84tn passing between 2021 and 2045 ([Cerulli, 2022](https://www.cerulli.com/press-releases/cerulli-anticipates-84-trillion-in-wealth-transfers-through-2045)), revised in December 2024 to [$124tn through 2048](https://www.cerulli.com/press-releases/cerulli-anticipates-124-trillion-in-wealth-will-transfer-through-2048), of which ~$105tn goes to heirs — i.e. roughly **$4–5tn/year** and rising. Federal estate and gift tax currently collects ~$32–34bn/year ($32bn in FY2023) [8] — an effective rate on the flow of ~1%, even more hollowed-out than the UK's. With US wealth concentration steeper than the UK's (top 1% hold 30%+ of household wealth, Federal Reserve DFA, 2024 [9]), the share of flow above $750k per recipient is plausibly **40–50%**, giving a pre-behavioural gross of $1.2–2tn/year and, applying the §3 attrition structure, a net perhaps in the **$500bn–1tn/year** range — comfortably above the ~$270bn endowment cost, reflecting the sheer top-heaviness of US wealth. These are order-of-magnitude sketches pending JCT/CBO-grade modelling.

## 7. Comparison with the existing take

| Measure | Current UK IHT | This proposal (near-term) | This proposal (2040s flows) |
|---|---|---|---|
| Revenue | £7.5–8.2bn (2023–24 to 2024–25) [5] | ~£10–25bn (illustrative) | ~£25–60bn (illustrative) |
| Effective rate on aggregate flow | ~7–8% | ~15–25% | ~15–25% |
| Share of estates/recipients affected | 4.62% of deaths (2022–23) [5] | ~3–7% of recipients ([`thresholds.md`](thresholds.md)) | similar |
| Incidence above threshold | Inversely correlated with wealth (reliefs) | Flat 100% by construction | same |

The proposal's revenue gain over current IHT is real but modest relative to total taxation (~1–2% of UK tax receipts). Anyone selling this policy primarily as a revenue measure is mis-selling it.

## 8. Which number matters

Two different success criteria, and the distinction should be stated plainly rather than blurred:

1. **Politically**, the binding number is whether every 25-year-old's endowment is paid in full, on time, every year. That is what sustains the stakeholder coalition described in [`endowment.md`](endowment.md) §8 and [`constitutional-design.md`](constitutional-design.md) §6. The fund-smoothing and bridge architecture exist to make this number robust to revenue volatility.
2. **Structurally**, the binding number is the share of large fortunes that fails to arrive intact in a single heir's hands. This number *improves* under dispersal, charitable diversion, and consumption — the very responses that depress revenue. A future headline that "the 100% inheritance tax is raising less than forecast" is compatible with the policy succeeding completely; the pre-emptive answer is written at [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) and should be part of the communications toolkit from day one ([`../14-communications/debate-toolkit.md`](../14-communications/debate-toolkit.md)).

## Sources

1. [IFS — Bourquin, Joyce and Sturrock, *Inheritances and inequality over the life cycle* (2021)](https://ifs.org.uk/publications/inheritances-and-inequality-over-life-cycle-what-will-they-mean-younger-generations) — projected lifetime receipt distributions for the 1980s-born.
2. [IFS Green Budget 2023 — Advani and Sturrock, "Reforming inheritance tax"](https://ifs.org.uk/publications/reforming-inheritance-tax) — annual gift flow ≈ 20% of the inheritance flow (citing Boileau and Sturrock, 2023); only gifts within seven years of death are observed by HMRC.
3. [ONS — Population estimates for the UK, mid-year](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates) — mid-2024: 892,223 residents aged 25 (single year of age, UK).
4. [US Census Bureau — National Population by Characteristics](https://www.census.gov/data/tables/time-series/demo/popest/2020s-national-detail.html) — NC-EST2024: 4,466,652 residents aged 25 at 1 July 2024.
5. [HMRC — Inheritance Tax liabilities statistics](https://www.gov.uk/government/statistics/inheritance-tax-liabilities-statistics) — 4.62% of UK deaths in 2022–23 resulted in an IHT charge; receipts £7.50bn (2023–24) and £8.25bn (2024–25).
6. [ONS — Household total wealth in Great Britain: April 2018 to March 2020](https://www.ons.gov.uk/peoplepopulationandcommunity/personalandhouseholdfinances/incomeandwealth/bulletins/totalwealthingreatbritain/april2018tomarch2020) — wealthiest 10% of households held 43% of all wealth.
7. [Federal Reserve — Survey of Consumer Finances, intergenerational transfer module](https://www.federalreserve.gov/econres/scfindex.htm).
8. [Congressional Research Service — *The Estate and Gift Tax: An Overview* (R48183, 2025)](https://www.congress.gov/crs-product/R48183) — FY2023 receipts $32bn, 0.7% of federal revenues.
9. [Federal Reserve — Distributional Financial Accounts](https://www.federalreserve.gov/releases/z1/dataviz/dfa/) — top 1% share of household net worth, ~30–31% through 2024.
10. [Demos — Goss and Glover, *A New Age of Inheritance* (2023)](https://demos.co.uk/research/a-new-age-of-inheritance-what-does-it-mean-for-the-uk/) — HMRC-reported inheritances rose (2021–22 prices) from £24bn (1979) to £48bn (1999) to £98bn (2019–20); Resolution Foundation-based projection of doubling again in England by 2040.
