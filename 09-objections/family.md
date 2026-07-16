# Family Objections

**Executive summary.** Family objections are the most politically dangerous in the set — historical inheritance taxes died at televised farm auctions and over ordinary family homes, not in economics seminars — so every answer here must lead with the concrete numbers that show ordinary families untouched. The design facts: £500,000 tax-free *per recipient*, spouses never taxed — every widow and widower, every time — homes below the threshold pass intact, and operating farms and businesses are never force-sold.

Rules of engagement: concede, one-liner, full answer. Master table in [README.md](README.md). The steelmanned hard case is [`../04-case-against/family-business.md`](../04-case-against/family-business.md).

## "You'll destroy family farms and businesses"

**Concede first.** This objection has the best historical track record of any in the repo: liquidity crises at succession genuinely broke up firms and farms under past regimes, the resulting stories helped abolish taxes in Sweden, Norway, and Australia, and section [04](../04-case-against/README.md) rates it the single most important objection to engineer around.

**One-line answer.** No operating farm or business is ever force-sold under this design: heirs above the threshold pay over 30 years at gilts + 1% out of the asset's own earnings, or the state takes a passive equity stake instead of cash.

**Full answer.**

- **The historical failures were liquidity failures:** a tax bill due in months against an asset that takes years to yield. The design answer is to match the payment schedule to the asset ([`../02-proposal/carveouts.md`](../02-proposal/carveouts.md)).
- **A 30-year statutory deferral at a near-riskless rate** converts a confiscatory-looking headline into an annual charge an operating business can service out of earnings.
- **Where even that fails, the optional state equity stake** means the public becomes a silent minority partner rather than a bailiff. The farm keeps farming; the family keeps managing; what ends is only the *untaxed* transmission of multi-million-pound capital.
- **The status quo is not the farmer's friend.** UK APR/BPR reliefs have made farmland and business assets into avoidance wrappers: buying farmland is one of the best-known ways to shelter wealth from IHT, and ministers and tax bodies acknowledge the exemption "artificially" inflates farmland prices beyond what working farmers can pay [1][2].
- Genuinely wrenching edge cases exist and are catalogued honestly in [`../07-implementation/hard-cases.md`](../07-implementation/hard-cases.md).

**Deep treatment:** [`../04-case-against/family-business.md`](../04-case-against/family-business.md) · [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) · [`../07-implementation/hard-cases.md`](../07-implementation/hard-cases.md)

## "I can't even leave my house to my kids"

**Concede first.** The family home is the emotionally central asset in this debate, and threshold drift onto ordinary housing is exactly what killed the Swedish tax — the fear has a real historical referent.

**One-line answer.** You almost certainly can: each child can receive £500,000 tax-free, so a couple's home passes to two children untouched up to £1m — several times the average UK house price — and the threshold is indexed to house prices so that stays true.

**Full answer.** Run the arithmetic the objection never runs:

- The threshold is per *recipient*, cumulative over their lifetime ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)): two children can jointly receive £1m of parental housing wealth at 0%.
- Add bequests to their partners or to grandchildren and a family can pass £2m or more before any tax applies — four recipients at £500k each, matching the worked examples in [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md).
- The average UK house price is far below £500,000 — England averaged £293,000 in late 2025 — and even London's average home (£551,000) fits comfortably inside two children's allowances [3].
- On the design's own estimate, 90%+ of recipients are entirely unaffected ([`../02-proposal/README.md`](../02-proposal/README.md)).
- The Swedish failure mode — nominal thresholds silently overtaken by house-price booms — is specifically engineered out by indexing the threshold to the *maximum* of wage growth and median house-price growth ([`../05-history/abolitions.md`](../05-history/abolitions.md)).

Whoever this tax is for, it is not the owner of a three-bed semi.

**Deep treatment:** [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md) · [`../01-problem/housing.md`](../01-problem/housing.md)

## "Parents have a right to provide for their children"

**Concede first.** They do, and providing for one's children is among the most admirable motives in economic life; a policy that genuinely prevented it would deserve to fail.

**One-line answer.** Everything that actually constitutes providing — food, home, education, time, help with a deposit, support in crisis, and up to £500,000 of capital besides — remains fully intact; the only thing capped is the transfer of *more than half a million pounds per child* of unearned capital.

**Full answer.**

- **List what parents may still do without restriction:** house, feed, educate (including privately), fund training, pay for weddings, help with housing, support through illness, and transfer up to the lifetime threshold in outright gifts or bequests — a sum that on its own exceeds the entire net wealth (property, pensions and savings combined) of the median British household, £293,700 in 2020–22 [4].
- **The boundary between untaxed parental support and countable capital transfer is a genuine design question**, treated seriously in [`../07-implementation/boundary-problem.md`](../07-implementation/boundary-problem.md) and [`../07-implementation/human-capital.md`](../07-implementation/human-capital.md).
- **Then turn the objection around:** under the status quo, most parents *cannot* meaningfully provide capital to their children, because they have none to give. The endowment universalises the thing this objection valorises — every parent's child receives £50,000 at 25 ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)).
- A "right to provide" that only the top few percent can exercise is a privilege wearing a right's clothing.

