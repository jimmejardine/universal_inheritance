# The Revenue Bridge: Funding the Endowment Before the Tax Matures

**Executive summary.** The scheme has a built-in timing mismatch: if every 25-year-old is paid from year one, outlays begin at full scale immediately, while 100%-rate revenue matures only as deaths occur and lifetime ledgers fill — a process measured in decades. The bridge is a package, not a single instrument: a phased endowment amount, transitional revenue from the Phase 2 schedule, and debt finance through a sovereign endowment fund secured on the legislated future receipt stream.

## The mismatch stated precisely

**Outlays are demographic and immediate.** A UK cohort at age 25 is roughly 850,000–900,000 people — the UK population aged 25–29 was ≈4.45 million in 2024, about 890,000 per single year of age [2]. At £50,000 each, a full-rate universal endowment costs on the order of **£43–45bn per year from the first year** it is paid universally — comparable to a major department's budget (all figures in this file are illustrative and marked for micro-simulation; see [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)).

**Revenue is actuarial and slow.** Three lags stack:

1. **Deaths are slow.** The tax's largest receipts arrive at death, and the wealth-holding generation dies over 30–40 years, not at commencement.
2. **Cumulation starts near zero.** Lifetime ledgers begin (largely) empty at commencement; most recipients spend years consuming threshold headroom before any receipt crosses into the 100% band. Early-year effective yield is therefore *below* the mature rate even on the deaths that do occur.
3. **Forestalling thins the early base.** Pre-commencement transfers outside the lookback window ([announcement-effects.md](announcement-effects.md)) reduce early-decade taxable receipts; this leakage is one-generation-only but is concentrated exactly in the bridge period.

Mature-state annual revenue is plausibly of the same order as the endowment cost — UK annual inherited-and-gifted flows are estimated at just over £100 billion (inheritances ≈£98bn in 2019–20 plus lifetime gifts ≈£6bn a year, with inheritances projected to reach roughly 2.4× their 2021 level by the mid-2040s — over £230bn a year) [7], with the share above £500k-per-recipient to be established by micro-simulation ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)) — but maturity is 20+ years out. The bridge covers the gap.

## Bridge options

| Option | Mechanism | Pros | Cons |
|---|---|---|---|
| A. Phase in the amount | Endowment starts at e.g. £10k and rises with revenue on a legislated escalator | Outlays track receipts; no debt | Early cohorts get less; weakens launch impact and the constituency effect ([pilots.md](pilots.md)) |
| B. Cohort-partial start | Full £50k, but initially only to (say) those turning 25 from a named birth-year forward, or in pilot regions scaling nationally | Full-value demonstrations; controllable cost | Arbitrary cohort boundary is a fairness attack surface ([`../09-objections/fairness.md`](../09-objections/fairness.md)) |
| C. Debt finance via sovereign fund | An endowment fund borrows against the hypothecated, legislated future receipt stream; pays full endowment from year one | Full launch; intergenerationally coherent (see below) | Adds gross debt in-window; fiscal-rule collision ([legislative-path-uk.md](legislative-path-uk.md)); rate risk |
| D. Transitional lower-threshold / schedule revenue | Phase 2's rising schedule (and its lower effective starting threshold on large receipts) runs for the first bridge decade before the pure 0/100 kink | Revenue arrives a decade early; already implied by sequencing ([sequencing.md](sequencing.md)) | Delays the clean end-state design |
| E. General-revenue top-up | Treasury covers early shortfall as ordinary spending | Simple | Breaks the hypothecation story that is the scheme's core political defence ([`../05-history/abolitions.md`](../05-history/abolitions.md), error #6) |
| F. Transitional minimum effective tax on the largest fortunes | A Zucman-style 2%-of-wealth floor on centimillionaires' effective taxation, run for the bridge period only and sunsetting as 100%-rate receipts mature — ~£15bn/yr on Zucman's UK estimate [8] | Bites *now*, on exactly the living concentrations the transfer tax must wait for; internationally pre-tested (G20 blueprint 2024; French National Assembly vote, Feb 2025); hits the same ~200-family UK population whose transmission the regime later caps | Imports the annual form's valuation and flight frictions for its duration; must be visibly time-limited or it destroys the "owner never gets a bill" retention proposition ([`../03-case-for/wealth-tax-comparison.md`](../03-case-for/wealth-tax-comparison.md) §5) |

