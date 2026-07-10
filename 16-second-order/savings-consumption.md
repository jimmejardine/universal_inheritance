# Savings and Consumption Behaviour

**Executive summary.** Lifecycle theory makes clear predictions for households above the threshold — more annuitisation, more late-life consumption, less terminal hoarding of housing — while predicting essentially no change for the large majority whose saving was never bequest-driven. The effect on the *aggregate* savings rate is genuinely ambiguous: credible channels point in both directions, and this file presents both rather than picking a side.

## 1. The lifecycle baseline

In the pure Modigliani lifecycle model, people save for retirement and decumulate to zero; bequests are either accidental (death arrives before the money runs out) or intentional (a bequest motive in the utility function). The empirical literature finds motives are mixed and hard to separate: Hurd found little evidence of operative bequest motives for most households; Dynan, Skinner and Zeldes argue precautionary and bequest saving are observationally entangled ("mixed motives"); Kopczuk's Handbook of Public Economics survey concludes that intentional bequests are concentrated at the very top of the distribution, while most inherited wealth lower down is accidental (to verify) [1][2][3].

This decomposition is the key to the whole file: **the tax only changes behaviour where an intentional bequest motive above £500k per recipient was operative** — a small, wealthy minority. Everyone else's saving is retirement- and precaution-driven and continues unchanged.

## 2. Annuitisation: the annuity market's rebirth

The "annuity puzzle" — why so few retirees buy actuarially fair longevity insurance — is partly explained by bequest motives: unspent annuity premiums die with you, so bequest-minded savers avoid them (Lockwood and related work; to verify) [4]. Above the threshold, the tax removes that reason entirely. For above-threshold wealth, an annuity strictly dominates holding assets that will be taxed at 100% at death.

Predicted consequences:

- **Demand for annuities, deferred annuities, and longevity insurance rises sharply** among the wealthy elderly — reversing the post-2015 UK "pension freedoms" drift away from annuitisation.
- **Insurers' long-duration liabilities grow**, deepening demand for long gilts and infrastructure assets — a capital-market side-effect picked up in [macro.md](macro.md).
- **Welcome verdict:** better longevity insurance is a welfare gain in its own right, and the annuity pool's mortality credits effectively socialise what would have been accidental bequests.

Confidence: high on direction, medium on magnitude — the affected population is small in number though large in wealth.

## 3. Late-life consumption: "die with zero" culture

The corollary of taxing terminal wealth at 100% above the threshold is that spending it becomes the rational alternative. Expect more late-life consumption among the wealthy: travel, services, care quality, lifetime gifts within each recipient's threshold ([`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) covers the timing games). The cultural template already exists — Perkins' *Die With Zero* is a bestseller under the *current* regime.

Verdict: ambiguous. Consumption by the elderly rich is not obviously worse than dynastic transmission (it recycles money through wages in the services economy) but it is also not the policy's purpose. The design accepts it: lifetime consumption is the one untaxed use of a fortune, and that is deliberate — the target is transmission of unearned position, not spending by the person who earned the money ([`../03-case-for/ethical.md`](../03-case-for/ethical.md)).

## 4. Housing decumulation by the elderly

Elderly households systematically under-downsize. The literature attributes this to transaction costs, attachment, and — materially — the bequest motive plus tax privileges for housing at death (the UK residence nil-rate band explicitly rewards dying in a large house; US step-up in basis likewise) [5]. The proposal removes the above-threshold reward for dying housed. Predictions:

- More downsizing and equity release in the 70+ cohort; family homes reach the market a decade or two earlier than under bequest logic.
- Effect on housing supply and prices taken up in [asset-prices.md](asset-prices.md); the under-occupation problem it addresses is documented in [`../01-problem/housing.md`](../01-problem/housing.md).
- Confidence: medium — transaction costs and attachment are large frictions and will persist; expect a shift at the margin, not a wave.

## 5. Late-life work, care, and family power

Three further late-life margins, each held to this file's honesty standard:

