# Playbook: interview-scorecard

**Trigger:** "run the interview-scorecard playbook for [role title]"

**When to use:** After writing the JD, before the first interview is scheduled.

---

## What it does

1. Read the JD for this role from `Process/hiring/` and the company context from `CLAUDE.md`.
2. Read any previous hiring notes, past interview feedback, or lessons from hires that didn't work out.
3. Identify the 5 things that matter most for this role at this stage of the company. Not skills from a textbook — what actually predicts success in this specific job, in this specific environment.
4. For each of the 5 dimensions, write:
   - **The question:** One specific, open-ended question that reveals the truth about this dimension. Not "tell me about a time you..." clichés — questions that a great candidate will find interesting and a weak candidate will struggle with.
   - **What a strong answer sounds like:** Concrete signals to listen for.
   - **What a weak answer sounds like:** Red flags — including answers that sound good but aren't.
   - **Follow-up probe:** One question to go deeper if the first answer is vague.
5. Add a section on non-negotiable red flags for this role — things that should end the process immediately regardless of how well everything else goes.
6. Add a structured scoring guide: 1-4 scale per dimension with anchored descriptions so different interviewers can calibrate.
7. Save to `Process/hiring/[role]-scorecard-[date].md` and link to the JD.

**Output format:** `Process/hiring/[role]-scorecard-YYYY-MM-DD.md`

**Notes:**
- Share the scorecard with every interviewer before the interview, not after. Calibration before is what makes the debrief useful.
- Never hire on "gut feel." If someone can't score the candidate on the 5 dimensions, they didn't run a structured interview.
- The best interviews feel like a conversation. The scorecard gives you the structure so the conversation can be natural.
