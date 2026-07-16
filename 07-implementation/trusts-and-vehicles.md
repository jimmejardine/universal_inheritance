# Trusts and Vehicles

**Executive summary.** Trusts, foundations, family investment companies, and insurance wrappers exist in large part to separate legal ownership from enjoyment — which is precisely the separation a receipts tax must see through. This file specifies the operational look-through and attribution rules (tax distributions as receipts; deemed periodic charge on undistributed wealth; settlor/beneficiary attribution for controlled vehicles) and grounds each in a working precedent: the UK relevant-property regime, US grantor-trust rules, and CFC legislation.

## The threat model

The design commitments are set in [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §§2–3; this file is about making them operate. The generic move behind every vehicle is the same: interpose an entity so that no individual ever *receives* anything, while the family enjoys the wealth indefinitely.

| Vehicle | The move | Counter-rule |
|---|---|---|
| Discretionary trust | No beneficiary has an entitlement until trustees decide; wealth waits out the tax | Distribution charge + deemed periodic charge (§1) |
| Spousal life-interest trust (IPDI-style) | Claim spousal relief for a life interest while pointing the remainder at the children | Deferral continues for the life tenant only; remaindermen charged at full value (§1b) |
| Liechtenstein/Panama-style foundation | Orphan entity, no owner at all; "beneficiaries" informally serviced | Recharacterisation as trust-equivalent; attribution (§2) |
| Family investment company (FIC) | Parents keep voting shares, children hold growth shares; value accrues without a "transfer" | Value-shift rules + attribution (§3) |
| Life-insurance / offshore bond wrapper | Transfer dressed as policy proceeds | Full look-through, per [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §3 |
| Offshore trust with offshore trustees | Same as above, plus enforcement distance | Trustee registration, agent liability, exchange of information (§4) |

## 1. Trusts: distribution charge plus deemed periodic charge

Two charges, together closing both exits:

**(a) Distribution charge.** Any distribution — income, capital, or in-kind benefit (rent-free use of trust property is a distribution at market rate, aligning with [boundary-problem.md](boundary-problem.md) §3) — is a taxable receipt by the beneficiary at that date, posting to their lifetime ledger. This is the easy half; Ireland's CAT already taxes trust appointments to beneficiaries this way [1].

**(b) Deemed periodic charge on undistributed wealth.** The distribution charge alone invites the *warehouse strategy*: leave wealth in trust for eighty years, compound tax-free, distribute to remote descendants each of whom has fresh threshold headroom. The counter is a periodic charge on wealth that stays warehoused: every **10 years**, undistributed trust capital attributable to the beneficiary class is deemed received pro-rata by the identifiable beneficiaries (or, where the class is open, charged at the trust level at the top rate on a statutory fraction). The UK has charged discretionary-trust capital periodically since capital transfer tax in 1975, with the 10-yearly anniversary charge in its modern relevant-property form dating from 1982 — proof that periodic charging of discretionary trusts is administrable — but at a maximum of 6% per decade it functions as a modest rent for dynastic warehousing rather than a deterrent [2]. The proposal keeps the machinery (valuation dates, proportionate exit charges between anniversaries) and raises the consequence: deemed receipts consume real ledger headroom, and above headroom they are taxed at 100%. The 80-year perpetuity backstop ([`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §2) terminates anything that tries to wait even the periodic charge out.

**Interaction rule.** Amounts charged periodically create a credit against the later distribution charge for the same value — no double taxation, no gap.

## 1b. Spousal life interests: the IPDI structure

The classic will structure — a life interest in the estate to the surviving spouse, remainder to the children — must be mapped onto the deferred spousal relief of [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §1, or it becomes the cheap way to claim spousal treatment for wealth that is really pointed at the next generation. The rules:

- **The life interest is spousal relief in trust form: the deferral continues.** The survivor's entitlement to income and enjoyment of the settled property is untaxed and consumes no threshold, exactly as an outright spousal transfer would be. The trust corpus (above the standard threshold) carries the deferred-charge tag at trust level; while it supports a spouse's life interest — in this marriage or, if the fund is resettled on a later spouse, a subsequent one — nothing crystallises. The survivor's benefits are never distributions within §1(a); the periodic charge of §1(b) does not run against corpus supporting a qualifying spousal life interest. One boundary, owned by [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §1 ("The widow swap, priced honestly."): *qualifying* means the first marital hop — a life interest for the accumulator's own widow or widower; from the second hop onward (tagged corpus supporting a spouse who was never the accumulator's partner), the §1(b) periodic charge runs against the corpus exactly as it would in a discretionary trust — no arbitrage between settling on trustees and settling by marriage.
- **The remaindermen's receipt is charged in full when the life interest ends.** At the life tenant's death (or earlier termination in the remaindermen's favour), the remaindermen receive the corpus at its full market value on that date, posting to each remainderman's ledger as an ordinary receipt against their lifetime threshold. The remainder interest cannot be pre-received at a discounted actuarial value: the receipt is valued when possession falls in, not when the interest is drafted.
- **Contrast with current UK law.** Under the IPDI regime (IHTA 1984 s.49A, inserted by FA 2006), a spousal life interest created by will takes the s.18 spouse exemption on first death and the settled property is taxed as part of the *life tenant's* estate on second death [9] — deferral to the survivor's death, estate-side. This design keeps that deferral logic but moves the charge to the recipient axis: the tax lands on the remaindermen's ledgers at full value, with no nil-rate-band reset, no estate-side reliefs interposed, and no re-opening of the gap between "spousal exemption" and "who ultimately takes."

Cross-reference: the deferred-charge tag, the exit-crystallisation rule, and the serial-marriage analysis are owned by [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §1.

## 2. Foundations and ownerless entities

Civil-law foundations (*Stiftungen*, Panamanian *fundaciones*) and purpose trusts are designed to have no owner and no beneficiary with rights — the "orphan structure" familiar from leaks such as the Panama and Pandora Papers [3]. The operational rule is **substance over form, by statutory checklist**: an entity is a *trust-equivalent* if (i) it holds assets contributed gratuitously, (ii) any person may benefit at the discretion of its organs, and (iii) the contributor or their family retains influence over, or expectation of, benefit. Trust-equivalents are taxed under §1, with the founder treated as settlor and the de-facto benefited class as beneficiaries. The precedent is direct: UK transfer-of-assets-abroad legislation and the US grantor-trust rules (IRC §§671–679) both already attribute entity income to the person who retains dominion regardless of the label on the entity [4]; the foreign-grantor-trust rules in §679 attribute a foreign trust's income to a US settlor with US beneficiaries almost mechanically. The proposal ports this attribution from *income* to *receipts*.

## 3. Family investment companies and value-shifting

The FIC is the current UK planner's favourite: parents subscribe for voting/frozen shares, children for growth shares; future appreciation accrues to the children with no transfer ever recorded [5]. Counters:

- **Value-shift as receipt.** Any arrangement whose effect is to shift value between share classes held by connected persons is a taxable receipt of the shift, valued at the date of the arrangement — the analogue of existing CGT value-shifting rules (TCGA 1992 ss.29–34) applied on the receipts axis [6].
- **Attribution while control is retained.** While the parents control the company, growth accruing to children's shares is provisionally attributed but not yet charged (it may still be reversed); the charge crystallises at the earlier of distribution, disposal, or loss of parental control. This mirrors CFC logic — controlled foreign company rules attribute a controlled entity's profits to the controller rather than waiting for repatriation [7] — inverted to attribute to the *benefited* rather than the controller.
- **Companies House PSC data** ([gifts-and-timing.md](gifts-and-timing.md) §5) makes connected-person share structures visible at scale; new allotments of growth shares to minors in family-controlled companies are an automatic audit flag.

## 4. Offshore structures and enforcement distance

An offshore trustee outside the jurisdiction cannot be compelled directly; the regime therefore attaches consequences to every onshore touchpoint:

- **Registration or blockage.** Trusts and trust-equivalents with UK/US-resident settlors, beneficiaries, or assets must register (extending the UK Trust Registration Service and US Form 3520/3520-A regimes [8]); unregistered structures cannot hold UK/US land or securities in registered form, cannot open accounts at institutions with UK/US presence (banks bear the verification duty, as under FATCA), and distributions from them are presumed fully taxable with the burden on the recipient to prove headroom.
- **Recipient liability is the anchor.** However exotic the structure, the money must eventually reach a person; a UK/US-resident recipient of any benefit from an unregistered structure owes the tax personally, with penalties for non-declaration ([enforcement.md](enforcement.md)). Enforcement rides the beneficiary, who is within reach, not the trustee, who is not.
- **Information exchange.** CRS already collects controlling-person data on passive entities; the extension to transfer reporting is specified in [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §7. Where the settlor or beneficiary emigrates as well, the problem becomes capital flight and is treated in [`../08-capital-flight/exit-options.md`](../08-capital-flight/exit-options.md) and [`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md).

## 5. Precedent summary

| Precedent | What it proves | What the proposal changes |
|---|---|---|
| UK relevant-property regime (10-year charge) [2] | Periodic charging of discretionary trusts is administrable at national scale | Charge lands on beneficiaries' ledgers at real rates, not 6%/decade at trust level |
| US grantor-trust rules §§671–679 [4] | Statutory attribution through entities to the person with dominion works, and is drafted law, not doctrine | Attribution axis flipped from income to receipts |
| CFC rules (UK Part 9A TIOPA; US subpart F/GILTI) [7] | Anti-deferral through controlled entities survives decades of planning pressure | Same anti-deferral logic aimed at gratuitous value, not business profits |
| Ireland CAT trust appointments [1] | Recipient-side taxation of trust distributions is a solved problem | Adds the periodic charge Ireland lacks |
| UK IPDI — IHTA 1984 s.49A [9] | Spousal life interests already carry the spouse exemption with tax deferred to the life tenant's death | Charge moves to the remaindermen's ledgers at full value, integrated with the deferred spousal tag ([`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §1) |

The rhetorical point for [`../09-objections/avoidance.md`](../09-objections/avoidance.md): every rule in this file is an existing rule somewhere, doing this job now. The proposal's novelty is assembling them on one axis, not inventing machinery.

## Worked example: the warehouse trust

The Harrington 1990 Settlement holds £40m of listed equities for "the descendants of the settlor," none with fixed entitlements. Under current UK rules it pays at most 6% per decade and can drip capital to grandchildren with fresh planning each generation. Under this regime:

| Event | Charge |
|---|---|
| Regime commencement | Trust registers; beneficiary class identified (2 children, 5 grandchildren) |
| Year 3: £1m appointed to a grandchild | Receipt posts to her ledger; £500k within headroom at 0%, £500k taxed at 100% |
| Year 10: first anniversary, £39m undistributed | Deemed received pro-rata across the seven identifiable beneficiaries; roughly £5.6m each, taxed at 100% above each ledger's remaining headroom, creditable against future distributions |
| Trustee response | Distribute early to spread across genuine headroom, or wind up — either way the warehouse empties within a generation |

The design intent is visible in the trustee's option set: every path leads to wealth reaching identifiable people and their ledgers within a bounded period. What no path permits is the current equilibrium — capital compounding ownerless across generations at a 6%-per-decade toll.

## Research gaps

- Behaviour of the existing UK 10-year charge population if the rate rose sharply — how much relevant-property wealth would distribute early vs migrate offshore (to model against HMRC's annual trust statistics).
- Whether the FIC provisional-attribution rule can be drafted to avoid charging reversible paper growth (interaction with valuation volatility).
- Treatment of genuinely charitable foundations with family board control — boundary with [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §4's control test.

## Sources

1. [Irish Revenue — CAT treatment of trusts and appointments; discretionary trust tax](https://www.revenue.ie/en/gains-gifts-and-inheritance/discretionary-trust-tax/index.aspx)
2. [HMRC — IHTM42000: relevant property regime, principal (10-year) charge](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm42000)
3. [ICIJ — Panama Papers and Pandora Papers investigations (offshore foundations and orphan structures)](https://www.icij.org/investigations/)
4. [US IRC §§671–679 — grantor trust rules](https://www.law.cornell.edu/uscode/text/26/671); [UK transfer of assets abroad — ITA 2007 Part 13 Ch 2](https://www.gov.uk/hmrc-internal-manuals/international-manual/intm600000)
5. [STEP / professional literature on family investment companies; HMRC's (disbanded) FIC review unit, reported 2021](https://www.step.org/)
6. [TCGA 1992 ss.29–34 — value shifting](https://www.legislation.gov.uk/ukpga/1992/12/section/29)
7. [TIOPA 2010 Part 9A — UK CFC rules](https://www.legislation.gov.uk/ukpga/2010/8/part/9A); [US subpart F, IRC §§951–965](https://www.law.cornell.edu/uscode/text/26/951)
8. [UK Trust Registration Service (MLR 2017 as amended)](https://www.gov.uk/guidance/register-a-trust-as-a-trustee); [IRS Forms 3520 / 3520-A — foreign trust reporting](https://www.irs.gov/forms-pubs/about-form-3520)
9. [HMRC — IHTM16061: Finance Act 2006 interests in possession, including the immediate post-death interest (IHTA 1984 s.49A)](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm16061)
