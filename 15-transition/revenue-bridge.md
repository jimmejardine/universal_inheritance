# The Revenue Bridge: Funding the Endowment Before the Tax Matures

**Executive summary.** The scheme has a built-in timing mismatch: if every 25-year-old is paid from year one, outlays begin at full scale immediately, while 100%-rate revenue matures only as deaths occur and lifetime ledgers fill — a process measured in decades. The bridge is a package, not a single instrument: a phased endowment amount, transitional revenue from the Phase 2 schedule, and debt finance through a sovereign endowment fund secured on the legislated future receipt stream.

## The mismatch stated precisely

**Outlays are demographic and immediate.** A UK birth-cohort reaching 25 is roughly 700,000–800,000 people (to verify against ONS cohort data). At £50,000 each, a full-rate universal endowment costs on the order of **£35–40bn per year from the first year** it is paid universally — comparable to a major department's budget (all figures in this file are illustrative and marked for micro-simulation; see [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)).

**Revenue is actuarial and slow.** Three lags stack:

1. **Deaths are slow.** The tax's largest receipts arrive at death, and the wealth-holding generation dies over 30–40 years, not at commencement.
2. **Cumulation starts near zero.** Lifetime ledgers begin (largely) empty at commencement; most recipients spend years consuming threshold headroom before any receipt crosses into the 100% band. Early-year effective yield is therefore *below* the mature rate even on the deaths that do occur.
3. **Forestalling thins the early base.** Pre-commencement transfers outside the lookback window ([announcement-effects.md](announcement-effects.md)) reduce early-decade taxable receipts; this leakage is one-generation-only but is concentrated exactly in the bridge period.

Mature-state annual revenue is plausibly of the same order as the endowment cost — UK annual inherited-and-gifted flows are estimated in the low hundreds of billions, with the share above £500k-per-recipient to be established by micro-simulation (to verify; [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)) — but maturity is 20+ years out. The bridge covers the gap.

## Bridge options

| Option | Mechanism | Pros | Cons |
|---|---|---|---|
| A. Phase in the amount | Endowment starts at e.g. £10k and rises with revenue on a legislated escalator | Outlays track receipts; no debt | Early cohorts get less; weakens launch impact and the constituency effect ([pilots.md](pilots.md)) |
| B. Cohort-partial start | Full £50k, but initially only to (say) those turning 25 from a named birth-year forward, or in pilot regions scaling nationally | Full-value demonstrations; controllable cost | Arbitrary cohort boundary is a fairness attack surface ([`../09-objections/fairness.md`](../09-objections/fairness.md)) |
| C. Debt finance via sovereign fund | An endowment fund borrows against the hypothecated, legislated future receipt stream; pays full endowment from year one | Full launch; intergenerationally coherent (see below) | Adds gross debt in-window; fiscal-rule collision ([legislative-path-uk.md](legislative-path-uk.md)); rate risk |
| D. Transitional lower-threshold / schedule revenue | Phase 2's rising schedule (and its lower effective starting threshold on large receipts) runs for the first bridge decade before the pure 0/100 kink | Revenue arrives a decade early; already implied by sequencing ([sequencing.md](sequencing.md)) | Delays the clean end-state design |
| E. General-revenue top-up | Treasury covers early shortfall as ordinary spending | Simple | Breaks the hypothecation story that is the scheme's core political defence ([`../05-history/abolitions.md`](../05-history/abolitions.md), error #6) |

**Recommended package: D + C + a bounded element of A.** Phase 2 schedule revenue flows into the fund for a decade before the endowment launches at full rate; the fund borrows to smooth the residual gap; if micro-simulation shows the gap still excessive, the launch amount starts at (say) £35k on a fast statutory escalator to £50k rather than delaying launch. Option E is excluded on principle; Option B is retained only in its pilot form ([pilots.md](pilots.md)).

## The endowment fund as a sovereign vehicle

Structuring the bridge through a statutory **National Endowment Fund** rather than the general Exchequer does four jobs:

