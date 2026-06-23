# Playbook: release-notes

**Trigger:** "run the release-notes playbook for [version or date range]"

**When to use:** After every product release. Drop the engineering tickets, changelog, or PR descriptions into Inputs first.

---

## What it does

1. Read the engineering tickets, PR descriptions, or internal changelog from Inputs for the specified release.
2. Read the ICP definition and active venture context from `CLAUDE.md` to understand who the audience is.
3. Filter out internal-only changes (infrastructure updates, refactors, dependency upgrades) that users don't need to know about.
4. For each user-facing change, translate it from technical language into benefit language:
   - Technical: "Refactored the report query to use indexed joins"
   - Human: "Reports now load in under 2 seconds, down from 8"
   - Technical: "Added rate limiting to the export endpoint"
   - Human: "Exports are more reliable and won't fail during high usage"
5. Organize changes into sections:
   - **What's new** — new features or capabilities
   - **What's better** — improvements to existing features
   - **What's fixed** — bugs resolved
6. Write two versions:
   - **In-app / email version:** Conversational, short, benefit-led. Max 150 words.
   - **Changelog version:** Structured list, slightly more technical, for the changelog page.
7. Save to `Outputs/releases/[version]-[date].md`

**Output format:** `Outputs/releases/[version]-YYYY-MM-DD.md`

**Rules:**
- Never say "we've been working hard on" or "we're excited to announce." Just say what it does.
- If a change benefits only a specific user type, say so.
- Every release note is an opportunity to remind users why they're paying you. Write it that way.
