# Mechanism

This specification defines a 100% marginal inheritance and gift tax as a **recipient-based, lifetime-cumulative** levy on all capital transfers received above a per-person threshold, replacing the UK's estate-side Inheritance Tax (IHT) and the US federal estate/gift tax. It is modelled on the lifetime-receipts-tax architecture recommended by the Mirrlees Review [1] and the operating mechanics of Ireland's Capital Acquisitions Tax (CAT) [2], extended to a confiscatory top rate as argued by Piketty [3] and Atkinson [4].

## Key commitments

- Tax base is the **recipient's cumulative lifetime receipts** of bequests, gifts, trust distributions, and deemed receipts — not the donor's estate [1].
- Threshold of **£500,000 / $750,000 per recipient, lifetime**, indexed annually to the greater of national wage growth or national median house-price growth.
- Marginal rate: **0% below threshold, 100% above** — a sharp kink, not a schedule.
- Liability rests on the **recipient** where resident, or on the **asset** where UK-/US-situated (dual nexus) [2].
- **Spousal transfers** are never taxed and never consume threshold, but operate as *deferral with a tracked charge*, not clean exemption: above-threshold relieved corpus carries a deferred-charge tag that crystallises on any exit from the marriage chain to a non-spouse (§2; [carveouts.md](carveouts.md) §1). **Registered-charitable** transfers are fully exempt and do not consume threshold.
- **Family businesses and farms**: liability stands but payment is deferrable up to 30 years at gilts/Treasuries + 1%, with a state-equity option for illiquid operating assets.
- **Exit tax**: deemed receipt at market value on loss of tax residence, with a **10-year residency tail** to defeat pre-emptive expatriation.
- Proceeds are hypothecated to a **universal citizen's endowment** of £50,000 at 25 / $60,000, wage-indexed.
- **Coordination rule**: a transfer that triggers this tax is excluded from income tax and rebases (not realises) for CGT [5].
- Administered by HMRC / IRS through a **Central Register of Receipts** integrated with probate and the existing self-assessment infrastructure [2].

## 1. Tax base

A **taxable receipt** is any of: (i) a bequest under will or intestacy; (ii) an inter-vivos gift of money, property, or rights; (iii) a distribution from a trust to an identified beneficiary (with deemed-distribution rules for discretionary trusts on ten-year anniversaries, echoing the current UK relevant-property regime); (iv) the proceeds of a life-insurance policy where the recipient is not the policyholder; (v) the forgiveness of a debt; (vi) below-market-value transfers (the gift element being the market-value shortfall); (vii) deemed receipts on exit (§3) and on certain trust-termination events. Accounting is **receiver-centric**: the identity and residence of the recipient, not the donor, determine inclusion.

**Debt netting.** A receipt is measured **net of liabilities genuinely attached to it** — a bequest of a mortgaged house is a receipt of the equity — but only where the debt is of **arm's-length origin** and is **actually discharged** (from the estate, or assumed with full recourse by the recipient). Liabilities owed to connected persons or to vehicles within the family's perimeter are **not deductible**, and repayment of such a debt is itself a receipt by the creditor where the creditor sits inside that perimeter. The precedent is the FA 2013 restriction of IHT debt deductions ([IHTA 1984 ss.162A/175A — HMRC IHTM28000](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm28000)). A guarantee or collateral pledge by a connected person is an annual deemed receipt of the market-fee shortfall while outstanding, and a receipt in full to the extent called. Full rules, and why this defeats "buy, borrow, die": [`../07-implementation/buy-borrow-die.md`](../07-implementation/buy-borrow-die.md).

## 2. Lifetime cumulation

Each recipient has a **single running total** of taxable receipts, net of exemptions, maintained for life on the Central Register. Each new receipt is added to the running total; the portion (if any) that crosses the threshold is taxed at 100%; the portion below is taxed at 0% but reduces remaining headroom. The threshold is a **stock**, not an annual allowance — once exhausted, it is gone. This is the Mirrlees "Lifetime Capital Receipts Tax" structure [1] and mirrors the CAT Group-A aggregation rule in Ireland [2].

**Spousal receipts are deferred, not exempt.** A transfer from a spouse or civil partner is a *deferred receipt*: it is never taxed and consumes no threshold in the survivor's hands, but relieved corpus above the standard threshold posts to the survivor's ledger with a **deferred-charge tag** (amount and source line). The tag does not tax the survivor — it travels. When tagged wealth exits the marriage chain to any non-spouse — bequest, gift, trust distribution, debt forgiveness, in this marriage or any later one — the exit is an ordinary taxable receipt against the ultimate recipient's threshold under §1, and the tag supplies the Register's audit trail. The tag also records *whose* accumulation the corpus was: from the second spousal hop onward — corpus held by a spouse who was never the accumulator's partner — the tagged corpus additionally attracts the trust-equivalent periodic charge (chain-hop parity; [carveouts.md](carveouts.md) §1). Design rationale, precedents (US QDOT, IRC §2056A; UK IPDI, IHTA 1984 s.49A), and the serial-remarriage analysis: [carveouts.md](carveouts.md) §1.

**Transitional credit.** Receipts before the regime's commencement date are disregarded except that recipients may elect to declare pre-regime receipts within a 24-month window; declared amounts are applied against the threshold at **50% weight** (a transitional discount compensating for prior IHT/estate-tax exposure and valuation uncertainty). Undeclared pre-regime receipts remain outside the base but cannot be re-gifted onward without crystallising.

## 3. Liability and nexus

