# Enforcement

**Executive summary.** At a 100% marginal rate the reward for successful evasion equals the entire amount hidden, so enforcement must be engineered until evasion is negative expected-value for a well-advised taxpayer — through risk-scored plus random audit, penalties that scale past the tax itself, whistleblower bounties, automatic information exchange, and no limitation period for concealment. The strategic aim is not to catch everyone but to make professional advisers unwilling to sell evasion, which is where most sophisticated evasion actually originates.

## 1. The evasion calculus

A rational evader weighs: (probability of detection) × (tax + penalty + prosecution risk) against (amount saved). At 100% the amount saved is maximal, so the regime must raise the other side. The levers, in order of cost-effectiveness:

| Lever | Effect on calculus |
|---|---|
| Third-party reporting mesh ([gifts-and-timing.md](gifts-and-timing.md) §5) | Raises detection probability structurally, before any audit — the single most powerful lever; income-tax compliance research consistently finds evasion collapses where third-party reporting exists [1] |
| Penalty gradient (§3) | Makes the loss-given-detection a multiple of the gain |
| No limitation period for concealment (§5) | Removes the "outlast the clock" strategy; detection probability accumulates over a lifetime instead of resetting |
| Whistleblower rewards (§4) | Turns every insider — the second spouse, the disgruntled sibling, the ex-adviser — into a detection risk |
| Adviser liability (§6) | Cuts supply of evasion schemes at source |

## 2. Audit strategy

Per the "valuation lottery" architecture in [valuation.md](valuation.md) §8: **risk-scored selection with a pure random component**. The risk model consumes the mesh (mismatches between third-party feeds and declared receipts), valuation-gap flags, appraiser history, connected-party transaction patterns, and offshore indicators; the random layer guarantees no profile is safe. Coverage is concentrated where the money is: returns crossing the threshold face materially higher audit rates than the sub-threshold mass, and the Tier-3 mandatory-review population ([valuation.md](valuation.md) §7) is effectively audited at 100%. Published *aggregate* audit statistics (rates by tier, yield) build deterrence; the selection model itself stays opaque. The staffing and funding insulation this requires is specified in [administration.md](administration.md) §4 — enforcement design is worthless if the audit budget can be quietly starved, the fate of the US estate tax in the 2010s and the sabotage route anticipated in [`../10-opposition/sabotage-after-passage.md`](../10-opposition/sabotage-after-passage.md).

## 3. Penalties: calibrated to negative EV

The penalty ladder distinguishes error from concealment:

