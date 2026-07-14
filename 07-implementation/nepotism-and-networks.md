# Nepotism and Networks

**Executive summary.** Wealth transfers travel not only as assets but as favours: the cushy job in the family firm, the board seat, the client book quietly handed over, the "salary" that is really a bequest in monthly instalments. This file separates the favours that are disguised capital transfers — taxable, with existing legal machinery to catch them — from the favours that are genuinely untaxable (introductions, reputation), and argues that the tax still matters because it shrinks the capital that gives nepotism its leverage.

## The taxonomy

| Favour | Nature | Reachable? |
|---|---|---|
| Heir "employed" at 3x market salary | Disguised transfer of cash | Yes — market-rate test (§1) |
| Business sold to heir at undervalue | Disguised transfer of equity | Yes — undervalue claw-back (§2) |
| Client book / customer relationships handed to heir | Transfer of goodwill | Partially — where it moves with equity or contract (§2); not where purely relational |
| Board seat at the family-controlled listed company | Position, some pay | Governance/disclosure, not tax (§3) |
| Cushy job at a *friend's* firm, reciprocated | Network exchange | No — untaxable remainder (§4) |
| Introductions, reputation, surname | Pure social capital | No — untaxable remainder (§4) |

The design principle: **where the favour has a market price and a paper trail, price it and tax the shortfall; where it does not, be honest and rely on the capital channel.**

## 1. Family employment: the market-rate test

Paying an heir £300k for a £60k job converts inheritance into deductible salary, drip-fed below the radar. The remedy is the transfer-pricing analogy: related-party compensation in closely held firms must be defensible at **arm's length**, exactly as cross-border intra-group transactions must be under OECD transfer-pricing rules [1]. Mechanics:

- For companies under family control, compensation to connected persons above a disclosure floor is reported annually (a schedule to the corporate return — most of the data already exists in RTI/payroll filings).
- The excess of pay over the arm's-length band for the role is recharacterised as a **taxable receipt** on the heir's lifetime ledger ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §1), not merely disallowed as a corporate deduction.
- Precedents already operating: US IRC §162 "reasonable compensation" case law polices exactly this line for closely held C-corps (developed through cases like *Exacto Spring*'s independent-investor test) [2]; HMRC applies a wholly-and-exclusively test to family wages (*Copeman v William Flood & Sons* is the classic authority on excessive family remuneration) [3]. The proposal reuses this machinery, changing only the destination of the recharacterised amount: the ledger, not just the corporation-tax computation.

The same test covers the adjacent dodge of employing heirs **pre-death at inflated salaries** to run down the estate: recharacterised excess is a gift when paid, cumulating under [gifts-and-timing.md](gifts-and-timing.md). The equity twin of the inflated salary — cheap options, founder-class shares, or carried interest granted to heirs — is owned by [buy-borrow-die.md](buy-borrow-die.md) §3: receipt at grant, appraisal discipline, ERS-feed detection.

## 2. Succession at undervalue and the client-book handover

Selling the business to the heir at half its value transfers the other half invisibly. The base rule already catches it — below-market transfers are receipts of the shortfall ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) §1(vi)) — but enforcement needs claw-back teeth for the cases discovered late:

- **Undervalue-transaction claw-back.** Existing law supplies two tested templates: UK IHT's *gifts with reservation of benefit* doctrine (FA 1986 s.102 — you cannot give it away and keep enjoying it) [4], and **s.423 Insolvency Act 1986** (transactions defrauding creditors — a court can unwind undervalue transfers whenever they were made, with no limitation period where the purpose was to put assets beyond reach) [5]. The proposal creates a parallel civil power: HMRC/IRS may reassess any connected-party transaction at market value within 12 years, and without time limit where concealment is shown ([enforcement.md](enforcement.md)).
- **Goodwill and client books.** Where the client relationships are an asset of the firm, they pass with the equity and are valued within it ([valuation.md](valuation.md) §2). Where a retiring parent simply *introduces* clients to the child's new firm, there is no asset transfer in law and the proposal does not pretend otherwise — this migrates to §4. The intermediate case (formal referral agreements, restrictive covenants waived for the heir) is caught where documented: waiving an enforceable covenant of value is a disposition.

## 3. Listed firms: governance and disclosure, not tax

The board seat for the founder's child at a listed company is a real transfer of position, but its cash value is mostly future salary — which income tax already reaches — and its remainder is reputational. The right instruments are corporate-governance ones, most already in place: related-party-transaction disclosure under listing rules, remuneration-committee independence, and shareholder votes [6]. The proposal adds one item: family-successor appointments at family-controlled listed firms are flagged in the annual related-party schedule, feeding the audit-risk model in [enforcement.md](enforcement.md). Beyond that, this is a problem for governance codes and, ultimately, for the diffusion of ownership that the tax itself accelerates (§5).

## 4. The untaxable remainder

