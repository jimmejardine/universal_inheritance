# The Formal Case: Optimal Tax Theory

**Executive summary.** The modern optimal-taxation literature — the same formal apparatus used to argue *against* high capital-income taxes — generates strikingly high optimal inheritance-tax rates under plausible parameters: 50–60% in Piketty–Saez's baseline calibrations, and rates approaching or exceeding 80% when the social welfare function weights the majority of each cohort who inherit little or nothing (to verify) [1]. This file walks through the four main theoretical results, answers the one serious theoretical objection (Atkinson–Stiglitz), and translates every result into plain English — because a formal case that cannot be stated plainly is politically useless.

([`economic-efficiency.md`](economic-efficiency.md) covers the empirical efficiency evidence — bequest elasticities, abolition natural experiments, administrative cost. This file covers the *theory*: what the models say the rate should be, and why. The two files should be read together.)

## Key findings

- Piketty–Saez (2013) derive the optimal inheritance-tax rate from three sufficient statistics — the elasticity of bequests, the aggregate importance of inheritance in lifetime resources, and the distribution of inheritances received. From the perspective of the ~half of each cohort who receive negligible inheritance, calibrated optimal rates reach 50–60% and rise toward 70–80%+ under meritocratic social preferences (to verify) [1].
- Farhi–Werning (2010) show that once heirs' welfare enters the social objective at all, the optimal estate tax is *progressive* and includes a corrective component — bequests confer an externality on recipients that donors do not internalise [2].
- The Atkinson–Stiglitz theorem, the strongest theoretical argument for a zero rate, does not apply: bequests are not an ordinary consumption good, because the "purchase" creates unearned resources in a *second* person whose position enters the social welfare function directly [3][4].
- Accidental and precautionary bequests — the majority category empirically (see [`economic-efficiency.md`](economic-efficiency.md) §2) — can be taxed at up to 100% with near-zero deadweight loss; they are the closest thing to a lump-sum tax base that exists in a real economy [5][6].
- The Cremer–Pestieau survey literature concludes that no mainstream model, honestly calibrated, supports a zero or near-zero rate; disagreement is over *how high*, not *whether* [6].
- The proposal's design choices — recipient-based, lifetime-cumulative, 100% marginal above a threshold — each correspond to a specific theoretical result rather than to rhetorical preference (§6).

## 1. The Piketty–Saez framework

Piketty and Saez (2013, *Econometrica*) pose the question in the standard modern form: choose the linear inheritance-tax rate that maximises a social welfare function, subject to behavioural responses [1]. The optimal rate collapses to a formula in three observable quantities:

1. **The elasticity of bequests** with respect to the net-of-tax rate — how much less people leave when the tax rises. Empirically small (see [`economic-efficiency.md`](economic-efficiency.md) §2 and [`../04-case-against/bequest-motive.md`](../04-case-against/bequest-motive.md)).
2. **The aggregate inheritance share** — how large inherited resources are relative to lifetime labour income. Piketty's *by* ratio, historically 10–15% of national income in Europe and rising [7].
3. **The distributional position of the evaluator** — optimal policy depends on *whose* welfare the social welfare function tracks.

The third statistic is the politically decisive one. Because inheritance is far more concentrated than labour income, the majority of each cohort receives little or nothing. For a social welfare function anchored on those zero-or-negligible-receivers — which is simply majoritarian democracy expressed as mathematics — the calibrated optimal rate on large inheritances is 50–60% in the baseline and rises above 70–80% when social preferences are "meritocratic," i.e. place low or zero weight on the consumption value of *received* (as opposed to earned) resources (to verify) [1]. The paper's own summary is blunt: for the bottom 70% of receivers, the optimal top inheritance-tax rate is high under essentially any plausible parameterisation.

## 2. Farhi–Werning: the externality result

Farhi and Werning (2010, *QJE*) work in a Mirrleesian framework and add one assumption that almost everyone accepts on reflection: the welfare of *heirs* counts in the social objective, not merely the welfare of donors [2]. Two results follow. First, optimal estate taxation is **progressive** — marginal rates rise with estate size. Second, the tax has a **corrective** (Pigouvian) component: a bequest changes the resources, and hence the relative position, of a person other than the choosing agent. The donor internalises their own warm glow but not the effect on the distribution of opportunity across the next cohort. Where individual choices impose uninternalised effects on third parties, taxation of the choice is efficiency-*improving*, not merely redistributive. Dynastic transmission is, in this precise sense, a negative externality on everyone else's children.

