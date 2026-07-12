# The First Twelve Months: A Founder's Runbook

**Executive summary.** This file converts the doctrine of this section into a dated, sequenced runbook for one specific situation: a UK-based private individual with a manifesto repository and no organisation, deciding whether and how to become a movement. The design principle is *cheap reversibility* — every commitment in months 0–9 is sized so that the pre-registered month-12 decision (kill, pivot, or scale) can be taken without sunk-cost pressure.

Everything strategic below is judgement unless a source is cited; costs are verified where marked, otherwise flagged as rough estimates.

## Key findings

- The three month-0 decisions — founder positioning, name, legal entity — are all cheap and largely reversible: online incorporation of a company limited by guarantee costs £100 (fee doubled from £50 on 1 February 2026) plus a £50 annual confirmation statement [1][2], and Charity Commission registration is free (a CIO can register with no income; a charitable company needs £5,000 income first) [3].
- The polling the movement needs first (P1 full-package test, P3 recipient-vs-estate framing — [../06-palatability/polling.md](../06-palatability/polling.md) §7) is affordable at seed scale: YouGov's published UK Academic Omnibus rate card is £240 setup + £360 per question on a politically representative 2,000-adult sample [4]; a bespoke three-arm split-sample experiment is a rough-estimate £10k–£30k.
- The closest verified comparator, Tax Justice UK, incorporated as a company limited by guarantee in May 2017 [5] and now runs on a publicly itemised mix of multi-year grants (£18k–£400k) plus ~£193k of individual donations over an 18-month period [6] — evidence that a single-issue UK tax-campaign org is sustainable at roughly £200k–£400k/year, and a working model of the glass-house funding doctrine ([funding.md](funding.md)).
- The calendar supplies two free media hooks a year: HMRC's Inheritance Tax liabilities statistics, published every July [7], and the autumn Budget. Year one should aim to be quoted at exactly one of them — no more ([theory-of-change.md](theory-of-change.md): credibility before attention).
- The binding constraint in year one is not money or law; it is the founder's own exposure decision and day-job runway — which is why the runbook opens with the personal-exposure audit from [../10-opposition/personal-attacks.md](../10-opposition/personal-attacks.md), not with incorporation.

## 1. Month 0: three decisions before anything is public

### 1.1 Founder positioning (judgement)

**Public founder, institutional architecture.** The alternatives are (a) public founder-spokesperson, (b) anonymous convenor who recruits others to front the work. Judgement: (a), with discipline. Anonymity is the astroturf signature the movement attacks in others ([funding.md](funding.md)); someone must sign the corpus for it to be citable; and the disclosure-first doctrine only works if practised from day one ([../10-opposition/personal-attacks.md](../10-opposition/personal-attacks.md), mitigation 1). But the *architecture* is built for rotation from the start — institutional byline on research, no personal brand in the org name (§1.2), and the explicit plan that the founder is one of several faces by year two ([messengers.md](messengers.md), anti-doctrine: no single permanent face).

**The personal-exposure audit, before the site goes live.** Run the opposition's stage-1 research on yourself ([../10-opposition/personal-attacks.md](../10-opposition/personal-attacks.md), "anatomy of a hit piece"): land-registry entries, Companies House directorships, old social media, family wealth, expected inheritances, anything a diary column could frame as hypocrisy. Then publish the standard declaration — assets, expected inheritances, how the policy would treat you — as a page on the manifesto site. The whole attack chain depends on concealment; a founder with a pre-published declaration has no reveal to fear.

**The day-job question (judgement).** Keep it through at least month 9. Nothing in quarters 1–3 requires full-time hours so much as consistent part-time ones, and a founder with independent income cannot be starved out by a funder's phone call — the personal version of the funding-diversity rule. Going full-time is a *consequence* of the month-12 scale decision (§4), taken only if the seed round can fund a salary without breaching the diversity caps in [funding.md](funding.md), plus 12 months of personal runway either way.

