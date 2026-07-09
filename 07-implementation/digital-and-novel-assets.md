# Digital and Novel Assets

**Executive summary.** Crypto held on self-custodied keys, royalty streams, domain portfolios, influencer goodwill, and unvested equity all pose the same pair of questions in new clothing: can the state *see* the transfer, and can it *price* it? This file sets out detection (chain analysis, exchange reporting under CARF), valuation approaches per asset class, and the burden-of-proof architecture for the signature hard case — the estate that claims the seed phrase died with the deceased.

## The asset landscape

| Asset | Detection difficulty | Valuation difficulty | Primary tool |
|---|---|---|---|
| Exchange-held crypto | Low (reporting) | Low (market price) | CARF/exchange feeds (§1) |
| Self-custodied crypto | High | Low | Chain analysis + presumptions (§1–2) |
| IP and royalty streams | Low (registered, contracted) | Medium | PV at statutory rate + true-up (§3) |
| Domain names | Low (registrars) | Medium | Comparables; realisation true-up (§3) |
| Personal brand / influencer goodwill | Medium | High | Tax only what is alienable (§4) |
| Data and in-game assets | Medium | Usually immaterial | Materiality floor (§4) |
| Unvested equity, options, carry | Low (issuer records) | Medium | Tax point at vesting/realisation (§5) |

## 1. Crypto: detection

Self-custody removes the intermediary but not the trail — public-ledger assets are *more* traceable than cash once an address is linked to a person, and commercial chain-analysis is now routine in law enforcement and exchange compliance [1]. The regime's layers:

- **Exchange and custodian reporting.** The OECD's Crypto-Asset Reporting Framework (CARF) extends CRS-style automatic exchange to crypto intermediaries, with first exchanges of information in the late 2020s [2]; the Central Register consumes these feeds like bank feeds ([gifts-and-timing.md](gifts-and-timing.md) §5).
- **On/off-ramp choke points.** Dynastic sums must eventually touch the banked economy — buying property, funding a company, spending at scale. AML source-of-funds checks at those ramps force a provenance story, which is checked against the ledger.
- **Estate discovery duties.** Executors must make reasonable enquiry for digital assets (device forensics, exchange statements, password managers) and certify the search in the Estate Information Return; professional executor standards bodies already publish digital-asset checklists [3].
- **Chain analysis on audit.** Where audit flags a mismatch, tracing from known addresses (historic exchange withdrawals reported under CARF) follows funds to current wallets. Privacy coins and mixers narrow this — acknowledged; they then collide with the ramps and the presumptions below.

## 2. "Died with the seed phrase": burden of proof

The signature evasion story: the deceased held 200 BTC, the heirs shrug, the keys are "lost." Genuine loss is real (early-era holders demonstrably have lost fortunes), so a blanket deemed receipt would be unjust; a free pass would make every hodler's estate tax-free. The resolution is a **rebuttable presumption keyed to movement and enjoyment**:

- Assets whose keys are certified lost are entered on the Register as **suspended receipts** at date-of-death value, taxed at 0% now.
- If the assets *ever move* on-chain, the movement is conclusive evidence the keys existed; the suspended receipt crystallises at the higher of death-date or movement-date value, attributed to the estate's beneficiaries pro-rata, plus fraud penalties where the loss certification was knowingly false ([enforcement.md](enforcement.md) — no limitation period for fraud).
- Watching for movement is cheap and permanent: the addresses are public, and monitoring is automated.

This makes the false-loss strategy a lifetime freeze: the heirs may keep the claim or the coins, not both. The same suspended-receipt device generalises to any asset that is claimed inaccessible but might resurface (bearer instruments, safe-deposit contents abroad).

## 3. IP, royalties, and domains

