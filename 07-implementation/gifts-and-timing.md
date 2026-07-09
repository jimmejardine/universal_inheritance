# Gifts and Timing

**Executive summary.** A death-time tax is trivially avoided by giving before death, which is why the proposal taxes lifetime receipts on one cumulative ledger; this file works through the operational mechanics — cumulation bookkeeping, deathbed transfers, the pre-commencement gift rush, cash traceability, and the third-party reporting mesh that catches undeclared gifts. The central design claim: the UK's seven-year rule is a case study in how *not* to handle timing, and lifetime cumulation dissolves the entire category of timing games rather than regulating them.

## 1. Why the seven-year rule fails, and what replaces it

Current UK IHT treats lifetime gifts as "potentially exempt transfers": survive seven years and the gift escapes tax entirely, with taper relief on the way [1]. The consequences are well documented (OTS, IFS [2]):

| Feature of the 7-year rule | Consequence |
|---|---|
| Gifts expire from the tax base | The healthy, advised wealthy give early and often, escaping tax; sudden death taxes the unlucky and the unadvised |
| Clock per gift | Serial gifting programmes ("annual settlement conveyor") are standard planning |
| Estate-side accounting | Recipient's total receipts are invisible; spraying gifts across children and grandchildren multiplies nil-rate bands |
| Taper relief on the *tax*, not the value | Widely misunderstood; benefits large gifts most |

The effective inheritance-tax rate consequently *falls* with estate size at the very top — the inverse-incidence pattern that the abolitions literature identifies as the legitimacy-killer ([`../05-history/abolitions.md`](../05-history/abolitions.md)).

