# Interactions with the Existing Tax System

**Executive summary.** A recipient-based receipts tax does not land on empty ground: it must mesh with capital gains tax at death, income tax on inherited pensions, means-tested benefits, stamp duty, and the existing trust tax regimes it supersedes — and each junction is a place where double taxation, double non-taxation, or a cliff edge can discredit the whole design. This file specifies the coordination rules, resolves one genuine tension with [`carveouts.md`](carveouts.md) on pensions, and identifies which existing taxes could be cut with the proceeds as the political dividend.

## Key commitments

- **The CGT death uplift is abolished as a free-standing benefit.** The recipient's market-value base survives *only because* full market value has entered the taxable-receipts base; where a receipt escapes the base, the donor's base cost carries over (§1).
- **Receipts are excluded from income tax** — a separate lifetime-receipts levy, following Mirrlees and Irish CAT practice, not a Haig–Simons fold-in (§3).
- **Inherited pension pots count against the lifetime threshold** at transfer value, with collection via income tax on drawdown and a receipts-tax true-up above threshold — closing the leak that a drawdown-only rule would open under a 100% regime (§2).
- **No benefit cliff edges.** The endowment is disregarded while held in its default wrapper; inherited receipts get a time-limited disregard and a tapered notional-income treatment thereafter (§4).
- **No SDLT/transfer-tax cascade** on receipts, deemed receipts, state-equity elections, or forced sales within 24 months of a receipts-tax charge (§5).
- **The existing trust tax regimes are superseded**, not layered on: relevant-property charges, exit charges, and GST tax are repealed where the distribution-based receipt charge applies (§6).
- **The visible dividend is a cut to taxes on work and transactions** — candidates ranked in §7 — presented as shifting tax from earned to unearned receipts ([`../12-political-adoption/right-parties.md`](../12-political-adoption/right-parties.md)).

## 1. Capital gains at death: end the uplift as a windfall

