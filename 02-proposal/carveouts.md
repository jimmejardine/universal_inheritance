# Carve-outs and Reliefs

**Executive summary.** Inheritance tax regimes do not die from their headline rate; they die from their hard cases. This file designs the exemptions and reliefs — spousal, charitable, dependant, residence, business, farm, collectible, pension — needed to make a 100%-above-threshold recipient tax durable, drawing on the documented leaks in UK BPR/APR, US QFOBI and section 2032A, and German *Erbschaftsteuer* business relief.

## Headline design commitments

- Unlimited spousal/civil-partner relief — transfers between partners are never taxed and never consume threshold, for every widow and widower, every time — structured as a **deferral with a tracked charge**, not a clean exemption: above-threshold corpus carries a deferred-charge tag that crystallises when the wealth exits the marriage chain to a non-spouse (§1). Full exemption for registered charities, with a statutory anti-cycling rule [1].
- Full exemption for transfers settled for the lifetime care of a disabled dependant, via a regulated care trust [2].
- Principal-residence relief is *personal to the occupier*: deferral-until-sale for a surviving spouse or dependent occupier, not a free pass to adult children who have already moved out [3].
- Operating family businesses: tax crystallises on receipt but payment is deferred up to 30 years at gilts/Treasuries + 1%, secured against business equity, with an optional non-voting state preferred-equity stake [4].
- Operating family farms: identical 30-year deferral, gated by a working-farm test (active farming, minimum acreage, primary occupation) to close the "hobby farm" leak documented in APR and section 2032A literature [5][6].
- Twenty-year claw-back on business and farm reliefs if the asset is sold, liquidated, or converted to non-qualifying use [7].
- Collectibles receive no special relief except a narrow, public-access conditional exemption modelled on HMRC's cultural-property scheme [8].
- Pensions are taxed on draw-down as income, not at death, closing the 2015 UK pension-freedom IHT shelter identified by the IFS and OTS [9].

## 1. Spouse / civil partner

**What it covers.** Transfers of any size between legally married spouses or registered civil partners — lifetime gifts, transfers on death, and settlements on divorce or dissolution.