**Recommended package: D + C + a bounded element of A.** Phase 2 schedule revenue flows into the fund for a decade before the endowment launches at full rate; the fund borrows to smooth the residual gap; if micro-simulation shows the gap still excessive, the launch amount starts at (say) £35k on a fast statutory escalator to £50k rather than delaying launch. Option E is excluded on principle; Option B is retained only in its pilot form ([pilots.md](pilots.md)). Option F is the credible *external* supplement if the financed gap proves excessive — a sunset-dated Zucman floor closes most of a £13–25bn annual gap on its own — but it is weighed, not adopted: the retention-proposition and hybrid-bundling cautions of [`../03-case-for/wealth-tax-comparison.md`](../03-case-for/wealth-tax-comparison.md) §§5–6 apply in full, and its statutory sunset must be tied to the same escalator that matures the 100% rate.

## The endowment fund as a sovereign vehicle

Structuring the bridge through a statutory **National Endowment Fund** rather than the general Exchequer does four jobs:

- **Hypothecation made structural.** Receipts are paid into the fund by law; endowments are paid out of it; the annual accounts make the tax's purpose visible — the anti-abolition architecture of [`../02-proposal/endowment.md`](../02-proposal/endowment.md) given institutional form.
- **A borrower with collateral.** The fund issues debt (or receives an on-lent Treasury facility) secured on a legislated receipt stream with demographic — not cyclical — fundamentals. The analogy is infrastructure finance against a regulated revenue stream, not deficit spending.
- **Classification and fiscal rules.** A fund holding a legislated receivable and, in some cases, assets in kind (the state-equity stakes taken from illiquid business receipts, [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §4, live here and are managed to maturity) has a defensible claim to capital rather than current treatment; the ONS/OBR classification battle is anticipated in [legislative-path-uk.md](legislative-path-uk.md).
- **Insulation from raid and from sabotage.** Statutory ring-fencing raises the legislative cost of a future government quietly diverting receipts or starving the endowment — the post-passage attack surface mapped in [`../10-opposition/sabotage-after-passage.md`](../10-opposition/sabotage-after-passage.md).

**The intergenerational logic of borrowing here is unusually clean.** The bridge debt pays today's 25-year-olds; it is serviced by tomorrow's 100%-rate receipts — which are levied on the *largest* inheritors of the wealth accumulated by today's older generations. Borrowing against that stream does not shift burden onto future workers; it shifts it onto future dynastic heirs, which is the policy's exact intent. This is the answer to the "burdening our grandchildren" attack, developed further in [`../09-objections/economic.md`](../09-objections/economic.md).

## Stylised 20-year cashflow sketch

All figures illustrative, UK, constant prices, **to be replaced by micro-simulation** against wealth-holding and mortality data ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)). Assumes Phase 2 begins year 1, Phase 3 (100% rate + full endowment) begins year 6, per [sequencing.md](sequencing.md).

| Years | Receipts (illustrative) | Outlays (illustrative) | Fund position |
|---|---|---|---|
| 1–5 (Phase 2) | Rising schedule on large receipts: grows from ~current IHT yield (£8.2bn in 2024–25 [3]) toward £15–20bn/yr as rates step up | Pilots only (£0.5–1bn/yr); fund accumulates | Builds a £40–60bn opening reserve |
| 6–10 (Phase 3 launch) | 100% rate in force but ledgers young and forestalling shadow at its deepest: £20–30bn/yr | Full endowment £43–45bn/yr | Annual gap £13–25bn: met from reserve, then fund borrowing; peak cumulative borrowing plausibly £75–125bn |
| 11–15 | Ledgers filling; first post-commencement generation's large bequests arriving: £30–40bn/yr | £44–47bn/yr (wage-indexed) | Gap narrows; borrowing peaks and plateaus |
| 16–20 | Wealth-holding cohorts' mortality peak approaching; forestalling shadow expired: £40–55bn/yr | £46–49bn/yr | Approaching balance; upper-range receipts begin retiring bridge debt |
| 20+ | Mature regime | Endowment fully funded | Structural surplus to general revenue, per [`../02-proposal/README.md`](../02-proposal/README.md) |

The shape — reserve build, a roughly decade-long financed gap peaking in the tens of billions, then self-amortisation — is robust to parameter changes even though every number in the table is a placeholder. The two genuine risks are (i) mature revenue disappointing because avoidance beats the spine ([`../02-proposal/avoidance.md`](../02-proposal/avoidance.md), [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md)), and (ii) a mid-bridge government cancelling the escalator — a political risk, answered by the constituency the early endowments themselves create ([pilots.md](pilots.md), [`../13-movement/theory-of-change.md`](../13-movement/theory-of-change.md)).

