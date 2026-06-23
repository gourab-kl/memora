# Playbook: monthly-investor-update

**Trigger:** "run the monthly-investor-update playbook"

**When to use:** Last working day of each month, every month — whether you're raising or not.

---

## What it does

1. Read all Feedback and Outputs from the past 30 days across active ventures.
2. Pull the north star metric, current fundraise status, and active goals from `CLAUDE.md`.
3. Read the previous investor update from `Outputs/investor-updates/` to maintain continuity — what was promised last month, what actually happened.
4. Draft a monthly investor update email structured as:

   **Subject:** [Company Name] — [Month Year] Update

   **The number that matters:** Lead with the single most important metric this month and whether it moved in the right direction. One sentence.

   **What we shipped:** 3-5 bullet points. Specific. No adjectives.

   **What's working:** One honest paragraph on the thing gaining traction and why.

   **What's not working:** One honest paragraph on the thing that's stuck and what we're doing about it. This is the most important section. Investors who see you be honest about problems trust you with money.

   **The ask:** One specific request — an intro to a specific person, a reference, a question you want their input on. Never leave this blank.

5. Save the draft to `Outputs/investor-updates/YYYY-MM.md`.
6. Cross-link to the relevant venture Outputs and Feedback it drew from.

**Output format:** `Outputs/investor-updates/YYYY-MM.md`

**Rules:**
- Never spin a bad month. Investors have seen every version of spin. Honest updates build the relationship that helps you when you need it.
- If a metric went backwards, say so and say why.
- Keep it under 300 words. If you can't say it in 300 words, you don't understand it yet.
- The ask must be specific. "Any intros would be great" is not an ask.