**Mechanism — DESIGN DECISION: unlimited deferral with a tracked charge, not a clean exemption.** Transfers between partners are never taxed and never consume the recipient's threshold — for every widow and widower, every time, however many marriages deep. No grieving spouse ever sees a bill, a form beyond probate, or a question about their marriage. But large relieved transfers are not invisible to the Register: corpus received under the relief in excess of the standard threshold posts to the survivor's ledger as a **deferred-charge tag** — an amount and a source line, with no tax due while the wealth stays inside a marriage (from the second marital hop the tagged corpus itself meets the trusts' periodic charge — see "The widow swap, priced honestly." below). Any exit of tagged wealth to a non-spouse — bequest, gift, trust distribution, debt forgiveness, or any other transmission, however many marriages later — is an ordinary receipt against the *ultimate recipient's* lifetime threshold, exactly as [mechanism.md](mechanism.md) §1 provides, with the tag supplying the audit trail that distinguishes relayed corpus from the survivor's own wealth. What existing regimes call the "second death" is thereby generalised to **exit from the marriage chain**: wealth may relay spouse-to-spouse indefinitely, and the deferred claim rides along until the wealth leaves the chain — which, since every holder dies and only non-spouses can ultimately take, it must. Ordinary widowed households never see a tag; the relief they experience is indistinguishable from today's exemption.

**Considered and rejected: duration rules and genuineness tests.** Two conventional anti-abuse instruments were examined and set aside. *Minimum-duration rules* have real precedent — US Social Security requires nine months of marriage before survivor benefits vest, with narrow accident/active-duty exceptions (20 CFR §404.335) [19], and German survivor-pension law presumes a marriage of under one year is a *Versorgungsehe* (a marriage for the pension) and denies the widow's pension unless the presumption is rebutted (§46(2a) SGB VI) [20]. *Sham-marriage genuineness tests* mirror immigration law, and were this design's own earlier answer. Both fail the same two ways: they are intrusive — the state adjudicating, at the graveside, why two people married — and they are beatable, because a *genuine* marriage entered partly for tax passes any duration or genuineness test; the prohibited degrees (Marriage Act 1949, Sch. 1) bar marrying one's own descendants but not an unrelated chosen successor [18]. The deferred tag makes marriage timing and motive **irrelevant**: a deathbed marriage or a serial chain buys entry to the relay, never escape from the charge, so the state never needs to inquire into the quality of anyone's marriage. The grieving widow keeps everything, untaxed and unquestioned; the fisc keeps its claim.

**Precedent.** The unlimited relief itself follows the UK spousal exemption (IHTA 1984 s.18) and the US unlimited marital deduction (IRC §2056), both long-standing and politically untouchable [1]; removing them would generate precisely the "grieving widow" headline that ended Swedish and Austrian estate taxation [10]. Deferral-with-a-tracked-charge is *also* precedented, in current law: the **US Qualified Domestic Trust (QDOT, IRC §2056A)** converts the marital deduction into exactly this structure where the surviving spouse is not a US citizen — the deduction is allowed only for property passing into a qualified trust, and the deferred estate tax is collected on corpus distributions from the trust and on the survivor's death [21]. The **UK immediate post-death interest (IPDI, IHTA 1984 s.49A)** shows the spousal exemption already operating through life-interest structures, with tax deferred to the life tenant's death [22] — the structure whose receipts-tax treatment is specified in [`../07-implementation/trusts-and-vehicles.md`](../07-implementation/trusts-and-vehicles.md) §1b. And the problem class is documented, not hypothetical: the Law Commission's *Modernising Wills* report (May 2025) recommended abolishing the revocation of wills by marriage in part because the rule is exploited through **predatory marriages** to vulnerable, often elderly, testators [23].

**The serial chain, priced honestly.** Under the previous clean exemption, capital could in principle chain down a generation over two hops (dynast marries younger spouse; the surviving spouse later marries the dynast's grandchild, who is unrelated to *them*), and nothing bounded the chain at two hops: the taxable second death receded indefinitely. Real frictions attend every hop — each transfers full, defection-capable beneficial ownership to an outsider (any binding side-arrangement to pass the wealth on is a settlement in substance, caught by [avoidance.md](avoidance.md) §3A); the trust required compounds adversely with each successive spouse; the chain runs on mortality orderings it cannot control; and every marriage adds divorce exposure — but the design no longer depends on those frictions. Structurally, the tag reveals what the chain always was: it defers the fisc but never delivers to the dynasty. Any exit to the bloodline — a bequest or gift to the dynast's child, grandchild, or chosen successor — is a receipt against that recipient's threshold, and even *marrying* a dynastic member into the chain buys them only what every surviving spouse gets: lifetime enjoyment of tagged corpus they can never pass onward untaxed. The abuse was a fiscal perpetuity, not a dynastic escape; the tag ends the perpetuity while leaving every widow and widower exactly as the headline promises.

**The dynastic alliance, priced honestly.** The oldest strategy of all — two great fortunes merging estates through their children's marriage, as in times of old — runs backwards under a receipts tax. Family A (£1bn) marries its child to Family B's (£1bn). The wedding moves nothing: transfers *between the spouses* are relieved (and tagged, as above), but neither family can pass wealth to the *other family's* child except as an ordinary receipt against that child's £500k lifetime threshold — the receiver-centric rule of [mechanism.md](mechanism.md) §2 cumulates receipts **from all sources**, so a gift from the in-laws consumes exactly the headroom a gift from the child's own parents would. And the joint grandchildren make the alliance worse, not better: each is one recipient with one £500k lifetime cap standing against *both* billions. Had the houses stayed apart and each produced four grandchildren, the two fortunes would face eight ledgers and £4m of combined grandchild headroom; allied, four joint grandchildren give them four ledgers and £2m — merging two descendant pools into one joint set strictly *reduces* combined family headroom, because headroom scales with the number of distinct recipients, not the grandeur of the union. Under primogeniture and zero transfer tax the alliance marriage did the opposite work: it concentrated two estates onto one heir — which is exactly the outcome the 100% band annihilates, so the strategy of old inverts into a tax penalty. This is the mechanism behind the marriage-market prediction in [`../16-second-order/family-and-culture.md`](../16-second-order/family-and-culture.md) §2: the "merger of estates" leaves the marriage market because it no longer has an object.

**The widow swap, priced honestly.** The sharper revival: House A's son marries House B's widow, and House B's son marries House A's widow. Each widow carries her late husband's tagged fortune into the new marriage and passes it, spouse-to-spouse and relieved, to the other house's young heir; each house thereby holds the other's billion, and reciprocity substitutes for trust — the hostage exchange of the old royal houses, relaying wealth down the generations two hops at a time. First, what the tag already denies. Every hop stays tagged, so the swap perpetuates a *usufruct*, not an inheritance: no child of either bloodline ever receives untaxed, and every attempted exit to a descendant — bequest, gift, anything — is a charged receipt against that recipient's threshold. Any **binding** compact between the houses — cross-marriage covenants, reciprocal wills, an enforceable promise to relay — is a settlement in substance under [avoidance.md](avoidance.md) §3A: looked through and charged on the intended takers' ledgers at once. The pact must therefore run on unenforceable honour between two families each holding the other's billion, with total defection exposure at every node (a widow simply keeps it; a son declines the marriage; one divorce court splits it) and maximum visibility on the Register, where two billion-pound tags shuttling between the same two surnames is not a subtle pattern. But the design does not rest on frictions. **DESIGN DECISION — chain-hop parity with trusts.** Hop 1 — the widow or widower of the person who accumulated the wealth, the deceased's actual partner — is untouched: full deferral, forever, no charge, no inquiry, exactly as the headline promises. From hop 2 onward — tagged corpus passing under the relief to a spouse who was never the accumulator's partner — the tagged corpus enters the same relevant-property-equivalent periodic-charge regime that perpetual trusts face, at the rate and on the machinery of [`../07-implementation/trusts-and-vehicles.md`](../07-implementation/trusts-and-vehicles.md) §1: deemed periodic receipts on the ten-year anniversary cycle, creditable against the eventual exit charge. The rationale is parity, not suspicion: a marital chain beyond the first hop is economically a settlement — corpus warehoused for enjoyment while pointed onward — and without the rule, marriage would be a strictly *better* trust (same warehousing, no periodic charge), an arbitrage the design cannot leave open. With it, the widow swap collapses to perpetual-trust economics, which the design already prices; the relay buys the houses nothing a discretionary trust would not, at far higher human cost. What the rule does **not** do: it never touches any actual widow or widower of the wealth-builder, and it never inquires into any marriage's motive or quality — it keys off ledger facts already on the Register (whose accumulation the tag records, and how many spousal hops it has travelled), never off the marriage. The grieving widow or widower of the person who built the fortune keeps everything, untaxed and unquestioned, every time; only wealth relayed onward into marriages the builder was never part of meets the trust clock.

## 2. Disabled dependants

**What it covers.** Transfers, in life or at death, settled for the care and maintenance of a person with a qualifying long-term disability (DWP/SSA definitions).
**Mechanism.** Funds must flow into a regulated care trust (analogue of the UK disabled-person's trust under IHTA s.89 and the US ABLE account / special-needs trust) [2]. Distributions are for care, housing, and quality-of-life needs. Residual on the beneficiary's death is taxed in the ordinary way against any further recipient's lifetime threshold.
**Anti-abuse.** Trustee reporting; medical re-certification; no pass-through to non-disabled remaindermen without tax.
**Failure mode avoided.** Opaque "family protection" trusts used as generic dynastic vehicles — the structure is tightly tied to an identified disabled beneficiary.

## 3. Primary residence

**What it covers.** The deceased's principal private residence, where a surviving spouse, civil partner, or dependent minor/disabled occupier continues to live in it.
**Mechanism.** The heir's tax liability on the dwelling is *deferred* until the property is sold or the qualifying occupier dies or ceases to occupy. No interest accrues during qualifying occupation. An adult child who has left home and inherits the house receives no deferral: tax crystallises on receipt at market value, above their threshold.
**Anti-abuse.** Occupation test (primary residence for 2 of the preceding 5 years); no deferral for second homes, buy-to-lets, or absentee heirs.
**Precedent.** The UK Residence Nil-Rate Band (FA 2016) was criticised by the IFS and OTS as complex, regressive, and concentrated on the London/SE housing corridor [3]. Our design is narrower and tied to actual occupation rather than lineal descent.

## 4. Registered charitable bodies

**What it covers.** Transfers to bodies registered with the Charity Commission (UK) or holding IRC §501(c)(3) status (US), subject to a public-benefit test.
**Mechanism.** Full exemption at point of transfer.
**Anti-abuse.**
- **Anti-cycling rule.** Assets gifted to a charity and subsequently received back (directly or indirectly) by the donor, their family, or a controlled entity trigger full crystallisation plus penalty.
- **Control test.** Foundations where the donor family retains majority board control, directs grant-making to family-adjacent causes, or draws material employment income are recharacterised as private vehicles.
- **Payout floor.** Minimum 5% annual qualifying distribution (mirroring the US private-foundation payout under IRC §4942) [11].
**Failure mode avoided.** Rob Reich's critique in *Just Giving* and sustained scrutiny of the Gates Foundation document how large private foundations can function as tax-advantaged perpetual vehicles of donor power rather than genuine public-benefit institutions [12]. The control test and payout floor prevent "quasi-philanthropy" from becoming a dynastic-trust substitute.

## 5. Family businesses — operating

**What it covers.** An *active operating business* in which the heir takes a material management role within 2 years of receipt and commits to continuing operation. Passive investment companies, holding vehicles, AIM-share portfolios assembled for IHT purposes, and enterprise-investment-scheme warehousing are excluded.

**Mechanism.**
- Tax crystallises on receipt at market value above the heir's £500k/$750k lifetime threshold.
- *Payment* is deferred up to 30 years at statutory interest of gilts/Treasuries + 1%.
- Liability is secured as a registered charge on business equity.
- Heir may elect that the state take a **non-voting preferred equity stake** equal to the liability, with a statutory buy-back option at audited valuation.

**Anti-abuse.** Twenty-year claw-back: sale, liquidation, de-listing-and-sale, or cessation of active operation crystallises the deferred tax plus accrued interest. Active-management test re-certified every 5 years.

**Precedent and failure modes avoided.**
- UK **Business Property Relief** grants 100% relief on unquoted trading businesses and 50% on some quoted holdings; the OTS, IFS and Resolution Foundation have documented abuse via AIM-listed share portfolios marketed explicitly as IHT shelters, and structuring of passive property companies as "trading" [13][14].
- US **QFOBI** (IRC §2057, repealed 2004) was narrow, heavily litigated, and ineffective; only 415 estates claimed it in its peak year [15].
- German *Erbschaftsteuer* business relief was struck down by the Federal Constitutional Court in 2014 for being over-generous to large enterprises; the 2016 reform introduced a means-test above €26m [16].
- Austria abolished its inheritance tax in 2008 partly because the Constitutional Court found the business-valuation rules arbitrary [10].

Our design keeps the business intact (deferral, not forced sale) while ensuring tax is ultimately paid — *or* the state becomes a long-horizon passive co-owner.

## 6. Family farms — operating

**What it covers.** Working farms where the owner's primary occupation is farming, with a minimum-acreage/turnover threshold set regionally, and the heir continues active farming.
**Mechanism.** 30-year deferral identical to the business rule; claw-back on sale, development, or conversion to non-agricultural use.
**Anti-abuse.** Working-farm test: minimum days of active farming per year; primary-occupation test; no relief for absentee-owned land let to tenant farmers as a passive rentier asset.
**Precedent and failure modes avoided.** UK **Agricultural Property Relief**, expanded after 2006 to cover let land, has been documented by the IFS and the Sutton Trust as inflating farmland prices and attracting non-farming purchasers seeking inheritance-tax shelter [17]. US **section 2032A special-use valuation** allows reduction of up to $1.31m (2024) but is gamed by "hobby farm" estates; GAO has criticised enforcement [6]. Our working-farm test removes the absentee and hobby-farmer routes.

## 7. Collectibles and illiquid personal property

**What it covers.** Art, wine, classic cars, jewellery, manuscripts.
**Mechanism.** No special relief. Valuation at open-market value; payment in instalments over up to 10 years at statutory interest is permitted for genuine liquidity problems.
**Narrow exception.** The UK-style **conditional exemption** for pre-eminent cultural property (national-importance test, public-access undertaking, heritage-body approval) is retained as the *only* collectibles carve-out [8].
**Failure mode avoided.** "Museum loans" that are in practice private enjoyment; access undertakings will be audited and enforceable.

## 8. Pensions

**What it covers.** Defined-contribution pots and remaining annuity rights.
**Mechanism.** Taxed as income on draw-down in the recipient's hands, not as a death-time capital transfer. Aligns pension taxation with the income-tax logic on which pension reliefs were originally granted.
**Failure mode avoided.** The 2015 UK pension freedoms, by making unused pots inheritable largely outside IHT, created a substantial and well-documented shelter flagged by the IFS, OTS and latterly closed in the 2024 Budget [9].

## Comparison table

| Dimension | UK BPR | US QFOBI (repealed) | German *Erbschaftsteuer* relief | This project |
|---|---|---|---|---|
| Eligibility test | Unquoted trading business; 2-yr ownership | Family-owned, >50% US, active trade | Active business; wage-bill/job-retention test | Active operating business; heir in management within 2 yrs |
| Rate of relief | 100% (unquoted) / 50% (quoted, controlling) | Up to $675k exclusion | 85% or 100% standard, means-test >€26m | Deferral, not exclusion; 100% payable, 0–30 yrs |
| Claw-back period | 2 years ownership; limited post-death clawback | 10 years (recapture) | 5 or 7 years (continuation period) | 20 years |
| Known failure mode | AIM-share IHT shelters; passive recharacterisation | Narrow, under-used, litigated | Struck down 2014 as over-generous | Designed against all three |

## Sources

1. [HMRC — "Inheritance Tax Manual IHTM11032: Spouse or civil partner exemption"](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm11032)
2. [HMRC — "Trusts for disabled beneficiaries (IHTA 1984 s.89)"](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm42805); [US ABLE Act 2014](https://www.irs.gov/government-entities/federal-state-local-governments/able-accounts-tax-benefit-for-people-with-disabilities)
3. [Office of Tax Simplification — "Inheritance Tax Review — Second Report" (2019)](https://www.gov.uk/government/publications/ots-inheritance-tax-review-simplifying-the-design-of-the-tax)
4. [HMRC — "Instalment option for IHT" (IHTM30191)](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm30191)
5. [Institute for Fiscal Studies — "Reforming Inheritance Tax" (2023)](https://ifs.org.uk/publications/reforming-inheritance-tax)
6. [US GAO — "Estate Tax: Special-Use Valuation under IRC §2032A" (GAO-15-440)](https://www.gao.gov/products/gao-15-440)
7. Design of this project; draws on BPR 2-year and APR 7-year rules extended.
8. [HMRC — "Conditional Exemption Tax Incentive Scheme"](https://www.gov.uk/guidance/capital-taxation-and-tax-exempt-heritage-assets)
9. [IFS — "Death and Taxes and Pensions" (2023)](https://ifs.org.uk/publications/death-and-taxes-and-pensions); [HM Treasury, Autumn Budget 2024](https://www.gov.uk/government/publications/autumn-budget-2024).
10. See `../05-history/abolitions.md` in this repo.
11. [IRS — "Private foundation minimum distribution requirements — IRC §4942"](https://www.irs.gov/charities-non-profits/private-foundations/taxes-on-failure-to-distribute-income-private-foundations)
12. Rob Reich, [*Just Giving: Why Philanthropy is Failing Democracy and How It Can Do Better*](https://press.princeton.edu/books/paperback/9780691202273/just-giving) (Princeton, 2018); Linsey McGoey, [*No Such Thing as a Free Gift*](https://www.versobooks.com/products/129-no-such-thing-as-a-free-gift) (Verso, 2015).
13. [Resolution Foundation — "Inheritance Tax and the AIM market" (2020)](https://www.resolutionfoundation.org/publications/)
14. [OTS Inheritance Tax Review — First Report (2018)](https://www.gov.uk/government/publications/ots-inheritance-tax-review-overview-of-the-tax-and-dealing-with-it)
15. [Congressional Research Service — "Qualified Family-Owned Business Interest Deduction" (RL30600)](https://crsreports.congress.gov/)
16. [Bundesverfassungsgericht — 1 BvL 21/12 (17 Dec 2014)](https://www.bundesverfassungsgericht.de/SharedDocs/Entscheidungen/EN/2014/12/ls20141217_1bvl002112en.html); [Erbschaftsteuerreformgesetz 2016](https://www.bundesfinanzministerium.de/Content/DE/Gesetzestexte/Gesetze_Gesetzesvorhaben/Abteilungen/Abteilung_IV/18_Legislaturperiode/Gesetze_Verordnungen/2016-11-09-Gesetz-zur-Anpassung-des-ErbStG-an-BVerfG/0-Gesetz.html).
17. [IFS — "The effects of Agricultural Property Relief on farmland prices" (2024)](https://ifs.org.uk/publications); Sutton Trust, "Land and inheritance" (2022).
18. [Marriage Act 1949, Schedule 1 — kindred and affinity (prohibited degrees)](https://www.legislation.gov.uk/ukpga/Geo6/12-13-14/76/schedule/1)
19. [SSA — 20 CFR §404.335: widow's/widower's benefits, nine-month duration-of-marriage requirement and exceptions](https://www.ssa.gov/OP_Home/cfr20/404/404-0335.htm); [SSA — Who can get Survivor benefits](https://www.ssa.gov/survivor/eligibility)
20. [§ 46 Abs. 2a SGB VI — Witwenrente/Witwerrente: *Versorgungsehe* presumption for marriages under one year](https://dejure.org/gesetze/SGB_VI/46.html)
21. [26 U.S.C. §2056A — Qualified domestic trust](https://www.law.cornell.edu/uscode/text/26/2056A); [IRS — Instructions for Form 706-QDT (estate tax on QDOT distributions)](https://www.irs.gov/instructions/i706qdt)
22. [HMRC — IHTM16061: Finance Act 2006 interests in possession, including the immediate post-death interest (IHTA 1984 s.49A)](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm16061)
23. [Law Commission — Wills project: *Modernising Wills Law* final report and draft Bill (16 May 2025), recommending abolition of revocation of wills by marriage, citing predatory marriage](https://lawcom.gov.uk/project/wills/)
