# Anti-avoidance Spine

**Executive summary.** A recipient-based, lifetime-cumulative inheritance tax survives or dies by its anti-avoidance architecture: the historical abolitions surveyed in [`05-history/abolitions.md`](../05-history/abolitions.md) show that any regime whose incidence is inversely correlated with wealth above the threshold eventually loses legitimacy and is repealed. This spine closes the main routes — inter-vivos gifting, trust settlement, insurance wrappers, emigration, situs manipulation, and soft valuation — by tracking *receipts* across a recipient's life rather than *settlements* at a donor's death [1][2].

## Headline commitments

- **Lifetime aggregation, no death-reset.** Every inter-vivos gift counts against the recipient's £500k / $750k cumulative threshold; the clock does not restart at the donor's death [1].
- **Trust look-through.** Distributions from discretionary or bare trusts are taxable receipts by the identified beneficiary on distribution; entry charges apply on settlement of reserved assets; the proposed rule is structurally cleaner than the UK Relevant Property Regime's 10-year anniversary charge [3] and the US GST tax [4].
- **Wrapper look-through.** Life-insurance, deferred-annuity and investment-bond payouts on death are taxable receipts. No special regime; no offshore-bond carve-out [2].
- **Debt is not a deduction machine.** Receipts net only genuine, arm's-length, actually-discharged debts; connected-party and contrived debts are non-deductible, and loan-and-derivative structures that deliver an asset's economics without moving title are receipts of the value delivered (§3A).
- **Exit tax as deemed receipt.** On change of tax residence, a departing individual is treated as having received unrealised accrual they would otherwise dodge, modelled on US IRC §877A [5] but applied on the recipient axis.
- **10-year residency tail.** Former residents remain within charge for 10 years on UK-situated property and on worldwide receipts if long-term resident or UK-domiciled, extending the logic of UK deemed-domicile [6].
- **Two-fold nexus.** Tax applies if the recipient is UK-resident *or* the property is UK-situated; dual-trigger eliminates the "resident of nowhere" gap.
- **Hard valuation.** Mark-to-market for listed assets and crypto; professional appraisal with rebuttable presumption for real estate and unlisted equity; capped minority/marketability discounts; no frozen cadastral values (the Austrian failure mode [7]).
- **Multilateral floor.** Pursue an OECD-template minimum standard for inheritance taxation analogous to Pillar Two [8], with CRS-style information exchange on transfers [9].

## 1. Gift aggregation

All lifetime gifts received count against the recipient's running total. There is no seven-year taper, no potentially-exempt-transfer construct, and no reset at the donor's death: these UK-inherited devices are precisely the features that let wealthy donors plan around the tax while surprising the merely comfortable who die unexpectedly. A *de minimis* annual exclusion — modelled on the current US §2503(b) $18,000 annual exclusion [10] but with lifetime tracking — exempts ordinary family transfers (birthday cash, routine school-fee payments, small inter-household support), set at £3,000 / $18,000 per donor-recipient pair per year. Contributions to registered education and disability trusts for the recipient are treated analogously to US §529 and ABLE accounts [10]: excluded up to an annual cap, tracked thereafter. Reporting thresholds mirror the thresholds of IRS Form 709 and HMRC IHT403 [11] but are consolidated into a single lifetime ledger held by the revenue authority.

## 2. Trusts — discretionary and bare

The rule is one line: *distributions from a trust to an identifiable individual are taxable receipts by that individual at the time of distribution*, valued at fair market value, and count against that individual's lifetime threshold. Settlements in which the settlor retains no interest still trigger an entry charge where the beneficiaries are identified; reserved-asset settlements (where the settlor retains a revocable interest or benefit) are charged on settlement and again on distribution only to the extent the value has grown. Anti-perpetual-trust rules cap the duration of any tax-deferred trust at 80 years (the current UK perpetuity period post-2009 [12]), after which undistributed assets are deemed received pro-rata by the beneficiary class. The UK Relevant Property Regime's 10-year anniversary charge [3] and the US generation-skipping-transfer tax [4] are partial precedents — both recognise that trusts without periodic charges become inter-generational wealth tunnels — but both tax the *settlement* rather than the *receipt*, producing arbitrage between trust and non-trust holdings. Tracking the receipt eliminates that arbitrage.

## 3. Life insurance, annuities, investment bonds

Full look-through. A payout to an individual on death is a taxable receipt; a payout to a trust is taxed under section 2 on eventual distribution. No "written in trust" special regime (the standard UK IHT avoidance route for life policies [13]); no offshore investment-bond carve-out; no §101(a) income-tax-free treatment passed through as a transfer-tax exemption [10]. Insurance continues to perform its genuine function — liquidity for the estate to pay the tax — but ceases to be a wrapper that converts a taxable transfer into a tax-free one.