### 1.2 The name (judgement, applying the criteria in [../14-communications/naming-and-language.md](../14-communications/naming-and-language.md))

The *policy* names are already fixed — retail "Universal Inheritance", flagship "100% inheritance tax". Month 0 names the *organisation*. Shortlist, scored on the same four criteria:

| Candidate | Concreteness | Self-explaining | Attack-resistance | Ownability | Verdict |
|---|---|---|---|---|---|
| **Universal Inheritance** (entity: "Universal Inheritance UK") | Medium | High — org and demand are the same words | High — inherits the retail name's resilience | High if registered promptly | **Adopt now** |
| **The Inheritance Project** | Low | Medium — could be a genealogy service | High — bland survives sneering | Medium — generic | Fallback if the primary name is blocked |
| **Everyone Inherits** | Medium | High | Medium — reads as slogan, not institution | High | Keep as strapline, not entity name |
| **Fifty at 25** | High — the number is the name | Medium — needs one sentence | Medium — gimmick risk in serious rooms | High | Campaign-product name (e.g. the newsletter), not the org |
| **Centre for Inheritance and Opportunity** | Low | Medium | High — institute register | High | Reserve for the phase-2 research arm ([organisational-forms.md](organisational-forms.md)) |

Judgement: name the organisation after the retail name, because every mention of the org then repeats the demand — the discipline rule that the retail name appears in the first sentence of every artefact becomes automatic. Month-0 checks (an afternoon's work): Companies House name availability, domain, and social handles; note that P3's framing result ([../06-palatability/polling.md](../06-palatability/polling.md)) arrives in Q1 and the naming file's own message-testing item remains open, so treat the entity name as settled but the strapline as testable.

### 1.3 The legal entity (mechanics verified July 2026)

Apply [organisational-forms.md](organisational-forms.md): the campaigning vehicle cannot be a charity, so the first entity is a **private company limited by guarantee without share capital** — the structure Tax Justice UK uses [5]. Mechanics:

- Online incorporation: **£100** (raised from £50 on 1 February 2026); annual confirmation statement **£50** [1][2]. Same-day digital service £156 [2].
- A guarantee company with suitable non-distribution objects can apply the "Limited"-name exemption, as Tax Justice UK did [5] — take advice at drafting, not a month-0 blocker.
- The **charitable research arm comes later** (year 2+, per the build sequence): Charity Commission registration is free; a charitable company or trust needs £5,000 income (or an equivalent grant offer) to register, whereas a **CIO can register with no income at all** [3] — so the charitable arm is never gated on money, only on the governance-separation design in [organisational-forms.md](organisational-forms.md).
- Election law is not a year-one constraint but should be known now: non-party campaigners must notify the Electoral Commission only above **£10,000** of regulated campaign spend in the regulated period [8]; year-one activity is research and recruitment, nowhere near it. Diarise a review if a general election is called.

Judgement on timing: incorporate when the first external money or contract needs a counterparty (likely early Q1, to sign the polling contract and open a bank account), not on day one. Total entity cost in year one: roughly £150 plus a few hundred pounds of legal review — negligible against the decisions it enables.

## 2. Quarter 1 (months 1–3): Foundations

1. **Publish the manifesto site.** This repository is the content; the site is a static build of it — the "permanent, linkable proof-of-depth layer" of [../14-communications/overton-strategies.md](../14-communications/overton-strategies.md). Static hosting is effectively free (rough estimate: under £100/year including domain); the real cost is editorial — the verification pass that makes the corpus citable (stage-1 milestone, [theory-of-change.md](theory-of-change.md)). Every page ends at a capture step (newsletter signup) per [recruitment.md](recruitment.md) ring-4 doctrine.
2. **Commission P1 and P3** ([../06-palatability/polling.md](../06-palatability/polling.md) §7). P3 (recipient vs estate framing, identical incidence described both ways) fits a split-sample omnibus; P1 (tax-only vs tax+endowment vs endowment-led) needs a bespoke three-arm experiment. Verified anchor: YouGov's UK Academic Omnibus rate card is £240 setup + £360 per question, £180 per extra cross-break, on 2,000 UK adults with next-working-day results [4] — note it is priced for academic researchers, which is itself an argument for running these *with* a university collaborator ([recruitment.md](recruitment.md), ring 2: the bounded prestigious ask). Commercial omnibus pricing starts around £0.80 per complete and scales with questions and targeting [9]. Rough estimates, flagged as such: P3 on omnibus ≈ £2k–£5k; P1 as a full-service three-arm experiment (~3,000 respondents) ≈ £10k–£30k, or a £5k–£8k online-panel pilot first with the headline replicated by a named pollster for citability. Pre-register the analysis — an unregistered favourable poll is worth little against the attack playbook.
3. **First ten recruits, by skills matrix, not enthusiasm.** Sourced and converted per [recruitment.md](recruitment.md); each is a bounded ask, not a job offer:

| # | Role | Ring | First bounded ask |
|---|---|---|---|
| 1 | Academic economist-adviser | 2 | Peer-review the revenue and threshold chapters |
| 2 | Tax lawyer / estate planner (defector) | 2 | Anonymous technical review of [../07-implementation/trusts-and-vehicles.md](../07-implementation/trusts-and-vehicles.md) |
| 3 | Comms professional | 2 | Critique the site's first-hour experience |
| 4 | Community organiser | 1–2 | Design the ladder from subscriber to first event |
| 5 | Charity/election lawyer | 2 | Entity objects + gift-acceptance policy review |
| 6 | Fundraiser | 2 | Map ten realistic first funders against [funding.md](funding.md) |
| 7 | Pollster / survey methodologist | 2 | Co-design P1/P3 instruments |
| 8 | Designer / web developer | 2 | Ship the static site |
| 9 | Second writer-researcher | 1 | Own one section of the corpus as named maintainer |
| 10 | Heir- or founder-defector messenger | 2 | Private conversation; no public ask yet ([messengers.md](messengers.md)) |

4. **Open the advisory outreach maps.** Work the named-target files as they land: [outreach-academics.md](outreach-academics.md), [../12-political-adoption/target-politicians.md](../12-political-adoption/target-politicians.md), [../14-communications/outreach-creators.md](../14-communications/outreach-creators.md). Q1 asks are advisory and private — no politician-facing activity before the corpus is citable ([../14-communications/overton-strategies.md](../14-communications/overton-strategies.md): skipping rungs loses the salience war).

## 3. Quarters 2–3 (months 4–9): Proof

1. **First funding round: £100k–£250k seed (judgement on size).** Calibration from the verified comparator: Tax Justice UK's publicly itemised funding runs from an £18k one-year grant to a £400k four-year grant, with £193,390 of individual public donations across an 18-month period [6] — so a £100k–£250k first-year ask sits inside the normal range of the UK funders already listed in [funding.md](funding.md) (Friends Provident's comparable grant is £84,400 over 2024–26 [6]). Apply the diversity rules from day one: no single funder above the published cap, irrevocable gifts preferred, the gift-acceptance policy shown before negotiation. Publish the funder ledger in the Tax Justice UK format [6] from the first pound — the glass house is cheapest to build empty.
2. **First media moment, keyed to the calendar.** HMRC publishes its Inheritance Tax liabilities statistics every July [7]; the autumn Budget is the other fixed hook. The play is the Tax Justice UK model: a short, verified, pre-written briefing ("who actually pays, what a recipient-based alternative looks like") pitched to wealth-beat journalists the week before, with the founder or — better — recruit #10 available for quotes. Success in year one is being quoted *as the recognised proponent* once ([theory-of-change.md](theory-of-change.md), stage 3); failure twice running is a listed falsifier.
3. **The first heir-defector testimonial.** The Engelhorn archetype ([../10-opposition/personal-attacks.md](../10-opposition/personal-attacks.md)) sourced via the Patriotic Millionaires orbit per [messengers.md](messengers.md) and [heir-defectors.md](heir-defectors.md): one credible person saying "tax what I'm due to inherit" on the record, disclosure-first, fully vetted. Judgement: this single artefact is worth more than any Q2 press release — if a choice must be made, delay the media moment, not the vetting.
4. **University society seeding.** Two or three pilot societies (economics/PPE-heavy campuses), per [recruitment.md](recruitment.md) ring 3: a starter kit (debate-toolkit one-pagers, a speaker visit, the £50k-at-25 offer as the recruiting hook), each society asked to run one termly event that ends with a specific next ask. Cheap, and the first test of whether the ladder converts.