**Deep treatment:** [`../07-implementation/boundary-problem.md`](../07-implementation/boundary-problem.md) · [`../02-proposal/endowment.md`](../02-proposal/endowment.md) · [`../03-case-for/ethical.md`](../03-case-for/ethical.md)

## "It breaks the natural bond between generations"

**Concede first.** Intergenerational obligation is deep, cross-cultural, and older than any state; a policy that treated family continuity as valueless would be both wrong and doomed.

**One-line answer.** The bond between generations is made of care, teaching, and time — not of capital transfers above £500,000 per head — and this argument's pedigree is a warning: it was deployed, in the same words, against abolishing primogeniture and entail, against married women's property rights, and against the 1894 estate duty.

**Full answer.**

- **The "proves too much" test:** if taxing seven-figure bequests severs the natural bond, then the bond was already severed for the large majority of families in history who had nothing material to leave — an absurd conclusion, which shows the bond never resided in the money.
- **Every previous reform of inheritance** — ending primogeniture, ending entail, letting daughters inherit equally — was denounced as an attack on the family and is now regarded as obvious justice ([`../05-history/`](../05-history/README.md)).
- **The empirical converse is uncomfortable for the objection:** very large expected bequests can *corrode* family bonds — contested wills, sibling litigation, and what the succession literature politely calls "strategic bequest behaviour," where inheritance becomes an instrument of control over adult children ([`../03-case-for/heirs-burden.md`](../03-case-for/heirs-burden.md)).
- The cultural second-order effects, in both directions, are examined in [`../16-second-order/family-and-culture.md`](../16-second-order/family-and-culture.md).

**Deep treatment:** [`../03-case-for/heirs-burden.md`](../03-case-for/heirs-burden.md) · [`../16-second-order/family-and-culture.md`](../16-second-order/family-and-culture.md) · [`../04-case-against/liberty-autonomy.md`](../04-case-against/liberty-autonomy.md)

## "You're taxing grief"

**Concede first.** The timing is inherently painful: any tax connected to a death arrives at the worst moment of a family's life, and "death tax" rhetoric works because it points at something real.

**One-line answer.** For the grieving majority nothing happens at all — over 90% of recipients owe nothing and most will never file — and for the minority above the threshold, deferral rules mean no one is forced to sell anything, or even think about the bill, in the months of mourning.

**Full answer.**

- **The recipient basis changes the emotional structure of the tax.** Estate taxes intrude into the administration of the dead person's affairs; a receipts tax is simply an entry on the *recipient's* lifetime ledger, handled alongside probate paperwork that already exists ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md), [`../07-implementation/administration.md`](../07-implementation/administration.md)).
- **The widow or widower never pays — ever, in any marriage, and is never questioned about it.** Spousal transfers are untaxed for every widow and widower, every time; the deferred charge only ever lands when wealth finally leaves the marriage to a non-spouse ([`../02-proposal/carveouts.md`](../02-proposal/carveouts.md) §1). That promise is engineered to survive even deliberate abuse — dynastic alliance marriages and reciprocal "widow swaps" are priced out by ledger arithmetic alone, without the state ever questioning a marriage (same section).
- **Payment schedules are designed never to force a grieving family's hand** — deferral for illiquid assets, long filing windows, no bailiff-at-the-funeral scenarios.
- **The money at issue exists in the recipient's hands *only because of* the death** — the tax takes a share of a windfall, not a toll on a loss.
- Handling this framing battle — including why the proposal should never be defended under the opponent's name for it — is the business of [`../14-communications/naming-and-language.md`](../14-communications/naming-and-language.md).

**Deep treatment:** [`../14-communications/naming-and-language.md`](../14-communications/naming-and-language.md) · [`../06-palatability/framing.md`](../06-palatability/framing.md)

## Sources

1. [Chartered Institute of Taxation, "IHT unlimited exemption is 'unsustainable', minister tells peers"](https://www.tax.org.uk/iht-unlimited-exemption-is-unsustainable-minister-tells-peers)
2. [Sustain, "Inheritance Tax: What the new rules mean for farmers" (November 2024)](https://www.sustainweb.org/blogs/nov24-farming-budget-inheritance-tax-apr/)
3. [ONS, Private rent and house prices, UK (January 2026 bulletin, data to late 2025)](https://www.ons.gov.uk/economy/inflationandpriceindices/bulletins/privaterentandhousepricesuk/january2026)
4. [ONS, Household total wealth in Great Britain: April 2020 to March 2022](https://www.ons.gov.uk/peoplepopulationandcommunity/personalandhouseholdfinances/incomeandwealth/bulletins/totalwealthingreatbritain/april2020tomarch2022)

## See also

- The fairness variants ("my money", "double tax"): [fairness.md](fairness.md)
- Escalations ("first they take the estate, then the house"): [slippery-slope.md](slippery-slope.md)
- Polling on family-frame attacks: [`../06-palatability/polling.md`](../06-palatability/polling.md)
