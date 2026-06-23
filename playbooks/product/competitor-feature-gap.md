# Playbook: competitor-feature-gap

**Trigger:** "run the competitor-feature-gap playbook for [competitor name]"

**When to use:** When a competitor ships something notable — a new feature, a pricing change, an acquisition, a new market move.

---

## What it does

1. Read the existing competitor page for this competitor from the vault.
2. Read the ICP, value proposition, and GTM motion from `CLAUDE.md`.
3. Read the new signal about this competitor from Inputs (their changelog, announcement, press release, or your own notes from a customer call where they came up).
4. Analyse the move across three dimensions:

   **Threat level:**
   - Does this directly compete with a core feature we rely on for differentiation?
   - Does this target our ICP specifically, or a different segment?
   - Does this change how customers will evaluate us in a head-to-head?

   **Opportunity:**
   - Does this move signal where the market is going — and do we need to be there first?
   - Did they ship this because customers demanded it? (If so, our customers probably want it too.)
   - Did they move up-market or down-market? Does that open space they're leaving behind?

   **Positioning response:**
   - Does our current differentiation story still hold?
   - Is there a reframe we need to make in sales decks or on the website?
   - Is there a counter-narrative we can use — something we do better that this move highlights by contrast?

5. Write a competitive response brief covering:
   - What they shipped and what it means
   - Threat level (low / medium / high) with specific reasoning
   - Recommended product response (build / watch / ignore), with timeline
   - Recommended positioning response — the one sentence change in how we describe ourselves
   - The message to give the sales team for when this comes up in deals

6. Update the competitor page in the vault with the new information.
7. Save the brief to `Outputs/competitive/[competitor]-[date].md`

**Output format:** `Outputs/competitive/[competitor]-YYYY-MM-DD.md`