## 4. Quarter 4 (months 10–12): Choose the vehicle

**Assess against pre-registered criteria — written down now, in month 0, precisely so month-12 arguing is impossible.** Thresholds are judgement; the pre-registration is the point:

| Signal | Scale (all four) | Pivot (any) | Kill (any) |
|---|---|---|---|
| Polling | P1 shows endowment-led package net-positive with under-45s and beating tax-only framing | Package helps but framing gaps contradict the lexicon → revise [../14-communications/](../14-communications/README.md) first | P1 shows the endowment pairing makes opinion *worse* and P3 shows no framing recovers it |
| Funding | ≥ £100k committed within diversity caps | £25k–£100k → stay part-time, extend foundations 12 months | < £25k after 20+ qualified approaches |
| Recruits | ≥ 7 of the 10 roles filled with credible people | 4–6 filled | < 4, or the economist and lawyer rings decline association (stage-1 falsifier, [theory-of-change.md](theory-of-change.md)) |
| Media | Quoted by name at one calendar hook | Coverage without attribution | Two hooks pass unmentioned *and* pitching feedback is "not credible" rather than "not yet" |

- **Scale** means: first hire, founder goes full-time (with the runway condition from §1.1), begin the phase-1/phase-2 conversation with host institutions per [organisational-forms.md](organisational-forms.md), and start the charitable-arm design (CIO route, §1.3).
- **Pivot** means: the idea survives, the current vehicle doesn't — most likely toward the hosted-programme form (donate the corpus's momentum to a think-tank programme) rather than an independent org.
- **Kill** means, honestly: the repo stays online, openly licensed, as ideas lying around for a future crisis window ([theory-of-change.md](theory-of-change.md)) — a kill of the *organisation*, not the corpus.
- **Publish the year-one transparency report regardless of outcome**: every pound in and out, the funder ledger, the refusal log, poll tables including unfavourable ones ([funding.md](funding.md) transparency-as-armour). A movement that publishes its own kill decision buys credibility no living org can.

