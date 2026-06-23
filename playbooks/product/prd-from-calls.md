# Playbook: prd-from-calls

**Trigger:** "run the prd-from-calls playbook for [feature or problem area]"

**When to use:** After 3+ customer discovery calls on a specific problem. Drop the transcripts or notes into Inputs first.

---

## What it does

1. Read all call notes, transcripts, or summaries in the Inputs folder related to the named feature or problem area.
2. Read the ICP definition and north star metric from `CLAUDE.md`.
3. Synthesise across all calls to extract:
   - The verbatim language customers use to describe the problem (their words, not yours)
   - How often the problem was mentioned and how urgently across calls
   - The current workarounds customers are using — what they're cobbling together to solve this without you
   - What they've tried before and why it didn't work
   - The outcome they're actually trying to achieve (not the feature they asked for)
4. Write a Product Requirements Document structured as:

   **Problem statement:** One paragraph. What is the real problem, in customer language. Not a solution.

   **Who has this problem:** The specific ICP segment affected, with evidence from the calls.

   **Evidence:** Direct quotes from calls with attribution. The quotes that will make an engineer understand why this matters.

   **Current workarounds:** What customers do today. This defines the "good enough" bar you must beat.

   **Success metric:** How we know we've solved it. Tied to a measurable customer outcome, not a feature shipped.

   **Scope — what this is:**
   - Must have (solves the core problem)
   - Should have (makes it meaningfully better)
   - Won't have in v1 (explicitly out of scope, and why)

   **Open questions:** Things we still don't know that would change the design.

5. Save to `Process/[venture]/PRDs/[feature]-[date].md` and cross-link to the customer call notes it was built from.

**Output format:** `Process/[venture]/PRDs/[feature]-YYYY-MM-DD.md`

**Notes:**
- A PRD that isn't grounded in customer quotes isn't a PRD — it's a wish list.
- "Won't have in v1" is as important as "must have." Scope creep kills shipping.
- If fewer than 3 customers mentioned this problem, this is a hypothesis, not a PRD. Say so.