| Conduct | Consequence |
|---|---|
| Late filing / payment | Existing self-assessment ladder ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §5) |
| Careless understatement | Tax + 30% of the understatement |
| Deliberate understatement | Tax + 100% |
| Deliberate with concealment / offshore | Tax + up to 200% (mirroring the UK's offshore-penalty enhancements, which already reach 200% for the least-transparent jurisdictions [2]) |
| Fraud | Criminal track (§7) plus civil recovery |

The arithmetic to hold: with detection probability *p* and penalty multiple *m* (total repayment = tax × (1+m)), evasion is negative-EV when p × (1+m) > 1. At a 200% penalty ceiling, detection probability above ~33% over the *lifetime of the concealment* (not per year — see §5) suffices; the mesh plus whistleblower channel plus no-limitation rule is designed to push lifetime detection probability for large concealed receipts well past that. Exact calibration to verify with compliance modelling.

## 4. Whistleblowers

The IRS whistleblower programme under IRC §7623(b) — mandatory awards of 15–30% of collected proceeds, made famous by the UBS/Birkenfeld award — demonstrates that paying insiders works at the top of the wealth distribution, where evasion is a conspiracy among family members, advisers, and fiduciaries [3]. The regime adopts a mandatory-percentage award for information leading to recovery above a floor, with protection against retaliation. HMRC's discretionary small-payments practice is the counter-example: low, uncertain rewards produce few high-value tips [4]. Family estrangement is, bluntly, an enforcement asset — the excluded sibling and the divorced spouse know where the assets are, and the award converts that knowledge into filings. Contested-probate litigation also surfaces concealment organically: every will dispute deposes the estate's true contents.

## 5. Limitation periods

- **Declared, good-faith returns:** assessment window closes after 4 years (aligning with existing self-assessment finality — taxpayers who disclose deserve certainty).
- **Careless:** 6 years.
- **Deliberate concealment or fraud: no limitation period.** A hidden receipt remains assessable whenever discovered, including against the recipient's own estate at their death — which is the moment concealment most often surfaces, since the concealed asset must either appear in their estate or be concealed again by the next generation, compounding the conspiracy. The UK's 20-year window for deliberate conduct and the unlimited US window for fraud/non-filing (IRC §6501(c)) are the precedents; the proposal takes the US rule [5].

The generational point deserves emphasis in communications: concealment is not a one-off act but a *perpetual liability* that must be re-managed at every subsequent death, marriage, divorce, and falling-out. Dynasties are long; the limitation clock never starts.

## 6. Advisers and enablers

Sophisticated evasion is sold, not invented at kitchen tables. The regime extends existing UK enabler-penalty legislation (penalties on those who design or market defeated avoidance, up to 100% of fees) and DOTAS-style scheme-disclosure duties to transfer-tax arrangements [6]; conviction-level conduct triggers the corporate offence of failure to prevent tax-evasion facilitation (Criminal Finances Act 2017) against firms [7]. Combined with the appraiser-licensing regime in [valuation.md](valuation.md) §6, the goal is that no regulated professional can profitably sign off an evasion structure — pushing evasion into the unadvised, error-prone form the audit model catches easily.

## 7. Criminal vs civil track

Civil recovery is the workhorse: faster, lower burden of proof, and the money is the point. The criminal track is reserved for deliberate fraud, false loss-certifications ([digital-and-novel-assets.md](digital-and-novel-assets.md) §2), enabler conspiracies, and obstruction — prosecuted selectively but *visibly*, because publicised prosecutions carry most of the deterrence weight (the pattern familiar from HMRC and DOJ Tax Division practice [8]). Charging standards should target the advised and the large; criminalising confused executors would be both unjust and politically suicidal. Interaction rule: criminal conviction does not displace civil assessment — tax, penalties, and interest survive prosecution.

## 8. International enforcement

Cross-border information flows ride CRS/FATCA and their extension to transfer reporting ([`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §7), CARF for crypto ([digital-and-novel-assets.md](digital-and-novel-assets.md) §1), and mutual-assistance instruments for collection (the OECD/CoE Convention on Mutual Administrative Assistance already provides for assistance in recovery [9]). Enforcement against emigrated taxpayers and haven-resident structures is the boundary with capital flight and is treated in [`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md) and [`../08-capital-flight/exit-tax-design.md`](../08-capital-flight/exit-tax-design.md); the domestic anchor is always the same — recipient liability plus onshore assets and onshore life as security ([trusts-and-vehicles.md](trusts-and-vehicles.md) §4).

## Research gaps

- Empirical detection-probability estimates for concealed transfers under current regimes (tax-gap literature is income-centric; transfer-tax gap estimates are thin — to verify what HMRC/IRS publish).
- Optimal whistleblower award floor for family-scale (vs corporate-scale) evasion.
- Whether penalty maxima above 200% would face proportionality challenges (ECHR A1P1 / US Eighth Amendment excessive-fines line — link [`../10-opposition/legal-challenges.md`](../10-opposition/legal-challenges.md)).

## Sources

1. [IRS — tax-gap studies showing compliance by information-reporting category](https://www.irs.gov/statistics/irs-the-tax-gap); Kleven et al. (2011), "Unwilling or Unable to Cheat?", *Econometrica* — Danish audit experiment.
2. [FA 2010 Sch 10 / HMRC offshore penalty regime — up to 200% for category 3 jurisdictions](https://www.gov.uk/government/publications/compliance-checks-penalties-for-offshore-non-compliance-ccfs17)
3. [US IRC §7623(b) — whistleblower awards; IRS Whistleblower Office annual reports; Bradley Birkenfeld/UBS award (2012)](https://www.irs.gov/compliance/whistleblower-office)
4. [HMRC — discretionary payments for information; NAO commentary](https://www.nao.org.uk/reports/)
5. [TMA 1970 ss.34–36 — 4/6/20-year assessment windows](https://www.legislation.gov.uk/ukpga/1970/9); [US IRC §6501(c) — no limitation for fraud or non-filing](https://www.law.cornell.edu/uscode/text/26/6501)
6. [Finance (No. 2) Act 2017 Sch 16 — penalties for enablers of defeated tax avoidance](https://www.legislation.gov.uk/ukpga/2017/32/schedule/16); [DOTAS — disclosure of tax avoidance schemes](https://www.gov.uk/guidance/disclosure-of-tax-avoidance-schemes-overview)
7. [Criminal Finances Act 2017 Part 3 — corporate failure to prevent facilitation of tax evasion](https://www.legislation.gov.uk/ukpga/2017/22/part/3)
8. [DOJ Tax Division — criminal enforcement policy](https://www.justice.gov/tax); HMRC criminal-investigation policy.
9. [OECD/Council of Europe — Convention on Mutual Administrative Assistance in Tax Matters, Arts. 11–16 (assistance in recovery)](https://www.oecd.org/tax/exchange-of-tax-information/convention-on-mutual-administrative-assistance-in-tax-matters.htm)
