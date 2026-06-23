# Playbook: case-study

**Trigger:** "run the case-study playbook for [customer name]"

**When to use:** When a customer has achieved a clear, measurable outcome with your product and you have notes from their journey.

---

## What it does

1. Read all notes related to this customer — onboarding notes, success check-ins, any emails or call transcripts in the vault, Feedback entries.
2. Read the ICP and value proposition from `CLAUDE.md`.
3. Extract the raw material for the story:
   - What was the situation before they found us? (the pain, the workaround, the cost of doing nothing)
   - What made them choose us over alternatives?
   - What did implementation look like — what was hard, what surprised them?
   - What changed after? Specific numbers wherever possible.
   - What would they tell another company like them who is evaluating us?
4. Write the case study in two formats:

   **Full version (for website / PDF):**
   - **Company snapshot:** 2-3 lines on who the customer is and what they do.
   - **The challenge:** Their situation before, in their language if quotes are available. Specific and honest.
   - **The solution:** What they use and how — focused on the workflow, not the feature list.
   - **The result:** Numbers first. Then the qualitative shift. Then the quote.
   - **The quote:** One pull quote that could stand alone on a sales deck slide. If no quotes exist in the vault, write a placeholder and flag it for approval.

   **Short version (for sales deck / one-pager):**
   - 3 bullets: challenge, solution, result. One sentence each. The result bullet has the number.

5. Flag any claims that need customer confirmation before publishing.
6. Save to `Outputs/case-studies/[customer]-[date].md`

**Output format:** `Outputs/case-studies/[customer]-YYYY-MM-DD.md`

**Notes:**
- The best case studies are specific and honest about what was hard, not just what worked. Buyers trust specificity.
- If you don't have a number, get one. "Saved time" is not a result. "Cut report generation from 4 hours to 20 minutes" is.
- Always get customer approval before publishing. Never assume.