- **Labour supply at the top: ambiguous, probably small.** A founder whose accumulation motive was dynastic loses the reason to keep compounding past the family's threshold headroom — earlier retirement or earlier sale at the margin. But the evidence on the very successful points to mastery, status, and identity as the operative late-career motives ([`../04-case-against/bequest-motive.md`](../04-case-against/bequest-motive.md) — the incentive steelman and its answer), and the design keeps control-until-death: the founder who loves the firm keeps building it, and the philanthropic channel gives the surplus a purpose ([charitable-giving.md](charitable-giving.md)). Direction unknown, magnitude small; flagged for the modelling agenda in [macro.md](macro.md).
- **Care: from estate-preservation to care-purchase.** Today's wealthy elderly visibly under-spend on their own care to keep the estate intact — the house is preserved, the cheaper home is chosen, family members provide unpaid care so the inheritance survives (self-rationing patterns to verify against the care-funding literature). Above the threshold the calculus inverts: the better care home, the private nurse, the adapted house strictly dominate dying richer. Expect higher-quality self-funded care in the top wealth band, with a modest relief to public care budgets and to the unpaid-care burden on (usually) daughters. This is one of the policy's quietest welfare gains: it repurchases comfort for the old from the estates of the old.
- **The end of the strategic bequest.** Bernheim, Shleifer and Summers documented what families know: bequeathable wealth is an instrument of control, and adult children's attention responds to it ("The Strategic Bequest Motive" — to verify) [8]. Capping the bequest disarms the instrument — a welfare gain for heirs held in orbit ([`../03-case-for/heirs-burden.md`](../03-case-for/heirs-burden.md)) and, honestly, the loss of one inducement for filial attentiveness; the net effect on late-life family contact is unknown and belongs to [family-and-culture.md](family-and-culture.md). What clearly improves is the *timing* of generosity: with the ledger indifferent to when transfers happen, giving while alive — when the children are 30, not 60 — dominates the deathbed transfer, and the donor gets to watch the money matter ([`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md)).

## 6. Precautionary saving: unchanged

Kopczuk and Lupton, and the long-term-care saving literature, find that much late-life wealth-holding is precautionary — insurance against medical and care costs — rather than bequest-driven (to verify) [3][6]. Precautionary saving is untouched by the tax: it is spent or held against risk, not transmitted. For the ~90%+ of households below the threshold ([`../02-proposal/thresholds.md`](../02-proposal/thresholds.md)), nothing in the savings calculus changes at all. Claims that "the tax destroys the incentive to save" conflate the top tail's bequest saving with the population's retirement and precautionary saving; [`../04-case-against/bequest-motive.md`](../04-case-against/bequest-motive.md) steelmans and answers the stronger version.

## 7. The aggregate savings rate: both directions, honestly

The share of the existing capital stock attributable to inherited versus life-cycle saving has been disputed since the Kotlikoff–Summers (~80%) versus Modigliani (~20%) exchange of the 1980s — the range itself signals how uncertain this terrain is [7].

| Channel | Direction for aggregate saving | Confidence |
|---|---|---|
| Bequest-motivated accumulation above threshold falls | Down | High that it falls; the aggregate share it represents is the uncertainty |
| Late-life consumption rises among the wealthy | Down | Medium |
| Endowment recipients: some consume the grant | Down (small) | Medium |
| Endowment recipients: deposits, education, business equity | Up (capital formation by the young) | Medium |
| Annuitisation channels wealth into invested insurance reserves | Up / neutral for aggregate K | Medium |
| State receipts invested in-specie via the endowment fund rather than consumed | Up / neutral | Depends on fiscal rules ([macro.md](macro.md)) |
| Precautionary and retirement saving (the majority) | Unchanged | High |

Net: the honest position is that the sign of the aggregate effect is unknown and probably small, because the downward channels are concentrated in a thin (if wealthy) slice while several offsetting channels recycle the same resources into invested forms. The empirical record from the abolition wave supports agnosticism in the other direction: no country that abolished inheritance tax detected a measurable savings or growth dividend ([`../05-history/abolitions.md`](../05-history/abolitions.md)).

## 8. What would change this assessment

- Micro-simulation on wealth-survey data (ONS WAS; US SCF) of the share of top-decile saving plausibly bequest-motivated — part of the modelling agenda in [macro.md](macro.md).
- Evidence from announcement-window behaviour if any jurisdiction legislates first ([`../15-transition/announcement-effects.md`](../15-transition/announcement-effects.md)).
- The size of the charitable diversion ([charitable-giving.md](charitable-giving.md)): bequests redirected to foundations remain saved/invested, muting any decline.

## Sources

1. Hurd, M. — "Savings of the Elderly and Desired Bequests," *AER* (1987) (to verify)
2. Dynan, K., Skinner, J. & Zeldes, S. — "The Importance of Bequests and Life-Cycle Saving in Capital Accumulation," *AER P&P* (2002) (to verify)
3. Kopczuk, W. — "Taxation of Intergenerational Transfers and Wealth," *Handbook of Public Economics* vol. 5 (2013)
4. Lockwood, L. — "Bequest Motives and the Annuity Puzzle," *Review of Economic Dynamics* (2012) (to verify)
5. IFS / OTS analyses of the residence nil-rate band; US step-up in basis literature (to verify)
6. De Nardi, M., French, E. & Jones, J. — medical-expense risk and elderly saving, *JPE* (2010) (to verify)
7. Kotlikoff, L. & Summers, L. (1981) vs Modigliani, F. (1988), *JPE* / *JEP* exchange on the inherited share of wealth
8. Bernheim, B. D., Shleifer, A. & Summers, L. — "The Strategic Bequest Motive," *JPE* 93(6), 1985 (to verify)