Introductions, the lunch that leads to the internship, the surname that gets the CV read, the implicit guarantee that lets the heir take risks — none of this can be valued, evidenced, or taxed, and a regime that tried would be both totalitarian and ridiculous. This must be conceded plainly, for the same structural reason as [human-capital.md](human-capital.md): a receipts tax reaches *alienable value*, and social capital is not alienable. Three mitigations are worth naming without overclaiming:

- Network advantage **decays without capital behind it**. The introduction gets the meeting; the family balance sheet gets the shareholding, seeds the fund, underwrites the venture. Strip the balance sheet above the threshold and the surname opens doors onto rooms where the heir must still perform.
- Network advantage is **already partially priced through income tax** when it converts into salary or carried interest.
- The endowment ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)) gives the unconnected a fraction of what connections buy: the buffer to take the unpaid-ish internship, the stake to start the firm without a family guarantee.

## 5. The structural argument: shrink the capital, shrink the leverage

Nepotism is not merely distasteful; it is *load-bearing* because family capital makes it credible — the heir is hired partly because the family owns the client, the building, the stake ([`../01-problem/political-capture.md`](../01-problem/political-capture.md), [`../01-problem/rentier-economy.md`](../01-problem/rentier-economy.md)). A tax that caps inherited financial capital at the threshold does not stop a parent making calls, but over one or two generations it dissolves the *institutional* nepotism of family-controlled blocks of capital: fewer firms where the controlling family can install heirs at will, fewer family offices to employ them, fewer landlord dynasties to absorb them. The favour economy survives; its balance sheet does not. That is the honest, and sufficient, claim — argued at greater length in [`../16-second-order/dynasties-and-power.md`](../16-second-order/dynasties-and-power.md).

A second-order effect worth flagging for [`../16-second-order/heirs-and-work.md`](../16-second-order/heirs-and-work.md): where the family firm can no longer be *given* to the heir, the rational family strategy shifts from installing heirs toward selling to the best owner and giving the heir their threshold in cash — which is better for the firm, the heir, and everyone who would otherwise have worked under an unqualified successor.

## Worked example

Patel Logistics Ltd, family-controlled, turnover £20m. The founder's son joins at 30 as "Strategy Director" on £280,000; the arm's-length band for the role in that sector and firm size benchmarks at £90,000–£130,000.

| Year | Salary paid | Arm's-length ceiling | Recharacterised receipt |
|---|---|---|---|
| 1 | £280,000 | £130,000 | £150,000 |
| 2 | £290,000 | £134,000 | £156,000 |
| 3 | £300,000 | £138,000 | £162,000 |

Three years of "employment" post £468,000 to the son's lifetime ledger — nearly a full £500k threshold consumed before any bequest arrives. The corporation-tax deduction for the excess is also disallowed under existing wholly-and-exclusively rules [3], so the structure is penalised twice. Had the son genuinely performed a £280k-calibre role — demonstrable through the same evidence an unrelated hire would generate (recruitment process, comparable external offers, output) — the band itself moves and nothing is recharacterised: the test burdens sham employment, not family talent.

## Research gaps

- Frequency of formal client-book transfers (referral agreements, covenant waivers) in professional-services succession — how much of §2's intermediate case is documented in practice.
- Empirical scale of excess family compensation in closely held firms (US reasonable-compensation litigation gives cases, not magnitudes — to verify whether any systematic study exists).
- Whether a statutory arm's-length band by role/sector is feasible or whether case-by-case benchmarking (as in transfer pricing) is the only workable form.
- Evidence from Nordic economies on whether lower inherited wealth correlates with lower rates of dynastic firm succession (link [`../11-geographies/nordics.md`](../11-geographies/nordics.md)).

## Sources

1. [OECD Transfer Pricing Guidelines for Multinational Enterprises and Tax Administrations](https://www.oecd.org/tax/transfer-pricing/oecd-transfer-pricing-guidelines-for-multinational-enterprises-and-tax-administrations-20769717.htm)
2. [US IRC §162(a)(1) reasonable-compensation doctrine; *Exacto Spring Corp. v. Commissioner*, 196 F.3d 833 (7th Cir. 1999)](https://www.law.cornell.edu/uscode/text/26/162)
3. [*Copeman v William Flood & Sons Ltd* [1941] 1 KB 202; HMRC BIM47105 — wages paid to relatives](https://www.gov.uk/hmrc-internal-manuals/business-income-manual/bim47105)
4. [Finance Act 1986 s.102 — gifts with reservation of benefit; HMRC IHTM14301](https://www.gov.uk/hmrc-internal-manuals/inheritance-tax-manual/ihtm14301)
5. [Insolvency Act 1986 s.423 — transactions defrauding creditors](https://www.legislation.gov.uk/ukpga/1986/45/section/423)
6. [FCA Listing Rules / UK Corporate Governance Code — related-party transactions and board independence](https://www.frc.org.uk/library/standards-codes-policy/corporate-governance/uk-corporate-governance-code/)
7. [Perez-Gonzalez, F. (2006), "Inherited Control and Firm Performance", *American Economic Review*](https://www.aeaweb.org/articles?id=10.1257/aer.96.5.1559) — evidence that heir-CEO succession underperforms professional succession.
