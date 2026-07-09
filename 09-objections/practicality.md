# Practicality Objections

**Executive summary.** The practicality objections — impossible valuation, wasted revenue, trivial yield, and admin costs — share a rhetorical shape: they present routine, solved administrative problems as fatal impossibilities. Each answer below names where the "impossible" thing is already done every day, and notes that the proposal's aim is structural (ending dynastic transmission) as much as fiscal, so it does not stand or fall on the revenue line alone.

Rules of engagement: concede, one-liner, full answer. Master table in [README.md](README.md). The administrative machinery lives in [`../07-implementation/`](../07-implementation/README.md).

## "You can't value a private company, an artwork, or a farm"

**Concede first.** Valuing unlisted and unique assets is genuinely hard, reasonable professionals disagree by wide margins, and a fragile valuation regime destroyed the Austrian tax outright in 2008 ([`../05-history/abolitions.md`](../05-history/abolitions.md)).

**One-line answer.** These exact assets are valued every day — for CGT, existing IHT, divorce settlements, insurance, probate, and company transactions — so the question is not whether valuation is possible but whether the regime is well-engineered, which is a design task, not a mystery.

**Full answer.** The UK already values private companies for CGT and the existing 40% IHT; family courts value them in every big divorce; insurers value artworks annually; banks value farms for lending. What killed historical regimes was not valuation difficulty but valuation *anachronism* — Austria's 1973-vintage cadastral values frozen for 35 years. The design here uses mark-to-market for listed assets, RICS-style professional appraisal with rebuttable presumptions for property, capped minority and marketability discounts for private companies, and deferred true-up mechanisms (earn-out style) where a sale within a defined window revises the assessed value to the realised price ([`../07-implementation/valuation.md`](../07-implementation/valuation.md), [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md)). Hard categories — carried interest, IP, crypto, unique digital assets — get dedicated treatment in [`../07-implementation/digital-and-novel-assets.md`](../07-implementation/digital-and-novel-assets.md). Disagreement at the margin is priced in: a tax does not need pinpoint valuation, only unbiased valuation with dispute machinery, which is what every existing capital tax already runs on.

**Deep treatment:** [`../07-implementation/valuation.md`](../07-implementation/valuation.md) · [`../07-implementation/digital-and-novel-assets.md`](../07-implementation/digital-and-novel-assets.md) · [`../07-implementation/hard-cases.md`](../07-implementation/hard-cases.md)

## "The government will just waste the money"

**Concede first.** The record of discretionary state spending is mixed at best, scepticism about it is bipartisan common sense, and section [04](../04-case-against/README.md) treats state failure as a first-rank objection, not a talking point.

**One-line answer.** The revenue never enters the discretionary pot: it is hypothecated to a named £50,000 endowment paid directly to every citizen at 25, so the state functions as a pipe, not a spender.

**Full answer.** This objection is the reason the proposal is architected the way it is. Proceeds fund the universal endowment first, with only any surplus reaching general revenue ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)); no minister allocates it, no department programme absorbs it, no procurement process touches it. The citizen — not the state — decides what the capital does, which is why thinkers deeply sceptical of the state (from the Paine of *Agrarian Justice* to Ackerman and Alstott's stakeholder model, [`../05-history/ackerman-alstott.md`](../05-history/ackerman-alstott.md)) converge on the grant design. In debate, the move is to agree enthusiastically: *because* governments waste money, this policy gives the money to citizens instead. The honest residue — the state must still run the register, collect the tax, and resist raiding the fund — is steelmanned in [`../04-case-against/state-failure.md`](../04-case-against/state-failure.md), and the fund-governance safeguards are specified in [`../02-proposal/endowment.md`](../02-proposal/endowment.md).

**Deep treatment:** [`../04-case-against/state-failure.md`](../04-case-against/state-failure.md) · [`../02-proposal/endowment.md`](../02-proposal/endowment.md)

## "It raises trivial revenue, so why bother"

**Concede first.** Historically true: every abolished regime raised under 0.5% of tax receipts, and current UK IHT brings in roughly £7–8bn a year (to verify) — real money, but small against a ~£1tn tax take.

**One-line answer.** Those regimes were 40%-with-loopholes taxes on a relief-riddled base; a 100% rate above £500k per recipient on the full annual inheritance flow is a different fiscal object — and even at pessimistic yield, the primary objective is structural (no more dynasties), which the tax achieves whether or not the Treasury gets rich.

**Full answer.** The base matters more than the rate history suggests. Annual UK wealth transfers at death and by major gift run to well over £100bn and are projected to grow as the largest-ever cohort of housing and pension wealth passes on (to verify against ONS/IFS inheritance-flow projections; the revenue modelling lives in [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)). Taxing the slice above £500k per recipient at 100% plausibly yields an order of magnitude more than the current regime — enough to fund the endowment, which is the fiscal test that matters ([`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md)). But the deeper answer refuses the frame: this is a *distributional-primary* tax, not a revenue-primary one. Income tax exists to raise money; this exists to stop the formation of hereditary economic dynasties ([`../01-problem/wealth-concentration.md`](../01-problem/wealth-concentration.md), [`../16-second-order/dynasties-and-power.md`](../16-second-order/dynasties-and-power.md)). Judging it purely on yield is like judging the smoking ban on cigarette-duty receipts.

**Deep treatment:** [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md) · [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md) · [`../01-problem/README.md`](../01-problem/README.md)

## "The admin costs will eat the revenue"

**Concede first.** Dying regimes did have ugly cost-to-yield ratios — a shrinking base under a complex statute is the worst of both worlds — and any new tax carries setup costs for the register, valuation capacity, and guidance.

**One-line answer.** Collection costs scale with complexity, not with rate: one threshold, one rate, few reliefs, and a single lifetime ledger is administratively *simpler* than the current IHT relief thicket, and the base is large enough to make plausible cost-to-collect ratios unremarkable by HMRC standards.

**Full answer.** HMRC's overall cost of collection runs at well under a penny per pound (to verify against HMRC annual accounts), and even the taxes with the worst ratios sit at a few pence. The historical regimes that looked administratively hopeless were hopeless because relief-layering multiplied assessment work while shrinking the taxable remainder — cost stayed, yield left. This design runs the arithmetic the other way: the 0/100 kink eliminates rate-banding computation; abolishing the relief thicket (BPR, APR, taper, normal-expenditure rules) removes the most litigation-intensive assessments; the Central Register of Receipts piggybacks on probate and gift-reporting events that already generate paperwork ([`../07-implementation/administration.md`](../07-implementation/administration.md), [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md)); and most estates never interact with the system at all because their recipients sit below threshold. Benchmarked cost-to-collect estimates belong in the implementation file and are flagged there for verification.

**Deep treatment:** [`../07-implementation/administration.md`](../07-implementation/administration.md) · [`../07-implementation/enforcement.md`](../07-implementation/enforcement.md)

## See also

- "The rich will dodge it anyway" (the practicality objection's cousin): [avoidance.md](avoidance.md)
- "Why not some easier tax instead": [whataboutery.md](whataboutery.md)
- Sequencing and setup costs at introduction: [`../15-transition/sequencing.md`](../15-transition/sequencing.md)
