# Playbook: deal-autopsy

**Trigger:** "run the deal-autopsy playbook for [company name]"

**When to use:** Within 48 hours of losing any deal. The faster you do this, the more honest the analysis.

---

## What it does

1. Read all notes related to the named company — discovery call notes, emails, proposal drafts, objection notes — from any folder in the vault.
2. Read the ICP definition in `CLAUDE.md` and the objection-handling page if it exists.
3. Reconstruct the deal timeline: first contact → discovery → proposal → loss.
4. Diagnose the loss across these categories:
   - **ICP fit** — was this ever our buyer? Did we ignore early signs it wasn't?
   - **Champion strength** — did we have a real internal champion or just a friendly contact?
   - **Timing** — was the pain urgent enough for them to buy now?
   - **Competition** — who did they go with and why? What did that competitor offer that we didn't?
   - **Execution** — what did we do wrong or too slowly, regardless of fit?
5. Write the autopsy to `Outputs/deal-autopsies/` with:
   - One-line verdict (ICP miss / champion failure / timing / lost to competitor / execution failure)
   - What the signals were and when they appeared
   - What we should have done differently and at what stage
   - One change to make to the sales process immediately
6. Update the objection-handling page with any new objection encountered. Cross-link to the autopsy.
7. If the competitor is new or said something new, update the competitor page.

**Output format:** `Outputs/deal-autopsies/YYYY-MM-DD-[company].md`

**Notes:**
- Be surgical. The goal is a process change, not a post-mortem that collects dust.
- If we lost on price, the real question is why the value wasn't clear — not whether the price was wrong.
- Every autopsy should produce exactly one concrete change. If it produces zero, redo it.
