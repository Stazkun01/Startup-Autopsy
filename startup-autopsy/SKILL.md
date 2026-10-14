---
name: startup-autopsy
description: Audit a startup plan against the reasons real startups died, then give it a 0-100 survival score, the most likely cause of death, look-alike dead companies, and a prioritized list of what to avoid and fix. Use this whenever someone shares a business plan, pitch deck, website, team or hiring plan, financial model, or just describes their startup idea and asks for a rating, review, reality check, red flags, "will this work", "what could kill us", "roast my startup", or wants it checked against failed startups or the startup graveyard, even if they don't use the word audit.
---

# Startup Autopsy

Run a post-mortem on a company *before* it dies. The idea: almost every dead startup died of one of about a dozen well-documented causes, and the warning signs were usually visible early. This skill reads the founder's whole plan (idea, market, product, website, team, money, legal) and checks it against those causes, the way a doctor checks symptoms against known diseases.

The founder wants an honest read, not encouragement. A flattering audit that misses the thing that kills them is worse than useless. At the same time, be fair: say what is strong, and separate "this is a real red flag" from "I don't have enough information".

## Step 1: Gather the plan

Collect whatever the person has. Useful inputs, in rough order of value:

1. **The idea and customer**: what problem, for whom, how they solve it today, and any evidence they care (interviews, waitlist, pre-orders, paying users, retention).
2. **Business model and numbers**: pricing, cost to serve, customer acquisition cost (CAC), lifetime value (LTV), gross margin, monthly burn, cash in the bank, runway, funding plans.
3. **Team and employees**: founders (roles, background, equity split, vesting, full-time or not), current employees and contractors, hiring plan with timing and salaries, advisors.
4. **Website**: the URL. Fetch it and review it as a first-time visitor would (see Step 3).
5. **Competition**: who else does this, including the "do nothing / spreadsheet / incumbent" option.
6. **Go-to-market**: how the first 100 and first 1,000 customers will be found.
7. **Legal and regulatory**: licenses, data handled (health, finance, kids, personal data), worker classification, IP ownership.
8. **Stage and timing**: idea, pre-launch, launched, revenue, and why now.

If attachments are provided (deck, PDF, doc, spreadsheet), read them fully before judging.

If major pieces are missing, ask for them once in a short checklist, then proceed with what is there. Don't block the audit on missing info: a partial audit with clearly marked unknowns is more useful than a questionnaire. When the person isn't around to answer, just proceed.

## Step 2: Check the plan against each cause of death

Read `references/failure-patterns.md`. It lists the main causes of startup death, how often founders cite each one in post-mortems, the early warning signs, real companies that died of it, and what survivors did differently.

For each pattern, decide:
- **Present** (clear evidence in the plan), **Possible** (some signs, or a likely risk given the model), **Not seen**, or **Unknown** (no information).
- Quote or point to the specific part of their plan that triggered it. "Your plan says you'll hire 6 engineers in month 2 with 9 months of runway" beats "watch your burn".

Remember that cash running out is usually a symptom. When you find a cash problem, trace it back to its root (no demand, bad unit economics, overhiring, slow sales cycle) and name the root.

## Step 3: Review the website (if a URL was given)

Fetch the site. If it can't be fetched, say so and score from the rest. Check:

- **Five-second test**: can a stranger tell what it is, who it's for, and why it's better, from the top of the homepage?
- **Call to action**: one clear next step (sign up, book a demo, buy). Is it the right step for the stage?
- **Pricing**: shown, or a reason not to? Does it match the business model in the plan?
- **Proof**: real customers, numbers, testimonials, logos. Flag anything that looks invented or unverifiable, since fake proof is a legal and trust risk.
- **Promises vs. plan**: features or claims the site makes that the plan says aren't built yet, or claims that would be regulated (health, financial returns, "AI" claims the product can't back up).
- **Basics**: privacy policy and terms (required if collecting personal data or payments), contact info, works on a phone, no broken pages.
- **Consistency**: does the site target the same customer the plan describes?

Website findings feed mostly into "Product and go-to-market" and "Legal" scores.

## Step 4: Review the team and employees

Specifically look for:
- **Missing critical skills**: e.g., a software product with no technical founder, a sales-led business with no one who has sold, a regulated business with no domain expert.
- **Founder setup**: unequal commitment (one full-time, one part-time), no vesting, unclear decision-maker, equity splits that will cause resentment. Co-founder conflict is a top killer.
- **Hiring ahead of demand**: headcount growing before evidence that customers want the product. Compare total monthly payroll to revenue and runway.
- **Single points of failure**: one person holding all customer relationships, all code, or all credentials.
- **Worker classification**: contractors doing employee-like work (this killed Homejoy).
- **Burnout signs**: founders covering 4+ roles indefinitely, no plan to hand anything off.

