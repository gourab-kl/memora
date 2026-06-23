# Playbook: customer-expansion

**Trigger:** "run the customer-expansion playbook"

**When to use:** Quarterly, or any time you want to find upsell and expansion opportunities before they come to you.

---

## What it does

1. Read all existing customer notes from the vault — onboarding notes, success check-ins, Feedback entries, any NPS or satisfaction signals.
2. Read the ICP definition and value proposition from `CLAUDE.md`.
3. Identify the profile of your highest-value customers — the ones with the most positive Feedback entries, strongest outcomes noted, and deepest engagement signals.
4. Scan all other customer accounts and score each one for expansion potential based on:
   - How closely they match the highest-value customer profile
   - Whether there are untapped use cases mentioned in their notes
   - Whether their team size or company growth suggests they've outgrown their current plan
   - Whether any contact at the account has changed roles (new champion opportunity)
5. Write an expansion brief to `Outputs/expansion/` covering:
   - Top 3 accounts to prioritize for expansion, with specific reasoning per account
   - The expansion angle for each (upsell, cross-sell, new team/department, new use case)
   - The specific person to contact and what to say
   - Accounts to watch but not act on yet — and what signal would trigger action
6. Cross-link to the relevant customer notes and the pipeline-review if one exists.

**Output format:** `Outputs/expansion/YYYY-MM-DD.md`

**Notes:**
- Expansion is cheaper than acquisition. Treat it with the same rigor as new pipeline.
- If a customer hasn't been contacted in 60+ days, flag them separately — they are at churn risk, not expansion opportunity.