## 3A. Loans, debt and derivatives

Debt is the last relabelling frontier at scale: the US "buy, borrow, die" strategy shows how borrowing against appreciated assets substitutes for realisation in life and how debt deductions shrink the taxable estate at death. Three rules close it on the receipts axis:

- **Soft loans are annually imputed.** Interest-free and below-market loans from connected persons generate an annual deemed receipt of the shortfall at the official rate, with a 10-year dormancy presumption of forgiveness — the machinery in [`../07-implementation/boundary-problem.md`](../07-implementation/boundary-problem.md) §3.
- **Receipts net only genuine debt.** A receipt is measured net of arm's-length, actually-discharged liabilities; connected-party and contrived debts are non-deductible, and their repayment is the creditor's receipt where the creditor sits inside the dynasty's perimeter ([`mechanism.md`](mechanism.md) §1, on the FA 2013 / IHTA ss.162A/175A template).
- **Substance over form for economic transfers without title.** A derivative, loan package, or guarantee structure that delivers an asset's economics to another person — a prepaid variable forward paying into an heir's account, a parent-collateralised credit line — is a taxable receipt of the value delivered or the benefit conferred, however documented. This is the rule [`../08-capital-flight/composition-and-concealment.md`](../08-capital-flight/composition-and-concealment.md) §3 relies on for derivative monetisation.

The deep treatment — the classic strategy verified at scale, the startup variants, the mutation catalogue, the lender-feed detection architecture, and the honest enforcement costs — is [`../07-implementation/buy-borrow-die.md`](../07-implementation/buy-borrow-die.md).

## 4. Exit tax and residence rules