## 5. Twelve-month milestone table

| Month | Milestone | Measured by |
|---|---|---|
| 0 | Exposure audit done; declaration drafted; name checked and reserved; kill/pivot/scale criteria written and dated | Documents exist before any public step |
| 1–2 | Manifesto site live with capture step; entity incorporated when first contract needs it | Site up; £100 spent [1] |
| 2–3 | P1/P3 commissioned with academic collaborator; recruits 1–5 engaged | Signed fieldwork dates; named reviewers |
| 4–5 | P1/P3 results in, pre-registered analysis published (favourable or not) | Public write-up |
| 4–6 | Funder approaches begin (10+ qualified); funder ledger page live | First committed money |
| 7 (July) | First calendar-hook media attempt: HMRC IHT statistics release [7] | Named quote in national outlet |
| 6–9 | Heir-defector vetted and recorded; 2–3 university societies seeded | Testimonial ready to publish; first society events held |
| 9 | Recruits 6–10 engaged; seed round at or past halfway | Skills matrix ≥ 7/10 |
| 10–11 | Second hook prepared (Budget); year-one accounts drafted | Briefing pack pre-written |
| 12 | Kill/pivot/scale decision against §4 table; transparency report published | Decision memo, public |

## 6. Minimal year-one budget (illustrative — every line a rough estimate)

Mid-case, assuming the seed round part-funds the year; a no-funding year compresses to the starred lines (~£10k, self-funded discipline cap):