**Current law is indefensible under *any* inheritance-tax regime.** In the UK, assets rebase to market value at death with no CGT charge ([TCGA 1992 s.62](https://www.legislation.gov.uk/ukpga/1992/12/section/62)), so lifetime gains vanish; worse, BPR/APR-relieved assets historically enjoyed *both* the uplift *and* 100% IHT relief — a double benefit the OTS recommended ending [1], with the IFS putting the CGT forgone through the death uplift at roughly £1.6bn a year (≈£8bn of gains wiped out at death in 2021–22, taxed at 20%) [8]. In the US, [§1014](https://www.law.cornell.edu/uscode/text/26/1014) stepped-up basis erases accrued gains at death at a cost the JCT estimates at $72.5bn of forgone revenue in 2026 alone [2], and is the keystone of "buy, borrow, die" planning.

**Our rule** (restating [`mechanism.md`](mechanism.md) §7 with the boundary made precise):

| Situation | CGT treatment | Rationale |
|---|---|---|
| Receipt enters the taxable-receipts base (above *or* below threshold) | Donor: no-gain/no-loss. Recipient: market-value base | The full market value — including accrued gain — has been counted against the threshold or taxed at 100%; a CGT charge on the same gain would double-count |
| Transfer exempt from the receipts base (spousal) | Carryover basis — donor's base cost travels with the asset | Exempt transfers consume no threshold, so nothing has "paid for" an uplift; gain is preserved for eventual taxation |
| Charitable transfers | Existing no-gain/no-loss to charity retained | Charity is tax-exempt on disposal anyway |
| Assets held at emigration | Deemed receipt (exit tax) with CGT credit | [`mechanism.md`](mechanism.md) §3; no double charge on the same accrual |

The principled statement: **basis uplift is earned by inclusion in the transfer-tax base, never granted by death itself.** This also makes standalone abolition of the uplift a natural stepping-stone reform that a government could enact *before* the full scheme ([`../12-political-adoption/stepping-stones.md`](../12-political-adoption/stepping-stones.md)).

## 2. Inherited pensions: reconciling with carveouts.md §8

[`carveouts.md`](carveouts.md) §8 taxes inherited pension pots as income on drawdown, matching the UK's post-2024 direction (unused pension funds and death benefits brought within IHT from 6 April 2027) [3]. Under a 40% IHT that is adequate; under a 100%-above-threshold regime it is a leak: income tax tops out at 45% (UK additional rate) and 37% (US federal top rate, made permanent from 2026) [9], so an unlimited drawdown-only rule would make large pension pots the premier avoidance wrapper.

**Coordination rule.** The inherited pot's transfer value counts against the recipient's lifetime threshold on the date of death. Below-threshold amounts are then simply income-taxed on drawdown as now. For above-threshold amounts, a receipts-tax charge applies to the excess, collected on drawdown, with income tax paid on those drawdowns credited against it — so the *total* take on above-threshold pension wealth reaches 100% without ever taxing the same pound twice. Illustrative: a recipient with no remaining headroom inherits a £300k pot; each £1,000 drawn suffers £400 income tax (at 40%) plus £600 receipts-tax true-up. This refines rather than contradicts the carveout: modest inherited pensions are untouched; dynastic-scale pots stop being a shelter. Implementation detail sits with [`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) and [`../07-implementation/administration.md`](../07-implementation/administration.md).

## 3. Is a receipt "income"? The boundary with income tax

Under a comprehensive Haig–Simons definition, gratuitous receipts *are* income, and some economists would simply add them to the recipient's income-tax return. We follow the Mirrlees Review [4] and Irish practice [5] in keeping a **separate lifetime-receipts tax**, for three reasons:

1. **Lumpiness.** Annual income-tax schedules mishandle once-in-a-lifetime receipts; averaging provisions would be needed and are notoriously complex. A lifetime threshold *is* the averaging device.
2. **Rate architecture.** The 0%/100% kink cannot be expressed inside a progressive income-tax schedule without wrecking that schedule's logic.
3. **Precedent.** Ireland's CAT taxes gratuitous receipts under a separate code with group thresholds and a same-event CGT credit [5] — the closest operating relative of our design and evidence the boundary is administrable.

The coordination rules are one line each: a taxable receipt is excluded from income tax ([`mechanism.md`](mechanism.md) §7); income *generated by* received assets after the tax point (rent, dividends, interest) is ordinary income; employment income disguised as gift (e.g., "gifts" from an employer) is recharacterised as earnings under existing disguised-remuneration principles — in the UK, Part 7A ITEPA 2003, "employment income provided through third parties" [10]. The same boundary runs through equity: options and RSUs earned from one's own employment are employment income at exercise or vest under existing ERS/§83 rules and never touch the receipts ledger, while equity granted on non-commercial terms to a connected person qua heir is a receipt at grant — the line, and the employer-feed detection behind it, are specified in [`../07-implementation/buy-borrow-die.md`](../07-implementation/buy-borrow-die.md) §3.

## 4. Means-tested benefits: no cliff edges

Current UK capital rules disqualify Universal Credit claimants above £16,000 in money, savings and investments [6]; unmodified, they would make the £50k endowment a poisoned chalice for the poorest recipients and turn a sub-threshold inheritance into a benefits catastrophe. Design:

| Receipt | Benefit treatment |
|---|---|
| Universal endowment, held in default wrapper | Fully disregarded as capital for as long as it remains in the wrapper; withdrawals treated as capital from the date of withdrawal, with a 12-month disregard ([`endowment-delivery.md`](endowment-delivery.md)) |
| Inherited/gifted receipts below threshold | 12-month full disregard (bereavement adjustment period), then ordinary capital rules with a **taper** — notional income imputed at a statutory rate — replacing the binary £16k cut-off (rate to be set with DWP modelling) |
| Social-care means tests | Endowment-in-wrapper disregarded; inherited receipts follow the tapered rule above (the legislated £86,000 lifetime care-cost cap was scrapped in July 2024, so the operative interaction is with the unreformed capital means-test limits [11]) |

The principle: the state must never simultaneously give with the endowment hand and confiscate with the benefits hand. A cliff edge here would supply the opposition's most sympathetic anecdote ([`../10-opposition/attack-playbook.md`](../10-opposition/attack-playbook.md)).

## 5. Stamp duty and transaction taxes

Inherited property currently attracts no SDLT (acquisitions under a will or on intestacy are exempt — FA 2003 Sch 3 para 3A) [7]; this is preserved. Three junctions need explicit rules:

- **Deemed receipts** (exit tax, trust deemed-distributions) are not land transactions and trigger no SDLT.
- **State-equity elections** ([`carveouts.md`](carveouts.md) §5) — the transfer of a preferred stake to the state in satisfaction of tax is exempt from SDLT/stamp duty on shares, as is its later buy-back.
- **Forced sales**: where a recipient sells property within 24 months specifically to fund a receipts-tax liability, no additional-dwelling SDLT surcharge distortions should arise for the *buyer-side* chain; and the recipient's sale itself bears CGT only on post-receipt appreciation given the §1 market-value base. Asset-market effects of tax-motivated sales are analysed at [`../16-second-order/asset-prices.md`](../16-second-order/asset-prices.md).

## 6. Trust tax regimes superseded

The UK relevant-property regime (entry, ten-year anniversary, and exit charges), trust-rate income tax add-ons designed as IHT backstops, and the US generation-skipping transfer tax all exist to patch a donor-based tax that trusts would otherwise tunnel under. The distribution-based receipt charge in [`avoidance.md`](avoidance.md) §2 replaces the lot: settlement-side charges are repealed where the receipt charge applies, trusts' *income* remains taxed under ordinary trust income-tax rules, and the 80-year deemed-distribution long-stop replaces perpetuity-policing charges. One regime, one tax point, no settlement-vs-outright arbitrage. Detailed transition for existing trusts — a genuinely hard grandfathering problem — is assigned to [`../07-implementation/trusts-and-vehicles.md`](../07-implementation/trusts-and-vehicles.md) and [`../15-transition/grandfathering.md`](../15-transition/grandfathering.md).

## 7. The political dividend: which taxes to cut

Hypothecation to the endowment absorbs the core proceeds ([`revenue-model.md`](revenue-model.md)), but two categories of fiscal room still open up: the repeal dividend (existing IHT/estate-tax machinery and its £7–8bn are folded in, not additive) and the mature-flow surplus. Ranked candidates for the visible cut, chosen for both efficiency and coalition value:

| Candidate cut | Approx. cost | Case |
|---|---|---|
| Abolish existing IHT / estate tax | — (replaced by this scheme) | Automatic; lets proponents truthfully say "we abolished inheritance tax on 95%+ of families" |
| Cut/abolish SDLT on primary homes | up to £10.4bn — total residential SDLT receipts, UK 2024–25; the primary-home share is smaller [12] | Economists' most-condemned tax (Mirrlees [4]); directly helps the young the endowment targets; strong right-of-centre appeal |
| Cut employee NI / payroll tax | ~£5.35bn per point of the employee main rate (UK, 2026–27) [13] | Purest "tax work less, tax windfalls more" framing |
| Raise income-tax personal allowance | ~£8bn per £1,000 (scaled from HMRC's £810m per £100, 2026–27) [13] | Broad but less salient per pound |

The strategic point, developed in [`../12-political-adoption/right-parties.md`](../12-political-adoption/right-parties.md) and [`../06-palatability/framing.md`](../06-palatability/framing.md): pairing the receipts tax with a named cut to a hated tax on effort converts the package from "new tax" to "tax swap," which is the only shape in which right-of-centre parties have historically been able to support transfer taxation.

## Sources

1. [Office of Tax Simplification — *Capital Gains Tax Review: Simplifying by design* (2020)](https://www.gov.uk/government/publications/ots-capital-gains-tax-review-simplifying-by-design) — recommends ending the combination of an IHT relief/exemption with the CGT uplift, moving to no-gain/no-loss carryover.
2. [Joint Committee on Taxation — *Estimates of Federal Tax Expenditures* (JCX-59-23)](https://www.jct.gov/publications/2023/jcx-59-23/) — exclusion of capital gains at death estimated at $72.5bn forgone in 2026; summarised by the [Peter G. Peterson Foundation](https://www.pgpf.org/article/what-is-the-stepped-up-basis-and-how-does-it-affect-the-federal-budget/).
3. [HMRC — Inheritance Tax on unused pension funds and death benefits (policy paper)](https://www.gov.uk/government/publications/reforming-inheritance-tax-unused-pension-funds-and-death-benefits/inheritance-tax-on-unused-pension-funds-and-death-benefits) — in scope of IHT from 6 April 2027.
4. [Mirrlees Review, *Tax by Design*, Chs. 6 and 15](https://ifs.org.uk/books/tax-design) — transaction taxes and wealth-transfer taxation.
5. [Irish Revenue — Capital Acquisitions Tax; CAT/CGT same-event credit](https://www.revenue.ie/en/gains-gifts-and-inheritance/index.aspx).
6. [DWP — Universal Credit: eligibility](https://www.gov.uk/universal-credit/eligibility) — £16,000 limit on money, savings and investments.
7. [HMRC — SDLT manual SDLTM00570: assents and appropriations by personal representatives (FA03/Sch 3 para 3A)](https://www.gov.uk/hmrc-internal-manuals/stamp-duty-land-tax-manual/sdltm00570) — acquisitions under a will or intestacy exempt from SDLT.
8. [Institute for Fiscal Studies — *Reforming inheritance tax* (2023)](https://ifs.org.uk/publications/reforming-inheritance-tax) — ≈£8bn of gains forgiven at death in 2021–22, implying ≈£1.6bn of CGT forgone at a 20% rate.
9. [HMRC — Income Tax rates and Personal Allowances](https://www.gov.uk/income-tax-rates) (45% additional rate above £125,140); [IRS — tax year 2026 inflation adjustments, including One Big Beautiful Bill amendments](https://www.irs.gov/newsroom/irs-releases-tax-inflation-adjustments-for-tax-year-2026-including-amendments-from-the-one-big-beautiful-bill) (top rate 37% for 2026).
10. [HMRC — Employment Income Manual EIM45000: employment income provided through third parties (Part 7A ITEPA 2003)](https://www.gov.uk/hmrc-internal-manuals/employment-income-manual/eim45000).
11. [Community Care — Government scraps cap on care costs (29 July 2024)](https://www.communitycare.co.uk/2024/07/29/government-scraps-cap-on-care-costs-to-help-tackle-22bn-public-spending-black-hole/) — £86,000 cap and associated means-test changes cancelled.
12. [HMRC — UK Stamp Tax statistics: annual commentary](https://www.gov.uk/government/statistics/uk-stamp-tax-statistics/uk-stamp-tax-statistics-2023-to-2024-commentary) — residential SDLT receipts £10,380m in 2024–25 (total SDLT £13,885m).
13. [HMRC — Direct effects of illustrative tax changes bulletin](https://www.gov.uk/government/statistics/direct-effects-of-illustrative-tax-changes/direct-effects-of-illustrative-tax-changes-bulletin-january-2025) — employee Class 1 main rate ±1ppt ≈ £5,350m and personal allowance ±£100 ≈ £810m, both 2026–27.