**Lifetime cumulation replaces all of it.** Every taxable receipt, whenever made, joins the recipient's single lifetime total ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §2); nothing expires, nothing tapers, and the donor's death date is irrelevant to the arithmetic. Timing is no longer a tax variable. Giving early still has real advantages (the recipient enjoys the money sooner; growth accrues in the recipient's hands) — those are legitimate and untouched. What disappears is the *tax* reward for beating the actuarial clock.

## 2. Cumulation mechanics in practice

- **The ledger is the recipient's, for life.** Each declared receipt above the de-minimis allowance ([boundary-problem.md](boundary-problem.md) §1) posts to the Central Register of Receipts with date, donor, asset class, and value. Headroom remaining is visible to the taxpayer through their Government Gateway / IRS online account, like a pension annual-allowance tracker — see [administration.md](administration.md).
- **Order of operations is mechanical:** receipts fill remaining headroom at 0%; the excess is taxed at 100% at the tax point. No averaging, no carry-back.
- **Valuation disputes do not reopen the ledger** retroactively except for fraud: a receipt revalued on audit adjusts the ledger at the original date, cascading forward through subsequent entries — which is why early entries must be right, and why the audit lottery in [valuation.md](valuation.md) §8 samples below-threshold returns too.
- **Deathbed transfers are a non-event.** A gift made the week before death and a bequest made at death post identically. The entire genre of *donatio mortis causa* planning, deathbed-marriage-adjacent transfers, and last-minute settlement drafting loses its object.

## 3. The pre-commencement gift rush

The dangerous timing game is not within the regime but *before* it: between announcement and commencement, every advised family has an incentive to shovel wealth to heirs under the old rules. Sweden's pre-abolition experience ran in reverse (transfers delayed to beat repeal), demonstrating how responsive transfer timing is to known regime changes [3]. Handling this belongs to the transition design and is treated fully in [`../15-transition/announcement-effects.md`](../15-transition/announcement-effects.md) and [`../15-transition/grandfathering.md`](../15-transition/grandfathering.md); the commitments that matter here:

- **Anti-forestalling from announcement date.** The legislation applies ledger inclusion to gifts made on or after the day the bill is announced — standard practice for UK anti-avoidance measures, which routinely take effect from announcement to kill exactly this window [4].
- **Pre-regime receipts** are handled by the transitional 50%-weight election in [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §2, which gives honest declaration a positive value and leaves the silent with assets they cannot re-gift without crystallising.
- The residual rush into the announcement itself is a one-off level effect, not a structural leak: it advances transfers that would have escaped anyway under the old regime.

## 4. Cash and traceability

Cash is the anonymity asset. Three containments, none perfect, jointly adequate:

- **Cash is self-limiting at scale.** Moving dynastic sums (£500k+) in physical cash collides with existing anti-money-laundering architecture: deposit reporting, cash-transaction thresholds, source-of-funds checks on any re-entry into property, securities, or banking [5]. The heir who receives a suitcase can hold a suitcase; spending or investing it re-enters the reported economy, where unexplained wealth meets §6's mesh and, at the top end, unexplained-wealth-order-style powers [6].
- **De-minimis absorbs the legitimate small end.** Birthday cash never needed tracing ([boundary-problem.md](boundary-problem.md)).
- **Presumption on unexplained accretions.** Where audit finds assets materially exceeding declared receipts plus taxed income, the excess is a rebuttable deemed receipt — burden on the taxpayer, mirroring the logic HMRC already applies in discovery assessments and the US applies in net-worth-method reconstructions [7].

## 5. Third-party reporting: the mesh

Self-declaration is the front door; the mesh catches what walks past it. Feeds into the Central Register, all from systems that already exist:

| Source | What it reports | Existing infrastructure |
|---|---|---|
| Banks and payment institutions | Transfers above a reporting floor between accounts of connected persons; large third-party credits | AML/suspicious-activity plumbing; CRS for cross-border [8] |
| Land Registry / county recorders | All conveyances, with consideration; flags for undervalue vs automated valuation and for connected parties | Price-paid data already public (UK) |
| Companies House / state registries | Share transfers and new allotments in private companies involving connected persons | PSC (persons of significant control) register [9] |
| Probate registries | Full estate inventories and beneficiary schedules | Estate Information Return ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §5) |
| Insurers | Death-benefit payouts and policy assignments | Existing chargeable-event reporting |
| Trustees | Distributions and beneficiary changes | Trust Registration Service (UK) / Form 3520 (US) — see [trusts-and-vehicles.md](trusts-and-vehicles.md) |

Matching declared receipts against the mesh is a data-reconciliation problem of the kind HMRC's Connect system already performs across income-tax data [10]. Undeclared gifts surface as mismatches; mismatches feed the risk-scored audit queue in [enforcement.md](enforcement.md). Offshore and wrapper-based evasion of the mesh is treated in [trusts-and-vehicles.md](trusts-and-vehicles.md) and, for emigration, deferred entirely to [`../08-capital-flight/`](../08-capital-flight/).

## Research gaps

- Optimal reporting floor for bank-transfer feeds — too low drowns the system, too high invites structuring just beneath it (structuring itself should be an offence, as in US 31 USC §5324).
- Evidence on gift-timing elasticity around regime changes beyond Sweden (Norway 2014 abolition; German reform windows) — to verify magnitudes for the transition modelling.
- Whether the deemed-receipt presumption on unexplained wealth needs a statutory floor to stay ECHR/due-process-proof.

## Sources

1. [HMRC — IHTM04057 and IHTM14513: potentially exempt transfers and taper relief](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm14513)
2. [OTS, Inheritance Tax Review — Second Report (2019)](https://www.gov.uk/government/publications/ots-inheritance-tax-review-simplifying-the-design-of-the-tax); [IFS, "Reforming Inheritance Tax" (2023)](https://ifs.org.uk/publications/reforming-inheritance-tax)
3. [Henrekson & Waldenström (2014), *Inheritance Taxation in Sweden, 1885–2004*, IFN WP 1032](https://www.ifn.se/wfiles/wp/wp1032.pdf)
4. [HM Treasury / HMRC — anti-forestalling practice in Finance Bills (e.g. announcement-day effect for avoidance measures)](https://www.gov.uk/government/collections/tax-policy-making)
5. [Money Laundering Regulations 2017 (UK)](https://www.legislation.gov.uk/uksi/2017/692/contents); [FinCEN — currency transaction reporting](https://www.fincen.gov/)
6. [Criminal Finances Act 2017 — unexplained wealth orders](https://www.legislation.gov.uk/ukpga/2017/22/contents)
7. [HMRC — discovery assessment powers, TMA 1970 s.29](https://www.legislation.gov.uk/ukpga/1970/9/section/29); *Holland v United States*, 348 U.S. 121 (1954) (net-worth method).
8. [OECD — Common Reporting Standard](https://www.oecd.org/tax/automatic-exchange/common-reporting-standard/)
9. [Companies House — people with significant control register](https://www.gov.uk/guidance/people-with-significant-control-pscs)
10. [HMRC Connect data-matching system — NAO and press coverage](https://www.nao.org.uk/reports/)