Copyrights, patents, catalogues, and trademarks are registered, contracted, and generate observable cash flows — detection is easy; valuation is the issue, and the music-catalogue boom shows both that markets price these assets and that prices swing widely [4]. Per [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) §6: present value of projected cash flows at gilts + 3%, with a **five-year true-up** — actual royalties materially above projection trigger reassessment of the original receipt. The true-up converts forecasting disputes into wait-and-see, the same design used for private businesses in [valuation.md](valuation.md) §2. The US estate of Michael Jackson litigation — a court finding image-and-likeness value orders of magnitude between taxpayer and IRS positions [5] — is the cautionary case for point-estimate valuation of fame assets; earn-out-style settlement is the answer. Domains: registrar records make transfers visible; valuation by comparables with a realisation true-up on sale within 3 years.

## 4. Personal brands, goodwill, data, in-game assets

A follower count, a reputation, an audience relationship — like the networks in [nepotism-and-networks.md](nepotism-and-networks.md) — is mostly **non-alienable and therefore not a receipt**. The rule: tax what actually transfers in law. Where the brand is incorporated (the influencer's company owning channels, contracts, and trademark), the *shares* transfer and are valued as a private business, with the honest discount that the personal element dies with the person; where nothing but memory transfers, nothing is taxed. Account-based assets (channels, handles, in-game holdings) are receipts where platform terms make them transferable and a market prices them; a **materiality floor** (assets below the de-minimis line need no valuation) keeps the regime out of teenagers' game inventories. Personal data has no established heir-side market value and is ignored until one exists.

## 5. Unvested equity, options, and carried interest

The deceased's unvested RSUs, options, and fund carry are contingent claims. Taxing at death forces valuation of contingencies; the regime instead **defers the tax point to vesting or realisation in the heir's hands**: the heir takes the position with a ledger marker, and value entering the ledger is measured when the contingency resolves (vesting date fair value; carry when distributed). Issuer and fund-administrator reporting makes these events visible. This mirrors how income tax already handles the timing of equity compensation and avoids importing the US §409A-style valuation industry into estates [6]. Anti-abuse: arrangements that park transfers inside artificial "unvested" wrappers to defer indefinitely are recharacterised under the general value-shift rule ([trusts-and-vehicles.md](trusts-and-vehicles.md) §3).

## 6. Design principle: technology changes detection, not the base

None of these assets requires a new tax base — a receipt is a receipt whether it arrives as land or as a key ceremony. What changes is the evidence layer, and the regime's posture is to reuse the international plumbing being built anyway (CARF, CRS, AML ramps) rather than invent bespoke surveillance. The residual leak — genuinely undetected self-custody transfers, never touching a regulated ramp, spent covertly forever — is real but shares the structure of the cash leak in [gifts-and-timing.md](gifts-and-timing.md) §4: it forces wealth to stay outside the institutions that make wealth *useful*, which is a heavy standing cost and no basis for a dynasty. Jurisdictional escape via crypto-friendly havens is a capital-flight question: [`../08-capital-flight/exit-options.md`](../08-capital-flight/exit-options.md).

## Research gaps

- CARF implementation timelines and coverage gaps by jurisdiction (to verify current state; DeFi and unhosted-wallet reporting remain contested).
- Empirical base rates of genuine key loss for estimating the suspended-receipts population.
- Whether the vesting-deferral rule for carry needs an interest charge to remove deferral advantage.

## Sources

1. [Chainalysis — Crypto Crime Reports; use of chain analysis in enforcement](https://www.chainalysis.com/reports/); UK NCA and IRS-CI seizure practice.
2. [OECD — Crypto-Asset Reporting Framework and amendments to the CRS (2022)](https://www.oecd.org/tax/exchange-of-tax-information/crypto-asset-reporting-framework-and-amendments-to-the-common-reporting-standard.htm)
3. [STEP — digital assets guidance for practitioners](https://www.step.org/); Law Society practice notes on digital assets in estates.
4. Coverage of music-catalogue acquisitions (Hipgnosis, Sony/Dylan, Springsteen) — market pricing of royalty streams (to verify multiples).
5. [*Estate of Michael J. Jackson v. Commissioner*, T.C. Memo. 2021-48](https://www.ustaxcourt.gov/) — image-and-likeness valuation dispute.
6. [US IRC §409A and equity-compensation valuation practice](https://www.law.cornell.edu/uscode/text/26/409A)
