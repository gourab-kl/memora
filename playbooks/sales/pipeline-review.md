# Playbook: pipeline-review

**Trigger:** "run the pipeline-review playbook"

**When to use:** Every Monday morning before your week starts, or before any sales team sync.

---

## What it does

1. Read every open deal note inside `Inputs/` and `Process/` folders across all ventures. Look for anything labelled as a deal, prospect, or opportunity.
2. For each deal found, extract:
   - Company name and contact
   - Current stage (outreach / discovery / proposal / negotiation / verbal)
   - Last activity date
   - Next agreed action and who owns it
   - Deal size if mentioned
3. Flag any deal with no update in the last 7 days as **stale**. Flag any deal where the next action is unowned as **at risk**.
4. Check the ICP definition in `CLAUDE.md`. Flag any deal that looks like an ICP mismatch — deals we're chasing that we probably shouldn't be.
5. Write a pipeline summary to `Outputs/pipeline-reviews/` dated today covering:
   - Total open deals and combined pipeline value
   - Deals that moved forward this week
   - Stale deals with recommended next action
   - Deals to consider dropping and why
   - The one deal most likely to close in the next 14 days, and what it needs
6. Link the summary to relevant deal pages and the ICP page.

**Output format:** A dated Markdown file in `Outputs/pipeline-reviews/YYYY-MM-DD.md`

**Notes:**
- Be direct about stale deals. Do not soften it.
- An unowned next action is a dead deal. Flag every one.
- Check the last quarterly-planning output if it exists — are we chasing the deals that match our current quarter's goal?