The emigrating individual is treated, on the date of residence change, as having received at market value any unrealised accrual that would otherwise escape the charge (*deemed-receipt* construction). As a mirror rule, the jurisdiction may instead treat the donor/settlor as having made a deemed transfer on emigration, creating a charge on future recipients — the choice is a drafting preference, not a substantive difference. A 10-year residency tail extends liability to former residents on UK-situated property and on worldwide receipts where the person was UK-domiciled or long-term resident (UK's reformed deemed-domicile rules [6] provide the template). The design draws on US IRC §877A expatriation regime [5] and the Netherlands' exit-tax practice on substantial shareholdings [14]; the Norwegian 2022–23 wealth-tax exit episode [15] is the cautionary case — announcing a headline-grabbing rate without a functioning residency tail produced precisely the high-visibility emigration cascade the abolitions literature warns against [1].

| Feature | US §877A [5] | UK deemed-domicile [6] | Proposed design |
|---|---|---|---|
| Trigger | Expatriation (surrender of citizenship / LTR status) | 15 of 20 years UK residence | Change of tax residence |
| Basis | Deemed sale of worldwide assets | Worldwide IHT for deemed-domiciliaries | Deemed *receipt* by departing person |
| Tail | One-time exit; no retrospective tail | 4-year "tail" post-loss of deemed-dom | 10-year tail on UK-situated + worldwide-if-LTR |
| Threshold | ~$866k net-worth / income alternative | None (binary) | £500k / $750k lifetime, unified |

## 5. Situs and residence nexus

Two triggers, either sufficient: (a) the recipient is UK-resident, or (b) the transferred property is UK-situated. (For how the dual nexus and the 10-year tail operate across borders *inside the EU* — differing national thresholds, the *van Hilten*/*Mattner*/*Welte* case law, and credit ordering — see [`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md) §"Free movement and the mobile ledger".) Situs rules follow established categories — real estate at its physical location; registered shares at the register's jurisdiction; bearer instruments where held; business assets where the permanent establishment sits; IP at the registering authority (with a substance override for artificial holding structures); crypto at the recipient's residence (the only workable rule given on-chain assets have no physical situs). Chains of holding companies are looked through using the OECD's Pillar Two substance tests [8].

## 6. Valuation

The most avoidance-prone area, and historically the most litigated. Rules:

- **Listed assets:** mark-to-market at date of receipt, five-trading-day average to smooth.
- **Real estate:** professional appraisal with rebuttable presumption; HMRC/IRS review and re-appraisal rights. No reliance on frozen cadastral values — the Austrian *Einheitswerte* failure [7] is the canonical counter-example.
- **Unlisted operating businesses:** formal valuation combining DCF and transaction-comparison multiples. Minority-interest and lack-of-marketability discounts are capped (10% and 15% respectively), addressing the aggressive discount-stacking visible in US Tax Court cases such as *Estate of Elkins v. Commissioner* [16] and in UK Business Property Relief valuation disputes [17].
- **IP and royalty streams:** present value of projected cash flows at a statutory discount rate (gilts + 3%), with a mandatory review at each payment event for the first five years.
- **Crypto:** market value at date of receipt using a regulated-exchange reference price; stablecoin receipts at par only where attested by audited reserves.
- **Art and collectibles:** appraisal with review right; audit sampling across the top decile of declared values annually.

## 7. International coordination

The OECD's 2021 two-pillar agreement [8] is the template. A Pillar-Two-analogue minimum standard on inheritance taxation — a floor rate above a floor threshold — removes the race-to-the-bottom dynamic that destroyed Australia's regime [1]. Double-tax treaties are updated to allocate primary taxing rights to the recipient's residence jurisdiction with a credit mechanism for situs-state tax. The Common Reporting Standard [9] is extended to cover cross-border transfers, not merely account balances, with a dedicated annex schedule on trust and foundation distributions.

## 8. The political-economy backstop

Even with all of the above, some avoidance will persist. Robustness rests on two structural features, not on perfect enforcement. *First*, the recipient-based, lifetime-cumulative threshold removes the cheap avoidance routes (spraying gifts across time and across marital units) that a donor-based or annual-reset design leaves open. *Second*, the universal endowment at 25 supplies the political counterweight: when avoidance does occur, the visible cost is borne against a visible universal benefit, not against an abstract Treasury line. This closes the loop identified in [`05-history/abolitions.md`](../05-history/abolitions.md) §"common failure pattern": the abolished regimes failed not because avoidance existed but because avoidance was asymmetric and the beneficiaries of the tax were diffuse. Symmetric design and concrete beneficiaries together make the regime politically durable even when some avoidance leaks through [1][2].

## Sources

1. [Henrekson, M. and Waldenström, D. (2014). *Inheritance Taxation in Sweden, 1885–2004*. IFN Working Paper No. 1032](https://www.ifn.se/wfiles/wp/wp1032.pdf)
2. [OECD (2021). *Inheritance Taxation in OECD Countries*. OECD Tax Policy Studies No. 28](https://www.oecd.org/tax/inheritance-taxation-in-oecd-countries-e2879a7d-en.htm)
3. [HMRC — Inheritance Tax Manual IHTM42000: Relevant Property Regime / 10-year anniversary charge](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm42000)
4. [IRS — Generation-Skipping Transfer Tax (26 U.S.C. Chapter 13)](https://www.law.cornell.edu/uscode/text/26/subtitle-B/chapter-13)
5. [US IRC §877A — Tax responsibilities of expatriation](https://www.law.cornell.edu/uscode/text/26/877A)
6. [HMRC — Residence, Domicile and Remittance Basis Manual RDRM20000 (deemed domicile)](https://www.gov.uk/hmrc-internal-manuals/residence-domicile-remittance/rdrm20000)
7. [Verfassungsgerichtshof Österreich — Decisions G 54/06 (2007) and G 23/07 (2007)](https://www.vfgh.gv.at/)
8. [OECD/G20 Inclusive Framework (2021). *Statement on a Two-Pillar Solution to Address the Tax Challenges Arising from the Digitalisation of the Economy*](https://www.oecd.org/tax/beps/statement-on-a-two-pillar-solution-to-address-the-tax-challenges-arising-from-the-digitalisation-of-the-economy-october-2021.pdf)
9. [OECD — Common Reporting Standard (Standard for Automatic Exchange of Financial Account Information)](https://www.oecd.org/tax/automatic-exchange/common-reporting-standard/)
10. [US IRC §2503 (annual gift exclusion) and §101 (life-insurance proceeds)](https://www.law.cornell.edu/uscode/text/26/2503)
11. [HMRC Form IHT403 — Gifts and other transfers of value](https://www.gov.uk/government/publications/inheritance-tax-gifts-and-other-transfers-of-value-iht403); [IRS Form 709 — US Gift (and GST) Tax Return](https://www.irs.gov/forms-pubs/about-form-709)
12. [Perpetuities and Accumulations Act 2009 (UK)](https://www.legislation.gov.uk/ukpga/2009/18/contents)
13. [HMRC — IHTM20000: life policies and the "written in trust" route](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm20000)
14. [Netherlands — Wet inkomstenbelasting 2001, art. 4.16 (exit tax on substantial shareholdings)](https://wetten.overheid.nl/BWBR0011353/)
15. [Norwegian Ministry of Finance — Prop. 1 LS (2022–2023), wealth-tax and exit-tax amendments; coverage in OECD (2023), *Tax Policy Reforms 2023*](https://www.oecd.org/tax/tax-policy-reforms-26173433.htm)
16. [*Estate of Elkins v. Commissioner*, 767 F.3d 443 (5th Cir. 2014)](https://www.courtlistener.com/opinion/2680533/estate-of-elkins-v-commr/)
17. [HMRC — Inheritance Tax Manual IHTM25000: Business Property Relief and valuation](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm25000)
