# Administration

**Executive summary.** The Central Register of Receipts defined in [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §6 is the operational heart of the regime: a lifetime ledger per person, fed by probate, third-party reporting, and taxpayer returns. This file specifies how it integrates with probate, what executors must do, what the revenue authority must staff, what it should cost relative to existing taxes, and how privacy, benefits interaction, and appeals are handled.

## 1. The Central Register of Receipts

One ledger per person, keyed to the existing taxpayer identifier (NI number / SSN), holding: dated receipt entries with donor, asset class, and value; remaining threshold headroom; suspended and provisional entries ([digital-and-novel-assets.md](digital-and-novel-assets.md) §2, [trusts-and-vehicles.md](trusts-and-vehicles.md) §3); and links to supporting valuations. The taxpayer sees their own ledger through Government Gateway / IRS Online Account, the way pension annual-allowance and NI-contribution records are already exposed. Nothing in the Register is technologically novel: it is a receivables ledger with identity resolution, smaller in row count than PAYE RTI, which processes the entire national payroll in near-real time [1]. The genuinely hard components are data-matching (donor–recipient linkage across feeds — the problem HMRC's Connect system already solves for income [2]) and identity assurance for people who never previously interacted with the tax system, since the Register must cover every adult, not just current taxpayers — the same population-coverage problem the endowment ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)) has to solve anyway, and the two systems should share the solution.

## 2. Probate integration

Probate is the natural checkpoint for death-time transfers, and the regime strengthens rather than reinvents it:

- **No grant without the Estate Information Return.** The personal representative files a full inventory and beneficiary schedule; the grant of probate/letters of administration issues only after lodgment ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §5). The UK already conditions probate on IHT accounts (the IHT421/probate summary flow), so this is a modification of an existing gate, not a new one [3].
- **Auto-population.** The Return pre-populates each beneficiary's Register entry as *provisional*; the beneficiary's own Receipts Return confirms or disputes within the filing window. Two-sided reporting (executor and recipient) is the structural fraud check — mismatches are audit flags.
- **Clearance.** Executors receive a statutory clearance certificate once assessments are settled, capping their exposure — critical for professional executors' willingness to act.
- **Intestacy and small estates** follow the same path with simplified short-form returns below a materiality floor, keeping the median estate's paperwork trivial: most estates produce receipts nowhere near any recipient's threshold, and their entire obligation is a beneficiary schedule.

## 3. Executor and intermediary obligations

| Actor | Obligation | Sanction for failure |
|---|---|---|
| Personal representative | Estate Information Return; reasonable enquiry for assets incl. digital ([digital-and-novel-assets.md](digital-and-novel-assets.md) §1); distribute only after retaining tax due | Personal liability up to assets distributed (as under existing IHT [3]) |
| Recipient | Receipts Return within 12 months (6 for bequests) | Penalty ladder per [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §5 |
| Banks, registries, insurers, trustees | Third-party feeds per [gifts-and-timing.md](gifts-and-timing.md) §5 | Regulatory penalties, as for CRS/FATCA non-compliance |
| Valuers | Statutory-register duties per [valuation.md](valuation.md) §6 | Licence loss; §6695A-style penalties |

## 4. Staffing and capacity

The receipt-side design economises on the scarcest resource — skilled valuers and investigators — because (a) the long tail of estates is automated end-to-end, (b) mandatory review concentrates expert effort on the small Tier-3 population ([valuation.md](valuation.md) §7), and (c) the taxpayer holding the asset has less informational advantage than an executor valuing someone else's affairs. Capacity needs concentrate in: the valuation office (District Valuer / IRS Engineering & Valuation), trust and offshore specialists, and data engineering for the mesh. The cautionary tale is the chronic under-resourcing that hollowed out US estate-tax audit coverage over the 2010s — IRS estate-tax specialist headcount fell even as planning sophistication rose [4]; the regime's funding rule should hard-wire administration funding as a percentage of assessed liabilities, insulating it from the appropriations sabotage anticipated in [`../10-opposition/sabotage-after-passage.md`](../10-opposition/sabotage-after-passage.md).

## 5. Cost to collect

Directional benchmarks (all to verify against current HMRC/IRS publications):

| Tax | Cost-to-yield, order of magnitude |
|---|---|
| UK IHT historically | ~1% [5] |
| UK income tax (PAYE-dominated) | well under 1% [5] |
| Complex self-assessed taxes generally | low single-digit % |
| This regime, projected | ~1–2% initially, falling as the Register matures |

The regime should be *cheaper per pound* than current IHT at maturity for structural reasons: lifetime data accumulates instead of being reconstructed at death (the seven-year gift archaeology that consumes current IHT casework disappears — [gifts-and-timing.md](gifts-and-timing.md) §1), third-party feeds replace manual disclosure, and the sharp 0/100 kink eliminates the rate-banding and relief-interaction complexity that the OTS identified as the current tax's cost driver [6]. Against this: more people file (recipients, not estates) and audit intensity must be higher at a 100% marginal rate. Net projection needs modelling.

## 6. Interaction with means-tested benefits

A receipt below threshold is tax-free but is still *wealth*, and means-tested systems (Universal Credit capital limits; Medicaid asset tests) would otherwise claw at modest inheritances with effective marginal rates the tax itself never imposes. Design commitments: (a) receipts data flows one way — the Register may verify a benefit claimant's declared capital, but benefit agencies do not receive proactive feeds of sub-threshold family gifts, which would turn the Register into a means-testing surveillance tool and poison consent for the whole system; (b) the **universal endowment is statutorily disregarded** for all means tests, as argued in [`../02-proposal/endowment.md`](../02-proposal/endowment.md) — a five-figure grant that switches off a claimant's housing support is a political and moral own-goal. Existing capital-limit rules continue to apply to inherited wealth as they do today; the regime neither worsens nor is responsible for fixing them, but the manifesto should note the interaction honestly.

## 7. Privacy and data protection

The Register concentrates sensitive family financial data and must be designed for GDPR/data-protection compliance from the start: purpose limitation (transfer-tax administration and endowment eligibility only), access on a need-to-know audit trail, no public inspection of individual ledgers, taxpayer subject-access to their own record, and statutory bars on onward sharing beyond existing tax-information gateways. The political dimension matters as much as the legal: opponents will run "Big Brother ledger of every family gift" ([`../10-opposition/attack-playbook.md`](../10-opposition/attack-playbook.md)), and the honest response is that the Register holds *less* than banks already report under AML/CRS, that sub-de-minimis gifts never enter it at all ([boundary-problem.md](boundary-problem.md) §4), and that the median citizen's ledger is empty or trivial. Aggregate, anonymised Register statistics should be published annually — the transparency dividend that makes wealth-transfer flows visible to researchers for the first time.

## 8. Appeals and dispute resolution

Standard two-track design, reusing existing machinery: internal statutory review, then the First-tier Tribunal (Tax Chamber) and onward appeals (UK) / IRS Independent Office of Appeals and Tax Court (US) [7]. Specifics: valuation disputes go to a specialist valuation track with the blind-second-appraisal file ([valuation.md](valuation.md) §6) as the evidential baseline; the binding pre-clearance ruling ([valuation.md](valuation.md) §7) removes the biggest dispute class ex ante; hardship deferral of *payment* (not liability) pending appeal prevents forced sales during disputes, answering the due-process attack anticipated in [`../10-opposition/legal-challenges.md`](../10-opposition/legal-challenges.md).

## 9. A typical estate's journey

The median case should be near-invisible; the flow for an ordinary £600k estate split between two children:

| Step | Actor | Action | Elapsed |
|---|---|---|---|
| Death registered | Registrar | Auto-notification to Register | Day 0 |
| Estate Information Return | Executor | Online inventory + beneficiary schedule; mostly pre-populated from bank/registry feeds | ~3 months |
| Probate granted | Court | Gate passes on lodgment | ~4 months |
| Provisional ledger entries | Register | £300k posts provisionally to each child | Automatic |
| Receipts Returns | Each child | One-screen confirmation; both well within headroom | By 6 months |
| Clearance | HMRC | Executor certificate issues; case closes with zero tax | ~7 months |

Neither child pays anything, meets a valuer, or files more than a confirmation screen. The contrast with the current IHT400 experience — routinely described as the worst administrative encounter bereaved families have with the state [6] — is itself a selling point: for the 90%+ of families below threshold, this regime is *less* paperwork than the tax it replaces.

## Research gaps

- Actual current HMRC IHT and IRS estate-tax cost-to-yield and headcount figures (to verify §5 table).
- Identity-assurance coverage for Register onboarding of non-filers — lessons from Child Trust Fund dormancy and endowment design.
- Volume modelling: expected annual Receipts Returns by tier under the £500k threshold.

## Sources

1. [HMRC — PAYE Real Time Information programme](https://www.gov.uk/government/publications/real-time-information-improving-the-operation-of-pay-as-you-earn)
2. [NAO / press coverage of HMRC's Connect data-matching system](https://www.nao.org.uk/reports/)
3. [HMRC — probate and IHT process (IHT400/IHT421); personal representative liability, IHTM30000](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm30000)
4. [TIGTA and ProPublica reporting on declining IRS estate-and-gift audit resources](https://www.propublica.org/series/gutting-the-irs) (to verify current figures)
5. [HMRC Annual Report and Accounts — cost-of-collection tables](https://www.gov.uk/government/collections/hmrcs-annual-report-and-accounts)
6. [OTS — Inheritance Tax Review, First and Second Reports (2018–19)](https://www.gov.uk/government/publications/ots-inheritance-tax-review-simplifying-the-design-of-the-tax)
7. [First-tier Tribunal (Tax Chamber)](https://www.gov.uk/courts-tribunals/first-tier-tribunal-tax); [IRS Independent Office of Appeals](https://www.irs.gov/appeals); [US Tax Court](https://www.ustaxcourt.gov/)