## Step 5: Score

Score each category on its own scale, based on the evidence. Use the full range; most early plans should land somewhere in the middle, and a 90+ should be rare and earned.

| Category | Max | What earns points |
|---|---|---|
| Market need and demand evidence | 20 | Painful, frequent problem; evidence people pay or commit (not just "they said it's cool") |
| Business model and unit economics | 15 | Clear pricing; positive gross margin; LTV well above CAC, or a credible path there |
| Cash and runway | 15 | 12+ months runway or near profitability; burn tied to milestones; fundraising started with 6+ months left |
| Team and hiring | 15 | Founders cover the critical skills; vesting in place; hiring follows demand; no single point of failure |
| Competition and differentiation | 10 | Knows real competitors including the status quo; a reason customers switch that's hard to copy |
| Product and go-to-market (incl. website) | 10 | Simple first product; a specific channel to the first customers; website passes the checks above |
| Legal, regulatory and compliance | 8 | Licenses, data rules, worker classification, IP and claims handled for this industry |
| Timing and focus | 7 | A real "why now"; one customer and one product focus rather than five |

**Unknowns:** when a category has no information, give it roughly half its points, mark it "Unknown", and say what information would move it. Don't silently assume the best or the worst.

**Fatal flaw cap:** if any single pattern is clearly present and severe enough to kill the company on its own (e.g., no evidence anyone wants it plus heavy spending, fraud-like claims, an unlicensed activity that requires a license, under 3 months of runway with no revenue), cap the total at 49 regardless of other scores, and explain why. A great team doesn't save a company with no customers.

**Bands:**
- **80-100: Built to survive.** Real risks exist but are being managed.
- **60-79: Fixable.** One or two serious risks; addressing them soon changes the outcome.
- **40-59: Danger zone.** Several patterns that killed real companies are present.
- **0-39: Graveyard trajectory.** On the current path, this ends the way the look-alikes ended.

The score is a structured opinion, not a prediction. Say so once, briefly, near the score.

## Step 6: Find graveyard twins

Pick 2-3 dead companies whose situation most resembles this plan (same business model, same mistake, or same market). Use `references/failure-patterns.md` first. If web search is available, also check live startup-failure databases for companies in the same industry, for example:
- https://www.vcbacked.co/startup-graveyard (large database of shut-down venture-backed startups with funding data)
- The original Startup Graveyard site (post-mortems with founder-stated reasons; search for it by name)
- CB Insights' startup post-mortems collection

Industry matters a lot here: a dead food-delivery startup is a better warning for a food-delivery plan than a famous dead social app. Prefer same-industry twins when you can find accurate ones.

Only name a company and its cause of death when you are confident it's accurate. For each twin: what they did, what killed them, and the exact way this plan resembles them *and differs* from them. The difference matters: it's what tells the founder whether they're actually on the same path.

## Step 7: Write the report

Use this structure. Keep it tight and specific; every point should refer to something in their plan.

```
# Startup Autopsy: [Company name]

## Survival score: [N]/100 — [Band name]
[2-3 sentences: the overall verdict and the single biggest reason for the score. One short line that this is a structured opinion, not a prediction.]

## Most likely cause of death
[The one pattern most likely to kill this company if nothing changes, with the evidence from their plan, and roughly when it would bite (e.g., "around month 7, when runway hits zero before revenue").]

## Scorecard
[Table: category | score/max | one-line reason. Mark Unknown where relevant.]

## What to avoid
[The prioritized red flags, most dangerous first. For each:
- **The risk**, tied to the failure pattern by name
- **Evidence** from their plan, website or team
- **Who died of this**: a real example in one line
- **Fix**: a concrete action and a deadline or trigger ("before hiring anyone else, get 10 paying customers")]

## What's working
[2-4 genuine strengths, specific. Skip anything generic.]

## Graveyard twins
[2-3 look-alike dead companies: resemblance, cause of death, and the key difference.]

## Website notes
[Only if a site was reviewed: top issues, most important first.]

## Team notes
[Gaps, hiring timing, founder setup, single points of failure.]

## Next 30 days
[3-5 actions, ordered, that would most raise the score. Each one testable.]

## What would change this score
[The unknowns, and which answers would move the score up or down.]
```

If the session offers a way to create a document the person can keep and share, put the report there, since founders tend to come back to it and share it with co-founders or advisors. Otherwise, write it in the reply.

## Tone

Write like a sharp, experienced advisor who wants them to win: direct, specific, no hedging fog, no cheerleading, no cruelty. Name the uncomfortable thing plainly once, then move to the fix. If the plan is strong, say so without inventing problems to look rigorous.

## Re-audits

If the person comes back with changes, re-score only what changed, show old vs. new scores per category, and say which risks are now resolved and which remain.
