# 07 — Implementation

**Executive summary.** This section takes the design in [`../02-proposal/`](../02-proposal/) as given and works through every concrete operational difficulty — valuation, line-drawing, vehicles, digital assets, administration, enforcement, and the catalogue of sympathetic hard cases — pairing each with a specific, precedented solution. The honest headline up front: two channels of inheritance (human capital and social networks) cannot be taxed at all, and the section argues explicitly why the tax is decisive anyway.

## The difficulty map

| Difficulty | Severity if unsolved | Tractability | File | One-line solution |
|---|---|---|---|---|
| Undervaluation of illiquid assets | Fatal (Austrian/German strike-downs) | High | [valuation.md](valuation.md) | Statutory methodology, insurance cross-checks, capped discounts, state-equity backstop, audit lottery |
| Receipt vs parental support boundary | High (ridicule + relabelling) | Medium | [boundary-problem.md](boundary-problem.md) | De-minimis allowance, support-to-25 exemption, market-rate imputation, disclosure tiers |
| Human-capital inheritance | Untaxable | — | [human-capital.md](human-capital.md) | Not taxed, by design; the tax severs the *compounding* stage instead |
| Nepotism and network transfers | Mostly untaxable; cash forms reachable | Medium | [nepotism-and-networks.md](nepotism-and-networks.md) | Arm's-length pay tests, undervalue claw-back; concede the pure-favour remainder |
| Gift timing and undeclared transfers | High (the 7-year-rule failure) | High | [gifts-and-timing.md](gifts-and-timing.md) | Lifetime cumulation kills timing games; third-party reporting mesh catches the undeclared |
| Trusts, foundations, wrappers | Fatal if open | High | [trusts-and-vehicles.md](trusts-and-vehicles.md) | Distribution charge + 10-year deemed charge + attribution; all from existing precedents |
| Crypto and novel assets | Medium, growing | Medium | [digital-and-novel-assets.md](digital-and-novel-assets.md) | CARF/chain-analysis detection; suspended-receipt rule for "lost keys" |
| Administrative burden and cost | Medium | High | [administration.md](administration.md) | Central Register on existing rails; probate gate; tiered returns; ~1–2% cost-to-yield target (to verify) |
| Evasion at a 100% marginal rate | High | Medium–high | [enforcement.md](enforcement.md) | Negative-EV design: mesh + penalties to 200% + whistleblowers + no limitation for fraud |
| Sympathetic hard cases | Fatal politically | High | [hard-cases.md](hard-cases.md) | Payment-side instruments (deferral, instalments, sweat-equity credit), never liability-side exemptions |

Capital flight — the one first-order difficulty not in this section — has its own section: [`../08-capital-flight/`](../08-capital-flight/).

## The honest headline: what cannot be taxed

Two inheritance channels are beyond any receipts tax, and this section says so before critics do:

1. **Human capital** — elite schooling, tutoring, cultivation, parental time ([human-capital.md](human-capital.md)). Taxing it would require pricing the unpriceable and policing family life; every design option examined fails on paternalism, valuation, or timing.
2. **Networks and reputation** — introductions, the surname, the favour economy ([nepotism-and-networks.md](nepotism-and-networks.md)). Non-alienable, non-evidencable, untaxable.

Why the tax is still worth having: both untaxable channels are **self-limiting** — they must be converted into position through the heir's own performance in labour and product markets, where income tax already waits — whereas financial capital is **self-compounding**, paying out regardless of talent or effort and ratcheting across generations. The tax targets the compounding channel, which is the one that builds dynasties ([`../03-case-for/piketty-r-vs-g.md`](../03-case-for/piketty-r-vs-g.md)); and the endowment ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)) attacks the same gap from below by capitalising everyone at 25. A tax need not close every channel of advantage to be the highest-leverage intervention available — income tax does not capture leisure, and no one thinks that an argument for abolishing it.

## Recurring design principles

- **Reuse, don't invent.** Every rule in this section is an existing rule somewhere — relevant-property charges, grantor-trust attribution, transfer pricing, s.423 claw-backs, CRS/CARF, §7623 whistleblower awards — reassembled on the receipts axis. The practicality objection ([`../09-objections/practicality.md`](../09-objections/practicality.md)) must contend with the fact that each component already operates.
- **Payment-side relief, never liability-side exemption.** Hardship is answered with deferral, instalments, and state equity; exemptions become avoidance vehicles (the BPR/APR lesson — [`../02-proposal/carveouts.md`](../02-proposal/carveouts.md)).
- **Make the taxpayer's own documents testify.** Insurance schedules, loan collateral valuations, payroll records, PSC filings — enforcement built on numbers the wealthy generate for their own purposes.
- **Negative expected value, not perfect detection.** The system needs evasion to be a bad bet for advised taxpayers, not a solved problem ([enforcement.md](enforcement.md)).
- **Concede the residue explicitly.** Bounded, consumption-shaped leakage (de-minimis gifting, hospitality, favours) is tolerated by design; it cannot move capital, and capital is the target.

## Files in this section

- [valuation.md](valuation.md) — pricing what people receive, asset class by asset class; the appraisal-capture problem; the audit lottery
- [boundary-problem.md](boundary-problem.md) — the receipt/support line: de-minimis, age-based exemption, imputation, disclosure
- [human-capital.md](human-capital.md) — the inheritance you cannot tax, and why the tax works anyway
- [nepotism-and-networks.md](nepotism-and-networks.md) — disguised transfers through jobs and firms; the untaxable favour economy
- [gifts-and-timing.md](gifts-and-timing.md) — lifetime cumulation mechanics; the death of timing games; traceability
- [trusts-and-vehicles.md](trusts-and-vehicles.md) — look-through and attribution for trusts, foundations, FICs, wrappers
- [digital-and-novel-assets.md](digital-and-novel-assets.md) — crypto, IP, brands, unvested equity; the seed-phrase problem
- [administration.md](administration.md) — the Central Register, probate integration, staffing, cost, privacy, appeals
- [enforcement.md](enforcement.md) — audits, penalties, whistleblowers, limitation periods, criminal track
- [hard-cases.md](hard-cases.md) — the farm, the family home, the disabled dependant, the unpaid heir, and the rest

## Reading order

For the sceptic asking "can this possibly work?": [administration.md](administration.md) → [valuation.md](valuation.md) → [enforcement.md](enforcement.md). For the philosopher asking "where does the line go?": [boundary-problem.md](boundary-problem.md) → [human-capital.md](human-capital.md) → [nepotism-and-networks.md](nepotism-and-networks.md). For the campaigner preparing for attack anecdotes: [hard-cases.md](hard-cases.md) first, then [`../10-opposition/attack-playbook.md`](../10-opposition/attack-playbook.md).