| Line | Estimate |
|---|---|
| *Entity, filings, basic legal review | £1,500 |
| *Site, domain, newsletter tooling | £1,000 |
| Polling P1 + P3 (§2) | £15,000–£35,000 |
| Specialist legal (gift policy, election-law memo) | £4,000 |
| *Travel, events, university seeding | £4,000 |
| Comms/design freelance support | £8,000 |
| First hire, part-year (researcher-organiser, from ~month 9 if scaling) | £20,000–£30,000 |
| Founder stipend (only if scale criteria met) | £0–£15,000 |
| Contingency (~10%) | £6,000 |
| **Total** | **~£60k–£105k** against a £100k–£250k seed target |

## 7. Founder succession and the bus factor

A 25-year theory of change must survive month one's single point of failure. Minimums, from day 0: the corpus openly licensed so doctrine outlives the founder ([theory-of-change.md](theory-of-change.md), implication 3); all credentials (domain, repo, mailing list, socials, bank) held in a password manager with a named second keyholder; a one-page "if I stop" memo naming a convenor-successor among the first ten recruits; and, at incorporation, the founder-capture governance from [organisational-forms.md](organisational-forms.md) — fixed founder board terms and a named succession plan written into year one, not deferred to maturity.

## 8. Honest limits

- **Survivorship bias.** Runbooks are reverse-engineered from movements that survived; Tax Justice UK is cited here *because* it lived. The failed single-issue campaigns that would discipline these estimates mostly left no accounts worth reading, and no reliable base-rate statistic for UK campaign-org survival could be located — the honest prior, stated as judgement, is that most such launches fizzle within two years, which is exactly why §4's criteria are pre-registered.
- **The comparator gap.** Tax Justice UK's *early-year* income could not be verified from public filings (small-company accounts disclose no income statement); its current funder ledger [6] is the best public proxy, and the seed-round sizing built on it is inference, not evidence.
- **Costs move.** Companies House fees doubled in February 2026 [2]; polling rate cards revise annually. Re-verify every figure here before spending against it.
- **What this file cannot decide.** The founder's risk tolerance, financial runway, family situation, and appetite for the personal fire documented in [../10-opposition/personal-attacks.md](../10-opposition/personal-attacks.md) are inputs to the runbook, not outputs of it. The runbook's honest promise is narrower: if you run year one this way, month 12's decision will be cheap, informed, and yours.

## Sources

1. [GOV.UK — Companies House fees (current fee table)](https://www.gov.uk/government/publications/companies-house-fees/companies-house-fees)
2. [GOV.UK — Companies House fees are changing from 1 February 2026](https://www.gov.uk/government/news/companies-house-fees-are-changing-from-1-february-2026)
3. [GOV.UK — Set up a charity: register your charity](https://www.gov.uk/setting-up-charity/register-your-charity)
4. [YouGov — UK Academic Omnibus (rate card: £240 setup, £360/question, 2,000 UK adults)](https://yougov.com/en-gb/business/products/serviced-surveys/uk-academic-omnibus)
5. [Companies House — Tax Justice UK, company 10761736 (incorporated 9 May 2017; private company limited by guarantee)](https://find-and-update.company-information.service.gov.uk/company/10761736)
6. [Tax Justice UK — Our funders (itemised grants and public-donation totals)](https://www.taxjustice.uk/funders.html)
7. [GOV.UK — HMRC Inheritance Tax liabilities statistics (annual, published each July)](https://www.gov.uk/government/statistics/inheritance-tax-liabilities-statistics)
8. [Electoral Commission — Elections Act 2022: reporting and notification thresholds for non-party campaigners](https://www.electoralcommission.org.uk/non-party-campaigners-where-start/elections-act-2022-reporting-threshold)
9. [YouGov — GB/UK Omnibus (commercial omnibus, pricing from £0.80 per complete)](https://yougov.com/business/products/serviced-surveys/gb-uk-omnibus)
