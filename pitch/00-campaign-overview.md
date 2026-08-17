# Campaign Overview — Read This First

**Prepared 17 August 2026.** This file is the entry point to `pitch/`. It says what the campaign was
meant to do, what the work actually found, and what to do about it.

---

## The one-paragraph version

You asked for a campaign to persuade Abu Dhabi developers to create a rent-to-own villa or townhouse
at ≤ AED 150,000/yr, structured as a Tawtheeq tenancy your employer could pay directly. We built the
economics, the target dossiers, the term sheet and the pitch — then had three adversarial reviewers
attack them. **The commercial review falsified the product.** There is no combination of equity credit
rate, term and option strike that both clears a developer's hurdle rate and accumulates enough for
you to reach a financeable deposit. Not at three years, not at five, not at any hurdle rate from 6% to
10%. The campaign material still exists and is now honest about this, but you should not send it as a
proposal — you should use it as the basis for a much smaller, cheaper set of questions.

---

## What the numbers actually say

Two constraints, set against each other on an illustrative AED 2.2M outer-ring townhouse:

- **You need** enough accrued credit to reach a mortgageable deposit (~20% of value, plus transaction
  costs the credit cannot pay).
- **The developer needs** the deal to beat their live alternatives — letting the unit normally, or
  discounting it to sell today.

| Hurdle rate | Term | Developer can afford to credit | You need | Gap |
|---|---|---|---|---|
| 6% | 5 yr | 35.3% | 44.0% | −2.2% of value |
| **8%** | **5 yr** | **38.5%** | **44.0%** | **−1.3%** ← closest it ever gets |
| 8% | 3 yr | 42.1% | 73.3% | −5.1% |
| 10% | 5 yr | ceiling collapses vs a clearing sale | 44.0% | nothing works |

**The regions never overlap.** Under the all-in AED 150k cap (rent *plus* service charge *plus*
management fee), the closest miss widens to −3.6% and **no term from three to ten years clears at all.**
Adding transaction costs to the sizing — which is correct, since accrued credit cannot pay transfer
fees — pushes your requirement to ~51% and closes the last surviving cell.

**The cleanest form of the finding:** the structure only works on stock yielding **above ~9% gross**.
The Abu Dhabi townhouse market averages nearer **6%**. That gap is the whole story, and it is why this
is a market-structure problem rather than a negotiation problem.

**What this is not.** It is not a claim that rent-to-own can never work in Abu Dhabi — Aldar launched
schemes twice in 2019. It is a claim that *at AED 150k/yr, on villa and townhouse stock, with the
occupier needing to reach a deposit*, the arithmetic does not close. Aldar's only villa scheme was
priced at AED 220k/yr **plus** AED 15k/yr management — roughly 57% above this budget, all-in. That is
the market telling you where the number has to be.

---

## The three things that were wrong and are now fixed

Worth knowing, because they are the kind of error that would have cost you a meeting:

1. **The pitch claimed your employer funding as an existing fact** while its own appendix told you to
   describe yourself as someone still checking. If HR came back "tenancy only, no purchase option",
   you would already have put the opposite in writing to a developer. Now stated conditionally
   throughout, with a forced-honesty field for the HR status.
2. **Nobody asked whether you can take title at all.** Of the target communities, only Al Reef is
   confirmed in the research as freehold for all nationalities. You could win every other argument and
   still hold an option over an asset you cannot own. Now question zero, ahead of everything.
3. **The "Aldar published a 6–7% equity rate" claim was ours, not Aldar's.** Aldar published
   16%/19%/22% at years 1/2/3. The 6–7% was a derived gloss that turns out to be simply
   AED 150,000 ÷ AED 2.2M — our own assumed price wearing Aldar's name. A developer's analyst would
   have caught it. Removed everywhere outside the one section that correctly flagged it.

---

## What to do instead — in this order, and stop if one fails

The point of this ordering is that **the first three cost you nothing and can each kill the idea
before you spend anyone's goodwill.** Do not approach a developer until they are done.

