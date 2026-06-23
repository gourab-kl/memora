# Playbook: quarterly-planning

**Trigger:** "run the quarterly-planning playbook for Q[N] [year]"

**When to use:** Last week of each quarter. Run this before setting goals for the next quarter.

---

## What it does

1. Read all Feedback folders across every active venture for the past 90 days.
2. Read all weekly-debrief outputs from the past quarter.
3. Pull the north star metric history from CLAUDE.md and Feedback notes — what the target was, what actually happened each month.
4. Read the goals that were set at the start of this quarter (from the previous quarterly-planning output or from CLAUDE.md).

5. Run a quarter in review:

   **What the data says:**
   - North star metric: target vs. actual, and the trend
   - Goals set at the start of the quarter: hit / missed / abandoned, and the honest reason for each
   - Top 3 things that went well — specific, with evidence from the vault
   - Top 3 things that didn't — specific, with the root cause, not the surface explanation

   **What the pattern says:**
   - Looking across all 3 monthly debriefs: what kept recurring as a problem?
   - What did we keep saying we'd fix but didn't?
   - Where did we get distracted from the original plan, and was that distraction right or wrong?

6. Set next quarter goals:
   - One north star metric target — specific number, specific date
   - 3 goals that, if hit, make the quarter a clear success
   - For each goal: the metric, the owner, the first action to take in week 1
   - The one thing we're explicitly NOT doing next quarter, and why (saying no is a strategy)

7. Save to `Outputs/quarterly-planning/Q[N]-[year].md` and update CLAUDE.md with the new goals and north star target.

**Output format:** `Outputs/quarterly-planning/Q[N]-YYYY.md`

**Notes:**
- A quarterly plan that doesn't reference what actually happened last quarter is just hope with a deadline.
- Three goals is the maximum. More than three means none of them are real priorities.
- Update CLAUDE.md after this runs. Every future session should load the new quarter's goals automatically.
