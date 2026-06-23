# Playbook: board-pack

**Trigger:** "run the board-pack playbook for [meeting date]"

**When to use:** 5 days before any board meeting or formal investor review.

---

## What it does

1. Read all Outputs and Feedback from the past 30-90 days (since the last board meeting) across all active ventures.
2. Read the north star metric history and all quarterly-planning outputs.
3. Read any previous board-pack output to ensure continuity — what was decided last time, what was committed to, what actually happened.
4. Read active venture context and fundraise status from `CLAUDE.md`.

5. Build the full board pack structured as:

   **Cover page context:**
   Company name, meeting date, attendees, board composition.

   **Executive summary (1 page):**
   The state of the company in 5 bullets. Not polished — honest. What's working, what's not, what we need from this meeting.

   **Metrics dashboard:**
   North star metric: current vs. target vs. last period. Then the 3-4 supporting metrics that tell the full story — revenue or ARR, growth rate, burn, runway. Actual numbers, no ranges.

   **Commitments from last meeting:**
   What we said we would do. What we actually did. If something wasn't done — the honest reason, not the polished version.

   **Wins this period:**
   3-5 specific things that happened. Deals closed, products shipped, hires made, partnerships signed. Specific.

   **What's not working:**
   The 1-2 things that are genuinely stuck or behind plan. Include what we've tried and why it hasn't worked yet. This section builds more board trust than any win ever will.

   **Decisions needed from the board:**
   The specific items that require board input or approval — not updates, decisions. For each: the context, the options considered, and your recommendation.

   **The ask:**
   Intros, references, advice on a specific problem, connection to a specific person. Specific.

   **Appendix:**
   Detailed financials, hiring plan, roadmap — for reference, not for discussion.

6. Save to `Outputs/board-packs/[date].md`

**Output format:** `Outputs/board-packs/YYYY-MM-DD.md`

**Notes:**
- A board meeting where everything looks fine is a wasted board meeting. Bring the real problems.
- Board members read the pack in advance. Write it so it stands alone without you talking over it.
- The decisions-needed section is the most important. If there are no decisions to make, the meeting is an update — and updates can be emails.