## 3. The Atkinson–Stiglitz challenge, answered

The strongest theoretical argument *against* inheritance taxation is the Atkinson–Stiglitz theorem (1976): with an optimal nonlinear labour-income tax in place, differential commodity taxation is redundant — and if a bequest is modelled as just another consumption good the donor "buys," it should face the same (zero differential) rate as other consumption [3]. Three independent replies defeat the application, and they are worth stating carefully because this theorem is the entire intellectual foundation of the respectable zero-rate position.

*First, bequests are not ordinary consumption.* When a donor buys a holiday, the transaction ends with the donor's utility. When a donor "buys" a bequest, the spending *creates resources in a second person*. The recipient's income, opportunity set, and relative position all change, and all of these enter the social welfare function directly. Atkinson–Stiglitz has no second affected party in it; inheritance always does [1][4].

*Second, the double-counting asymmetry.* A bequest yields utility twice — once to the donor (warm glow) and once to the recipient (resources). Kaplow and others have noted this cuts in the direction of *subsidising* transfers; but the Farhi–Werning externality and the inequality-of-opportunity term cut the other way and, under empirically realistic concentration of bequests, dominate [2][4].
 
*Third, inheritance is correlated with ability-to-pay in a way commodities are not.* Atkinson–Stiglitz assumes the taxed good reveals nothing about earning capacity beyond what the income tax already captures. Received inheritance is a direct, observable signal of lifetime resources that labour-income taxation *cannot* reach — the heir who never works pays no income tax at all. Taxing receipts closes an otherwise open flank in the tax system [1][6].

The theorem, correctly applied, tells us not to tax *ordinary spending* differentially. It is silent — or actively hostile — on untaxed intergenerational transfers of relative position.

## 4. Accidental bequests: the free-lunch base

The theory divides bequests by motive, and the division carries the whole efficiency argument [5][6]:

| Bequest type | Why it exists | Behavioural response to tax | Efficient tax rate in theory |
|---|---|---|---|
| **Accidental** | Uncertain lifespan + imperfect annuity markets; wealth left over | None — the decedent never chose to leave it | Up to 100%; effectively lump-sum |
| **Precautionary residue** | Self-insurance against late-life costs, unspent at death | Near zero — the saving motive is insurance, not transfer | Very high |
| **Warm glow / joy of giving** | Donor values the *act* of giving | Modest — donor utility depends on giving, only partly on net amount | High, positive |
| **Altruistic (dynastic)** | Donor values heir's consumption | Largest in theory; small in the data | Positive; sign disputes exist at the extremes [2][6] |
| **Strategic / exchange** | Bequest as payment for attention or care | Tax partly falls on implicit wages | Moderate |

The empirical literature (Hurd; Kopczuk–Lupton; surveyed in [`economic-efficiency.md`](economic-efficiency.md)) places between a third and three-fifths of US estate wealth in the first two rows [5]. Public finance spends its life searching for non-distortionary tax bases and finds essentially none — every real tax changes some margin of choice. Accidental bequests are the exception: wealth the holder never intended to transfer, taxed at a moment when no one can respond. Declining to tax this base heavily, while taxing wages that workers *do* respond to, is — on the discipline's own terms — a straightforward misallocation of the tax burden.

## 5. Cremer–Pestieau and the survey consensus

Cremer and Pestieau's successive surveys of wealth-transfer taxation, and Kopczuk's *Handbook of Public Economics* chapter, are the field's reference summaries [5][6]. Their consistent conclusions: (i) the optimal rate depends on the bequest-motive mix, but every empirically plausible mix implies substantial positive taxation; (ii) recipient-based taxation dominates estate-based taxation on both equity and efficiency grounds; (iii) the zero-tax results in the literature require knife-edge assumptions (pure dynastic altruism, infinite horizons, no accidental bequests, no inequality aversion) that the data reject. The theoretical debate that filters into politics as "economists say death taxes are destructive" does not exist in the professional literature in that form.

## 6. Translation table: what the theory says in plain English

