# Playbook: data-room-checklist

**Trigger:** "run the data-room-checklist playbook"

**When to use:** When a VC asks to move forward and you need to prepare for due diligence.

---

## What it does

1. Read your current company stage, fundraise round size, and team details from `CLAUDE.md`.
2. Read any existing fundraise venture folder for context on what's already been shared.
3. Generate the complete due diligence checklist for your specific stage and round size. A pre-seed checklist is different from a Series A checklist — output the right one.
4. For each item on the checklist, check whether a corresponding note, document, or Output exists in the vault.
5. Produce a data room readiness report covering:
   - **Ready:** documents that exist in the vault or are referenced in Outputs
   - **Needs work:** documents that exist but are outdated or incomplete based on what's in the vault
   - **Missing:** documents with no evidence of existing anywhere — these are the gaps to close before sharing the data room
   - **Priority order:** which gaps to close first based on what VCs look at hardest at your stage
6. Save to `Process/fundraise/data-room-checklist-[date].md`

**Standard checklist by stage (Claude will apply the right one):**

*Pre-seed / Seed:*
Pitch deck · cap table · incorporation docs · founder bios · product demo or screenshots · early customer evidence · financial model (even simple) · any existing term sheets

*Series A:*
All of the above plus: audited or reviewed financials · detailed financial model with 3-year projection · org chart · key contracts and customer agreements · IP assignments · 409A valuation · board minutes · detailed cap table with all option grants

*Series B and beyond:*
All of the above plus: retention cohorts · unit economics by cohort · detailed GTM breakdown · customer references list · competitive analysis · employment agreements for key hires

**Output format:** `Process/fundraise/data-room-checklist-YYYY-MM-DD.md`

**Notes:**
- A data room that goes out with gaps kills momentum faster than bad metrics. Know your gaps before they do.
- VCs will find everything. Surfacing a problem yourself is professional. Having them find it is a trust issue.
