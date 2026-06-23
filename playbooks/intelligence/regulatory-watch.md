# Playbook: regulatory-watch

**Trigger:** "run the regulatory-watch playbook for [regulation or jurisdiction]"

**When to use:** When a regulatory change, new law, compliance requirement, or legal development may affect your product, customers, or market. Drop the source into Inputs first.

---

## What it does

1. Read the regulatory source from Inputs.
2. Read your ICP, product context, and the markets/jurisdictions you operate in from `CLAUDE.md`.
3. Evaluate the regulatory change across four dimensions:

   **Does it affect us directly?**
   Does our product, our data handling, or our business model fall within the scope of this regulation? If yes — which specific parts?

   **Does it affect our customers?**
   Even if we're not directly regulated, are our customers subject to this change? If our buyers are now required to do something new, that's a product opportunity or a sales objection, depending on how we respond.

   **Timeline:**
   When does this take effect? Is there a phased rollout? What's the enforcement date? When do we need to act?

   **What action is needed:**
   - **Immediate:** Something that must change now — in the product, in contracts, in data handling
   - **Planned:** Something that needs to be built into the roadmap or legal review in the next 90 days
   - **Watch:** Something that may affect us if it passes or expands, but no action needed yet
   - **None:** Not applicable to our current product, customers, or geography

4. Write a regulatory brief covering:
   - Plain-English summary of what changed
   - Impact assessment: direct / indirect / none, with specific reasoning
   - Required actions with owners and deadlines
   - How to use this in sales — is this a reason customers are now more likely to buy? Or a risk that needs to be addressed in contracts?

5. Save to `Outputs/regulatory/[regulation]-[date].md` and flag if legal review is needed.

**Output format:** `Outputs/regulatory/[regulation]-YYYY-MM-DD.md`

**Notes:**
- This playbook provides analysis, not legal advice. Any regulation with direct product or contractual implications requires a qualified lawyer.
- Regulatory changes that create compliance burdens for customers are often the best time to reach out — they suddenly have urgency.
- If this regulation is specific to a geography you don't currently operate in but plan to enter, file it and link it to the relevant market-expansion venture.
