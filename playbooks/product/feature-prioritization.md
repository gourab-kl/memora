# Playbook: feature-prioritization

**Trigger:** "run the feature-prioritization playbook" then list the features to evaluate

**When to use:** Before any sprint planning or quarterly roadmap session.

---

## What it does

1. Read the ICP definition, north star metric, GTM motion, and active venture goals from `CLAUDE.md`.
2. Read any customer call notes, deal notes, and deal-autopsy outputs for signals about what customers care about most.
3. For each feature listed, score it across four dimensions:

   **ICP impact (1-5):** How directly does this solve a pain for the core ICP? Not the noisiest customer — the best-fit customer.

   **North star contribution (1-5):** How directly does shipping this move the north star metric? If the connection is indirect, score it lower.

   **GTM leverage (1-5):** Does this help close deals, reduce churn, or accelerate expansion? Features that only satisfy existing users score lower than features that help acquire new ones.

   **Effort (1-5, inverted — lower effort = higher score):** Rough engineering complexity. Not a detailed estimate — a relative signal.

4. Calculate a weighted priority score per feature. Default weights: ICP impact (30%) + north star contribution (35%) + GTM leverage (25%) + effort (10%).
5. Output a ranked list with:
   - Score and rationale per feature
   - The top 3 to build next, with one sentence on why each made it
   - Features to cut from the current planning cycle and why
   - Features to watch but not build yet — and what signal would move them up

6. Save to `Process/[venture]/feature-priority-[date].md`

**Output format:** `Process/[venture]/feature-priority-YYYY-MM-DD.md`

**Notes:**
- If a feature scores high on effort and low on everything else, it's a no. Don't debate it.
- Features requested by your loudest customer and features that move the north star for your best-fit customer are often different things. Know which one you're building.
- Revisit this every 6 weeks. Priorities change as you learn more.