**1. Email HR. This week. This is the blocking item.**
The draft is in `abu-dhabi-rent-to-own-report.md` §3.6. The question is whether the housing allowance
can be paid against a tenancy that carries a purchase option and an equity credit — and whether it
converts to cash if you buy. **No employer was ever asked, by anyone, at any point in this research.**
If the answer is "standard Tawtheeq tenancy only", the entire rent-to-own line of enquiry closes and
you have saved yourself months.

**2. Ask one lender whether accrued rent credit counts as your equity contribution.**
Free to ask, and it is the one question that de-risks the developer at zero cost to them. If no lender
will treat vendor-accrued credit as your deposit, then every version of this lapses at exercise
regardless of what any developer agrees to.

**3. Get one lawyer's view on recharacterisation.**
If a lease-plus-equity-ledger is treated as a disguised sale, there is no Tawtheeq, no rental-dispute
protection, and — decisively — **no rent for an employer to pay**. The whole premise collapses. The
open-questions list in `03-term-sheet.md` Part 3 is written to be handed to a lawyer as-is.

**4. Only then, and only if 1–3 came back favourably, have a conversation — not a pitch.**
Ask the three answerable questions rather than proposing a product:
*What tranche size, on what stock, at what credit rate, would make this worth building? And would you
tell me if I came back with it?*
Target order and reasoning are in `02-target-dossiers.md`. Note the honest probability estimate there:
**~10–15% that any developer creates a product within twelve months; ~25–30% for a single bespoke
unit.** The realistic best outcome is a precedent, not a launch.

---

## The alternative you should price in parallel

Because it fits your actual constraints today, and the rent-to-own route may well close at step 1:

**Rent a ready outer-ring villa or townhouse now, and save toward an Ijara purchase.**
Al Reef (AED 90–160k/yr, average ~138k), Hydra Village (45–100k), Khalifa City, Al Ghadeer and
low-end Al Shamkha all sit inside your budget with immediate move-in and a Tawtheeq tenancy by
definition — the only structure in the entire analysis your employer can pay against without a policy
question. It accrues no equity, which is the real cost of it. The binding constraint on converting to
ownership later is the ~20% expat deposit (~AED 500–580k cash) plus 3–4% transaction costs, which a
housing allowance almost certainly cannot fund. That makes it a two-to-four year plan, not a
three-to-twelve month one.

---

## What is in this folder

| File | What it is | Status |
|---|---|---|
| `00-campaign-overview.md` | This file | — |
| `01-developer-economics.md` | The DCF and the constraint solve. Its centre is now the negative finding | Revised after review |
| `02-target-dossiers.md` | Per-counterparty approach profiles, sequencing, probability estimates | Round 1 — **not** red-teamed |
| `03-term-sheet.md` | The proposal, rebuilt around the structure that survives, with open legal questions for a lawyer | Revised after review |
| `04-pitch-and-objections.md` | One-pager and twelve objections, now leading with the falsification | Revised after review |
| `05-red-team-log.md` | All three critiques, what was accepted, what was rejected and why | — |
| `../abu-dhabi-rent-to-own-report.md` | The original research, analysis and outreach pack including the HR email | — |
| `../.claude/agents/rto-*.md` | The four reusable agent roles, for re-running this work | — |

---

## Standing limitations

**Nothing here is verified against a primary source.** Every external host was blocked by this
session's egress policy (HTTP 403 on CONNECT) — aldar.com, bayut.com, propertyfinder.ae,
bloomholding.com, reportageuae.com, psinv.net, adrec.gov.ae and every other. No developer page, no
portal listing, no press release and no regulation was ever opened. All market figures come from
search-engine snippets and carry `[UNVERIFIED]` labels; all deal arithmetic is `[ILLUSTRATIVE]` on an
assumed asset value.

**One document has not been adversarially reviewed.** `02-target-dossiers.md` was drafted before the
red team ran and only spot-checked. Treat its probability estimates and counterparty reasoning as
first-draft judgement.

**No legal advice is given anywhere in this folder**, and none of the structural questions could be
verified, because every regulator source was blocked. A UAE real-estate lawyer must close the open
questions before anything is signed or sent.

**Nothing here has been sent to anyone.** Every message, email and term sheet is a draft for you to
review, edit and send yourself.