The recipient owes the tax where **either** (a) the recipient is UK resident or UK domiciled/deemed-domiciled at the tax point, **or** (b) the asset transferred is UK-situated (UK land, shares in UK-incorporated companies, UK bank deposits, tangible UK chattels). The US parallel substitutes US tax residence / citizenship for (a) and US-situated property for (b), tracking the existing [§2104 IRC](https://www.law.cornell.edu/uscode/text/26/2104) situs rules.

**Exit tax.** On ceasing UK/US tax residence, the individual is treated as receiving at market value all previously-received assets still held, to the extent they exceed residual threshold headroom; any 100% charge crystallises at that date. A **10-year residency tail** preserves liability on gifts and bequests made to or by the individual within ten years of departure, irrespective of subsequent residence.

**The unit of escape is the dynasty, not the donor.** A donor-based estate tax is escaped by one person moving once; under this design, escape requires the donor to clear the exit charge and tail, *every* intended recipient to be durably non-resident (each clearing their own 10-year returning-heir look-back — [`../08-capital-flight/exit-tax-design.md`](../08-capital-flight/exit-tax-design.md)), and every charged asset to be re-sitused — simultaneously, and sustained for decades. The escape decision is therefore never an individual's; it is a whole bloodline's, and all flight analysis in this repo prices the family system, not the founder ([`../08-capital-flight/confiscatory-stakes.md`](../08-capital-flight/confiscatory-stakes.md) §5).

## 4. Tax point and valuation

The tax point is the **date of receipt** (for gifts and trust distributions), the **date of death** (for bequests), or the **date of the deemed event** (exit, trust termination). Valuation is market value at the tax point:

- **Listed securities**: mid-market close on the tax-point date.
- **Real estate**: independent RICS (UK) / state-certified appraiser (US) valuation, creating a **rebuttable presumption** that HMRC/IRS may challenge within 24 months.
- **Unlisted/illiquid assets** (private company shares, partnership interests, art, crypto): taxpayer-commissioned appraisal under statutory methodology, with a mandatory HMRC/IRS review for receipts above £2m / $3m; the **state-equity option** (taking a non-voting equity stake in lieu of cash) is available for operating businesses to resolve valuation disputes.

## 5. Returns and assessment

The **recipient** files a Receipts Return within **12 months** of the tax point (6 months for bequests, aligning with UK probate). Personal representatives file an Estate Information Return identifying all beneficiaries and values; probate cannot be granted until the Return is lodged. Penalties mirror existing self-assessment: 5% / 10% / 15% of tax for 30-day / 6-month / 12-month delay, plus daily interest at base + 2.5%. Recipients must retain valuation and receipt records until 12 years after death; the Register itself serves as the evidential base for cumulation.

## 6. Administrative design

A **Central Register of Receipts** is operated by HMRC (UK) / IRS (US), populated automatically from probate filings, Companies House / state registries (for share transfers), Land Registry (for conveyances at undervalue), and taxpayer returns. Each individual has a single ledger accessible via their Government Gateway / IRS Online Account. Administrative cost is projected in the same order of magnitude as existing IHT/estate-tax administration (UK IHT cost-to-yield has historically run at roughly 1% [6]); the receipt-side model reduces estate-valuation disputes because the taxpayer is the one holding the asset.

## 7. Relationship to income tax and capital gains

A transfer included in the taxable-receipts base is **excluded from income tax** (no double inclusion of gratuitous transfers). For **capital gains**, the donor is treated as disposing at no-gain/no-loss and the recipient takes the asset at market value at the tax point — a **rebase, not a realisation** — so the same appreciation is not taxed twice. Where a deemed receipt under the exit rule overlaps with a CGT deemed-disposal on emigration, the CGT charge is credited against any 100% charge arising on the same asset.

## 8. Worked example

Aisha (UK resident). Threshold £500,000.

| Age | Event | Amount | Cumulative | Taxable portion | Tax (100%) |
|-----|-------|--------|------------|-----------------|------------|
| 22  | Gift from grandmother | £80,000 | £80,000 | £0 | £0 |
| 30  | Wedding gift, father | £120,000 | £200,000 | £0 | £0 |
| 41  | Bequest, uncle | £250,000 | £450,000 | £0 | £0 |
| 52  | Bequest, mother (house, appraised) | £400,000 | £850,000 | £350,000 | £350,000 |
| 60  | Gift, father | £100,000 | £950,000 | £100,000 | £100,000 |

At 52, Aisha inherits a house valued at £400,000. £50,000 fits under remaining headroom; £350,000 is taxed at 100%. She may elect the 30-year deferral only if the asset forms part of an operating family business or farm — it does not here, so she must sell, mortgage, or cede a partial state-equity stake in the dwelling. At 60, every subsequent £1 received is taxed at 100%.

## Sources

1. [Mirrlees Review, *Tax by Design*, Ch. 15: "The Taxation of Wealth and Wealth Transfers"](https://ifs.org.uk/publications/taxation-wealth-and-wealth-transfers) — IFS, 2011.
2. [Irish Revenue — Capital Acquisitions Tax (CAT) guidance](https://www.revenue.ie/en/gains-gifts-and-inheritance/index.aspx).
3. [Thomas Piketty, *Capital and Ideology*](https://www.hup.harvard.edu/books/9780674980822) — Harvard University Press, 2020 (French ed. 2019).
4. [Anthony B. Atkinson, *Inequality: What Can Be Done?*](https://www.hup.harvard.edu/books/9780674979789) — Harvard University Press, 2015.
5. [HMRC Capital Gains Manual CG30700 — death and personal representatives](https://www.gov.uk/hmrc-internal-manuals/capital-gains-manual/cg30700).
6. [HMRC Annual Report and Accounts](https://www.gov.uk/government/collections/hmrcs-annual-report-and-accounts) — administrative cost benchmarks.
