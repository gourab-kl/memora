# Playbook: founder-newsletter

**Trigger:** "run the founder-newsletter playbook"

**When to use:** Weekly or biweekly, after running the weekly-debrief playbook. Turns your private debrief into a public one.

---

## What it does

1. Read the most recent weekly-debrief output from `Outputs/weekly-debriefs/`.
2. Read the ICP and positioning from `CLAUDE.md` to understand who reads this newsletter and what they care about.
3. Read any market signals, competitive notes, or customer insights captured this week in Inputs.
4. Write a founder newsletter draft structured as:

   **Subject line:** Specific, not clever. The reader should know exactly what they're getting. Give three options — let the founder pick.

   **The lead (2-3 sentences):** The most interesting or provocative thing that happened this week. Not the most comfortable thing — the most interesting.

   **What we shipped:** 1-3 bullets. Specific. What changed, not what we worked on.

   **What I'm thinking about:** One idea, one observation, or one question from the week that has genuine intellectual value for the reader. Not a company update — a real thought. This is the section that builds a real audience.

   **What I got wrong or learned:** One honest admission or lesson. This is optional but it's the section that builds trust faster than anything else a founder can write publicly.

   **One thing worth your time:** A link, a book, a conversation, a tool — something genuinely useful to the reader, not self-promotional.

5. Save to `Process/content/newsletter-[date].md`

**Output format:** `Process/content/newsletter-YYYY-MM-DD.md`

**Notes:**
- The newsletter that grows is the one that teaches something real every issue. Not the one that announces company news.
- If the "what I'm thinking about" section could have been written by anyone in your space, rewrite it until it couldn't.
- Keep it under 400 words. Founders are busy. So is your audience.