- **Hypothecation made structural.** Receipts are paid into the fund by law; endowments are paid out of it; the annual accounts make the tax's purpose visible — the anti-abolition architecture of [`../02-proposal/endowment.md`](../02-proposal/endowment.md) given institutional form.
- **A borrower with collateral.** The fund issues debt (or receives an on-lent Treasury facility) secured on a legislated receipt stream with demographic — not cyclical — fundamentals. The analogy is infrastructure finance against a regulated revenue stream, not deficit spending.
- **Classification and fiscal rules.** A fund holding a legislated receivable and, in some cases, assets in kind (the state-equity stakes taken from illiquid business receipts, [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §4, live here and are managed to maturity) has a defensible claim to capital rather than current treatment; the ONS/OBR classification battle is anticipated in [legislative-path-uk.md](legislative-path-uk.md).
- **Insulation from raid and from sabotage.** Statutory ring-fencing raises the legislative cost of a future government quietly diverting receipts or starving the endowment — the post-passage attack surface mapped in [`../10-opposition/sabotage-after-passage.md`](../10-opposition/sabotage-after-passage.md).

**The intergenerational logic of borrowing here is unusually clean.** The bridge debt pays today's 25-year-olds; it is serviced by tomorrow's 100%-rate receipts — which are levied on the *largest* inheritors of the wealth accumulated by today's older generations. Borrowing against that stream does not shift burden onto future workers; it shifts it onto future dynastic heirs, which is the policy's exact intent. This is the answer to the "burdening our grandchildren" attack, developed further in [`../09-objections/economic.md`](../09-objections/economic.md).

## Stylised 20-year cashflow sketch

All figures illustrative, UK, constant prices, **to verify by micro-simulation** against wealth-holding and mortality data ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)). Assumes Phase 2 begins year 1, Phase 3 (100% rate + full endowment) begins year 6, per [sequencing.md](sequencing.md).

| Years | Receipts (illustrative) | Outlays (illustrative) | Fund position |
|---|---|---|---|
| 1–5 (Phase 2) | Rising schedule on large receipts: grows from ~current IHT yield (£7–8bn) toward £15–20bn/yr as rates step up | Pilots only (£0.5–1bn/yr); fund accumulates | Builds a £40–60bn opening reserve |
| 6–10 (Phase 3 launch) | 100% rate in force but ledgers young and forestalling shadow at its deepest: £20–30bn/yr | Full endowment £35–40bn/yr | Annual gap £5–20bn: met from reserve, then fund borrowing; peak cumulative borrowing plausibly £50–100bn |
| 11–15 | Ledgers filling; first post-commencement generation's large bequests arriving: £30–40bn/yr | £38–42bn/yr (wage-indexed) | Gap narrows to roughly zero; borrowing peaks and plateaus |
| 16–20 | Wealth-holding cohorts' mortality peak approaching; forestalling shadow expired: £40–55bn/yr | £40–45bn/yr | Surplus services and retires bridge debt |
| 20+ | Mature regime | Endowment fully funded | Structural surplus to general revenue, per [`../02-proposal/README.md`](../02-proposal/README.md) |

The shape — reserve build, a roughly decade-long financed gap peaking in the tens of billions, then self-amortisation — is robust to parameter changes even though every number in the table is a placeholder. The two genuine risks are (i) mature revenue disappointing because avoidance beats the spine ([`../02-proposal/avoidance.md`](../02-proposal/avoidance.md), [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md)), and (ii) a mid-bridge government cancelling the escalator — a political risk, answered by the constituency the early endowments themselves create ([pilots.md](pilots.md), [`../13-movement/theory-of-change.md`](../13-movement/theory-of-change.md)).

## What must be true before Phase 3 is announced

1. A published micro-simulation replacing every figure above, with sensitivity bands ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)).
2. Fund legislation enacted and the Phase 2 reserve visibly accumulating — the bridge should be *seen working* before the big rate change.
3. Fiscal-rule language agreed that accommodates the bridge borrowing explicitly ([legislative-path-uk.md](legislative-path-uk.md)); discovering the collision after announcement is the avoidable own-goal.
4. Second-order revenue interactions modelled — behavioural shifts in giving, saving, and asset prices feed back into the receipts line: [`../16-second-order/savings-consumption.md`](../16-second-order/savings-consumption.md), [`../16-second-order/asset-prices.md`](../16-second-order/asset-prices.md), [`../16-second-order/macro.md`](../16-second-order/macro.md).
