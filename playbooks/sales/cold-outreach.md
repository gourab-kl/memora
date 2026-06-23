# Playbook: cold-outreach

**Trigger:** "run the cold-outreach playbook for [person name] at [company]"

**When to use:** Before writing any cold email or LinkedIn outreach to a new prospect.

---

## What it does

1. Read the ICP definition, value proposition, and GTM motion from `CLAUDE.md`.
2. Read the objection-handling page if it exists.
3. Search the vault for any existing notes on this company or person.
4. Based on the company name and role provided, reason about:
   - What pain they most likely have given their company type, size, and the role named
   - Which part of our value prop maps to that pain most directly
   - What a person in that role cares about that is NOT obvious (not just their job title)
5. Write three outreach variants:
   - **Short** (3 sentences max): pain → proof → ask. No fluff.
   - **Medium** (5-7 sentences): hook based on something specific about them → pain → how we solve it → social proof → ask.
   - **Follow-up** (for the second touch if they don't reply): different angle, shorter, no guilt.
6. For each variant, include the subject line separately.
7. Save to `Process/outreach/[company]-[date].md` and cross-link to the deal page if one exists.

**Output format:** `Process/outreach/[company]-YYYY-MM-DD.md`

**Rules:**
- Never mention features. Only mention outcomes.
- Never use the word "synergy", "leverage", "circle back", "touch base", or "hope this finds you well."
- The ask must be one specific small thing — a 20-minute call, a reply with one question answered, a specific date.
- If you don't have enough information to write something specific, say so and ask what you need instead of writing a generic email.