| Technical result | Plain English |
|---|---|
| Optimal rate rises with the share of zero-receivers whose welfare counts (Piketty–Saez) [1] | If policy is set for the majority who inherit little or nothing — i.e. democratically — the tax on big inheritances should be high. |
| Optimal estate taxation is progressive with a corrective component (Farhi–Werning) [2] | Big bequests don't just enrich one child; they demote everyone else's. A tax that corrects this makes the economy work *better*, not worse. |
| Atkinson–Stiglitz does not extend to bequests [1][3][4] | "Don't tax spending twice" is a rule about shopping. An inheritance isn't shopping — it lands in a second person's lap, unearned, and that person's head start is exactly what tax policy exists to weigh. |
| Accidental bequests are a near-lump-sum base [5][6] | Much inherited money was never meant as a gift — it's what was left over. Taxing leftovers changes nobody's behaviour. It is the closest thing to free revenue a state will ever see. |
| Small bequest elasticity ⇒ high revenue-maximising rate [1][5] | People barely change their saving when inheritance taxes rise. So the tax raises money without shrinking the pie. |
| Recipient-based, lifetime-cumulative base dominates estate-based (Cremer–Pestieau; Mirrlees) [6] | Tax what each *person receives over a lifetime*, not what each estate leaves. That targets unearned windfalls precisely and rewards spreading wealth widely. |
| 100% marginal above a high threshold ≈ optimal when social weight on marginal dynastic consumption → 0 [1] | Above half a million pounds of unearned receipts per person, society is entitled to say: enough is a fortune; the rest builds everyone's inheritance. |

## 7. From theory to the proposal's design

Each design choice in [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) instantiates a theoretical result: the **recipient base** implements the survey consensus of §5; the **lifetime cumulation** prevents the timing games analysed in [`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) from re-opening the base; the **generous threshold** concentrates the tax on the dynastic tail where the Farhi–Werning externality is largest and the accidental-bequest share of *marginal* wealth is highest; and the **100% top marginal rate** is the limiting case of the Piketty–Saez formula as the social weight on marginal inherited consumption goes to zero — which is precisely the "meritocratic" preference most voters profess (see [`meritocratic-legitimacy.md`](meritocratic-legitimacy.md)). The remaining gap between the 50–80% calibrated optima and 100% is a judgement about asymmetric risk: under-taxing re-starts the compounding ratchet ([`piketty-r-vs-g.md`](piketty-r-vs-g.md) §5), while over-taxing forgoes some warm-glow utility above a threshold already several multiples of median lifetime savings. The behavioural objections that the elasticity is higher than modelled are steelmanned in [`../04-case-against/bequest-motive.md`](../04-case-against/bequest-motive.md) and [`../09-objections/economic.md`](../09-objections/economic.md).

## Sources

1. [Piketty, T. & Saez, E. (2013). "A Theory of Optimal Inheritance Taxation." *Econometrica* 81(5)](https://www.econometricsociety.org/publications/econometrica/2013/09/01/theory-optimal-inheritance-taxation)
2. [Farhi, E. & Werning, I. (2010). "Progressive Estate Taxation." *QJE* 125(2)](https://academic.oup.com/qje/article/125/2/635/1882078)
3. [Atkinson, A. B. & Stiglitz, J. E. (1976). "The Design of Tax Structure: Direct versus Indirect Taxation." *Journal of Public Economics* 6](https://www.sciencedirect.com/science/article/abs/pii/0047272776900411)
4. [Kaplow, L. (2008). *The Theory of Taxation and Public Economics*. Princeton UP, chs. on transfer taxation](https://press.princeton.edu/books/paperback/9780691148212/the-theory-of-taxation-and-public-economics)
5. [Kopczuk, W. (2013). "Taxation of Intergenerational Transfers and Wealth." *Handbook of Public Economics*, vol. 5](https://www.sciencedirect.com/science/article/pii/B9780444537591000066)
6. [Cremer, H. & Pestieau, P. (2006). "Wealth Transfer Taxation: A Survey of the Theoretical Literature." *Handbook of the Economics of Giving, Altruism and Reciprocity*, vol. 2](https://www.sciencedirect.com/science/article/abs/pii/S1574071406020162)
7. [Piketty, T. (2011). "On the Long-Run Evolution of Inheritance: France 1820–2050." *QJE* 126(3)](https://academic.oup.com/qje/article/126/3/1071/1854714)

See also: [Mirrlees Review — *Tax by Design*, ch. 15 (IFS, 2011)](https://ifs.org.uk/publications/taxation-wealth-and-wealth-transfers) for the policy translation of these results, discussed in [`economic-efficiency.md`](economic-efficiency.md) §7.
