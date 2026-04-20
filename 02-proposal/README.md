# 02 — The Proposal: What "100% Inheritance Tax" Means

"100% inheritance tax" is a slogan, not a policy. This section specifies the actual mechanism being defended and distinguishes it from the strawman version opponents will attack.

## Core design

- **100% *marginal* rate above a generous threshold, not confiscation.** Nothing below the threshold is taxed. The threshold should be meaningful — e.g. a multiple of median annual wages, or the national median house price.
- **Recipient-based, not estate-based.** The tax falls on the person receiving, not on the deceased's estate as a whole. This rewards wide distribution (giving to ten heirs may incur no tax; giving to one may incur a lot) and strips out the "death tax" framing.
- **Lifetime-cumulative.** All gifts and bequests received over a lifetime count against the threshold. Without this, the tax is trivially avoided by giving during life.
- **Proceeds hypothecated** to a universal citizen's endowment paid at ~25, with any surplus funding public goods (housing, education).

## Why paired with a universal endowment?

The proposal is not "the state takes your money" but "inheritance is redistributed from the few who would receive millions to the many who currently inherit nothing." Piketty (2019), Ackerman & Alstott (1999), and Paine (1797) all couple the two. The pairing matters rhetorically *and* substantively: it converts inheritance from a lottery of birth into a universal entitlement.

## Carve-outs that must be designed well

| Case | Problem | Candidate solution |
|---|---|---|
| Family business | Illiquid asset, forced breakup | Deferred payment, state equity stake, operating-asset allowance |
| Family farm | Illiquid + politically radioactive | As above, with additional carve-out up to a working-farm threshold |
| Spousal transfer | Uncontroversially exempt | Full exemption |
| Primary residence | Forced home sale is politically fatal | Partial exemption to a cap; deferral until sale |
| Charitable giving | Shapes the entire philanthropic sector | Full or near-full exemption; shapes downstream design |

## Variants to compare

| Variant | Top rate | Threshold basis | Proceeds |
|---|---|---|---|
| Pure 100% (strawman) | 100% | none | general revenue |
| This project's proposal | 100% | per-recipient lifetime, generous | universal endowment |
| Piketty (2019) | progressive to ~90% | per-recipient | €120k at age 25 |
| Ackerman & Alstott (1999) | wealth tax, not pure IHT | — | $80k stakeholder grant |
| Paine (1797) | 10% | any estate | citizen's dividend at 21 + pension |
| Status quo (UK) | 40% | £325k per estate | general revenue |

## Files to add

- `mechanism.md` — the full specification
- `thresholds.md` — what "generous" means, quantitatively
- `endowment.md` — design of the universal grant
- `carveouts.md` — farms, businesses, homes, charity
- `avoidance.md` — trusts, gifts, emigration, valuation games