## What must be true before Phase 3 is announced

1. A published micro-simulation replacing every figure above, with sensitivity bands ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)).
2. Fund legislation enacted and the Phase 2 reserve visibly accumulating — the bridge should be *seen working* before the big rate change.
3. Fiscal-rule language agreed that accommodates the bridge borrowing explicitly ([legislative-path-uk.md](legislative-path-uk.md)); discovering the collision after announcement is the avoidable own-goal.
4. Second-order revenue interactions modelled — behavioural shifts in giving, saving, and asset prices feed back into the receipts line: [`../16-second-order/savings-consumption.md`](../16-second-order/savings-consumption.md), [`../16-second-order/asset-prices.md`](../16-second-order/asset-prices.md), [`../16-second-order/macro.md`](../16-second-order/macro.md).
5. The US variant re-derived under reconciliation scoring: the Byrd rule's out-year deficit test makes the bridge shape a *legislative survival* question there, not merely a financing one ([legislative-path-us.md](legislative-path-us.md)).

## Anticipated attacks on the bridge

| Attack | Response |
|---|---|
| "Borrowing to give money away" | The debt is secured on a legislated receipt stream and serviced by future dynastic heirs, not future workers; publish the fund's actuarial position annually |
| "The revenue will never come — avoidance will gut it" | The claim is testable in-flight: Phase 1–2 register data show realised yield years before Phase 3 borrowing peaks; abort criteria can be stated in advance ([`../09-objections/avoidance.md`](../09-objections/avoidance.md)) |
| "Off-balance-sheet trickery" | The fund is consolidated and transparent; the case for capital treatment is argued openly, not smuggled ([legislative-path-uk.md](legislative-path-uk.md)) |
| "Future government will raid the fund" | Statutory ring-fence, named beneficiaries, and the political cost of visibly taking £50k from every 25-year-old ([`../10-opposition/sabotage-after-passage.md`](../10-opposition/sabotage-after-passage.md)) |

## Sources

1. [Mirrlees Review, *Tax by Design*](https://ifs.org.uk/publications/taxation-wealth-and-wealth-transfers) — wealth-transfer flow estimates and lifetime-receipts architecture.
2. [UN World Population Prospects 2024 — UK population by age band (via PopulationPyramid.net)](https://www.populationpyramid.net/united-kingdom/2024/) — 25–29 cohort ≈4.45m in 2024; micro-simulation should use [ONS mid-year population estimates by single year of age](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates).
3. [HMRC — Inheritance Tax statistics (current yield baseline)](https://www.gov.uk/government/collections/inheritance-tax-statistics); [OBR — inheritance tax: forecasts in-depth](https://obr.uk/forecasts-in-depth/tax-by-tax-spend-by-spend/inheritance-tax/) — record £8.2bn receipts in 2024–25; OBR forecasts £8.7bn in 2025–26.
4. [OBR — fiscal-rules commentary and long-run fiscal sustainability reports](https://obr.uk/) — classification and rules interaction.
5. [Atkinson, A. B. (2015). *Inequality: What Can Be Done?*](https://www.hup.harvard.edu/books/9780674979789) — the paired minimum-inheritance/capital-endowment financing discussion.
6. [Leslie, J. and Shah, K. (2022). *Intergenerational rapport fair?* — Resolution Foundation](https://www.resolutionfoundation.org/app/uploads/2022/02/Intergenerational-rapport-fair.pdf) — intergenerational wealth-transfer flows, including the ≈£6bn/yr lifetime-gift estimate.
7. [Goss, D. and Glover, B. (2023). *A New Age of Inheritance* — Demos](https://demos.co.uk/research/a-new-age-of-inheritance-what-does-it-mean-for-the-uk/) — inheritances worth over £98bn in FYE 2020 (2021/22 prices) plus ≈£6bn/yr in gifts; inheritances projected to peak around 2046 at ~2.4× their 2021 value, over £230bn a year.
8. [Zucman, G. — *We Need to Tax Billionaires*, LSE lecture slides (20 May 2026) — UK revenue stakes of a 2% minimum effective tax put at £15bn/yr; UK billionaire class ≈200 families each above £700m](https://gabriel-zucman.eu/files/Zucman2026SlidesLSE.pdf)
